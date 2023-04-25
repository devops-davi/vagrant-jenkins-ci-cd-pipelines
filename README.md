<!DOCTYPE html>
<html>
  
  <body>
    <h1><img src="https://img.icons8.com/color/48/000000/jenkins.png"/> Vagrant Jenkins build Build Status</h1>
    <h2><img src="https://img.icons8.com/color/48/000000/ubuntu.png"/> Run latest Jenkins instance on Ubuntu 16.04 LTS using Vagrant</h2>

<h3>Prerequisites</h3>
    
<ul>
  <li><img src="https://img.icons8.com/color/48/000000/virtualbox.png"/> VirtualBox</li>
  <li><img src="https://img.icons8.com/windows/32/000000/vagrant.png"/> Vagrant</li>
</ul>

<h3>Installation</h3>
<p>Build the Vagrant box:</p>
    
<code>vagrant up</code>
<br>
<p>To access the Jenkins server:</p>
<ul>
  <li><code>http://localhost:8080</code></li>
  <br>
  <li>Add the following line to the hosts file:<br/><code>127.0.0.1   jenkins.local</code></li>
  <br>
  <li>Then run the server with:<br/><code>http://jenkins.local:8080</code></li>
</ul>

<h3>First time accessing Jenkins</h3>
<p>Jenkins is set up with one user with:</p>
<ul>
  <li>Username: admin</li>
  <br>
  <li>Password: admin</li>
</ul>
<p>Usual caveat about changing the password once setup.</p>
  </body>
</html>
