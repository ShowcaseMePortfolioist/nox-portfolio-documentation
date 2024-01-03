# Contact Page

## Contact Section Instruction

**_Code_**

```html
<section class="contact page">
  <h1 class="section-heading">Contact</h1>
  <h4 class="section-sub-heading">Get in Touch</h4>

  <div class="contact-info">
    <!-- Contact information boxes -->
    <div class="info-box">
      <ion-icon name="call-outline"></ion-icon>
      <p>123-456-7890</p>
    </div>
    <!-- Other contact info boxes follow similar structure -->
    <!-- ... -->
  </div>

  <div class="contact-form">
    <form action="">
      <!-- Form grid for inputs -->
      <div class="form-grid">
        <div class="grid-left">
          <input type="text" required placeholder="Full Name" />
          <input type="email" required placeholder="Email Address" />
          <input type="text" required placeholder="Subject" />
        </div>
        <div class="grid-right">
          <textarea placeholder="Message"></textarea>
        </div>
      </div>
      <a href="#" class="btn-primary">Send message</a>
    </form>
  </div>
</section>
```

### Section Heading

- Main heading: `<h1 class="section-heading">Contact</h1>`

- Subheading: `<h4 class="section-sub-heading">Get in Touch</h4>`

### Contact Information

- Each piece of contact information is structured within `<div class="info-box">`.

- Information includes:

  - Phone number (`<ion-icon name="call-outline"></ion-icon>`)

  - Location (`<ion-icon name="location-outline"></ion-icon>`)

  - Email address (`<ion-icon name="mail-outline"></ion-icon>`)

  - Availability for hire (`<ion-icon name="checkmark-circle-outline"></ion-icon>`)

### Contact Form

- Form includes fields for:

  - Full Name: `<input type="text" required placeholder="Full Name">`

  - Email Address: `<input type="email" required placeholder="Email Address">`

  - Subject: `<input type="text" required placeholder="Subject">`

  - Message: `<textarea placeholder="Message"></textarea>`

- Submission button with class `btn-primary` is labeled "Send message".

### Further Actions

- Update or replace placeholder contact information (phone number, email, etc.) with actual contact details.

### Icons

- The contact info uses icons from an ion-icons library. Make sure the necessary library is included for these icons to display correctly.

### Validation

- Inputs have the `required` attribute for basic form validation.
