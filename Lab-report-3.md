**I was struggling heavily with this lab, but I wanted to turn in
all if the stuff I was able to do. I apologize for the incomplete work**

# Streamlining ssh Congiguration
Streamlining ssh is pretty simple all you need is a config file with 
specific contents that allow you to make the signing in process seamless.
In the first screenshot is the contents of the .config file in the .ssh
directory. The second screenshot is what happens when you log in under
the alias that you provide. 

<img width="1440" alt="Screen Shot 2022-05-16 at 10 07 40 PM" src="https://user-images.githubusercontent.com/102937267/168742092-8b5a0649-3345-4b24-8e65-126f715eadba.png">


<img width="1440" alt="Screen Shot 2022-05-16 at 10 07 40 PM" src="https://user-images.githubusercontent.com/102937267/168742092-8b5a0649-3345-4b24-8e65-126f715eadba.png">
*under the contents of the congfig file is me logging into my remote account using the alias ieng6


# Setup Github Access from ieng6
In order to be able to allow access to github from ieng6, you must first 
store the public key that you have on your local machine on github.
The first screenshot shows the image of the key being saved on github.
Then you must put a private key on your user account so that you are 
allowed to have access on both github and your machine. The screenshot shows
the directory that contains the keys that are saved onto the remote machine.

<img width="1440" alt="Screen Shot 2022-05-16 at 10 24 33 PM" src="https://user-images.githubusercontent.com/102937267/168742581-d399d213-6126-4570-bf7e-78a493b95d52.png">



<img width="1440" alt="Screen Shot 2022-05-16 at 11 23 37 PM" src="https://user-images.githubusercontent.com/102937267/168742912-4be45057-0560-49e0-89e5-8c53c33f8c7f.png">


# Copy Whole directories with scp -r
scp is a command that allows you to safely copy directories and files
to remote machines. The first screenshot shows an example of using scp
to recursively copy files onto your remote machine from your public machine.

<img width="1440" alt="Screen Shot 2022-05-16 at 10 14 58 PM" src="https://user-images.githubusercontent.com/102937267/168743117-1a321373-2376-45db-8940-cbca2bbd9998.png">

