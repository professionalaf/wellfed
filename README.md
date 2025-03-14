# WellFed Website

This is the official website for WellFed, built with Jekyll and hosted on GitHub Pages.

## Quick Links for Content Updates

- [How to Update the Website](#how-to-update-the-website)
- [Creating News/Blog Posts](#creating-news-blog-posts)
- [Updating Pages](#updating-pages)
- [Updating Site Information](#updating-site-information)
- [Adding Images](#adding-images)
- [Deploying to GitHub Pages](#deploying-to-github-pages)

## How to Update the Website

This website is designed to be easily updated by non-technical users. There are two main ways to update content:

### Option 1: Direct Editing on GitHub (Easiest)

1. Go to [GitHub repository URL]
2. Navigate to the file you want to edit
3. Click the pencil icon in the upper right to edit
4. Make your changes (follow Markdown formatting)
5. Scroll down, add a brief description of your changes
6. Click "Commit changes"

The website will automatically update within a few minutes.

### Option 2: Local Editing (More Control)

For more extensive changes or if you want to preview before publishing:

1. Clone the repository to your computer
2. Make changes to the files using any text editor
3. Commit and push the changes to GitHub

## Creating News/Blog Posts

To add a new blog post:

1. Create a new file in the `_posts` folder
2. Name it using this format: `YYYY-MM-DD-title-with-hyphens.md`
3. Include the front matter at the top:
   ```
   ---
   layout: page
   title: Your Post Title
   date: YYYY-MM-DD
   author: Your Name
   ---
   ```
4. Write your content below using Markdown
5. Commit the changes

Example post: [2023-09-01-wellfed-celebrates-community-partnerships.md](_posts/2023-09-01-wellfed-celebrates-community-partnerships.md)

## Updating Pages

The main content pages are in the `pages` folder:

- About: [pages/about.md](pages/about.md)
- Contact: [pages/contact.md](pages/contact.md)
- Events: [pages/events.md](pages/events.md)
- News: [pages/news.md](pages/news.md)

To update a page:
1. Open the relevant file
2. Edit the content using Markdown formatting
3. Save your changes
4. Commit to GitHub

## Updating Site Information

Site-wide settings like title, description, and navigation are in the `_config.yml` file.

## Adding Images

1. Add image files to the `assets/images` folder
2. Reference them in your content as:
   ```
   ![Alt text](/assets/images/your-image.jpg)
   ```

## Markdown Quick Reference

- **Bold text**: `**bold**`
- *Italic text*: `*italic*`
- [Link](https://example.com): `[Link text](https://example.com)`
- Lists:
  ```
  - Item 1
  - Item 2
  ```
- Headings:
  ```
  ## Large heading
  ### Medium heading
  #### Small heading
  ```

## Deploying to GitHub Pages

The website is automatically deployed when changes are pushed to the main branch of the GitHub repository. No additional steps are required.

If you're developing locally and want to preview the site:

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run Jekyll with live reload:
   ```bash
   bundle exec jekyll serve --livereload
   ```
   This will:
   - Start the Jekyll server
   - Enable live reload (site automatically refreshes when files change)
   - Watch for file changes in real-time
4. View the site at `http://localhost:4000`

Note: If you encounter any issues with live reload, you can also run without it:
```bash
bundle exec jekyll serve
```

## Need Help?

If you have any questions or need assistance updating the website, please contact [technical contact person]. 