# FutureSupplyAI

Этот проект на Django представляет собой систему для отслеживания флота беспилотных грузовиков, предназначенную для управления, мониторинга и оптимизации логистических операций в реальном времени. Разработанная система позволяет компаниям повысить эффективность доставки грузов, обеспечивая централизованный доступ к данным о местоположении грузовиков, их состоянии, а также планировании маршрутов и расписаний доставки.

## Начало работы

Эти инструкции помогут вам запустить копию проекта на вашем локальном компьютере для разработки и тестирования. Смотрите раздел о развертывании для получения информации о том, как развернуть проект в рабочей среде.

### Предварительные требования

Что необходимо установить на ваш компьютер для использования проекта:

- Python (3.6 или выше)
- pip (Python Package Installer)
- Git

### Установка

Шаг за шагом изложите процесс установки и запуска проекта.

## 1. Клонирование репозитория

   Откройте терминал и перейдите в каталог, где вы хотите разместить проект. Затем выполните следующую команду:
  ```
git clone https://github.com/JJNikJJ/futureSupply
  ```

##2. Настройка виртуального окружения

Перейдите в каталог проекта:

  ```
cd futureSupply
  ```

Перейдите в папку проекта:

  ```
cd futuresup
  ```

Создайте виртуальное окружение:

- На Linux или macOS:

  ```
  python3 -m venv venv
  ```

- На Windows:

  ```
  python -m venv venv
  ```

Активируйте виртуальное окружение:

- На Linux или macOS:

  ```
  source venv/bin/activate
  ```

- На Windows:

  ```
  venv\Scripts\activate
  ```

##3. Запуск сервера разработки

Запустите локальный сервер разработки:

  ```
python manage.py runserver
  ```

Теперь вы можете перейти по адресу `http://127.0.0.1:8000/` в вашем браузере, чтобы увидеть работающий проект.
