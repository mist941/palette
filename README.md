# Your SCSS Variable Library

A collection of reusable SCSS variables to streamline styling across projects.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install and use this SCSS variable library in your project, you can use npm:

```bash
npm install @mist/palette
```

## Usage

Import the library in your SCSS file:

```scss
@import '@mist/palette';
```
Now you can use the variables in your styles:

```scss
body {
  color: $gray-300;
  background-color: $blue-900;
}
```

You can also use predefined colors for light and dark theme:

```scss
body {
  color: var(--text-light);
  background-color: var(--bg-base);
}
```

You can change the theme in any convenient way by setting the data attribute to the html tag. For example:
```js
document.documentElement.setAttribute('data-theme', 'light');
```
or
```js
document.documentElement.setAttribute('data-theme', 'dark');
```

## Contributing
If you would like to contribute to the library, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

## License
This project is licensed under the MIT License, which means you are free to use, modify, and distribute the code, but you must include the original copyright and license information.