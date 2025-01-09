# Multifunctional telegram-bot

Этот бот, написанный на Python с использованием библиотеки `telebot`, позволяет пользователям преобразовывать изображения в два различных стиля: пиксельную графику и ASCII-арт.

## Возможности

-   **Преобразование в пиксельную графику:** Пользователь отправляет изображение, и бот уменьшает его размер, создавая эффект пикселизации.
-   **Преобразование в ASCII-арт:** Пользователь отправляет изображение, и бот создает текстовое представление изображения с использованием символов ASCII.
-   **Простой интерфейс:** Бот взаимодействует с пользователем через команды и кнопки.

## Как использовать

1.  **Запустите бота** в Telegram.
2.  **Отправьте изображение** боту.
3.  Бот предложит вам на выбор три варианта преобразования:
    -   **Пиксельная графика**
    -   **ASCII-арт**
    -   **Пользовательский ASCII-арт**
4.  **Выберите нужный вариант**, нажав соответствующую кнопку.
5.  **Получите результат:** Бот отправит вам преобразованное изображение или текст.

## Требования

-   Python 3.6 или выше
-   Установленные библиотеки:
    -   `pyTelegramBotAPI`
    -   `Pillow` (PIL)
  
    Установите их с помощью pip:
    ```bash
    pip install pyTelegramBotAPI Pillow
    ```

## Запуск бота

1.  **Получите токен бота:** Создайте нового бота в Telegram через @BotFather и скопируйте его токен.
2.  **Клонируйте репозиторий:**

    ```bash
    git clone https://github.com/miwkom/Multifunctional_telegram-bot
    cd <папка_с_проектом>
    ```
3.  **Установите зависимости:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Настройте бота:**
    -   Откройте файл с кодом бота (например, `bot.py`) и замените `<YOUR_BOT_TOKEN>` на свой токен бота.
5.  **Запустите бота:**

    ```bash
    python bot.py
    ```

## Примечания

-   Возможны некоторые ограничения на размер и формат изображений.
-   Качество ASCII-арта может зависеть от исходного изображения.
