# Email Setup

## Email Setup Using Web3Forms

**_Code_**

```html
<form action="https://web3forms.com/success" id="contact-form" method="post">
  <div class="form-grid">
    <div class="grid-left">
      <input
        type="hidden"
        name="access_key"
        value="fffffff-ffff-ffff-ffff-ffffffffff"
      />

      <input type="hidden" name="from_name" value="portfolio" />

      <input
        id="name"
        name="name"
        type="text"
        required
        placeholder="Full Name"
      />
      <input
        id="email"
        type="email"
        name="email"
        required
        placeholder="Email Address"
      />
      <input
        id="subject"
        type="text"
        name="subject"
        required
        placeholder="Subject"
      />
    </div>

    <div class="grid-right">
      <textarea placeholder="Message" id="message" name="message"></textarea>
    </div>
  </div>

  <button type="submit" class="btn-submit">Send Message</button>
</form>
```

To integrate Web3Forms into your website for managing contact inquiries, follow these steps:

### Using Web3Forms

- Navigate to: https://web3forms.com/

- Choose the _HTML_ option provided under _Works with any Technologies_.

- Input your Email Address in the _Create Access Key Section_. Afterward, an access key will be sent to your provided email.

### HTML Form Integration

To integrate the Web3Forms functionality into your HTML file, perform the following steps within the `index.html` file:

- Find the `contact` section in the `index.html` file.

**_Adjust Form Code_**

```html
<input
  type="hidden"
  name="access_key"
  value="fffffff-ffff-ffff-ffff-ffffffffff"
/>
```

- Replace the `value` attribute with the _Access Key_ received via email from Web3Forms.

```html
<input type="hidden" name="from_name" value="portfolio" />
```

- Replace the `value` attribute with the desired name that you want to be displayed in your mailbox for identification purposes.

This process will configure your HTML form to interact with Web3Forms and manage incoming inquiries effectively.

Ensure accurate replacements of values and attributes to facilitate seamless communication between your website and the Web3Forms service.
