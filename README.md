# My Personal Website

This is my personal website built with [Hugo](https://gohugo.io/). It showcases my projects, blog posts, and other personal information.

## Table of Contents

- [Installation](#installation)
- [Running the Site](#running-the-site)
- [Updating Content](#updating-content)
- [Adding New Posts](#adding-new-posts)
- [Deploying the Site](#deploying-the-site)
- [Customizing the Site](#customizing-the-site)

## Installation

For more details, it's a good idea to refer to the [quickstart](https://gohugo.io/getting-started/quick-start/) guide on HUGO's website.

1. **Install Hugo**: Follow the instructions on the [Hugo installation page](https://gohugo.io/getting-started/installation/) to install Hugo on your machine.

2. **Clone the Repository**: Clone this repository to your local machine.

3. **Install Theme**: If you are using a specific theme, follow the theme's installation instructions.

## Running the Site

To run the site locally, use the following command (if it don't work on windows powershell, use git bash):

```bash
hugo server
```

Visit `http://localhost:1313` in your web browser to view your site.

## Updating Content

1. **Edit Existing Content**: Navigate to the `content` directory and edit the Markdown files as needed.

2. **Add New Content**: Create new Markdown files in the appropriate section (e.g., `content/posts/` for blog posts).

## Adding New Posts

To add a new blog post:

1. Run the following command to create a new post:

   ```bash
   hugo new posts/my-new-post.md
   ```

2. Open the newly created file in `content/posts/` and fill in the front matter and content.

3. Save your changes.

## Deploying the Site

1. **Build the Site**: Run the following command to build the static files:

   ```bash
   hugo
   ```

   The generated files will be located in the `public` directory.

2. **Deploy**: Use your preferred method to deploy the contents of the `public` directory to your web server or hosting service (e.g., GitHub Pages, Netlify, etc.).

## Customizing the Site

- **Configuration**: Edit the `config.toml` file to change site settings such as title, base URL, and pagination.

- **Themes**: Customize the theme by editing the files in the `layouts` and `static` directories. Note that a theme is already ```git submodule``` in the repo, as suggested in the Hugo's quickstart, so the theme will always be pulled from the original repository and always stay updated.

### Instructions for Use
- Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and repository name.
- Customize the sections as needed to fit your specific setup and preferences.
- Add any additional information that might be relevant to your website or workflow.
