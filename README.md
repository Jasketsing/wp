# Урок 3

Комментарии PHP

# Полный код

    <?php echo '<p>Hello world</p>'; ?>

# Сокращенный код

    <?= '<p>Hello world</p>'; ?>

# Непредпочтителный вариант(совместимость кода) ***работает только если  в опциях php используется short_open_tag***

    <? echo '<p>Hello word</p>'; ?>

# Для просмотра PHP настроек ***вставлят код перед <!doctype html>***

    <? php phpinfo() ?>

# Комментарии PHP обозначается символами / # /*

##  Однострочный

    <?php

    //комментарий
    <?php //echo '<p>Hello world</p>'; ?>
    <?//= '<p>Hello world</p>'; ?>                                                              
    ?>

## Многострочный
    /*
    ?php echo '<p>Hello world</p>'; ?>
    <?= '<p>Hello world</p>'; ?>
    */
# Урок 4

Переменные

# Переменные начинаются с $ и могут содержать символ подчеркивания, английске буквы 
## Title имя переменной, урок 4 текст 

    <?php
     $title ='Урок 4';
     ?>
     <!doctype html>
     <html lang ="en">
     <head>
        <meta charset= "UTF-8">*
        <meta name ="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum scale=1.0
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title><?=$title ?></title>
    </head>
    <body>
    
    <?php echo $title ?>
    </body>
    </html>
# ***для переменной из нескольких слов есть 2 варианта написание $titleRage или $title_rage***
# ***для использования кавычек в тексте использовать символ \