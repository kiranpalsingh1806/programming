## Coding Examples

You can also run code and see output yourself!!!   
Click on [Code] button on every example to run the code in online compiler

##### Date and Time Checker [Code](https://onecompiler.com/javascript/3y6cy68pq)  
```js
const month = ["January","February","March","April","May","June","July","August","September","October","November","December"];
const weekday = ["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"];


// Pase your date here.
var date = new Date(1650338852538);

const DATE = date.getDate();
const MONTH = month[date.getMonth()];
const YEAR = date.getYear() + 1900;
const HOURS = date.getHours();
const MINUTES = date.getMinutes();

console.log("DATE : " + DATE + " " + MONTH + " " + YEAR);

console.log("TIME : " + HOURS + ":" + MINUTES);
```