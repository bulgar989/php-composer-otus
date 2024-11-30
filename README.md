# Сложение чисел

Краткое описание пикета

## Требования

- PHP 7.4

## Установка

composer require bulgar989/php-composer-otus

## Использование

    <?php

    use <vendor>\<name>\Summ;
    use <vendor>\<name>\Subtract;

    $summ = new Summ();
    echo $summ->getSumm(5, 2); // 7

    $subtract = new Subtract();
    echo $subtract->getSubtract(5, 2); // 3