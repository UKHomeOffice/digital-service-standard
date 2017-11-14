<script> var chart = c3.generate({ 
axis: { x: { label: 'Sprint' }, y: { label: 'Work' } },

data: { x: 'x', columns: [ ['x', 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11], ['done', 6, 13, 18, 24, 31, 40, 48, 0, 0, 0, 0], ['to do', 94, 87, 82, 76, 69, 60, 52,0 ,0 , 0, 0], ['required', 9, 18, 27, 36, 45, 55, 64, 73, 82, 91, 100], ],

type: 'bar', types: { required: 'line', },

groups: [ ['to do','done'] ] },

legend: { position: 'right' },

bindto: '#chart1'

}); </script>
