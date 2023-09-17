# Домашнее задание к занятию "`8.1. Git`" - `Нагорный Артем`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

## Задание 1. 
```
 1.Зарегистрируйте аккаунт на https://github.com/.
 2.Создайте публичный репозиторий. Обязательно поставьте галочку Initialize this repository with a README.
 3.Склонируйте репозиторий, используя https протокол (git clone ...).
 4.Перейдите в каталог с клоном репозитория.
 5.Произведите первоначальную настройку git, указав свое настоящее имя и email (git config --global user.name и git config --global user.email johndoe@example.com).
 6.Выполните команду git status и запомните результат.
 7.Отредактируйте файл README.md любым удобным способом, тем самым переведя файл в состояние Modified.
 8.Еще раз выполните git status и продолжайте проверять вывод этой команды после каждого последующего шага.
 9.Давайте теперь посмотрим изменения в файле README.md, выполнив команды git diff и git diff --staged.
 10.Переведите файл в состояние staged (или как говорят просто добавьте файл в коммит) командой git add README.md.
 11.И еще раз выполните команды git diff и git diff --staged.
 12.Теперь можно сделать коммит git commit -m 'First commit'.
 13.Сделайте git push origin master.

 В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением
```
Решение: [First Commit](https://github.com/netology-code/sys-pattern-homework/commit/a2ddb8c9638aec00c3b6655dc3bfd70faf1b3c94)
 

## Задание 2.
```
1.Создайте файл .gitignore (обратите внимание на точку в начале файла), проверьте его статус сразу после создания.
2.Добавьте файл .gitignore в следующий коммит (git add...).
3.Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4.Сделайте коммит и пуш.

 В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением
 ```
 Решение: [add gitignore](https://github.com/netology-code/sys-pattern-homework/commit/eed05ff8c49306118e104c99b52aa7695ac03c40)
## Задание 3.
```
1.Создайте новую ветку dev и переключитесь на нее.
2.Создайте файл test.sh с произвольным содержимым.
3.Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
4. Переключитесь на основную ветку.
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
6.Сделайте мердж данной ветки в основную (для начала необходимо переключиться на нее, и потом вызывать git merge).
7.Сделайте коммит и пуш.
8. Не удаляйте ветку dev.

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ВАШ_ЛОГИН/ВАШ_РЕПОЗИТОРИЙ/network в ваш md-файл с решением
```
Решение: [Add brach and test](https://github.com/InFallen/8-03-hw/network)
