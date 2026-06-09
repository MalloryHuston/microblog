# Welcome to Microblog!

This is an example application featured in Miguel Grinberg's <a href="https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world">Flask Mega-Tutorial</a>. See the tutorial for instructions on how to work with it.

## VIRTUAL ENVIRONMENT

It is recommended to run this program in a ``venv`` environment. Assuming that has already been set up, you can create a ``venv`` environment:
<pre>
<code>$ python3 -m venv venv</code>
</pre>

Now you have to tell the system that you want to use this virtual environment, and you do that by <i>activating</i> it. To activate your brand new virtual environment you use the following command:
<pre>
<code>$ source venv/bin/activate
(venv) $ _</code>
</pre>

If you are using a Microsoft Windows command prompt window, the activation command is slightly different:
<pre>
<code>$ venv\Scripts\activate
(venv) $ _</code>
</pre>

If you are on Windows but are using PowerShell instead of the command prompt, then there is yet another activation command you should use:
<pre>
<code>$ venv\Scripts\Activate.ps1
(venv) $ _</code>
</pre>

## RUNNING THE CODE

Believe it or not, this first version of the application is now complete! Before running it, though, Flask needs to be told how to import it, by setting the ``FLASK_APP`` environment variable:
<pre>
<code>(venv) $ export FLASK_APP=microblog.py</code>
</pre>

If you are using the Microsoft Windows command prompt, use ``set`` instead of ``export`` in the command above.

Run the web application by typing the command ``flask run``:
<pre>
<code>(venv) $ flask run</code>
</pre>

Now open up your web browser and enter the following URL in the address field:
<pre>
<code>http://localhost:5000/</code>
</pre>
