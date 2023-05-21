# GITHUB
This repository is for the practice of creating branches, merging branches.
***1. Создал репозиторий на GitHub с названием `GITHUB`:**
> `Repositories -> New`
3. `git clone https://github.com/Evgenii180192/GITHUB.git`
4. На локальном репозитории сделать ветки для:- Postman - Jmeter - CheckLists - Bag Reports - SQL - Charles - Mobile testing - `git branch name_branch`
5. Запушить все ветки на внешний репозиторий - `git push origin name_branch ........`
6. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - `git checkout Bag_Reports -> touch bag_report.txt -> nano bag_report.txt`
7. Запушить структуру багрепорта на внешний репозиторий - `git push origin Bag_Reports`
8. Вмержить ветку Bag Reports в Main - `git checkout main -> git merge Bag_Reports`
9. В ветке CheckLists набросать структуру чек листа - `git checkout CheckLists -> touch checklist.txt -> nano checklist.txt`
10. Запушить структуру на внешний репозиторий - `git push origin CheckLists`
11. На внешнем репозитории сделать Pull Request ветки CheckLists в main - `Compare & pull reuest -> Create pull request`
12. Синхронизировать Внешнюю и Локальную ветки Main - `git pull`
