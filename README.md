<h3>How to get current date or time in ajax jquery</h3>
var dt = new Date();
var time = dt.getDay() + " " + dt.getMonth() + "," + dt.getFullYear() + " , " + dt.getHours() + ":" + dt.getMinutes() + ":" + dt.getSeconds();;
document.write(time);
<br>
<p>You can no call the + time + variable here ever you want to display current date or time</p>
