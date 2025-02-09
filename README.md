# hugo-kicking-the-tires

This project is a basic website built while exploring Hugo's "Kicking the Tires" chapter. The goal is to develop a fundamental understanding of Hugo's layouts, content management, and configuration.

## Project Features

- **Basic Home Page:** Created using Hugo's templating system.
- **About Page:** Demonstrates creating content with archetypes.
- **Development Server:** Live reload and local content preview using Hugo.

## Installation

1. Ensure Hugo is installed on your system

2. Create the project

3. Start the development server

4. Open your browser and navigate to [http://localhost:1313](http://localhost:1313) to view the site.

## Project Structure

```
kicking-tires/
├── archetypes/       # Templates for content creation
├── config.toml       # Site configuration file
├── content/          # Markdown content for pages
├── data/             # Data files for dynamic content
├── layouts/          # Templates and page layouts
├── static/           # Static assets like CSS and images
└── themes/           # Themes for additional styling
```

## Usage

- Create new content pages, for example teh about page using:

  ```bash
  hugo new about.md
  ```

## Key Concepts Covered

- **Installation of Hugo:** Installation via package managers and manual setup.
- **Creating a Basic Site:** Using the `hugo new site` command.
- **Templates and Layouts:** Building reusable page layouts.
- **Content Management:** Using archetypes and Markdown for content.
- **Development Preview:** Running Hugo's live server for rapid iteration.

## Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
