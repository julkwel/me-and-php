# Me and php
PHP for beginners, write your first php code, build your first application with php and learn fast.

### What is php ? 🤔

`- PHP is a server side scripting language stands for Hypertext Pre-processor and used to develop static or dynamic websites or Web application.` 👨‍💻  👩‍💻

### What is scripting language ? 🕵️‍♂️

`- A scripting language is a language that interprets scripts at runtime`  👨‍🏫

### Why use PHP ? 😏

`- PHP is open source and free, large community document and most web hosting servers support PHP by default ` 🤗

### Hello world 💥

```php
<?php 
  echo 'Hello world';
?>
```

### Installation

`PHP need web server, database and php parser,don't worry there are some excellent all-in-one windows, linux, and MacOs distributions that contain Apache, PHP, MySQL and other applications in a single installation file, e.g. XAMPP pick your own here and follow the installation instruction` [XAMPP SITE](https://www.apachefriends.org/fr/index.html)

### Syntax
`PHP general syntax is :`
```php
<?php ... ?>
```
`And short-open tags look like :`
```php
<?...?>
```

### Variables
`PHP variable are denoted with a ` $ `sign , php code always end with ` ; `ex :` 
```php
<?php
  $name = 'Susane';
?>
```

### DataTypes
`PHP has a total of eight data types:`

DataTypes  | Meanings | Ex
------------ | ------------- | -------------
Integers | Numbers without a decimal point | `$number = 123;`
Float | are floating-point numbers | `$float = 12.3;`
Boolean | Have two possible values `true` or `false` | `$bool = false;`
NULL |Special type has one value `NULL` | `$null = null;`
String | sequences of characters | `$strValues = 'My name is potato';`
Array | indexed collections values | `$arr = array('name',['potato'],1);`
Objects | instances of classes | `$herbie = new Person();`
Resources | It is the storing of a reference to functions and resources external to PHP | database call
