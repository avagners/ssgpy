# ssgpy

**ssgpy** - генератор статических сайтов. Преобразует **markdown** в **html**.

### Технологии
- Jinja2
- markdown2

## Запуск генератора
1) Клонировать репозиторий и перейти в него в командной строке:

        git clone git@github.com:avagners/ssgpy.git
        cd ssgpy

2) Cоздать и активировать виртуальное окружение:

        python3 -m venv venv
        source venv/bin/activate

3) Установить зависимости из файла requirements.txt:

        python3 -m pip install --upgrade pip
        pip install -r requirements.txt

4) Запустить файл **main.py**

5) В директории **ssgpy/public** появятся готовые страницы html.