<?php

print " Digite uma temperatura em Celsius: ";
$cel = (int) fgets (STDIN);

$nova= 9*$cel/5+32;

print "A temperatura em  Fahrenheit será $nova ";
