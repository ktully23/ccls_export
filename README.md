# ccls_export
(Assumption: you're using the latest Mac OSx and you have python 3.7 installed)

1. In the terminal, make sure you are in the directory that you would like to serve the application from. Don't make a new directory before cloning the repo.
2. Run <code>git clone https://github.com/ktully23/ccls_export.git && cd ccls_export</code>
3. Create a virtual environment and activate it 
<pre><code>python3 -m venv venv
source venv/bin/activate</code></pre>
4. Install the application requirements: <code>pip install -r requirements.txt</code>
5. Launch the server: <code>mod_wsgi-express start-server webtool.wsgi</code>
6. By going to http://localhost:8000/ you should see that the application is running. If not, it's helpful to check the error logs. When launching the server, it will tell you where the error log is located.
