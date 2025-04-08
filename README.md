Описание проекта:
Проект api_yatube - это API социальной сети yatube.
Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
 
git clone https://github.com/MoVa53/api_final_yatube2.git
cd api_final_yatube
Cоздать и активировать виртуальное окружение:
 
python3 -m venv venv
source venv/Scripts/activate
Установить зависимости из файла requirements.txt:
 
python3 -m pip install --upgrade pip
pip install -r requirements.txt
Выполнить миграции:
 
python3 manage.py migrate
Запустить проект:
 
python3 manage.py runserver
 
Примеры запросов к API:
Получить определенный пост (GET):
 
http://127.0.0.1:8000/api/v1/posts/1/
Получить коментарии определенного поста (GET):
 
http://127.0.0.1:8000/api/v1/posts/1/comments/
