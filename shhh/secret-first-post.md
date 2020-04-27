---
title: "go away, shoo shoo"
layout: archive
permalink: /asdasdasd/
---

hi, you found the first secret link on this site. congrats!

<p id="days">heheheheh</p>

<script>
    function dateDiffInDays(date1, date2) {   
return Math.round((date2-date1)/(1000*60*60*24)); 
} 
var today = new Date();
var date = (today.getMonth() + 1) + today.getdate() + ',' + today.getFullYear;
    var daysDiff = dateDiffInDays(new Date(date), new Date('April 27, 2020'));
    document.getElementById("days").innerHTML = 'This was made ' + daysDiff + "days ago";
</script>

