<?php

// Die Eingabe des Benutzers auslesen
$name = strtolower($_POST['eingabe']);

// Die URL der Zielseite zusammenstellen
$url = "https://sites.google.com/view/acportuguesespanol/startseite/" . $name;

// Die Zielseite öffnen
header("Location: $url");

?>