Building First app using Sencha
________________________________________________________________________________________________________________________

Prerequisite
 1. Start->run ->type java -version if it run then go to step 2 else download jdk (ver 1.7.0or 1.6.0 ) then again check java -version
 2. Download sencha-touch-2.3.1a-gpl and extract into a folder.
 3. Download Sencha Cmd and extract into a folder
 4. Download Ruby.
 5. Install Ruby.
 6. Install Sencha cmd check in command prompt type c:\>sencha (for successful installation)
 7. Start your web server. If using the Sencha Cmd web server,change directory to where you want to serve your application i.e. sencha-touch-2.3.1a-gpl\touch-2.3.1\.
 8. Open a new command line window and start the server with the"sencha web start" command. You can stop the server by typing CTRL+c oropening another command line and typing the "sencha web stop" command.
 9. You can access the Sencha Cmd web server using thehttp://localhost:1841/<app_name> URL.
 10. For more information about sencha: http://localhost:1841/SETUP.html
 ____________________________________________________________________________________________________________

If error occur during step 6 
Error type
 Error occured during installation of VM
 Could not reserve space for object heap
 Error : Could not create Java virtual Machine
 Error: A fatal exception occured program will exit.
 
Solution:
http://forum.unity3d.com/threads/88119-Could-not-reserve-enough-space-for-object-heap-RESOLVED

Anyway, here is how to fix it:Go to Start->Control Panel->System->Advanced(tab)->Environment Variables->System Variables->New:Variable name: _JAVA_OPTIONSVariable value: -Xmx512M

________________________________________________________________________________________________________________________

For building the first app follow the following link
1. http://docs.sencha.com/touch/2.0.2/#!/guide/getting_started
2. http://docs.sencha.com/touch/2.0.2/#!/guide/first_app

_________________________________________________________________________________________________________________________
