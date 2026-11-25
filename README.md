# Devops-P03

Практическая работа №3. Git.

Hello, Local and Remote Worlds!

Main branch changes
New feature

Практическая работа №3. Git
Цель работы: изучение системы контроля версий Git, работа с локальными и удалёнными репозиториями, ветками и конфликтами слияния.

Ход выполнения работы

1. Установила Git в Ubuntu, настроила имя пользователя и электронную почту. Создала локальный репозиторий devops_lab3, файл README.md и выполнила первый коммит.

Сгенерировала SSH-ключ с помощью команды ssh-keygen и добавила его в настройки GitHub.

<img width="1425" height="432" alt="image" src="https://github.com/user-attachments/assets/7dc71ef6-c058-4739-ad69-749dc815674f" />

2. Проверила подключение к GitHub командой ssh -T git@github.com. Аутентификация прошла успешно.

<img width="991" height="180" alt="image" src="https://github.com/user-attachments/assets/dba72f75-1d1c-4f72-842f-c97abc250bce" />

3. Создала удаленный репозиторий Devops--03, связала его с локальным репозиторием и отправила изменения командой git push.

<img width="1002" height="250" alt="image" src="https://github.com/user-attachments/assets/5ad834e0-7e20-488c-9235-55bca5f2e124" />

4. Внесла различные изменения в локальный и удалённый файлы README.md. При выполнении команды git pull возник конфликт слияния.

<img width="939" height="577" alt="image" src="https://github.com/user-attachments/assets/59b0d3c3-5337-4ff4-99cb-abdbb7678e30" />

5. Открыла файл README.md в редакторе nano для просмотра конфликтующих изменений.

<img width="754" height="186" alt="image" src="https://github.com/user-attachments/assets/1933dacb-1f47-44a6-b289-7b4a8aea2737" />

6. Объединила изменения, удалила маркеры конфликта, выполнила коммит и отправила результат на GitHub.

<img width="758" height="404" alt="image" src="https://github.com/user-attachments/assets/42d4d8d3-eac4-4c37-a532-54d00b7aa1d8" />

7. Создала новую ветку FEAT-123, внесла изменения в README.md и отправила ветку в удалённый репозиторий.

<img width="757" height="599" alt="image" src="https://github.com/user-attachments/assets/6cdf0f2d-4290-4dab-913a-eb7c6ee1af71" />


8. Переключилась на ветку main, внесла изменения и выполнила слияние с веткой FEAT-123. В результате возник конфликт между локальными ветками.

<img width="756" height="578" alt="image" src="https://github.com/user-attachments/assets/16aaf8b0-82a8-4641-8961-355b40d61508" />

9. Разрешила конфликт, отправила изменения на GitHub и просмотрела историю коммитов командой git log --oneline --graph --all.

<img width="760" height="270" alt="image" src="https://github.com/user-attachments/assets/0b598fc5-1aa0-45a5-9117-95838fc655af" />

10. Клонировала удалённый репозиторий командой git clone. Проверила содержимое файла README.md и список доступных веток.

<img width="955" height="533" alt="image" src="https://github.com/user-attachments/assets/ea23cfc8-a5e4-4592-bce2-1377c45b2b13" />

Ссылка на репозиторий: https://github.com/dusya-tolstik-13/Devops--03

Вывод: в ходе практической работы освоила основные команды Git, научилась работать с локальными и удаленными репозиториями, создавать ветки, выполнять слияние и разрешать конфликты.
