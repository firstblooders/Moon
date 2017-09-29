git   
openssh/ssh  
ssh-keygen -t rsa -C "example@example.com"  
.ssh/id_rsa.pub  
mkdir example  
cd example    
git init  
git remote add example.git  
git config --global user.name "example"  
git config --global user.email "example@email.com"
git add .  
git commit -m 'example'  
git push -u origin master  
git pull  
git status  
  
  
git add .  
git commit -m 'info'  
git push  
