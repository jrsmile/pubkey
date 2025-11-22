ssh-copy-id -i /home/user/.ssh/id_ed25519_sk.pub servername  
ssh -o IdentityAgent=none -i /home/user/.ssh/id_ed25519_sk servername
