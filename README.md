# 2019-2-18


GitHub SSH Key Cheat Sheet:

1. Create ssh key by running: 

`ssh-keygen -t rsa -b 4096 -C "github_email_address"`

This creates a public key and private key in ~/.ssh

2. Run the following and verify that you receive "Agent PID ###"

eval "$(ssh-agent -s)"

3. 



