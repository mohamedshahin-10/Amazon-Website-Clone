# Amazon-Website-Clone
This project is a compilation of work completed during ITI's intensive 4-month CMS track training.
## Important note: This is a clone of the Amazon-website created solely for learning purposes.

## 🎥 Project Overview
[![Watch the video](https://img.youtube.com/vi/Q6bVVHgdzF8/maxresdefault.jpg)](https://www.youtube.com/watch?v=Q6bVVHgdzF8)
## 🌐 Hosted Site
[Visit the hosted site on Pantheon.io](https://dev-amazon-marketplace.pantheonsite.io)
## 🛠️ Used Technologies & Tools
- **WordPress**
- **HTML, CSS, JavaScript**
- **PHP**

## 🎨 Themes
Electro Electronics 

## 🔌 Main Plugins
- WooCommerce
- WooCommerce PayPal Payments
- FOX Currency Switcher Professional for WooCommerce.
- Elementor Pro
- Forminator
- WPForms
- Brevo
- WPCode Snippet
- WPML
- weglot

# WordPress
This is a WordPress repository set up to run on the [Pantheon platform](https://pantheon.io).
Pantheon is a website platform optimized for high-performance sites, offering an outstanding developer workflow. It includes built-in support for features such as Varnish, Redis, Apache Solr, New Relic, Nginx, PHP-FPM, MySQL, PhantomJS, and more.

## Getting Started

### 1. Set up a Site
If you don't have a Pantheon account yet, you can create one for free. After verifying your email address, you'll be able to add sites from your dashboard. Select "WordPress" to use this distribution.

### 2. Load up the site

Once the spin-up process is complete, you will be redirected to the site's dashboard. Click on the link under the site's name to access the Dev environment.
![alt](http://i.imgur.com/2wjCj9j.png?1, '')

### 3. Run the WordPress installer

What about the WordPress database configuration screen? You don't need to worry about database connection details, as these are handled in the background. All you need to do is provide the site information, and the installation process will be complete.

We'll provide more details on how this works, but we recommend developers check out wp-config.php to gain a better understanding.
![alt](http://i.imgur.com/4EOcqYN.png, '')

If you would like to keep a separate set of configuration for local development, you can use a file called `wp-config-local.php`, which is already in our .gitignore file.

### 4. Enjoy!

![alt](http://i.imgur.com/fzIeQBP.png, '')

## Branches

The `default` branch of this repository is where PRs are merged, and has [CI](https://github.com/pantheon-systems/WordPress/tree/default/.circleci) that copies `default` to `master` after removing the CI directories. This allows customers to clone from `master` and implement their own CI without needing to worry about potential merge conflicts.

## Custom Upstreams

If you are using this repository as a starting point for a custom upstream, be sure to review the [documentation](https://pantheon.io/docs/create-custom-upstream#pull-in-core-from-pantheons-upstream) and pull the core files from the `master` branch.

## 👥 Authors
- Mohamed Shahin
- Marwan Khaled
- Assmaa Ibrahim
- Ahmed Ehab

  
