# Dividir-un-Array-en-otros-Array-PHP

```php
$array = [
    1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20    
];

$perPage = 4;

for($i = 0; $i<count($array); $i+=$perPage){
    $res = array_slice($array,$i,$perPage);
    print_r($res);
}

```
