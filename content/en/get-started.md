---
title: Get started
---
{{< brick_small >}}

{{< breadcrumbs >}}

# Contact Us

---

<img src="/form.php" style="position: absolute; opacity: 0; pointer-events: none;" />
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
<form id="contactform" class="form" method="POST" action="/form.php">
    <h3>Let’s partner together</h3>
    <div>
        <label class="inborder sr-only" for="name">Name</label>
        <input type="text" name="name" id="name" class="form-control" placeholder="Name" required>
    </div>
    <div>
        <label class="inborder sr-only" for="company">Company</label>
        <input type="text" name="company" id="company" class="form-control" placeholder="Company">
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
    <div class="checkbox">
        <label class="" for="services">What services are you interested in?</label>
        <label><input type="checkbox" name="terms" id="terms" >Research</label>
        <label><input type="checkbox" name="terms" id="terms" >Training</label>
        <label><input type="checkbox" name="terms" id="terms" >Other</label>
    </div>
    <div class="submit">
        <div><input type="submit" value="Submit form" class="button"></div>
    </div>
</form>



{{< /brick_small >}}
