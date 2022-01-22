# HM_GitHub_Branch
1. На локальном репозитории сделать ветки для: git brach Postman
- Postman git brach Postman
- Jmeter git brach Jmeter
- CheckLists git brach Checklists
- Bag Reports git brach Bug_reports
- SQL git brach SQL
- Charles git brach Charles
- Mobile testing git brach Mobile_testing

2. Запушить все ветки на внешний репозиторий  git push origin --all
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  git checkout Bug_reports >
vim bug_reports.txt
4. Запушить структуру багрепорта на внешний репозиторий  git add bug_reports.txt >  git commit -m "add file"
git push > git push --set-upstream origin Bug_reportsпше
5. Вмержить ветку Bag Reports в Main ### git checkout main > git merge Bug_reports
6. Запушить main на внешний репозиторий. git push 
7. В ветке CheckLists набросать структуру чек листа. git checkout CheckLists > vim checklist.txt
8. Запушить структуру на внешний репозиторий git add checklist.txt > git commit -m "add checklist" > git push > git push --set-upstream origin CheckLists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main ### на внешнем репозитории нажать вверху pull reques > git fetch
10. Синхроннешнюю и Локальную ветки Main git pull
