### Installing Terraform

- In the AWS Console, in the top search bar enter cloudshell, then click CloudShell.

Also close any pop-ups.

- In the CloudShell, click Close on the pop-up. (You can close other pop-ups too.)

- Run the following commands at the command prompt to install Terraform:



```bash
git clone https://github.com/tfutils/tfenv.git ~/.tfenv
mkdir ~/bin
ln -s ~/.tfenv/bin/* ~/bin/
tfenv install 1.2.5
tfenv use 1.2.5
terraform --version


You will see in one of the last lines of output Installation of terraform v1.2.5 successful.
