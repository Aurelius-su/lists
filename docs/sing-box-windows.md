# Windows

## Установка sing-box

1. Из письма скопируйте команду:

   > powershell -nop -ExecutionPolicy Bypass -c "Invoke-Command -ScriptBlock ([scriptblock]::Create([System.Text.Encoding]::UTF8.GetString((new-object system.net.WebClient).DownloadData('<https://gist.githubusercontent.com/Aurelius-su/ea4ffaafecd0fd0944f067230b9af7ab/raw/SetupVPN.ps1>')))) -ArgumentList @('sing-box', 't8...Y')"

1. Запустить окно командной строки (CMD) от [**имени администратора;**](https://dzen.ru/a/Y2zG2grUMBZPYslS)
1. Втавьте команду в окно CMD и нажмите \<Enter\>.

На экран выйдет лог установки. Если призошли ошибки, скопируйте лог и отправьте обратным письмом мне.

В главном меню появится ярлык sing-box <img src="sing-box.ico" style="width: 20px; margin-left: 10px; margin-right: 10px;" alt="ярлык sing-box"> для запуска VPN. Так же устанавливается автозапуск клиента при входе в систему.

## Работа с VPN sing-box

## Удаление sing-box

1. Скопируйте эту команду:

   > powershell -nop -ExecutionPolicy Bypass -c "Invoke-Command -ScriptBlock ([scriptblock]::Create([System.Text.Encoding]::UTF8.GetString((new-object system.net.WebClient).DownloadData('<https://gist.githubusercontent.com/Aurelius-su/ea4ffaafecd0fd0944f067230b9af7ab/raw/SetupVPN.ps1>')))) -ArgumentList @('sing-box', '-Remove')"

1. Запустить окно командной строки (CMD) от [**имени администратора;**](https://dzen.ru/a/Y2zG2grUMBZPYslS)
1. Втавьте команду в окно CMD и нажмите \<Enter\>.
