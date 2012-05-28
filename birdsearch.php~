<?php

header('Content-Type: application/json');
header('Cache-Control: no-cache');
header('Pragma: no-cache');
header("Access-Control-Allow-Origin: *");

$term = $_GET["term"];

$url = 'http://jqueryui.com/demos/autocomplete/search.php';

echo file_get_contents($url . "?term=$term");

?>
