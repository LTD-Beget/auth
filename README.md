# Описание
Сервис авторизации и обновления токенов пользователей. Так-же дает возможность обновления токенов и переключения записей пользователя.

# Глоссарий
Токен - JWT токен содержащий в себе необходимую для аутентификации пользователя информацию. Подписан RSA ключом.
2FA - двухфакторная авторизация. Код для нее высылается либо по email либо по sms если она включенна.

# Метаданные
HTTP Authorization header - заголовок в котором передаем JWT токен. Общий вид Authorization: BEARER {JWT}