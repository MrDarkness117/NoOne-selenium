# NoOne-selenium
 Selenium framework for testing NoOne shop website

Чтобы использовать фреймворк:
- Установите [Веб-драйвер Chrome](https://chromedriver.chromium.org/downloads) (ChromeDriver 91.0.4472.101), укажите его в системе переменных окружения PATH в папке назначения веб-драйверов.
- Активируйте скрипт при помощи `~/venv/Scripts/activate` (MAC/Linux) `activate.bat` (Командная строка Windows cmd.exe) `./activate.ps1` (PowerShell, тоже Windows). Подробное описание ниже.

1. В Папке venv/Scripts содержатся вышеуказанные скрипты для активации - выбирайте под вашу систему.
2. Для Windows: внутри папки Scripts зажмите клавишу Shift и нажмите правой кнопкой мыши по окну папки, откройте либо командную строку, либо окно PowerShell.
3. Ввести команду в командной строке: `activate.bat` или в Powershell: `./activate.ps1` (возможно понадобится предоставить права администратора перед использованием), в самом начале строки слева должна появиться метка `(venv)`
4. Ввести команду в командной строке/Powershell: `cd ../../`
5. Ввести команду в командной строке/Powershell: `py footwear_filter_test.py` или `python footwear_filter_test.py`

**Примечание:** данная программа может неправильно работать, если всплывает окно с рекламой. Также, по желанию, можно использовать другой веб драйвер.

Тестирование:
- Google Docs: https://docs.google.com/document/d/1S9KE83Q2tKjrLHXBTfxH9xCiPyBuDRN1bAhepxTRPKE/edit?usp=sharing
- Qase: https://drive.google.com/file/d/1FzKcHFaCfFXy3IU5UUamj07EcPf5XunB/view?usp=sharing
