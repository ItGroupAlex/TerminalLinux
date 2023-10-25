## GIT Homework 1

Все шаги сценария выполняются в терминале GitBush, Terminal, в папке под гитом.

>Ход выполнения задания XML ***[(link to XML)](https://github.com/ItGroupAlex/XML/blob/main/README.md "link")***  
>Ход выполнения задания JSON ***[(link to JSON)](https://github.com/ItGroupAlex/JSON/blob/main/README.md "link")***  


 
# Доп.команды  

`$ git reset file1.txt` - исключить из отправленных в "add" (до commit)  
`$ git cat > .gitignore` - добавление текстового файла со списком файлов не подлежащих передаче на GitHUB  
`$ git commit --amend -m "Комментарий"` - добавление доп.файлов в commit и изменение комментария  
`$ mv file.txt ../file.txt` - убрать файл из commit  
`$ git restore file1.txt` - восстановить версию файла прошлого commit (до того как файл добавлен в add)  
`$ git restore --staged file1.txt` - удаление файла из commit  
`$ rm -rf ../clone_dir` - удалить папку локально склонированного депозитория     
`$ git push origin --delete New_branch` - удаление ветки "New_branch"  
