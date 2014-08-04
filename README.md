Tomcat7SSL
==========
How to set up your Tomcat 7 to use SSL.
- Copy .keystore to your home directory. In Windows it should be C:\Users\<your username>\.keystore In Linux it should be /home/<your username>/.keystore
- Copy server.xml to your Eclipse server directory. It should be in <your workspace>/Servers/Tomcat v7.0 Server at localhost-config
- Browse to http://localhost:8080/IT3191-2014S1-Grp2-Azure and it should redirect to https://localhost:8443/IT3191-2014S1-Grp2-Azure/ using secured SSL connection
