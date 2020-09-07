# django-orm-watching-storage
 
## Описание проекта.   
Это внутренний репозиторий банка <<Синяние>>. Если вы попали в репозиторий случайно, то не сможете его запустить, т.к у вас нет доступа к БД, но сможете использовать свободно код вёрстки или посмотреть как реализованы запросы к БД.
    
## Подготовка к запуску(Mac OS, Linux).  
Уставновить Python 3+.
```
sudo apt-get install python3
```
Установить, создать и активировать виртуальное окружение.
```
pip3 install virtualenv
python3 -m venv env
source env/bin/activate
```
Установить библиотеки командой.  
```
pip3 install -r requirements.txt  
``` 
Создайте файл ".env" в него надо прописать ваши token'ы.   
В переменную **DEBUG** записываем True.   
В переменную **PASSWORD** записываем пароль от БД.   
В переменную **HOST** указываем url адрес хоста.    
В переменную **SECRET_KEY** секретный ключ.
    
```
DEBUG=True
PASSWORD=odsgsgsa23415
HOST=dvmn.org
SECRET_KEY=dgdsfjsldfs```    

## Запуск кода.  
```
python3 manage.py
```
    
