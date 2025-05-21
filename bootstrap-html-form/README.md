# Bootstrap HTML Form

This project is a simple HTML form styled with Bootstrap and includes form validation using HTML5 attributes. The form collects a user's name, email, and message.

## Project Structure

```
bootstrap-html-form
├── src
│   ├── index.html
│   └── css
│       └── styles.css
├── README.md
```

## Getting Started

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/bootstrap-html-form.git
   cd bootstrap-html-form
   ```

2. **Open the project**:
   Open the `src/index.html` file in your web browser to view the form.

## Dependencies

This project uses Bootstrap for styling. You can include Bootstrap via CDN in the `index.html` file:

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
```

## Form Validation

The form includes basic HTML5 validation attributes:
- `required`: Ensures that the user fills out the field.
- `type="email"`: Validates that the input is in the correct email format.
- `maxlength`: Limits the number of characters in the message field.

## Custom Styles

You can customize the appearance of the form by editing the `src/css/styles.css` file.

## Deploying with GitHub Pages

To deploy your form using GitHub Pages, follow these steps:

1. Push your code to a GitHub repository.
2. Go to the repository settings.
3. Scroll down to the "GitHub Pages" section.
4. Select the branch you want to deploy (usually `main` or `master`).
5. Click "Save".

Your form will be available at `https://yourusername.github.io/bootstrap-html-form/`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.