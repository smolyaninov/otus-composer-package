# Процессор строк

Краткое описание пакета

## Требования

- PHP 8.1 или выше
- Расширение mbstring

## Установка

````bash
composer require smolyaninov/otus-composer-package
````

## Использование

````php
<?php

$processor = new StringProcessor();
echo $processor->getLength('my string')' // 9
````