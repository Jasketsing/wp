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

