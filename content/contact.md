---
title: "Technical Support"
date: 2024-10-27
draft: false
post_url: "https://script.google.com/macros/s/AKfycbyYUWNnvMX4HDd7JhgTKky0cXITKgm-VQYCL56aFVvqRYP7VC5zvnG_pFxFGOmj9iAT1w/exec"
---

If you need technical support concerning the [Moneybird Gmail add-on](https://workspace.google.com/marketplace/app/moneybird_add-on), please fill out the form below, and we’ll get back to you as soon as possible.

{{< rawhtml >}}

<form action={{< param post_url>}} method="POST">
    <div class="">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>
    </div>
    
    <div class="">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
    </div>
    
    <div class="">
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>
    </div>
    
    <div class="">
        <button type="submit">Submit</button>
    </div>
</form>

{{< /rawhtml >}}
