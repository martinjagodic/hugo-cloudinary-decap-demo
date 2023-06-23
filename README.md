# Hugo Cloudinary Decap Demo

This is a demo of the [Hugo](https://gohugo.io/) static site generator, [Cloudinary](https://cloudinary.com/) digital asset manager and [Decap](https://decapcms.org/) CMS used together.

## Requirements

You need Hugo [installed on your machine](https://gohugo.io/getting-started/installing/).

You need a Cloudinary account and [get cloud name and api key](https://cloudinary.com/documentation/how_to_integrate_cloudinary#get_familiar_with_the_cloudinary_console). Replace the `CLD_CLOUD_NAME` and `CLD_API_KEY` in `static/admin/config.yaml`, `hugo.toml` and `layouts/_default/baseof.html` with your own. You also have to be logged in to Cloudinary in the browser you are using to use the CMS widget.

## Local development

Run hugo with `hugo server` and open http://localhost:1313/ in your browser.

To run Decap CMS, run `npx netlify-cms-proxy-server` in a parallel window.
