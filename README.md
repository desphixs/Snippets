<h3>How to get current date or time in ajax jquery</h3>
const monthNames = ["Jan", "Feb", "Mar", "April", "May", "June",
  "July", "Aug", "Sept", "Oct", "Nov", "Dec"
];
<br>
var dt = new Date(); 
<br>
var time = dt.getDay() + " " + monthNames[dt.getUTCMonth()] + "," + dt.getFullYear() + " , " + dt.getHours() + ":" + dt.getMinutes() + ":" + dt.getSeconds();; 
<br>
document.write(time);
<br>
<p>You can no call the + time + variable here ever you want to display current date or time</p>
