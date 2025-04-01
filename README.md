# AutoGLM - English Website

This project is an English website for the AutoGLM AI research platform, based on the original Chinese website at [https://autoglm-research.zhipuai.cn/](https://autoglm-research.zhipuai.cn/).

## Features

- Responsive design with dark theme
- Product introduction in English
- Video embedding
- Contact form
- Download links

## Project Structure

```
.
├── index.html              # Main HTML file
├── css/
│   └── style.css           # Stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── public/
│   ├── images/             # Image assets
│   └── videos/             # Video assets
└── README.md               # This file
```

## Setup

1. Clone the repository
2. Open `index.html` in your browser
3. Customize the content as needed

## Customization

### Adding Videos

Place your video files in the `public/videos/` directory and update the video source in the HTML:

```html
<video controls poster="public/images/video-thumbnail.jpg">
    <source src="public/videos/your-video-file.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

### Updating Download Links

Edit the download link URLs in the HTML to point to your files:

```html
<a href="your-download-link" class="btn download-btn">Download</a>
```

## License

This project is for demonstration purposes only.

## Contact

For any questions or support, please use the contact form on the website. 