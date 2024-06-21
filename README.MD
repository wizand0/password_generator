# Password Generator
based on https://habr.com/ru/articles/689536/ and https://github.com/lesskop/password-generator

Cross-platform GUI password generator written in Python


## Resources:
pyside6-rcc ui/resources.qrc -o ui/resources.py
pyside6-uic ui/main.ui -o ui/ui_main.py

## Build:
nuitka --onefile --follow-imports --enable-plugin=pyside6 --windows-disable-console --windows-icon-from-ico=ui\icons\key_48dp.ico --remove-output -o password-generator.exe app.py


## TODO:
Password keeper ui;
DB;
cryptography;
