# Kred-calcSwing-Java-20-Maven
Maven Java 20 Swing NetBeans project - Credit calculator (real estate, auto) (annuity, the classics)

Отправка в Github
---------------------------------------------------------------------------------

В Github создаем в public repository - Kred-calcSwing-Java-20-Maven
- Генерируем токен:
  - В Github -> Profile -> Developer settings (https://github.com/settings/apps) -> Personal access tokens -> Generate new token
    - Note - Netbeans
    - Expiration - 90 days
    - Выбираем - repo
    - Generate token
    - Копируем код токена
  - Копируем ключ (пример: ghp_****************************)

В Netbeans:
  - -> Team -> Git -> Initialize repository (если еще не создан)
  - -> Team -> Commit
  - -> Team -> Remote -> Push
    - Specify Git Repository Location
        - URL: https://github.com/LiaArtem/Kred-calcSwing-Java-20-Maven.git
        - User: git
        - Password: ghp_****************************
        - Next
            - master -> master  (Next)
            - master -> origin/master  (Finish)
