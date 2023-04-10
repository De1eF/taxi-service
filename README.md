# 🚖taxi-service🚖
A simple and light web aplication for tracking your taxi service business <br>
by interacting with local or remote MY SQL database through <br>
web browser from any device with internet connection <br>
<h2 tabindex="-1">﻿🛠️Functionality🛠️</h2>
 <ul dir="auto">
  <li>Applying CRUD operations to car manufacturers</li>
  <li>Applying CRUD operations to cars</li>
  <li>Applying CRUD operations to car drivers</li>
  <li>Connecting drivers to specific cars</li>
 </ul>
  <h2 tabindex="-1">﻿🔒Security🔒</h2>
 The service has a protection system <br>
 Only authenticated users will have acsess to the functionality
  <h2 tabindex="-1">﻿⚙️Used tech⚙️</h2>
The service is powered by APACHE TOMCAT (v9.0.73) <br> 
and uses JAVAX Servlet API (v4.0.1) together with <br>
My SQL (v8.0.24) relational database connected via JDBC (v4.2)
  <h2 tabindex="-1">﻿🎯Initialization🎯</h2>
 In order to start using taxi service, user will need to go throgh a few steps first
 in MY SQL WORKBENCH.
 <ul dir="auto">
  <li>install <b>MY SQL</b> and configure connection</li>
  <li>Go to <b>/taxi/util/ConnectionUtil.java</b>, and fill all the String constants</li>
  <li>Execute SQL query given in <b>/resources/init-db.sql</b> in MY SQL</li>
  <li>Configure Tomcat</li>
  <li>Start the APP and enjoy</li>
 </ul>
   <h2 tabindex="-1">﻿📡Structure📡</h2>
 <ul dir="auto">
  <li><b>/login</b> user authentication page, they will be redirected here unless authorized</li>
  <li><b>/drivers/add</b> user/driver creation page, new users may register here</li>
  <li><b>/index</b> home page, navigate to any point of the app with this</li>
 </ul>
 
