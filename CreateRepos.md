```
$ mkdir EXAMPLE   
$ cd EXAMPLE  
$ git init   
$ echo "This repos. was created remotely" >> README.md  
$ git add .  
$ git commit -m "repos. created"  
$ git remote add origin git@github.com:USER/EXAMPLE.git  
$ curl -u 'USER:TOKEN' https://api.github.com/user/repos -d '{"name":"EXAMPLE"}'  
$ git push -u origin master
```


* EXAMPLE - название репозитория  
* USER - ваш логин на гитхабе  
* TOKEN - токен типа ghp_6QmGnnIlTmk5udc8Yoe7VXCNENki1y0jwK32 сгенерированый в разделе https://github.com/settings/tokens  
