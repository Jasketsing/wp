# Урок 3

# Полный код

<?php echo '<p>Hello world</p>'; ?>

# Сокращенный код

<?= '<p>Hello world</p>'; ?>

# Непредпочтителный вариант(совместимость кода) ***работает только если только в опциях php используется поция short_open_tag***

<? echo '<p>Hello word</p>'; ?>

# Для просмотра PHP настроек ***вставлят код перед <!doctype html>***

<? php phpinfo() ?>

# Комментарии PHP обозначается символами / # /*

##  Однострочный

<?php

//комментарий
vecho '<p>Hello world</p>'; #комментарий
<?php //echo '<p>Hello world</p>'; ?>
<?//= '<p>Hello world</p>'; ?>                                                              
?>

## Многомстрочный
/*

<?php echo '<p>Hello world</p>'; ?>
<?= '<p>Hello world</p>'; ?>

*/

