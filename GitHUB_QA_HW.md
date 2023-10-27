<p align="center"><img src="AliakseiKhamchanouski_Git.png"></p>

## GIT Homework 1

Все шаги сценария выполняются в GitBush Terminal, в папке под гитом.

#HW1  
>Ход выполнения задания XML ***[(link to XML)](https://github.com/ItGroupAlex/XML/blob/main/README.md "link")***  
>Ход выполнения задания JSON ***[(link to JSON)](https://github.com/ItGroupAlex/JSON/blob/main/README.md "link")***
>
#HW2  
>Ход выполнения задания по веткам ***[(link to Branches)](https://github.com/ItGroupAlex/TerminalLinux/blob/main/branches.md "link")***



 
# Доп.команды  

* *gitignore*  
`$ git cat > .gitignore` - добавление текстового файла со списком файлов и папок не подлежащих передаче на GitHUB  

* *reset*  
`$ git reset file1.txt` - исключить из отправленных в "add" (до commit)  

* *restore*  
`$ git restore file1.txt` - восстановить версию файла прошлого commit (до того как файл добавлен в add)  
`$ git restore --staged file1.txt` - -//- (после того как файл добавлен в add)   

* *commit (closed)*  
`$ git commit --amend -m "Комментарий"` - добавление доп.файлов в commit и/или изменение комментария  
`$ mkdir ../temp && mv file1.txt ../temp/file1.txt` -  удаление файлов из commit 

* *delete*  
`$ git push origin --delete New_branch` - удаление ветки "New_branch"  
  
* *fetch/merge/pull*  
`$ git fetch` - собирает все коммиты из целевой ветки, которых нет в текущей ветке, и сохраняет их в локальном репозитории. Однако он не сливает их в текущую ветку.   
`$ merge` - сливает эти коммиты в основную ветвь.   
`$ git pull` — это шоткод для последовательности двух команд: git fetch (получение изменений с сервера) и git merge (сливание в локальную копию).  

* *repository*  
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
EXAMPLE - название репозитория  
USER - ваш логин на гитхабе  
TOKEN - токен типа ghp_6QmGnnIlTmk5udc8YoVXCNENk1y0jwK32 сгенерированый в разделе https://github.com/settings/tokens  
