# php-country-array
A list of all possible country names with their country code, and ISO code.

You can just loop through this array to show list of countries like -
<?php
foreach($country_list as $country => $data){  } ?>

or use any specific country details like -
<?php
echo $country_list['IN']['name'];

echo $country_list['US']['code']; ?>
