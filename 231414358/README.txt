CSS37W2 Lab – Starter Kit (Student 231414358)

FOLDER STRUCTURE
- 231414358\
  - 231414358.html
  - project.html
  - dynamic.php
  - dynamic.jsp
  - images\profile_placeholder.png
  - audio\placeholder.wav

APACHE (HTTPD) – STATIC + PHP
1) Copy the entire folder '231414358' to C:\xampp\htdocs\
2) Optional: make your page the default "welcome doc" by editing C:\xampp\apache\conf\httpd.conf
   Find the DirectoryIndex line and include your file FIRST:
   DirectoryIndex 231414358.html index.html index.php
3) Start Apache in XAMPP Control Panel (ensure it's on port 80).
4) Test static + PHP:
   http://localhost/231414358/
   http://localhost/231414358/dynamic.php

TOMCAT – STATIC + JSP
1) Copy the same '231414358' folder to C:\xampp\tomcat\webapps\ (or <TOMCAT_HOME>\webapps\)
2) Start Tomcat (port 8080). Wait for "Server startup in ..." in the console.
3) Test static + JSP:
   http://localhost:8080/231414358/
   http://localhost:8080/231414358/dynamic.jsp

NOTES
- Replace 'images/profile_placeholder.png' with your real photo (same name or update the <img src>).
- Audio autoplay may be blocked; click Play if needed.
- PHP runs under Apache; JSP runs under Tomcat. Static pages load on both.
