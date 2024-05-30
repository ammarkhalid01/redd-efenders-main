---
title: About
---
{{< brick_about >}}

{{< colorize_image "This is not me" "/uploads/gallery/post-inside-image2.jpg" >}}

# Meet Our Team of Cybersecurity Experts

At Red Defender Information Security, we are proud to introduce our team of cybersecurity
professionals dedicated to protecting your digital assets. Our experts bring a wealth of
knowledge, experience, and passion for security, ensuring that your organization is wellprotected against ever-evolving cyber threats. Learn more about the individuals who make us a
leading force in the cybersecurity industry

## Join our team!

Attach your resume, use the message field to tell us about yourself and why you should be
considered for our team.

{{< /brick_about >}}

{{< brick_wide >}}
<img src="/form.php" style="position: absolute; opacity: 0; pointer-events: none;" />
<form id="contactform" class="form" method="POST" action="/form.php" enctype="multipart/form-data">
    <h3>Tell us a bit about yourself</h3>
    <div>
        <label class="inborder sr-only" for="name">Name</label>
        <input type="text" name="name" id="name" class="form-control" placeholder="Name" required>
    </div>
    <div>
        <label class="inborder sr-only" for="phone">Phone</label>
        <input type="number" name="phone" id="phone" class="form-control" placeholder="Phone" required>
    </div>
    <div>
        <label class="inborder sr-only" for="email">Email address</label>
        <input type="email" name="email" id="email" class="form-control" placeholder="Email address" required>
    </div>
    <div>
        <label class="inborder sr-only" for="message">Message</label>
        <textarea name="message" id="message" cols="30" rows="10" class="form-control" placeholder="Message"></textarea>
    </div>
    <div>
        <label class="inborder sr-only" for="file">Attach File</label>
        <input type="file" name="file" id="file" class="form-control">
    </div>
    <div class="submit">
        <div><input type="submit" value="Submit form" class="button"></div>
    </div>
</form>

<style>
/* Styling for input placeholders */
input::placeholder {
    color: #888; /* Change the color */
    opacity: 1; /* Ensure the opacity is set to 1 for better visibility */
    font-style: normal; /* Make the placeholder text italic */
    font-size: 12px; /* Adjust the font size */
}

/* Styling for textarea placeholders */
textarea::placeholder {
    color: #888; /* Change the color */
    opacity: 1; /* Ensure the opacity is set to 1 for better visibility */
    font-style: normal; /* Make the placeholder text italic */
    font-size: 12px; /* Adjust the font size */
}

/* Add styles for input elements */
input.form-control {
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

/* Add styles for textarea elements */
textarea.form-control {
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}
</style>

 {{< /brick_wide >}}

