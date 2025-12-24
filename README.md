# git_homework_practice
Выполненные команды:

# Клонирование репозитория и добавление 6 файлов
git clone https://github.com/ВАШ_ЛОГИН/git_homework_practice.git
cd git_homework_practice
git add .
git commit -m "Add 3 HTML and 3 CSS files from previous homework"
git push origin main

# Создание веток
git checkout -b first_branch
echo "This is a text note from first_branch" > first_note.txt
git add first_note.txt
git commit -m "Add a text file to first_branch"
git push origin first_branch

git checkout main
git checkout -b second_branch
git add picture.jpg
git commit -m "Add a picture to second_branch"
git push origin second_branch
