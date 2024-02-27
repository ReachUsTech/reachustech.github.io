---
title: Reach Us!
layout: contact
description: Contact
---

Feel free to reach us for anything and everything.




<form action="https://api.staticforms.xyz/submit" method="post">
 <!-- Replace with accesKey sent to your email -->
 <input type="hidden" name="accessKey" value="7f842bd8-fc5d-4a5a-8f52-37f54a16c15b">
 <label for="name">Name:</label><br>
 <input type="text" id="name" name="name" required><br>
 <label for="email">Email:</label><br>
 <input type="email" id="email" name="email" required><br>
 <label for="phone">Phone:</label><br>
 <input type="text" id="phone" name="phone" required><br>
 <label for="message">Message:</label><br>
 <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
 
<!-- If you want replyTo to be set to specific email -->
 <!--input type="text" name="replyTo" value="reachus@reachus.tech"--> <!-- Optional -->
 <!-- Specify @ as reply to value if you want it to be customers email -->
 <input type="hidden" name="replyTo" value="@"> <!-- Optional -->
 <!-- If you want form to redirect to a specific url after submission -->
 <input type="hidden" name="redirectTo" value="https://reachus.tech/contacted"> <!-- Optional -->
<!-- If we receive data in this field submission will be ignored -->
 <input type="text" name="honeypot" style="display: none;"> <!-- Optional -->
 <input type="submit" value="Submit" />
</form>
