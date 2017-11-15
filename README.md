# sudrf

Пробиватель ФИО в ГАС РФ "Правосудие"

### Настройка локальной машины для запуска скрипта
 
 * Установить Firefox
 * Установить [Python 3](https://www.python.org/downloads/release/python-342/)
 * Прописать в переменную окружения PATH к установленному каталогу с python.exe (по умолчанию это C:\Python34\) и добавить путь к C:\Python34\Scripts
 * Установить [git-клиента](https://git-scm.com/downloads)
 * Запустить консоль git
 * Клонировать репозиторий себе на локальную машину
    ```bash
    git clone https://github.com/efpato/sudrf.git
    ```
 * Перейти в склонированный каталог и выполнить:
    ```bash
    cd sudrf
    pip install -r requirements.txt
    ```

### Использование

```bash
python fetch "Петров Петр Иванович"
```
На выходе получаем Excel-файл "Петров Петр Иванович.xlsx"
