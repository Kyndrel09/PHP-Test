# PHP-Test
Just testing

<?php
class Database
{
    private static $dbName = 'Databasephp' ;
    private static $dbHost = 'localhost' ;
    private static $dbUsername = 'root';
    private static $dbUserPassword = 'root';
     
    private static $cont  = null;
     
    public function __construct() {
        die('Init function is not allowed');
    }
?>
