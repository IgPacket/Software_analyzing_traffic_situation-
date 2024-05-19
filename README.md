# Software_analyzing_traffic_situation
Приложение предназначено для вывода рекомендаций и предупреждений при управлении транспортным средством. Может применяться водителями и обучающимися, занимающимися управлением или обучением управлению транспортного средством. 

# Установка
Для развертывания приложения необходимо:
  1) Прописать путь в Golang сервере (sppr/main.go) к example.jar файлу - это главный "обработчик программы"
  2) Необходимо запустить Golang сервер командой go run main.go
  3) Необходимо разахривировать SPPR_EXE.rar - в нём находится unity-клиент, необходимый для визуального отображения программы
  4) Запустить SPPR.exe

# Горячие клавиши
  * Space - Смена дорожного знака
  * Enter - Обработка знака, анализ ситуации и вывод информации на экран
  * Enter - Если обработка знака только что была, то эта клавиша приведет к возвращению к виду сверху   
