# Руководство по установке расширения Facebook Business v4.0.0

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

## Предварительные условия перед установкой плагина

1. Плагин поддерживает следующие версии OpenCart - от 2.0.x.x до 2.2.x.x, 2.3.x.x, 3.x.x.x и выше.

2. Удалите с веб-сайта все существующие реализации пикселей. События дублирования пикселей могут быть запущены, если существуют другие реализации пикселей.

3. Если вы ранее использовали плагин Facebook Business Extension версии 3.1.2 и ниже, следуйте приведенным ниже руководствам по удалению, чтобы удалить существующий плагин, прежде чем пытаться установить новый плагин:
    - Для Facebook Business Extension версии 2.x.x нажмите [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_2.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_2.x.x.md)
    - Для Facebook Business Extension версии 3.x.x нажмите [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_3.x.x.md) или [перевод](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/INSTALL_GUIDE_3.x.x.md)

4. Убедитесь, что ваш веб-сервер использует PHP версии 7.2 и выше. Это связано с тем, что плагин использует внутри Facebook Business SDK и требует PHP версии 7.2 и выше.

5. Загрузите последнюю версию файла плагина, ```Facebook_Business_Extension.ocmod.zip```.
    - Вы можете получить последнюю версию плагина на следующих сайтах:
      - [Маркетплейс OpenCart](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=32336)
      - [Последний выпуск на Github](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)
      - [Последний выпуск русской версии на Github](https://github.com/ruOpenCart/Facebook-For-OpenCart/releases/latest)

    - Убедитесь, что файл плагина имеет расширение ```.ocmod.zip```. [Скриншот](https://drive.google.com/file/d/1fHks0Ab0Wlo42xGqaK09QjHi8QKK-aIi/view?usp=sharing)

6. Установка плагина осуществляется через установщик расширений OpenCart для всех версий OpenCart. Для OpenCart 2.0.x - 2.2.x плагин также использует OCMOD (модификации OpenCart).
    - Для OpenCart 2.0.x - 2.2.x:
      - Вам нужно либо
        - Вариант 1. Включите опцию FTP. [Скриншот](https://drive.google.com/file/d/1-QS-vZtpZgun5lJXnn5H0UGriAm_YujF/view?usp=sharing)
          - Зайдите в админ-панель OpenCart и нажмите «Настройки».
          - Нажмите кнопку "Изменить" в своем магазине.
          - Перейдите на вкладку FTP и настройте данные FTP.
        - Вариант 2: установка QuickFix: проблема с установщиком расширений при отключенной поддержке FTP.
          - [Ссылка для скачивания](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=18892)
      - Установка плагина путем ручной загрузки файлов плагина на ваш веб-сервер не рекомендуется, так как скрипт OCMOD не будет установлен правильно.
      - установка vQmod НЕ поддерживается.

    - Для OpenCart 2.3.x или OpenCart 3.x:
      - Дополнительная настройка не требуется, поскольку расширение использует события OpenCart вместо OCMOD.
      - Поддерживается установка плагина путем ручной загрузки файлов плагина на ваш веб-сервер.

7. Наш плагин использует стандартную структуру папок OpenCart, то есть `admin`, `catalog` и `system`. Если ваша структура папок отличается **и** вы выполняете установку плагина посредством ручной загрузки, вам необходимо будет соответствующим образом изменить имена каталогов плагина или убедиться, что вы загружаете в правильные каталоги.

8. Наш плагин сгенерирует канал каталога всех ваших продуктов и загрузит его в Facebook после завершения настройки Facebook Pixel и Catalog. В зависимости от конфигурации вашего веб-сервера и сервера базы данных могут возникнуть проблемы, если у вас большой каталог продуктов, например более 5000 товаров. Вам также может потребоваться увеличить настройки памяти для вашего веб-сервера и сервера базы данных. Пожалуйста, обратитесь к [FAQ](https://github.com/facebookincubator/Facebook-For-OpenCart/blob/master/FAQ.md) или его [переводу](https://github.com/ruOpenCart/Facebook-For-OpenCart/blob/master/FAQ.md) для получения более подробной информации.

9. Поскольку наш плагин использует внутри Facebook Business SDK, размер файла плагина может превышать заданное вами заранее заданное PHP значение ```upload_max_filesize```. Возможно, вам потребуется увеличить значение ```upload_max_filesize``` для вашего веб-сервера, чтобы установить плагин.

## Установка плагина

1. Загрузите плагин Facebook для OpenCart с любого:
    - [Маркетплейс OpenCart](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=32336)
    - [Последний выпуск на Github](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)
    - [Последний выпуск русской версии на Github](https://github.com/ruOpenCart/Facebook-For-OpenCart/releases/latest)

2. Установите плагин Facebook для OpenCart через установщик OpenCart.
    - Видео-руководства доступны здесь:
      - Для OpenCart версии 2.0.x - 2.2.x: [Видеоруководство](https://drive.google.com/file/d/1abUNPAz2quGkDvq3gVau2_wz1zNcuu6_/view?usp=sharing)
      - Для OpenCart версии 2.3.x: [Видеоруководство](https://drive.google.com/file/d/146HbegvZz562qTRbYKueqkm_UkAgWOqB/view?usp=sharing)
      - Для OpenCart версии 3.x: [Видеоруководство](https://drive.google.com/file/d/1NdONuLUokc_Q0QBa_t41_doatbuUDDBA/view?usp=sharing)

    - Инструкция по установке:
      - Перейдите в админ-панель вашего магазина OpenCart и нажмите:
        - Расширения -> Установщик расширений. (Для OpenCart 2.x) [Скриншот](https://drive.google.com/open?id=18acMNnESWauvK6A7EJIeewM7TsqpAmYa)
        - Расширения -> Установщик. (Для OpenCart 3.x) [Скриншот](https://drive.google.com/open?id=1by3jIljlrz7sYJAAI1KovABOayRrnHSW)

      - Нажмите кнопку «Загрузить» и выберите zip-файл плагина (убедитесь, что zip-файл заканчивается на ```.ocmod.zip```). При необходимости нажмите кнопку «Продолжить». [Скриншот](https://drive.google.com/open?id=1iOyZNFow9qUiJITH4N60heml7-lZmCnF)

      - Снова зайдите в админ-панель вашего магазина OpenCart и нажмите:
        - Расширения -> Модули (Для OpenCart 2.0.x to 2.2.x) [Скриншот](https://drive.google.com/file/d/1KVaoKsdzaVvP3NB_3nghMLqoJX6aDwUS/view?usp=sharing)
        - Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)

      - Найдите расширение Facebook Business и нажмите кнопку «Установить». [Скриншот](https://drive.google.com/file/d/11-cvulIf9My1jYIHOs20wFSxxybEbiuw/view?usp=sharing)

      - (Дополнительный шаг) **Только для OpenCart 2.0.x - 2.2.x:**
        - Зайдите в админку OpenCart и нажмите Расширения -> Модификации. [Скриншот](https://drive.google.com/open?id=1H5ppQPXnx2UYo6v82d5comDJKPu064X2)
        - Нажмите кнопку "Обновить". [Скриншот](https://drive.google.com/open?id=1qy-ipwK1HCk8oSnUmGuy6MCJxQdUyGfw)

      - Установка завершена. Теперь вы можете продолжить интеграцию вашего магазина OpenCart с Facebook Business, нажав кнопку «Начать работу с Facebook».

3. Настройте права доступа для Facebook Business Extension, если вы столкнетесь с сообщением «В доступе отказано». [Скриншот.](https://drive.google.com/open?id=1wgBr11M5ikAVNXtxYw0bkYMsksTGW2ri) [Видеоруководство](https://drive.google.com/file/d/1jfOLd79zA-3wyGoiWopzf7ok0U0KaG6W/view?usp=sharing)
    - Убедитесь, что вы используете последнюю версию плагина Facebook Business. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)
    - Плагин Facebook Business Extension автоматически разрешит доступ для группы администраторов по умолчанию. Для других групп пользователей вам нужно будет предоставить доступ вручную.
    - Выполните следующие шаги, чтобы предоставить доступ к разрешению:
      - Перейдите в панель администратора и нажмите Меню -> Настройки -> Пользователи -> Группы пользователей. Найдите свою группу пользователей и нажмите кнопку «Изменить». [Скриншот](https://drive.google.com/open?id=1qNQQN4bFAk41CgW73rz6Dg5W_HIpnjMo)
      - Найдите ```extension/module/facebook_business``` для прав доступа и изменения. Убедитесь, что разрешения выбраны, и нажмите кнопку «Сохранить».
      - Получите доступ к расширению Facebook Business Extension, чтобы убедиться, что вы можете просматривать плагин.

## Настройка бизнес-менеджера Facebook, страницы, пикселя и каталога

1. Получите доступ к расширению Facebook Business для настройки бизнес-менеджера, страницы, пикселя и каталога.
    - Зайдите в админ-панель OpenCart и нажмите Меню -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
    - Нажмите кнопку «Начать работу с Facebook». [Скриншот](https://drive.google.com/file/d/1SATwGk6_YLFLwDiNR4m7BFGgDXsy4l_b/view?usp=sharing)
    - Всплывающее окно входа в систему Facebook просит вас сначала войти в систему. [Скриншот](https://drive.google.com/file/d/1h--LYUfTJFxQTKF7lf5OvdUxy84obBoZ/view?usp=sharing)
    - Прочтите приветственный текст и нажмите кнопку «Продолжить». [Скриншот](https://drive.google.com/file/d/1cGU6Gyw6aMqyI44UHkiK73ULiU1IjhUB/view?usp=sharing)
    - Экран подтверждения настроек позволяет вам настроить активы, которые вы хотите подключить. [Скриншот](https://drive.google.com/file/d/1_vllIHcR30uDIUdnxqy0QmXyciX0-HDL/view?usp=sharing)
    - Выберите существующий бизнес-менеджер Facebook или создайте новый бизнес-менеджер Facebook и нажмите кнопку «Продолжить». [Скриншот](https://drive.google.com/open?id=1nU1kGUke4pHMNX_XqZfQviJAJ49sUlZ-)
    - Выберите существующую страницу Facebook или создайте новую страницу Facebook и нажмите кнопку «Продолжить». [Скриншот](https://drive.google.com/open?id=1OlxR6EP7usoIH_Yy-5Z_gtFeOlkjvT6M)
    - Выберите существующий Каталог Facebook или создайте новый Каталог Facebook и нажмите «Продолжить». [Скриншот](https://drive.google.com/file/d/1h7jJmErWYlKthy-bXv-lBAEJVaksY0YD/view?usp=sharing)
    - Выберите существующую учетную запись Facebook Ad или создайте новую учетную запись Facebook Ad и нажмите «Продолжить». [Скриншот](https://drive.google.com/file/d/1YzD8CoZwUiTJ6-VfrOd7xsl2I4WkNuRN/view?usp=sharing)
    - Выберите пиксель Facebook, который вы хотите использовать для своего веб-сайта магазина OpenCart. Включите расширенное сопоставление, если вы хотите активировать расширенное сопоставление Facebook, и нажмите кнопку «Продолжить». [Скриншот](https://drive.google.com/open?id=1yQBJ3IvhtgH-pdVUkLfxGHidayg7NCC3)
    - Убедитесь, что выбранная вами компания отмечена по умолчанию. Это предоставит OpenCart разрешение на управление вашим бизнесом. [Скриншот](https://drive.google.com/file/d/1P68fH48uf79aBl57IqJerwT3FDCv60Gm/view?usp=sharing)
    - Нажмите кнопку «Далее», чтобы предоставить пользователю разрешения. [Скриншот](https://drive.google.com/open?id=120uo9sUrtdnW-HEQBY2rp6XhKn5oWfxO). Вам будет предложено предоставить дополнительные разрешения, если вы используете последнюю версию. [Скриншот](https://drive.google.com/file/d/1NfbEuZQcAmaJnty0a7tekY76fukiHfU0/view?usp=sharing)
    - Обратите внимание, что настройка Facebook Business Extension успешно завершена. Щелкните Готово. [Скриншот](https://drive.google.com/file/d/1YQYUt2cKkD3YHRwSTvWlX3-aeIpO6IcD/view?usp=sharing)
    - Закройте всплывающее окно и дождитесь автоматического обновления страницы FBE. [Скриншот](https://drive.google.com/file/d/1_rJiW7WIOMxdgQ7jMKVy-d42pkZLsLhk/view?usp=sharing)

2. Если вы уже являетесь пользователем предыдущих версий Facebook Business Extension, вы должны увидеть другой экран, на котором все ваши ранее подключенные ресурсы были автоматически заполнены. Нажмите кнопку «Продолжить», чтобы завершить настройку. [Скриншот](https://drive.google.com/open?id=1QdOM1ZdcoY8YfrJJPD6MeN76XpLRH6bm)

## Запустить представление управления

В Management View вы можете добавить дополнительные функции, такие как включить плагин Facebook Page Shop, плагин Facebook Messenger Chat и т. д.

1. Получите доступ к представлению управления расширениями для бизнеса Facebook.
    - Убедитесь, что вы используете плагин Facebook Business Extension версии 4.0.0 и выше. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)
    - Вы должны уже выполнить настройку бизнес-менеджера, страницы, пикселя и каталога для Facebook Business Extension. Шаги [здесь](#настройка-бизнес-менеджера-facebook-страницы-пикселя-и-каталога).
    - Перейдите в админку и:
      - Нажимаем на Facebook Business Extension (для всех версий OpenCart) [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
      - Или, (для OpenCart 2.0.x - 2.2.x) нажимаем на Расширения -> Модули -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
      - Или, (для OpenCart 2.3.x - 3.x.x) нажимаем на Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)
    - Нажмите кнопку "Управление настройками".. [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)

2. (Необязательно) Выполните шаги [здесь](#настройка-для-facebook-page-shop), чтобы включить плагин Facebook Page Shop.
3. (Необязательно) Выполните шаги [здесь](#настройка-чата-для-facebook-messenger), чтобы включить плагин Facebook Messenger Chat.

## Настройка для Facebook Page Shop

1. Включите плагин Facebook Page Shop.
    - Во всплывающем окне Management View убедитесь, что вы находитесь на вкладке «Главная», найдите раздел функций и нажмите кнопку «Просмотр» рядом с полем «Создать магазин на своей странице». [Скриншот](https://drive.google.com/open?id=100qDRgpxA0Rr2HyV49xSBPoRUWsnxLtR)
    - Во всплывающем окне нажмите кнопку Добавить плагин. [Скриншот](https://drive.google.com/open?id=1ivRBVCrJTu3ND-azhkdV4s-_IOsQdIvv)
    - В случае успешного добавления статус плагина Page Shop отображается как добавленный. [Скриншот](https://drive.google.com/open?id=1EcaufbbkJh0dtg3lWIatA08n9IKZrn3m)
2. Убедитесь, что ваш каталог Facebook правильно подключен к вашему Page Shop.
    - Во всплывающем окне Management View перейдите на вкладку «Каталог» и нажмите кнопку «Открыть диспетчер каталогов». [Скриншот](https://drive.google.com/open?id=18OCYzQMBtbQxW0II2-JtxzasA1_TD7e1)
    - В диспетчере каталогов щелкните вкладку «Настройки» и убедитесь, что ваш магазин страниц правильно подключен. [Скриншот](https://drive.google.com/open?id=1P2LrqzLhzIBcHphNHt_L6KE-E9M4H3TT)
3. Отключите плагин Facebook Page Shop.
    - Убедитесь, что вы включили плагин Facebook Page Shop, т.е. статус плагина Page Shop отображается как Добавлен. [Скриншот](https://drive.google.com/open?id=1EcaufbbkJh0dtg3lWIatA08n9IKZrn3m)
    - Нажмите кнопку «Просмотр» рядом с «Создать магазин на своей странице». [Скриншот](https://drive.google.com/open?id=12XRUxhzN4_9u3ojgZA_mHQD9LhAE17Zi)
    - Во всплывающем окне нажмите кнопку «Удалить». [Скриншот](https://drive.google.com/open?id=1J_kOcyIWBZeO3YJZMJFMQlWui5eSn3Kq)

## Настройка чата для Facebook Messenger

  1. Включите плагин чата Facebook Messenger.
      - Вы должны уже выполнить настройку бизнес-менеджера, страницы, пикселя и каталога для Facebook Business Extension. Шаги [здесь](#настройка-бизнес-менеджера-facebook-страницы-пикселя-и-каталога).
      - Заходим в админку и:
        - Нажимаем на Facebook Business Extension (для всех версий OpenCart) [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
        - Или, (для OpenCart 2.0.x - 2.2.x) нажмите Расширения -> Модули -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
        - Или, (для OpenCart 2.3.x - 3.x.x) нажмите Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)
      - Нажмите кнопку "Управление настройками". [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)
      - Во всплывающем окне найдите плагин Messenger Chat и нажмите кнопку Добавить. [Скриншот](https://drive.google.com/file/d/16v9JqISCDSGV37LbnP1gY25eEb1Rn1U7/view?usp=sharing)
      - Нажмите кнопку Добавить плагин. [Скриншот](https://drive.google.com/file/d/1rmGiH9O6XU58q5QTUCDChPlEDCfWbpyA/view?usp=sharing)
      - Установите и настройте параметры языка, приветствия и внешнего вида вашего подключаемого модуля Messenger, затем нажмите кнопку «Далее», когда закончите. [Скриншот](https://drive.google.com/file/d/1_jD7gSDYVhjJe7wgHPnEcm79bZWWT3ft/view?usp=sharing)
      - Добавьте свое доменное имя, например https://yourwebsite.com/ в белый список, чтобы появился ваш плагин Messenger. После добавления вашего домена в белый список нажмите «Готово». [Скриншот](https://drive.google.com/file/d/1YXThy_1YT614-ozZ-5K02hjSnWjHNJDd/view?usp=sharing)
      - Теперь вы можете закрыть всплывающее окно.
      - Нажмите кнопку "Управление настройками" еще раз, чтобы убедиться, что настройки правильно сохранены в вашем магазине OpenCart. [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)
      - Перейдите на домашнюю страницу вашего магазина OpenCart, и вы должны увидеть плагин чата Messenger в правом нижнем углу. [Скриншот](https://drive.google.com/file/d/1FmORE1qvQsKCtc_8Hd7lj_5SJvgVFDzF/view?usp=sharing)

  2. Измените настройки плагина чата Facebook Messenger.
      - Убедитесь, что вы включили плагин чата Facebook Messenger и уже выполнили вышеуказанные шаги в (1).
      - Заходим в админку и:
        - Нажимаем на Facebook Business Extension (для всех версий OpenCart) [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
        - Или, (для OpenCart 2.0.x - 2.2.x) нажмите Расширения -> Модули -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
        - Или, (для OpenCart 2.3.x - 3.x.x) нажмите Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)
      - Нажмите кнопку "Управление настройками". [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)
      - Во всплывающем окне найдите плагин Messenger Chat и нажмите кнопку «Просмотр». [Скриншот](https://drive.google.com/file/d/1PeSsW-7_JMSWBPIfFnBYr0RQ1fNkDdrZ/view?usp=sharing)
      - Нажмите кнопку «Обновить плагин», чтобы изменить существующие настройки и конфигурации. [Скриншот](https://drive.google.com/file/d/10mX_T_RzAGhJp1jync0zGJBBnQAtE7oY/view?usp=sharing)
      - Внесите изменения и нажмите кнопку «Готово», чтобы сохранить настройки.

  3. Отключите настройки плагина чата Facebook Messenger.
      - Убедитесь, что вы включили плагин чата Facebook Messenger и уже выполнили вышеуказанные шаги в (1).
      - Заходим в админку и:
        - Нажимаем на Facebook Business Extension (для всех версий OpenCart) [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
        - Или, (для OpenCart 2.0.x - 2.2.x) нажмите Расширения -> Модули -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
        - Или, (для OpenCart 2.3.x - 3.x.x) нажмите Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)
      - Во всплывающем окне найдите плагин Messenger Chat и нажмите кнопку «Отключить». [Скриншот](https://drive.google.com/file/d/178EWYukGfV0zOoEodiE76GQoh-9fN_P8/view?usp=sharing)

## Удалите существующие настройки Facebook для OpenCart

1. Удалить существующие настройки. [Видеоруководство](https://drive.google.com/file/d/1bhClnD8vw9Kwoh6is2zkdOY0MrJ4l3oa/view?usp=sharing)
    - Вы должны уже выполнить настройку бизнес-менеджера, страницы, пикселя и каталога для Facebook Business Extension. Шаги [здесь](#настройка-бизнес-менеджера-facebook-страницы-пикселя-и-каталога).
    - Заходим в админку и:
      - Нажимаем на Facebook Business Extension (для всех версий OpenCart) [Скриншот](https://drive.google.com/file/d/1DbKJ5i1-dA490VyUfQ-5d8cyGVYrup5Z/view?usp=sharing)
      - Или, (для OpenCart 2.0.x - 2.2.x) нажмите Расширения -> Модули -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
      - Или, (для OpenCart 2.3.x - 3.x.x) нажмите Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)
    - Вы должны увидеть кнопку «Удалить» на странице вашего плагина Facebook Business Extension. [Скриншот](https://drive.google.com/file/d/1SI7Fk5P17jr8OXB9vYoDX9WSKm1IDeVv/view?usp=sharing)
    - Должно появиться всплывающее окно с подтверждением. Нажмите кнопку ОК, чтобы продолжить удаление. [Скриншот](https://drive.google.com/file/d/1QLGBrf7FfYfXptcmtMydNPdLpJnSu-Cz/view?usp=sharing)
2. После успешного удаления вы должны увидеть страницу с кнопкой «Начать». [Скриншот](https://drive.google.com/open?id=11rel4BoOcxcmU_aqB6Pn-CIUwFVNTi2w)

## Удалите плагин

- Если вы используете Facebook Business Extension v3.x и ниже:

  1. [Видеоруководство](https://drive.google.com/open?id=1aPxqEcH1J3tT3bG0vMIC5DLnkDN7fo_d)

  2. У вас уже должен быть установлен плагин Facebook для OpenCart на своем веб-сайте OpenCart.

  3. Зайдите в админку вашего сайта OpenCart и нажмите Меню -> Расширения -> Модификации. [Скриншот](https://drive.google.com/open?id=1H5ppQPXnx2UYo6v82d5comDJKPu064X2)

  4. Найдите и выберите плагин Facebook Business Extension. Нажмите кнопку Удалить в правом верхнем углу экрана.. [Скриншот](https://drive.google.com/open?id=1cWMe0ChoDbTFm9on-9g89r7G_vZPylJP)

  5. Нажмите кнопку ОК, чтобы удалить плагин.. [Скриншот](https://drive.google.com/open?id=1swxbD99bfJxXGHfYPNYyZ3oaa6P7_rkY)

  6. Нажмите кнопку «Обновить», чтобы обновить существующие плагины на вашем сайте OpenCart. [Скриншот](https://drive.google.com/open?id=1Mfr49CzavKogSrOvZurJIvadfCwtR_6p)

- Если вы используете Facebook Business Extension v4.0.0 и выше:

  - Для OpenCart 2.0.x - 2.2.x:

    1. У вас уже должен быть установлен плагин Facebook для OpenCart на своем веб-сайте OpenCart.

    2. Зайдите в админку вашего магазина OpenCart и нажмите Расширения -> Модули -> Facebook Business Extension. Нажмите "Удалить". [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)

    3. Затем перейдите в Расширения -> Модификации и найдите 'Facebook Business Extension'. [Скриншот](https://drive.google.com/file/d/1wwhPvvf5AbULZqsrgPoYKoJx3rJvoCIN/view?usp=sharing)

    4. Нажмите кнопку "Удалить" для 'Facebook Business Extension'.

    5. Нажмите кнопку «Обновить», чтобы обновить существующие плагины на вашем сайте OpenCart. [Скриншот](https://drive.google.com/open?id=1Mfr49CzavKogSrOvZurJIvadfCwtR_6p)

    6. Обратите внимание, что если вы хотите удалить файлы плагинов со своего веб-сервера, вам придется удалить их вручную. Пожалуйста, проверьте расположение файлов в нашем репозитории GitHub [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/)

  - Для OpenCart 2.3.x:

    1. У вас уже должен быть установлен плагин Facebook для OpenCart на своем веб-сайте OpenCart.

    2. Зайдите в админку вашего сайта OpenCart и нажмите Расширения -> Расширения -> Модули -> Facebook Business Extension. Нажмите "Удалить". [Скриншот](https://drive.google.com/file/d/1u_Yz5bj7xx6Cu53qC5k9Qo3nWKpxRXPB/view?usp=sharing)

    3. Обратите внимание, что если вы хотите удалить файлы плагинов со своего веб-сервера, вам придется удалить их вручную. Пожалуйста, проверьте расположение файлов в нашем репозитории GitHub [здесь](https://github.com/facebookincubator/Facebook-For-OpenCart/)

  - Для OpenCart 3 и выше:

    1. У вас уже должен быть установлен плагин Facebook для OpenCart на своем веб-сайте OpenCart.

    2. Зайдите в админку вашего сайта OpenCart и нажмите Расширения -> Расширения -> Модули -> Facebook Business Extension. Нажмите "Удалить". [Скриншот](https://drive.google.com/file/d/1FqI2tTCTCdAnNyTDkmcFGAIHlO0OJ0VF/view?usp=sharing)

    3. Чтобы удалить файлы плагина с вашего веб-сервера, перейдите в Расширения -> Установщик и найдите файл ```.ocmod.zip```, который вы загрузили ранее, чтобы установить плагин Facebook Business Extension. Затем нажмите кнопку «Удалить». [Скриншот](https://drive.google.com/file/d/1HYkedlOIf-kkkMqkx_KvP1qytu5D2HSM/view?usp=sharing)

## Обновите плагин до более новой версии

- Если вы используете Facebook Business Extension v3.x и ниже и обновляетесь до Facebook Business Extension v4.x.x:

  1. У вас уже должен быть установлен плагин Facebook Business Extension на своем веб-сайте OpenCart.

  2. Удалите существующий плагин Facebook Business Extension. [Видеоруководство](https://drive.google.com/open?id=1aPxqEcH1J3tT3bG0vMIC5DLnkDN7fo_d)

  3. Установите новое расширение Facebook Business Extension версии 4.0.0 и выше, выполнив следующие действия [здесь](#установка-плагина).

- Если вы используете Facebook Business Extension v4.x.x и обновляетесь до Facebook Business Extension v4.x.x и выше:

  1. У вас уже должен быть установлен плагин Facebook Business Extension на своем веб-сайте OpenCart.

  2. Чтобы обновить существующее расширение Facebook Business Extension до версии 4.0.0 и выше, вы можете выбрать один из следующих вариантов:

      - Просто установите расширение еще раз с помощью установщика расширений. Вы можете обратиться к шагам [здесь](#установка-плагина) для установки с помощью установщика расширений..
          - Для OpenCart 2.0.x - 2.2.x необходимо удалить существующее расширение Facebook Business Extension OCMOD по адресу Расширения -> Модификации. [Скриншот](https://drive.google.com/file/d/1wwhPvvf5AbULZqsrgPoYKoJx3rJvoCIN/view?usp=sharing)
          - Для OpenCart 3 и выше вы можете удалить существующее расширение Facebook Business в Расширения -> Установщик. Просто найдите файл ```.ocmod.zip```, который вы загрузили ранее, чтобы установить плагин Facebook Business Extension. Затем нажмите кнопку «Удалить». [Скриншот](https://drive.google.com/file/d/1HYkedlOIf-kkkMqkx_KvP1qytu5D2HSM/view?usp=sharing)

      - Вручную загрузите содержимое папки 'upload' на свой веб-сервер и замените существующие файлы.
          - Обратите внимание, что это будет работать только с OpenCart v2.3.x и выше.

  3. После загрузки новой версии плагина вам необходимо:

      - Для OpenCart 2.0.x - 2.2.x:
          - Зайдите в админку вашего магазина OpenCart и нажмите Расширения -> Модули -> Facebook Business Extension. Нажмите "Удалить". [Скриншот](https://drive.google.com/file/d/1hh0TCxsM6lOeWdxNxxZYYkzQqvRJsxbj/view?usp=sharing)
          - Затем на той же странице снова нажмите «Установить».
          - Это необходимо для установки / удаления любых событий или изменений базы данных, которые могли быть внесены в новую версию плагина. Обратите внимание, что это не удалит ваше соединение с Facebook Business, но ваши настройки OpenCart для Facebook Business Extension (т. е. синхронизация специальных цен в качестве скидки с опцией каталога Facebook и включение опции панели cookie) будут сброшены.
          - Зайдите в админку OpenCart и нажмите Расширения -> Модификации. [Скриншот](https://drive.google.com/open?id=1H5ppQPXnx2UYo6v82d5comDJKPu064X2)
          - Нажмите кнопку "Обновить". [Скриншот](https://drive.google.com/open?id=1qy-ipwK1HCk8oSnUmGuy6MCJxQdUyGfw)

      Для OpenCart 2.3.x - 3.x.x:
          - Зайдите в админку вашего сайта OpenCart и нажмите Расширения -> Расширения -> Модули -> Facebook Business Extension. Нажмите "Удалить". [Скриншот](https://drive.google.com/file/d/1u_Yz5bj7xx6Cu53qC5k9Qo3nWKpxRXPB/view?usp=sharing)
          - Затем на той же странице снова нажмите «Установить».
          - Это необходимо для установки / удаления любых событий или изменений базы данных, которые могли быть внесены в новую версию плагина. Обратите внимание, что это не удалит ваше соединение с Facebook Business, но ваши настройки OpenCart для Facebook Business Extension (т. е. синхронизация специальных цен в качестве скидки с опцией каталога Facebook и включение опции панели cookie) будут сброшены.

- Если вы используете Facebook Business Extension v3.x и ниже и обновляетесь до Facebook Business Extension v3.x и ниже:

  1. [Видеоруководство](https://drive.google.com/open?id=12dX2wYTcE3Y7Wf-ZBD_6X4EAZU2L-8vp)

  2. У вас уже должен быть установлен плагин Facebook Business Extension на своем веб-сайте OpenCart.

  3. Удалите существующий плагин Facebook для OpenCart. [Видеоруководство](https://drive.google.com/open?id=1aPxqEcH1J3tT3bG0vMIC5DLnkDN7fo_d)

  4. Установите плагин более поздней версии. Убедитесь, что версия Facebook для OpenCart отображается как более поздняя версия. [Скриншот.](https://drive.google.com/open?id=19Nfp_1x9cQbGCk-rMmi3PkLy3NEPFHdS) [Видеоруководство](https://drive.google.com/open?id=1V4Nu8nlmHX5ppKqsjcR-xR05Rozb7MKN)

## Панель cookie на вашем сайте OpenCart

1. Отключить панель cookie.
    - Убедитесь, что вы используете плагин Facebook Business Extension версии 2.0.3 и выше. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)

    - Для Facebook Business Extension версии 3.1.2 и ниже:
      - Зайдите в админку OpenCart и нажмите Меню -> Facebook Business Extension -> Facebook Business Extension. [Скриншот](https://drive.google.com/open?id=1xC5hQLqn-6AR7mxPME3y-safDTY-LFya)
      - Снимите флажок Показывать панель cookie на веб-сайте магазина и нажмите кнопку Сохранить. [Скриншот](https://drive.google.com/open?id=1cdzTmI9pIqKx2olKku0-bjH1XMPEKcbn)

    - Для Facebook Business Extension версии 4.0.0 и выше;
      - Зайдите в админку вашего сайта OpenCart и нажмите на Facebook Business Extension. [Скриншот](https://drive.google.com/file/d/1138L_BqxjilQE4TT8iPqd5Z5A8PGNuTz/view?usp=sharing)
        - Или перейдите по ссылке:
          - Расширения -> Модули -> Facebook Business Extension (для OpenCart 2.0.x - 2.2.x) [Скриншот](https://drive.google.com/file/d/1KVaoKsdzaVvP3NB_3nghMLqoJX6aDwUS/view?usp=sharing)
          - Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension (для OpenCart 2.3.x и выше) [Скриншот](https://drive.google.com/file/d/1-jnNis1ZC0crNPqwVcAyA4-wCshBy3sc/view?usp=sharing)
      - Перейдите на вкладку «Настройки» и выберите «Отключить» для параметра «Показывать панель cookie на веб-сайте магазина». Затем нажмите кнопку Сохранить. [Скриншот](https://drive.google.com/file/d/1JY9gMSnopNJuDKdh1hwwUlzgZelcy0Fo/view?usp=sharing)

2. Включить панель cookie.
    - Убедитесь, что вы используете плагин Facebook Business Extension версии 2.0.3 и выше. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)

    - Для Facebook Business Extension версии 3.1.2 и ниже:
      - Зайдите в админку и нажмите Меню -> Facebook Business Extension -> Facebook Business Extension. Нажмите кнопку "Управление настройками". [Скриншот](https://drive.google.com/open?id=1nUNSsphp7ID8Ma4_5ESWI8DR_eQ4-IfI)
      - Установите флажок Показывать панель cookie на веб-сайте магазина и нажмите кнопку Сохранить. [Скриншот](https://drive.google.com/open?id=1CSeaZ0BPsue6eNKsLHXjahodXWgNh5ss)

    - Для Facebook Business Extension версии 4.0.0 и выше;
      - Зайдите в админку вашего сайта OpenCart и нажмите на Facebook Business Extension. [Скриншот](https://drive.google.com/file/d/1138L_BqxjilQE4TT8iPqd5Z5A8PGNuTz/view?usp=sharing)
        - Или перейдите по ссылке:
          - Расширения -> Модули -> Facebook Business Extension (для OpenCart 2.0.x - 2.2.x) [Скриншот](https://drive.google.com/file/d/1KVaoKsdzaVvP3NB_3nghMLqoJX6aDwUS/view?usp=sharing)
          - Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension (для OpenCart 2.3.x и выше) [Скриншот](https://drive.google.com/file/d/1-jnNis1ZC0crNPqwVcAyA4-wCshBy3sc/view?usp=sharing)
      - Перейдите на вкладку «Настройки» и выберите «Включить» для параметра «Показывать панель файлов cookie на веб-сайте магазина». Затем нажмите кнопку «Сохранить». [Скриншот](https://drive.google.com/file/d/1JY9gMSnopNJuDKdh1hwwUlzgZelcy0Fo/view?usp=sharing)

## Использование специальных предложений на продукты OpenCart в качестве цены продажи в каталоге Facebook

1. Отключите использование специальной цены в качестве скидки.
    - Убедитесь, что вы используете плагин Facebook Business Extension версии 2.1.11 и выше. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)

    - Для Facebook Business Extension версии 3.1.2 и ниже:
      - Зайдите в админку OpenCart и нажмите Меню -> Facebook Business Extension -> Facebook Business Extension. [Скриншот](https://drive.google.com/open?id=1xC5hQLqn-6AR7mxPME3y-safDTY-LFya)
      - Снимите флажок «Синхронизировать специальную цену продукта как скидку» и нажмите кнопку «Сохранить». [Скриншот](https://drive.google.com/open?id=1cdzTmI9pIqKx2olKku0-bjH1XMPEKcbn)
      - Нажмите кнопку «Повторно синхронизировать продукты с Facebook», чтобы повторно синхронизировать сведения о продукте с Facebook.

    - Для Facebook Business Extension версии 4.0.0 и выше:
      - Зайдите в админку вашего сайта OpenCart и нажмите на Facebook Business Extension. [Скриншот](https://drive.google.com/file/d/1138L_BqxjilQE4TT8iPqd5Z5A8PGNuTz/view?usp=sharing)
        - Или перейдите по ссылке:
          - Расширения -> Модули -> Facebook Business Extension (для OpenCart 2.0.x - 2.2.x) [Скриншот](https://drive.google.com/file/d/1KVaoKsdzaVvP3NB_3nghMLqoJX6aDwUS/view?usp=sharing)
          - Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension (для OpenCart 2.3.x и выше) [Скриншот](https://drive.google.com/file/d/1-jnNis1ZC0crNPqwVcAyA4-wCshBy3sc/view?usp=sharing)
      - Перейдите на вкладку «Настройки» и выберите «Отключить» для параметра «Синхронизировать специальную цену продукта как скидку с каталогом Facebook». Затем нажмите кнопку «Сохранить». [Скриншот](https://drive.google.com/file/d/19VSEg3iuvOylXqL3gCNQTf-sWKrnhsLv/view?usp=sharing)
      - Принудительно выполнить повторную синхронизацию продуктов с Каталогом Facebook:
        - Перейдите на вкладку «Подключение» и нажмите кнопку «Управление настройками». Должно появиться всплывающее окно. [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)
        - Во всплывающем окне найдите карточку «Каталог» и нажмите кнопку «Просмотр». В вашем браузере должно открыться новое окно.[Скриншот](https://drive.google.com/file/d/12iItSI74oiQUDQrid0cunrcG9OZ0ljgg/view?usp=sharing)
        - В новом окне найдите пункт «Источник данных» в меню левого столбца и щелкните по нему. [Скриншот](https://drive.google.com/file/d/1l43EzX8n0gY04rsdMPWw5CY8yzVRz_19/view?usp=sharing)
        - Найдите фид каталога, принадлежащий вашему магазину OpenCart, и щелкните его имя. [Скриншот](https://drive.google.com/file/d/1CeZvVDsxHlQvCzqO5TiUIIavTzYs5xTu/view?usp=sharing)
        - Нажмите кнопку «Загрузить сейчас», чтобы принудительно выполнить повторную синхронизацию ваших продуктов из магазина OpenCart с каталогом Facebook. [Скриншот](https://drive.google.com/file/d/1xzuid30fUL3otyiDzp8t_Da37EmtpZDz/view?usp=sharing)

2. Включите использование специальной цены в качестве скидки.
    - Убедитесь, что вы используете плагин Facebook Business Extension версии 2.1.11 и выше. [Последняя версия](https://github.com/facebookincubator/Facebook-For-OpenCart/releases/latest)

    - Для Facebook Business Extension версии 3.1.2 и ниже:
      - Зайдите в админку и нажмите Меню -> Facebook Business Extension -> Facebook Business Extension. Нажмите кнопку "Управление настройками". [Скриншот](https://drive.google.com/open?id=1nUNSsphp7ID8Ma4_5ESWI8DR_eQ4-IfI)
      - Отметьте опцию «Синхронизация специальной цены продукта как скидки» и нажмите кнопку «Сохранить». [Скриншот](https://drive.google.com/open?id=1CSeaZ0BPsue6eNKsLHXjahodXWgNh5ss)

    - Для Facebook Business Extension версии 4.0.0 и выше:
      - Зайдите в админку вашего сайта OpenCart и нажмите на Facebook Business Extension. [Скриншот](https://drive.google.com/file/d/1138L_BqxjilQE4TT8iPqd5Z5A8PGNuTz/view?usp=sharing)
        - Или перейдите по ссылке:
          - Расширения -> Модули -> Facebook Business Extension (для OpenCart 2.0.x - 2.2.x) [Скриншот](https://drive.google.com/file/d/1KVaoKsdzaVvP3NB_3nghMLqoJX6aDwUS/view?usp=sharing)
          - Расширения -> Расширения -> В раскрывающемся списке Тип расширения выберите «Модули» -> Facebook Business Extension (для OpenCart 2.3.x и выше) [Скриншот](https://drive.google.com/file/d/1-jnNis1ZC0crNPqwVcAyA4-wCshBy3sc/view?usp=sharing)
      - Перейдите на вкладку «Настройки» и выберите «Включить» для параметра «Синхронизировать специальную цену продукта как скидку с каталогом Facebook». Затем нажмите кнопку «Сохранить». [Скриншот](https://drive.google.com/file/d/19VSEg3iuvOylXqL3gCNQTf-sWKrnhsLv/view?usp=sharing)
      - Принудительно выполнить повторную синхронизацию продуктов с Каталогом Facebook:
        - Перейдите на вкладку «Подключение» и нажмите кнопку «Управление настройками». Должно появиться всплывающее окно. [Скриншот](https://drive.google.com/file/d/1rTrSpim-OeQaVt8UmhGozi_9yd4Idll4/view?usp=sharing)
        - Во всплывающем окне найдите карточку «Каталог» и нажмите кнопку «Просмотр». В вашем браузере должно открыться новое окно. [Скриншот](https://drive.google.com/file/d/12iItSI74oiQUDQrid0cunrcG9OZ0ljgg/view?usp=sharing)
        - В новом окне найдите пункт «Источник данных» в меню левого столбца и щелкните по нему. [Скриншот](https://drive.google.com/file/d/1l43EzX8n0gY04rsdMPWw5CY8yzVRz_19/view?usp=sharing)
        - Найдите фид каталога, принадлежащий вашему магазину OpenCart, и щелкните его имя. [Скриншот](https://drive.google.com/file/d/1CeZvVDsxHlQvCzqO5TiUIIavTzYs5xTu/view?usp=sharing)
        - Нажмите кнопку «Загрузить сейчас», чтобы принудительно выполнить повторную синхронизацию ваших продуктов из магазина OpenCart с каталогом Facebook. [Скриншот](https://drive.google.com/file/d/1xzuid30fUL3otyiDzp8t_Da37EmtpZDz/view?usp=sharing)
