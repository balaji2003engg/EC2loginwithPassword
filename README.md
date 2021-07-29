# EC2loginwithPassword

1.cd /etc/ssh/sshd_config


2.remove # from below line
PasswordAuthentication yes

3. Provide password to the ec2-user
   passwd ec2-user

4.  Restart the sshd

systemctl stop sshd
systemctl start sshd

5.Create the password to the ec2-user using below command

passwd ec2-user

6. Login with ec2-user and password with out pem file.

