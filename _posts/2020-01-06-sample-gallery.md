---
excerpt: "This post should display a **header with a solid background color**, if the theme supports it."
header:
  overlay_image: /assets/images/image.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"

gallery:
  - url: /assets/images/splash/unsplash-gallery-image-1.jpg
    image_path: /assets/images/splash/unsplash-gallery-image-1.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/splash/unsplash-gallery-image-2.jpg
    image_path: /assets/images/splash/unsplash-gallery-image-2.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/splash/unsplash-gallery-image-3.jpg
    image_path: /assets/images/splash/unsplash-gallery-image-3.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"

feature_row:
  - image_path: /assets/images/splash/unsplash-gallery-image-1.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/splash/unsplash-gallery-image-2.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/splash/unsplash-gallery-image-3.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
---

# Gallery

{% include gallery caption="This is a sample gallery with **Markdown support**." %}

# Feature-Row

{% include feature_row %}