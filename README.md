# login_aws from mac by ssh

chmod 600 $HOME/.ssh/ ./gpu_processing_jimmy_server.pem  

chmod 700 $HOME/.ssh  


ssh -A -i ./gpu_processing_jimmy_server.pem ec2-user@public_IP



# terminate 
sudo halt


# other operation
https://chatbotslife.com/aws-setup-for-deep-learning-fda04db6df75
