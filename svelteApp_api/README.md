<h4><u>General Dev Deployment</u></h4>

<ol>
<li>Create a new python virtual environment: <code>python -m venv virtualenv</code></li>
<li>Activate the new virtualenv:
    <ul>
        <li> <i>Windows:</i> <code>.\virtualenv\Scripts\activate.bat</code></li>
        <li><i>Linux:</i> <code>source ./virtualenv/bin/activate</code></li>
    </ul>
</li>
<li>Install dependencies from requirements.txt: <code>pip install -r requirements.txt</code></li>
<li>Run app using manage.py: <code>python manage.py runserver</code></li>
</ol>
<hr>
<h4><u>First time setup of postgresql</u></h4>

<p> 
As with any postgres instance where you want to connect to it externally from a machine
on the network, you must first modify the <code>postgresql.conf</code> and <code>pg_hba.conf</code> files
to allow for network connections. Additionally, you may also need to create a firewall rule to allow
communication with the default postgres port.
</p>

<h4>postgresql.conf:</h4>
<p>Set <code>listen_address = '*'</code> to allow all external connections, you can also use a cidr address
to limit these to a specific set of ips for more security</p>
<h4>pg_hba.conf:</h4>
<p>Add permissions for local ip addresses to connect to the database using md5:

<code>host    all             all              0.0.0.0/0                       md5</code>
<br>
<code>host    all             all              ::/0                            md5</code>

</p>
<hr>