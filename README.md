# wordpress-droplet


## STEP 1. Create Droplet in Digital Ocean 

<img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-01%20at%206.22.53%20PM.png"/>

<img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-01%20at%206.23.16%20PM.png"/>

<img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-01%20at%206.23.28%20PM.png"/>

<img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-02%20at%2012.59.15%20PM.png"/>


  ### Generate ssh key 🔑 🔐 
  
  <img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-02%20at%2012.58.07%20PM.png"/>
  
  
  ### Open a terminal and run the following command:
        
         ssh-keygen
           
You will be prompted to save and name the key.

Generating public/private rsa key pair. Enter file in which to save the key (/Users/USER/.ssh/id_rsa):
       
Next you will be asked to create and confirm a passphrase for the key (highly recommended):
 
 
       Enter passphrase (empty for no passphrase):
       Enter same passphrase again:

    
This will generate two files, by default called id_rsa and id_rsa.pub. Next, add this public key.
    
   ### Copy and paste the contents of the .pub file, typically id_rsa.pub, into the SSH key content field on the left.
    
       cat ~/.ssh/id_rsa.pub

and then paste it and give some name to it.
  
<img src="https://github.com/harsh6768/wordpress-droplet/blob/main/Screenshots/Screenshot%202022-02-02%20at%2012.58.39%20PM.png"/>



