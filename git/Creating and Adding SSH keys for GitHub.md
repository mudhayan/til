# This is how to create an SSH key and add it to GitHub:

1. Create a public and private ssh key in `~/.ssh` by running: `ssh-keygen -t rsa -b 4096 -C "github_email_address"`
2. Run the following and verify that you receive "Agent PID ###": `eval "$(ssh-agent -s)"`
3. Add the identiy to your keychain by runing: `ssh-add ~/.ssh/name_of_your_private_key`
4. Add the public key to your clipboard by running: `pbcopy < ~/.ssh/id_rsa.pub`
5. Github > Settings > SSH and GPG Keys > New SSH Key > paste your key the in Key Field and add Title to identify device (i.e. Personal Computer, Work Computer, etc.) > Add SSH key
