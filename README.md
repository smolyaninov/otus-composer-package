# Процессор строк

Краткое описание пакета

## Требования

- PHP 8.2

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