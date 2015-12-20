# Install_WebIOPi
How To Install WebIOPi

Install the webiopi in the raspberry pi, connect the pi to internet and following this line

    $ wget http://sourceforge.net/projects/webiopi/files/WebIOPi -0.7.1.tar.gz/
    $ wget https://www.dropbox.com/s/a8eao4m7krk5tmo/WebIOPi-0.7.1%20patc.tar.gz
    
where the webiopi is and using “wget” command i can download the tar.gz file, enter this command :

    $ tar xvzf WebIOPi-0.7.1.tar.gz
    $ tar xvzf WebIOPi-0.7.1 patc.tar.gz
    
 WebIOPi-0.7.1. u can see by entering command “ls -la" in your repository and following this command :
 
     $ cd WebIOPi-0.7.1
    
to install webiopi follow this command : 

     $ sudo ./setup.sh
     
after installing webiopi pi you need to start over local network :

    $ sudo webiopi -h 
    or 
    $ sudo /etc/init.d/webiopi start

to start webiopi over network write the below command :

    $ sudo webiopi -c config
    
it will create the server over the local network and you must open the GUI with Xming
download software Xming on windows to open the GUI and then you can open via chrome or ie
the assign ip address or web address will be shown after enterin above command :
note : localhost this your ip address and port this example running but you must check your ip

        localhost : 8000/webiopi/ or http://192.168.2.10:8000/webiopi/
        username  : webiopi
        password  : raspberry
        
note : if the some command error or corrupt maybe you can to copy the error command and paste to google

Refference : https://kushrami.wordpress.com/2015/02/02/tutorial-get-started-with-webiopi/ 
             http://webiopi.trouch.com/  
             http://syaefaanjar.blogspot.co.id/2015/05/menginstal-update-webopi-071-pada.html
