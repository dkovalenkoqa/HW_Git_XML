  # HW_Git_XML
  
  21. Создать внешний репозиторий c названием XML.
  22. Клонировать репозиторий XML на локальный компьютер.

      > git clone https://github.com/dkovalenkoqa/HW_Git_XML.git
  23. Внутри локального XML создать файл “new.xml”.
      > git touch new.xml
  24. Добавить файл под гит.
      > git add new.xml
  25. Закоммитить файл.
      > git commit -m "add new.xml"
  26. Отправить файл на внешний GitHub репозиторий.
      > git push
  27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
      ```
       <?xml version="1.0" encoding="windows-1251"?>
         <book category="WEB">
            <title lang="en">Learning XML</title>
            <name>Dima</name>
            <age>22</age>
            <pets>0</pets>
            <salary>5000$</salary>
         </book>
      ```
  28. Отправить изменения на внешний репозиторий.
       > git add new.xml

       > git commit -m "modify new.xml"

       > git push
  29. Создать файл preferences.xml
       > touch preferences.xml
  30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
       ```
       <?xml version="1.0" encoding="windows-1251"?>
          <book category="WEB">
             <title lang="en">Learning XML</title>
             <fav_movie>Interstellar</fav_movie>
             <fav_series>Game of Thrones</fav_series>
             <fav_food>Spaghetti</fav_food>
             <fav_season>Summer</fav_season>
             <country>Switzerland</country>
          </book>
       ```
  31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
       > touch skills.xml
       ```
       <?xml version="1.0" encoding="windows-1251"?>
          <book category="WEB">
             <title lang="en">Learning XML</title>
             <terminal>Terminal</terminal>
             <git_hub>Git Hub</git_hub>
             <postman>Postman</postman>
             <sql>SQL</sql>
             <jmeter>Jmeter</jmeter>
          </book>
       ```
  32. Сделать коммит в одну строку.
       > git add . && git commit -m "add preferences.xml skills.xml"
  33. Отправить сразу 2 файла на внешний репозиторий.
       > git push
  34. На веб интерфейсе создать файл bug_report.xml.
  35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
       ```
       <?xml version="1.0"?>
          <bug_reports>
              <email verbose="true" user_submission="true" />
              <json user_submission="false" directory="/tmp/reports/" />
              <sentry user_submission="false"/>
          </bug_reports>
       ```
  37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  38. Синхронизировать внешний и локальный репозиторий XML

       > git pull
