<!DOCTYPE html>
<html lang="en">
<head>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <script>
        let tg = window.Telegram.WebApp;
        tg.showAlert(`Добро пожаловать, @${tg.WebAppUser.username}.`);
    </script>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
