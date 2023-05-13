# YandexPracticum_auto_workflow
Bash script to autocreate workflow files. Based on Yandex.Practicum tutorial.

github_actions.sh is the only file and command you'll need to create workflow.
![The only command you'll need](https://github.com/sergey-samoylov/YandexPracticum_auto_workflow/blob/main/img/gitactions_YandexPracticum_1.png)

- It creates all the directories and all the files you'll need.
  - mkdir -p .github/workflows
  - touch .github/workflows/main.yml
  - writes all necessary content to it
  - creates setup.cfg  and include exceptions for flake8 checks into it
 
![The only command you'll need](https://github.com/sergey-samoylov/YandexPracticum_auto_workflow/blob/main/img/gitactions_YandexPracticum_2.png)

- Finally it pushes all your project files to GitHub
  - Actions will autostart
  - If there are any mistakes in your code, you'll see them right away
  - Feel free to modify this script to your needs and liking

![The only command you'll need](https://github.com/sergey-samoylov/YandexPracticum_auto_workflow/blob/main/img/gitactions_YandexPracticum_3a.png)


### Spend more time to create something useful and beautiful! 
 
Don't waste your energy on boring repetitive tasks. They are to be automated.
