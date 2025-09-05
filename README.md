# PX

Minimal image hosting powered by **GitHub + jsDelivr** ⚡

## ⚠️ Limitations

To ensure fast load times and fair use, each individual file must not exceed **1MB** in size.

## 📂 Directory Structure

All images must be placed inside a subdirectory. For better organization, you can create multiple folders for different categories. Uploading images directly to the root directory is not permitted.

Here is an example of a valid structure:

```
px/
└── demo/
    ├── test.png
    └── example.jpg
```

## 📸 Usage

1. Upload to a Subdirectory 

   Create a new folder within this repository and push your images to it, ensuring they are under the size limit.

2. Get the CDN link 

   Use the following format to access your image via jsDelivr:

   > `https://cdn.jsdelivr.net/gh/cvyuan/px@main/<your-directory-name>/<your-image-name>`

3. Embed in Markdown / HTML 

   For example, if you uploaded an image named test.png inside a directory named demo:

   Markdown

   ```
   ![demo](https://cdn.jsdelivr.net/gh/cvyuan/px@main/demo/test.png)
   ```