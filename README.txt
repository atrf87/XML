
21. Создать внешний репозиторий c названием XML.
22. Клонировать репозиторий XML на локальный компьютер.
    cd xml
    git clone https://github.com/atrf87/XML.git
23. Внутри локального XML создать файл “new.xml”.
    cat > new.xml
24. Добавить файл под гит.
    Git add new.xml
25. Закоммитить файл.
    Git commit -m "create file xml"
26. Отправить файл на внешний GitHub репозиторий.
    Git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе. Всё написать в формате XML.
    vi new.xml
    <info>
           <name>Trofimov Andrei</name>
           <age>35 years</age>
           <pet> no </pet>
           <quantity> 0 </quantity>
           <salary> 2000$</salary>
    </info>
28. Отправить изменения на внешний репозиторий.
    Git add .
    git commit -m "info xml"
    git push
29. Создать файл preferences.xml
    cat > preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
    vi preferences.xml
31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
    cat > sklls.xml
32. Сделать коммит в одну строку.
    git add .
    git commit -m "xml files"
33. Отправить сразу 2 файла на внешний репозиторий.
    Git push
34. На веб интерфейсе создать файл bug_report.xml.
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
38. Синхронизировать внешний и локальный репозиторий XML
    git pull
