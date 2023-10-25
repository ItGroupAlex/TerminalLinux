1. На локальном репозитории сделать ветки:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

 `$ git clone git@github.com:ItGroupAlex/Branches.git` - clone repos.  
 `$ git branch Postman` - create branch Postman   
 `$ git branch Jmeter` - create branch Jmeter   
 `$ git branch CheckLists` - create branch CheckLists   
 `$ git branch BagReports` - create branch BagReports   
 `$ git branch SQL` - create branch SQL   
 `$ git branch Charles` - create branch Charles   
 `$ git branch MobileTesting` - create branch MobileTesting   

2. Запушить все ветки на внешний репозиторий

`$ git push -u origin Postman`  
`$ git push -u origin Jmeter`  
`$ git push -u origin CheckLists`  
`$ git push -u origin BagReports`  
`$ git push -u origin SQL`  
`$ git push -u origin Charles`  
`$ git push -u origin MobileTesting`  

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

`$ git checkout bagreports` - move to branch "BagReports"  
`$ touch bug_report.json` - create file  
`$ vim bug_report.json`   - redact file  

4. Запушить структуру багрепорта на внешний репозиторий

`$ git add .`  
`$ git commit -m "Create json"`  
`$ git push`

5. Вмержить ветку Bag Reports в Main 
 
`$ git checkout master`  
`$ git merge bagReports`  

6. Запушить main на внешний репозиторий.

`$ git add .`  
`$ git commit -m "merge with bagreport json"`  
`$ git push`  

7. В ветке CheckLists набросать структуру чек листа.

`$ git checkout CheckLists` - move to branch "CheckLists"  
`$ touch check_list.json` - create file  
`$ vim check_list.json`   - redact file 

8. Запушить структуру на внешний репозиторий

`$ git add .`  
`$ git commit -m "Create json"`  
`$ git push`

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  

- Переходим на внешний репозиторий GitHUB "Branches" и нажимаем Pull Request  
- Принимаем измения добавив commit  

10. Синхронизировать Внешнюю и Локальную ветки Main

 `$ git clone git@github.com:ItGroupAlex/Branches.git`



