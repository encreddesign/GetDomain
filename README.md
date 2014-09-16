GetDomain
=========

Small command line application for getting domain from uri, it also checks the protocol such as:
<ol>
  <li>http</li>
  <li>https</li>
</ol>

***How to Use:***
=============

The exe file is located in the bin directory, copy the full path of this folder to the PATH variable on your system:

<pre><code>
  PATH=C:\User\Username\Directory\bin;
</code></pre>

<b>Note:</b>Make sure to replace user, username and directory to your own names.

Now your setup and ready to use the app. Open up your command line and type the following:

<pre><code>
  c:\user\username\dir\bin> getdomain http://www.unity3d.com
</code></pre>

<b>Note:</b>Make sure to replace user, username and dir to your own names.

Press enter, the result should be the following:

<pre><code>
  c:\user\username\dir\bin> getdomain http://www.unity3d.com
  This protocol is standard
  www.unity3d.com
</code></pre>

The line "This protocol is standard" shows because http is the standard protocol. The next line "www.unity3d.com" is the domain name
in the uri.

Now do the same again but this use the website:

<pre><code>
  https://github.com
</code></pre>

Once the changes were made, press enter. The result should be the following:

<pre><code>
  This protocol is secure
  github.com
</code></pre>

