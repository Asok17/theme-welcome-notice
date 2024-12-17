# Theme Welcome Notice

Simple code that adds theme's welcome notice in the WordPress dashboard.

== Usage ==

```php
// Load welcome notice class file.
require get_theme_file_path() . '/theme-welcome-notice/class-theme-welcome-notice.php';

// Initialize the class.
new Theme_Welcome_Notice(
    'Fascinate', // Theme name.
    home_url(),  // Redirect URL once "Get Started" button is clicked.
    array( // Required plugins.
        'plugin-slug/plugin-file.php' => 'https://downloads.wordpress.org/plugin/plugin-slug.zip',
    )
);
```

== Changelog ==

= 1.0.0 - 17 December 2024 =
* Initial release
