grsu-wifi
=========

Как подключиться и как испльзовать

# Проблемы при работе с Git

* Проблема: подвисают команды связанные с получение данных через протокол git://
  * похоже на то, что университесткий WiFi блокирует git:// протокол
  * решение: git config --global url."https://".insteadOf git://
    * не для всего сработает, но для github работать будет
    * источник: http://stackoverflow.com/questions/4891527/git-protocol-blocked-by-company-how-can-i-get-around-that
