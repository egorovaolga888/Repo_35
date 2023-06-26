# Repo_35 \
**GitHub. HW_2** 
1. На локальном репозитории сделать ветки для: 
- Postman 
- Jmeter 
- CheckLists 
- Bag Reports 
- SQL 
- Charles 
- Mobile testing \
  Создать репозиторий в гитхаб Repo_35 \
  Клонировать репозиторий в локальную папку \
  Создать любой файл на ветке main ( cat >> my_repo.txt) \
  git add . \
  git commit -m “...” \
  git push \
  git branch Postman \
  git branch BugReports \
  git branch Charles \
  git branch CheckLists \
  git branch Jmeter \
  git branch MobileTesting \
  git branch SQL 
2. Запушить все ветки на внешний репозиторий\
  git push origin –al (запушить ВСЕ ветки сразу)\
  git push origin branche_name - запушить одну конкретную ветку
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта\
  git checkout BugReports\
  vim BugReports.txt
4. Запушить структуру багрепорта на внешний репозиторий\
  git add .\
  git commit -m "add BugReports'structure"\
  git push --set-upstream origin BugReports  (настройка ветки для отслеживания)
5. Вмержить ветку Bag Reports в Main\
встать на ветку, в которую будем заливать изменения (main)\
  git checkout main\
  git merge BugReports
6. Запушить main на внешний репозиторий.\
  git push
7. В ветке CheckLists набросать структуру чек листа.\
  git checkout CheckLists\
  vim CheckLists_Structure.txt\
8. Запушить структуру на внешний репозиторий\
  git add .\
  git commit -m “text”\
  git push --set-upstream origin BugReports 
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main\
  Pull requests\
10. Синхронизировать Внешнюю и Локальную ветки Main\
  git pull
