# HA-test-task
Тестовое задание HypeAuditor  
  
Ошибки возникали из-за неучтенных данных, таких как дата вылета, дата прилета и часовой пояс аэропорта.  
Для исправления ошибок был добавлен функционал для учета дат вылета и прилета и часовых поясов при расчете продолжительности полета.
Добавил новые и дописал существующие методы для получения необходимых данных о полетах и аэропортах из файлов json. Также добавил два метода для приведения полученных данных к нужному формату. Из даты формата '2022-01-11' получил день '11'. Из часовых поясов формата 'GM+03' получено '+03'. Далее дописал метод, который считает продолжительность полета, для того чтобы при расчете учитывались даты и часовые пояса.  
Также улучшил вывод информации в таблицу, для того чтобы были видны все значения из которых вычисляется продолжительность полета. Добавил часовые пояса к каждому аэропорту и два столбца в которых отображена дата вылета и дата прилета.
