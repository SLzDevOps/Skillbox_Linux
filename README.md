# Skillbox-Linux  Анатолий Фомичев

### Скриншот настроек VirtualBox.


![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот развёрнутой ОС.
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот команд, с помощью которых устанавливали обновления.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот с созданными пользователями.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  


### Скриншот или файл с выводом команды ipconfig.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот или файл с выводом команды traceroute или ping при проверке доступности сервера с компьютера.


![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  


### Скриншот вывода команды ping yandex.ru.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот вывода команды cat ~/.ssh/id_rsa.pub.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот успешного подключения по SSH.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).   
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Вывод результата выполнения команды systemctl в виде файла или скриншота.  

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  


### Скриншот конфигурационных настроек apache с настройками SSL.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот добавленного разрешающего правила по 443 порту в iptables.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот с результатами подключения четырёх дополнительных модулей для apache.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот открытого дефолтного сайта на localhost или 127.0.0.1 через браузер на виртуальной машине, открытый по порту 443.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).   
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  

### Скриншот запущенного сайта на php.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).   
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).   

### Требования к длине пароля. Настроена парольная политика. Скриншот ответа при попытке ввода неподходящего по политике пароля.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_622.png).  


### Инструкция по установке безопасного пароля.

=== ПОЛИТИКА БЕЗОПАСНЫХ ПАРОЛЕЙ ===

Требования к паролю:
a) Длина пароля: минимум 12 символов
b) Использование спецсимволов: минимум 2 символа (!@#$%^&*()_+-=)
c) Использование заглавных букв: минимум 1 буква
d) Использование цифр: минимум 1 цифра
e) Использование строчных букв: минимум 1 буква
f) НЕ использовать: 
   - Личную информацию (имя, дата рождения)
   - Последовательности (123456, qwerty)
   - Повторяющиеся символы (aaa111)
   - Слова из словаря

Примеры надежных паролей:
- C0mpl3x!P@ssw0rd#
- S3cur!tyR0ck$2024
- M@st3rK3y!L0ngP@ss

Инструкция создания случайного пароля:
1. Используйте генератор паролей: pwgen -s 16 1
2. Или командой: openssl rand -base64 12
3. Используйте менеджер паролей: KeePass, LastPass

Проверка сложности пароля:
echo "ваш_пароль" | cracklib-check

Срок действия пароля: 90 дней
История паролей: 5 последних паролей нельзя повторять
Блокировка после 5 неудачных попыток: 15 минут


![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).   

###  Скриншоты, подтверждающие выполнение обязательных пунктов.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).    
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  


### Скриншоты и описание, подтверждающие пять дополнительных настроек безопасности Linux.

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).    
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).   


### Документ с описанием вероятных сценариев отказа и ваших действий при них.

  
a) Внутренние угрозы  
Сценарий 1: Непреднамеренная ошибка администратора   
Описание: Удаление критичных файлов конфигурации (/etc/apache2/, /etc/ssh/), неправильная настройка правил iptables, блокирующая легитимный трафик   
Вероятность: Высокая (особенно при работе новичков)   
Пример: sudo rm -rf /etc/apache2/sites-available/*    
  
Сценарий 2: Компрометация учетной записи пользователя   
Описание: Кража SSH-ключей или паролей, внедрение вредоносного кода через загруженные файлы   
Вероятность: Средняя   
Пример: Слабая политика паролей для пользователя webuser      
  
Сценарий 3: Исчерпание ресурсов  
Описание: Переполнение диска логами, DoS-атака fork-бомбой, утечка памяти в PHP-скриптах  
Вероятность: Средняя   
Пример: :(){ :|:& };: (fork-бомба в bash)    
  

b) Внешние угрозы
Сценарий 1: Брутфорс-атака на SSH  
Описание: Автоматический подбор паролей к SSH (порт 22)  
Вероятность: Очень высокая  
Источник: Ботнеты, сканеры Shodan   
  
Сценарий 2: Эксплойты веб-приложения  
Описание: Использование уязвимостей в PHP-коде, SQL-инъекции, XSS  
Вероятность: Высокая  
Пример: Уязвимый код $_GET['id'] без валидации  
  
Сценарий 3: DDoS-атака  
Описание: Нагрузка на порты 80/443, исчерпание сетевых ресурсов  
Вероятность: Средняя   
Тип: SYN-flood, HTTP-flood    

c) Последствия отказа системы  
Сценарий	                  Время простоя                	Финансовые потери          	Репутационные потери	             Сложность восстановления  
Удаление конфигов	            1-4 часа	                    Средние	                      Средние	                         Низкая (есть бэкапы)  
Взлом SSH	                    2-8 часов	                    Высокие	                      Высокие	                             Средняя  
DDoS-атака                    1-24 часа	                 Зависит от бизнеса	              Высокие	                             Низкая  
Переполнение диска	          0.5-2 часа	                  Низкие	                      Низкие	                             Низкая   
Эксплойт веб-приложения     	4-48 часов	                Критичные	                    Критичные                              Высокая  




![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  

### Скриншот, показывающий рабочий процесс резервного копирования.


![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).   
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  


### Скриншот, показывающий успешное чтение и настройку ротации

![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  
![alt text](https://github.com/SLzDevOps/Skillbox_Linux/blob/main/Pictures/Screenshot_680.png).  


