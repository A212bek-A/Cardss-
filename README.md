# Карточки: как собрать APK через GitHub

1. Зайди на github.com и войди в аккаунт (или зарегистрируйся).
2. Нажми "+" вверху, затем New repository. Имя, например, kartochki. Нажми Create repository.
3. На странице репозитория нажми "uploading an existing file".
4. Перетащи в окно ВСЁ содержимое распакованной папки (папки www, assets, .github и файлы package.json, capacitor.config.json, .gitignore). Не сам zip.
5. Нажми Commit changes.
6. Открой вкладку Actions. Если попросит, нажми "I understand my workflows, go ahead and enable them".
7. Сборка стартует сама, 3-6 минут. Если не стартовала: Build APK, затем Run workflow.
8. Когда появится зелёная галочка, открой этот запуск. Внизу в Artifacts скачай kartochki-apk.
9. Распакуй скачанный zip, внутри app-debug.apk. Перекинь на Android и установи (разреши установку из неизвестных источников).
10. При первом запуске разреши уведомления.

Если красный крестик: открой упавший шаг, скопируй текст ошибки.
