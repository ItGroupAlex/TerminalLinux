## GIT Homework 1

Все шаги сценария выполняются в терминале GitBush, Terminal, в папке под гитом.

>Ход выполнения задания XML ***[(link to XML)](https://github.com/ItGroupAlex/XML/blob/main/README.md "link")***  
>Ход выполнения задания JSON ***[(link to JSON)](https://github.com/ItGroupAlex/JSON/blob/main/README.md "link")***  


 
# Доп.команды  

*gitignore*  
`$ git cat > .gitignore` - добавление текстового файла со списком файлов и папок не подлежащих передаче на GitHUB  

*reset*  
`$ git reset file1.txt` - исключить из отправленных в "add" (до commit)  

*restore*  
`$ git restore file1.txt` - восстановить версию файла прошлого commit (до того как файл добавлен в add)  
`$ git restore --staged file1.txt` - -//- (после того как файл добавлен в add)   

*commit (closed)*  
`$ git commit --amend -m "Комментарий"` - добавление доп.файлов в commit и/или изменение комментария  
`$ mkdir ../temp && mv file1.txt ../temp/file1.txt` -  удаление файлов из commit 

*delete*  
`$ git push origin --delete New_branch` - удаление ветки "New_branch"  
