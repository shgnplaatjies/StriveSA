# Custom WordPress Plugin
##### Author: Shagan Plaatjies

## Description
This WordPress plugin allows users to add and display custom fields on the front end of WordPress posts. It implements custom text, date, and image fields with user-friendly customization options for a course summary card.

## Features
1. Custom fields for posts (text, date, image).
2. Front-end display of custom fields with custom post type.
3. User customization option for round and squared style elements.
4. User customization option for date format.

## Installation Instructions
1. Download the plugin file from the repository's /Plugins symlinked folder.
2. Upload the plugin folder to `/wp-content/plugins/` in your WordPress installation.
3. Activate the plugin through the 'Plugins' menu in WordPress.

## Custom Fields Implementation

### Fields Used
- **Duration (Date)**
- **Methodology Icon (Image)**
- **Methodology (Select)**
- **Course Summary (Text)**
- **Border Style**
- **Price (Number)**

![image](https://github.com/shgnplaatjies/StriveSA/assets/63879125/727db9c0-45b3-449a-a538-b15fcc9a2c67)


### Implementation Details
- The plugin implements custom fields for displaying images, dates, and text.

### Customization Options
- The border style field offers the choice of rounded or unrounded edges.
- Date fields allow users to select from different date formats and use different date formats.

## Documentation Considerations
- **Source Control:** Utilized symbolic linking for clean and maintainable source control.
- **WordPress Theme Customizations:** Used a Child Theme to ensure customizations remain intact after theme updates.
- **Plugin Repository Independence:** Employed symbolic link structure to separate concerns of plugins, themes, and their host WordPress installations. This enables compatibility testing and cleaner repository creation. 
- **WordPress Theme Customizations:** Used a Child Theme to ensure customizations remain intact after theme updates.
- **Plugin Repository Independence:** Employed symbolic links to make the plugin repository independent of specific websites.
- **Choice of Tools:** Avoided tools like Advanced Custom Fields and Custom Post Type UI plugins in favour of a manual approach.
- **Plugin Implementation:** Implemented as a Must-Use plugin to separate it from the theme and load it early during WordPress initialization.
- **Input Sanitization:** Sanitized the text fields to prevent script-injection.
- **File Access Control:** Employed absolute path checks to restrict PHP file access to within WordPress only.
- **Security Measures:** Used nonce's to prevent cross-site request forgery attacks.

Inspo: 
![image](https://github.com/shgnplaatjies/StriveSA/assets/63879125/2940497a-c745-455c-a55e-5fbabd2fac80)


![image](https://github.com/shgnplaatjies/StriveSA/assets/63879125/a8f71bee-53f0-4d42-b4eb-0c1f66663ff4)
