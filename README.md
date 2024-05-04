# Bootstrap 5.3+ Auto Dark / Light Mode
Switches Bootstrap 5.3+ theme automatically between light and dark mode based on the system settings

This simple JavaScript is designed for Bootstrap 5.3 + and modern browsers. The buttons below are just for testing and not used in production (although they could with little modification).

We use the "Window.matchMedia" method in combination with the "CSS prefers-color-scheme" media feature to determine if the user has indicated the preference for a dark color scheme.

## How it Works:
If the user has their system preference for a dark color scheme, set the data-bs-theme attribute to "dark" on the html tag. Please note that data-bs-theme is not a native Bootstrap -5.3 attribute – you'll need to implement the actual styling behavior corresponding to this attribute yourself if not using 5.3+.

The JavaScript automatically controls the < html lang="en" data-bs-theme="dark" > or < html lang="en" data-bs-theme="light" >

## Compatibility:
The Window.matchMedia method in combination with the CSS prefers-color-scheme media feature works on modern web browsers on Windows, macOS and Linux desktops. The feature should work on modern mobile browsers on both Android and iOS. On iOS, starting from iOS 13, users can choose their preferred color scheme.

However, note that this is a relatively new feature, and older browsers may not support it. It's always good to provide a fallback for users on these browsers IF you wish to support them.

### Learn More => https://codinginbarn.github.io/bootstrap5-auto-light-dark/
