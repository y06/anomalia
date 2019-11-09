---
title: "thank you"
description: "contact form message success"
repo: "#" # delete this line if you want blog-like posts for projects
weight: 0
draft: false
---


<h3 style="margin: auto;">Message was<br>
succesfully sent
</h3>

<i class="fa fa-check-circle" style="font-size: 2em; margin: 2.6rem auto !important; display: block; text-align: center;"></i>

<p style="text-align: center; display: block; font-size: 0.4em; padding: 0 0 3rem 0;">Few seconds to redirect back</p>

<script type="text/javascript">
var counter = 3;
setInterval(function() {
    counter--;
    if(counter < 0) {
        window.location = 'login.php';
    } else {
        document.getElementById("count").innerHTML = counter;
         }
}, 1000);​
</script>