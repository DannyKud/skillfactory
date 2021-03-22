git branch 17-3-homework - создаю новую ветку 17-3-homework
git checkout 17-3-homework - переключаюсь на ветку 17-3-homework
vim README.md - отредактировал файл README.md
vim INFO.md - отредактировал файл INFO.md
git add . - добавил все изменения в репозиторий
git branch 15-4-feature-1, 15-4-feature-2, 15-4-feature-3 - создал три новые ветки

git checkout 15-4-feature-1 - переключился на ветку 1
vim file-feature-2.txt - сделал изменения в первой строке файла file-feature-2.txt
git add file-feature-2.txt -добавил файл file-feature-2.txt в репозиторий ветки 1
git commit - зафиксировал.



git checkout 15-4-feature-2 - переключился на ветку 2
vim file-feature-2.txt - изменил первую строку файла file-feature-2.txt во 2 ветке
git add file-feature-2.txt и git commit - зафиксировал


git checkout 15-4-feature-3 - переключился на 3 ветку
vim file-feature-2.txt - редактирую 2-й абзац файла vim file-feature-2.txt
git add file-feature-2.txt и git commit - зафиксировал

git checkout main - переключаюсь на ветку main
vim file-feature-2 редактирую файл file-feature-2, добавляю
 новый текст перед 1-м абзацем, а второй абзац удаляю.
git add file-feature-2.txt и  git commit - зафиксировал изменения

git push origin 15-4-feature-1
git push origin 15-4-feature-2
git push origin 15-4-feature-3 
git push origin main - отправил все 4 ветки на сервер Github


