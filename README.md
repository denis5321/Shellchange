# Shellchange
Shellchange - это утилита, которая можеть быстро сменить графическую оболочку без перезагрузки.
Она работает путём изменения ключа `HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Winlogon\Shell` на что-то другое.
![Ключ Shell в реестре](https://raw.githubusercontent.com/denis5321/Shellchange/main/shellreg.png)
Пока эта программа может только сменить оболочку на `cmd` (командную строку) и обратно.
Вот она в действии: *(извините за графические глюки, просто я это снимал и редактировал с ВМ)*
![Shellchange в действии](https://raw.githubusercontent.com/denis5321/Shellchange/main/shellchange_in_action.gif)
# Установка
Это очень просто. Скачайте [установщик](https://github.com/denis5321/Shellchange/releases/download/releases/ShellchangeInstaller.exe) и запустите его **от имени администратора!** И это все.

> ВАЖНО: Если вы уже устанавливали ShellChange, то установщик выдаст ошибку!
> Чтобы исправить это, **обязательно перед установкой проверяйте, что у вас нет shellchange.exe в папке Windows!**

# Использование
Запустить Shellchange **можно из любого места**, так как **он находится в папке Windows**.
Примеры:
`shellchange explorer` - немедленно сменить оболочку на проводник (`explorer`)(по умолчанию);
`shellchange cmd` - немедленно сменить оболочку на командную строку (`cmd`).
# Удаление
Необходимо сделать следующее:
 - [ ] Удалить `shellchange.exe` в папке Windows;
 - [ ] Удалить папку Shellchange в папке Windows.

