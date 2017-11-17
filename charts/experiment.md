Chart 1

This is an experiment 

<div id="chart1"></div>

<script> 
var chart = c3.generate({

data: {

columns: [
['both', 10],
['public', 17],
['staff', 31],
],

type : 'bar',
},

bar: {
width: {
ratio: 0.5 // this makes bar width 50% of length between ticks
}

}); 



