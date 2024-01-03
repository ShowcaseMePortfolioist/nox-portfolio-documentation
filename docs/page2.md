## Sidebar

**_Code_**

```html
<div class="side-bar">
  <!-- Branding Section -->
  <img
    src="./assets/images/logo.jpg"
    alt=""
    class="brand-img"
    data-aos="fade-right"
  />
  <h1 class="brand-name" data-aos="fade-right">Name</h1>

  <!-- Navigation -->
  <nav>
    <ul class="nav">
      <li data-aos="fade-right" data-aos-duration="3100">
        <a href="#" class="active">About</a>
      </li>
      <li data-aos="fade-right" data-aos-duration="3300">
        <a href="#">Resume</a>
      </li>
      <li data-aos="fade-right" data-aos-duration="3500">
        <a href="#">Portfolio</a>
      </li>
      <li data-aos="fade-right" data-aos-duration="3700">
        <a href="#">Blog</a>
      </li>
      <li data-aos="fade-right" data-aos-duration="3900">
        <a href="#">Contact</a>
      </li>
    </ul>
  </nav>

  <!-- Social Links -->
  <div class="social-btn-groups" data-aos="fade-up">
    <a href="#" class="btn">
      <ion-icon name="logo-twitter"></ion-icon>
    </a>
    <a href="#" class="btn">
      <ion-icon name="logo-linkedin"></ion-icon>
    </a>
    <a href="#" class="btn">
      <ion-icon name="logo-facebook"></ion-icon>
    </a>
  </div>

  <!-- Sidebar Footer -->
  <footer class="side-bar-footer">
    <p class="copyright">
      &copy; showcaseme <br />2023 All rights <br />
      reserved.
    </p>
  </footer>
</div>
```

### Branding Section:

- Contains the logo image `<img>` with the class `brand-img`.

- Displays the name `Name` in the `<h1>` tag with the class `brand-name`.

### Navigation:

- Consists of a `<nav>` tag with an unordered list (`<ul>`) containing navigation items (`<li>`).

- Each list item contains an `<a>` tag with a respective link (`href`) and text for different sections like "About," "Resume," "Portfolio," "Blog," and "Contact."

### Social Links:

- Enclosed in a `<div>` with the class `social-btn-groups`.

- Includes three social media links `<a>` tags with respective icons from the `ion-icon` library for Twitter, LinkedIn, and Facebook.

### Sidebar Footer:

- A footer section denoted by `<footer>` with the class `side-bar-footer`.

- Contains a `<p>` tag displaying the copyright information.

## About Section Hero Structure

**_Code_**

```html
<!-- about section hero structure -->
      <div class="hero">
        <div class="hero-img-bx" data-aos="fade-up">
          <img src="./assets/images/hero.jpg" alt="">
        </div>

        <div class="hero-content" data-aos="fade-left">
          <div class="hero-content-wrapper">
            <p class="title">Role</p>
            <h1 class="name">Name</h1>
            <div class="desc">Description</p>
              <p>Description</p>
            </div>

            <a href="#" class="btn-primary">Download CV</a>
          </div>
        </div>
      </div>
```

### Hero Section Structure

#### Container Div

- Contains a `<div>` with the class `hero`, encapsulating the entire hero section.

- Inside this container, there are two divisions:

#### Image Box

- `<div>` with the class `hero-img-bx`.

- Contains an `<img>` tag displaying an image. Ensure the correct path to the image is provided in the `src` attribute.

#### Content Box

- `<div>` with the class `hero-content`.

- Contains the textual content displayed on the hero section.

- Within the content box:

#### Title and Name

- `<p>` tag with the class `title` for the designation/title ("Role").

- `<h1>` tag with the class `name` displaying the person's name ("Name").

#### Description

- `<div>` with the class `desc` containing two `<p>` tags for the description.

- First `<p>` tag describes the individual's skills and capabilities.

- Second `<p>` tag elaborates on the developer's expertise, including consulting, skill expansion, and adherence.

#### Button

- `<a>` tag with the class `btn-primary` linking to a resource, likely a CV or resume download.

- Update the `href` attribute to link to the correct download resource.

**Note:** Adjust content, text, and links according to the specific individual or context of your website.

### About Inner Section

**_Code_**

```html
<div class="about-inner">
  <div class="service">
    <h2>What I Do</h2>
    <div class="grid-item">
      <div class="item">
        <div class="item-icon">
          <ion-icon name="storefront-outline"></ion-icon>
        </div>
        <div class="item-wrapper">
          <h3>Service</h3>
          <p>Description</p>
        </div>
      </div>
    </div>
  </div>
</div>
```

#### Container Div

- `<div class="about-inner">`: Contains the entire section.

#### Service Section

- `<div class="service">`: Section containing information about the services or skills offered.

#### Section Title

    - `<h2>What I Do</h2>`: Heading displaying the title of the section.

#### Grid Items for Services

    - `<div class="grid-item">`: Container for grid items displaying different services.

#### Service Items

- Each service is represented as a grid item using the following structure:

- `<div class="item">`: Container for an individual service.

- Inside each item, there are:

  - `<div class="item-icon">`: Container for an icon representing the service.

  - Icons are represented using the `ion-icon` library.

  - `<div class="item-wrapper">`: Container for the service title and description.

#### Service Title

- `<h3>` Heading displaying the title of the service (e.g., "E-commerce," "Copywriter," "Web Design," "Management").

#### Service Description

- `<p>`: Paragraph containing a description of the service, outlining the expertise and what the service entails.

**Note:** Customize the service titles, descriptions, and icons as needed to accurately reflect the services or skills offered by the individual or organization.

### Testimonials Section

**_Code_**

```html
<div class="testimonials">
  <h2>Testimonials</h2>

  <div class="testimonials-row">
    <div class="testimonials-content">
      <div class="testimonials-text">
        <blockquote><i>Testimonial</i></blockquote>
      </div>
      <div class="testimonials-author">
        <img
          src="./assets/images/testimonial-1.jpg"
          alt=""
          class="author-img"
        />
        <div class="author-info">
          <h4 class="author-name">testimonialName</h4>
          <p class="author-title">testimonialRole</p>
        </div>
      </div>
    </div>
  </div>
</div>
```

#### Testimonial

- `<div class="testimonials-content">`
- `<div class="testimonials-text">`: containing a blockquote with a testimonial.
- `<h4 class="author-name">testimonialName</h4>`: contains client name.
- `<p class="author-title">testimonialRole</p>`: contains client role.

### Clients Section

```html
<!-- about section clients structure -->
<div class="clients">
  <h2>Clients</h2>
    <div class="clients-row">
      <img src="./assets/images/client-1.png" alt="">
    </div>
  </div>
</div>
```

#### Client Logo

- `<img src="./asstets/images/client-1.png" alt="">`: Contains client logos
