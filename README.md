<?php
    //using the class
    use MCPremium\MCPremium;

    //include composer autoload
    require_once('../vendor/autoload.php');

    //checking account
    $response=MCPremium::check('username','password');

    //get informations from object
    var_dump($response);

    //or from array
    var_dump($response->toArray());
?>
