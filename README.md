Веб_страницы привязаны к порту 8080
Адреса страниц:
 1. http://www.nikita.aleksandrov:8080                - главная страница
 2. http://www.nikita.aleksandrov:8080/admin_page/    - страница с закрытым доступом, выдает ошибку 403
 3. http://www.nikita.aleksandrov:8080/non_page/      - несуществующая страница, выдает код 404
 
 Файлы конфигурации Apache находятся по адресу ~\Bin\Apache24\conf
 Файлы самих страниц (в том числе .htaccess) находятся по адресу ~\Data\htdocs
