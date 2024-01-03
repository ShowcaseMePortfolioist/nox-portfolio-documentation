# Blog Section

## Blog Section Instruction

**_Code_**

```html
<section class="blog page">
  <h1 class="section-heading">heading</h1>
  <h4 class="section-sub-heading">subHeading</h4>

  <div class="blog-container">
    <!-- Individual blog posts -->
    <div class="blog-post">
      <div class="blog-img-box">
        <img src="./assets/images/blog_post_1.jpg" alt="" />
      </div>
      <div class="blog-category">service</div>
      <div class="blog-info">
        <p class="publish-date">date</p>
        <a href="#" class="blog-title">description</a>
      </div>
    </div>
    <!-- Other similar blog posts follow this structure -->
    <!-- ... -->
  </div>
</section>
```

### Section Heading

- Main heading: `<h1 class="section-heading">heading</h1>`

- Subheading: `<h4 class="section-sub-heading">subHeading</h4>`

### Blog Posts

#### Structure

- Each blog post is encapsulated within `<div class="blog-post">`.

- Includes an image, category, publish date, and a blog title within respective `<div>` elements.

#### Content

- Categories: `<div class="blog-category">service</div>`

- Publish date: `<p class="publish-date">date</p>`, for all posts.

#### Specifies

- Images: Linked within `<img>` tags with `src` attribute pointing to image files.

- Categories and titles are enclosed in `<div>` or `<a>` tags respectively.

- Each blog post contains a different title and category.

#### Links

- Blog titles are linked (`<a href="#">`) but do not have specific URLs assigned (`href="#"`).

#### Images

- Images (`<img>`) are referenced with local paths (`./assets/images/`).

#### Further Action

- The placeholder links (`href="#"`) need to be updated with actual URLs for respective blog posts.

- Ensure the image paths (`src="./assets/images/"`) are correctly pointing to the images' locations.

Please adjust the content, text, images and links as required for your specific project needs.
