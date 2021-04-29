# Расширение Facebook Business для OpenCart v2.0.1.1 to v3.0.3.7

- Последнюю версию плагина можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/releases/latest)
- Последнюю версию README можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/README.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/README.md)
- Последнюю версию INSTALL_GUIDE можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE.md)
- Предыдущую версию INSTALL_GUIDE до v4.0.0 можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_3.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_3.x.x.md)
- Предыдущую версию INSTALL_GUIDE до v3.0.0 можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_2.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_2.x.x.md)
- Последнюю версию FAQ можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/FAQ.md)
- Предыдущую версию FAQ до v4.0.0 можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ_3.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/FAQ_3.x.x.md)
- Предыдущую версию FAQ до v3.0.0 можно найти по адресу [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ_2.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/FAQ_2.x.x.md)
- По другим вопросам или сообщениям об ошибках **в отношении плагина OpenCart**, пожалуйста, откройте заявку на нашем сайте [helpdesk](https://marketinsg.zendesk.com/') или откройте новую проблему на [github](https://github.com/facebookincubator/)
- Если у вас возникли вопросы или вопросы, связанные с Facebook, отправьте заявку в службу поддержки Facebook Business на странице [Справочный центр Facebook Business](https://www.facebook.com/business/help/support)

Исходный код бизнес-расширения Facebook для OpenCart. Это для OpenCart v2.0.1.1 to v3.0.3.7.

## Особенности

1. Автоматическая инъекция событий Facebook Pixel на все веб-страницы магазина в традиционном/адаптивном веб-дизайне. Также отслеживаются межсерверные события Pixel. Запущенные пиксельные события включают:
    - PageView
    - ViewContent
    - Purchase
    - AddToCart
    - InitiateCheckout
    - Search
    - ViewCategory
    - AddToWishlist
    - CompleteRegistration
    - Contact
    - ViewBrand
2. Автоматическая синхронизация ваших товаров OpenCart с каталогом Facebook.
3. Дополнительные поля каталога Facebook могут быть добавлены в продукты OpenCart для каталога Facebook, то есть конкретная категория продуктов Google, цвет, пол, материал и т. д.
4. Отправка персональной идентифицирующей информации в пиксельных событиях в виде адреса электронной почты, имени, фамилии и телефона. Эта опция по умолчанию отключена и может быть изменена на этапе установки плагина.
5. Возможность отображать панель согласия на использование файлов cookie для клиентов, просматривающих ваш веб-сайт OpenCart.
6. Включение плагина чата Facebook Messenger на вашем веб-сайте OpenCart.

## Сборка Facebook Business Extension для OpenCart из исходных кодов

Найдите правильную версию для вашей установки OpenCart и заархивируйте содержимое папки. Переименуйте zip-файл в `Facebook_Business_Extension.ocmod.zip`. Убедитесь, что zip-файл заканчивается на `.ocmod.zip`, иначе установка будет неудачной.

- Единственная папка, которая должна находиться в корне zip-файла, - это папка "upload". НЕ включайте никакие другие подпапки в корень zip-файла, так как это приведет к неудачной установке плагина.
- Для **OpenCart 2.0.x - 2.2.x** убедитесь, что файл `install.xml` также находится в корне zip-файла. Это означает, что корень вашего zip-файла содержит **два** элемента: одну папку `upload` и один файл `install.xml`.
- Для **OpenCart 2.3.x - 3.x.x** и выше корень вашего zip-файла должен содержать только **один** элемент: одну папку `upload`.

## Установка расширения Facebook Business Extension на работающий веб-сайт OpenCart

Смотрите руководство по установке [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE.md) или его [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE.md).

## Часто задаваемые вопросы

Обратитесь к руководству по часто задаваемым вопросам [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ.md) или к ее [переводу](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/FAQ.md).

## Лицензия

Расширение Facebook Business Extension для OpenCart имеет лицензию на платформу, как указано в файле LICENSE [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/LICENSE).