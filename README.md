# README ME


# API

To use the library, see the example below:

    <?php
    require_once 'vendor/autoload.php';

    use Json\Json;

    echo Json::encode("foo") . PHP_EOL;
    echo Json::encode(array('foo' => 'bar')) . PHP_EOL;
    echo var_export(Json::decode('{"foo":"bar"}')) . PHP_EOL;

    
# License

Licensed under the Apache License, Version 2.0;

   http://www.apache.org/licenses/LICENSE-2.0