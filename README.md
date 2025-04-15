# Static Portfolio

![GitHub License](https://img.shields.io/github/license/devdanielsun/static-portfolio)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/devdanielsun/static-portfolio)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/devdanielsun/static-portfolio)



This is a static portfolio website created using [Hugo](https://gohugo.io/), a fast and flexible static site generator written in Go. It is widely used for creating static websites, blogs, and portfolios due to its speed, simplicity, and support for Markdown and templating.

## Getting Started

### Prerequisites
- Install [Hugo](https://gohugo.io/getting-started/installing/) on your system.
- Install [Go](https://go.dev/doc/install) on your system.

### Running the Project
1. Clone the repository:
   ```bash
   $ git clone https://github.com/devdanielsun/static-portfolio.git
   $ cd static-portfolio
   ```

2. Start the development server:
    ```
    $ hugo server --ignoreCache
    ```

3. Open your browser and navigate to [localhost:1313](http://localhost:1313). Building for Production

    To generate the static files for deployment:

    ```
    $ hugo
    ```

    The output will be in the [public/](/public/) directory.

## About the Codebase

### Theme

The project uses the [hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack), a modern and feature-rich theme designed for portfolios and blogs.

### Configuration

The site settings are managed in `config.toml` and `params.toml` files stored in the [config](/config/_default/) directory, where you can define sections, themes, and other parameters.

### Content Management

Content is stored in the [content](/content/) directory, organized into folders like post, projects, etc.

### Static Files

The [public](/public/) directory contains the generated static files for deployment.

###Customization

You can modify the theme, add widgets, or create custom layouts by editing the theme files or overriding them in your project.

## License
This project is licensed under the [MIT License](LICENSE).
