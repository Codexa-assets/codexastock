# codexastock

A repository to manage cover images for personal blog websites.

# Blog Cover Image Repository

This repository is used to manage and store cover images for personal blog websites. It allows you to easily hotlink images for use in blog posts without storing them locally.

## File Structure

```
/cover-images
  ├── image1.jpg
  ├── image2.png
  ├── image3.jpeg
  └── ...
```

- **/cover-images**: The directory where all cover images are stored.
- **image1.jpg, image2.png, etc.**: The individual cover image files that can be hotlinked into blog posts.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/blog-cover-images.git
   ```

2. Upload your cover images to the `/cover-images` directory.

3. To use an image in your blog, link to it using the raw URL:

   ```html
   <img src="https://raw.githubusercontent.com/yourusername/blog-cover-images/main/cover-images/image1.jpg" alt="Cover Image">
   ```

That's it! Simply use the direct image URL wherever you need the cover image in your blog posts.
