# How to calculate P/E ratio


## PHP

```php

function calculatePE($currentSharePrice, $earningsPerShare) {
  return $currentSharePrice / $earningsPerShare;
}

$currentSharePrice  = 100;
$earningsPerShare = 10;

$pe = calculatePE($currentSharePrice, $earningsPerShare);

echo "The P/E ratio is: " . $pe;

```

## JavaScript

```javascript

function calculatePE(currentSharePrice, earningsPerShare) {
  return currentSharePrice / earningsPerShare;
}

var currentSharePrice = 100;
var earningsPerShare = 10;

var pe = calculatePE(currentSharePrice, earningsPerShare);

console.log("The P/E ratio is: " + pe);

```

The **calculatePE** function takes in two arguments: currentSharePrice and earningsPerShare, and returns the P/E ratio by dividing currentSharePrice by earningsPerShare. 

P/E Ratio Calculator avaliable [https://www.capitalizeup.com/tools/pe-ratio/](https://www.capitalizeup.com/tools/pe-ratio/).
