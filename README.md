# Проект Шифрования и Дешифрования

## Описание

Этот проект предназначен для шифрования и дешифрования файлов. Он позволяет пользователю легко зашифровывать и расшифровывать текстовые данные.

## Структура проекта

```
project-root/
├── .venv/
├── encrypt/
│   ├── input.txt
└── decrypt/
```

## Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш_логин/ваш_репозиторий.git
   cd ваш_репозиторий
   ```

2. Создайте виртуальное окружение:
   ```bash
   python -m venv .venv
   ```

3. Активируйте виртуальное окружение:
   - Для Windows:
     ```bash
     .venv\Scripts\activate
     ```
   - Для MacOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

4. Установите необходимые зависимости:
   ```bash
   pip install -r requirements.txt
   ```

## Использование

### Создание папок

Создайте две папки: `encrypt` и `decrypt`, выполнив следующую команду:
```bash
mkdir encrypt decrypt
```

### Добавление файла

Поместите файл `input.txt` в папку `encrypt`:
```bash
echo "Ваш текст для шифрования" > encrypt/input.txt
```

### Шифрование и Дешифрование

Инструкции по шифрованию и дешифрованию файлов будут добавлены позже. Следите за обновлениями!

## Указания по игнорированию файлов

В проекте используется файл `.gitignore` для игнорирования временных файлов и папок. Убедитесь, что у вас есть следующие строки в вашем `.gitignore`:

```
/.venv
encrypt/*
decrypt/*
```

## Вклад

Если вы хотите внести свой вклад в проект, пожалуйста, создайте форк и отправьте пулл-реквест с описанием ваших изменений.

## Лицензия

Этот проект лицензирован под MIT License - подробности смотрите в файле [LICENSE](LICENSE).
