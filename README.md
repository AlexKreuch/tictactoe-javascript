created AWS account

created : EC2 t2.micro instance (ubuntu 16.04) (free-tier)  ( downloaded pem-file )

used ssh to log onto the system via the command : <br/>
&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;ssh -i "ec2Instances000.pem" ubuntu@ec2-35-161-140-144.us-west-2.compute.amazonaws.com

installed nginx on the virtual machine

replaced default nginx.html file with my javascript program

Now when you navigate to my virtual machine public IP address from a browser, 
the nginx server will send the the default webpage containing my javascript game.
