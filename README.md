# Redirect Confirmer

[![Website Status](https://img.shields.io/website?down_color=red&down_message=Offline&up_color=green&up_message=Online&url=https%3A%2F%2Fredirect-confirmer.vercel.app%2F)](https://redirect-confirmer.vercel.app/)

## Overview

**Redirect Confirmer** is a simple and effective tool for validating redirects on your website. By appending the target link to the base URL, you can quickly and easily test and confirm the behavior of your site's redirects. This is especially useful for debugging and ensuring smooth user navigation.

### Key Features

- **Redirect Confirmation**: Add the desired path after the base URL to see how your redirects perform.
- **Custom 404 Page**: Utilizes a custom `404.html` page to make redirect testing pages functional and intuitive.
- **Dark Mode Toggle**: Seamlessly switch between light and dark themes for an improved user experience.
- **Validation of Destination URL**: Ensures the provided URL is valid before redirecting.
- **Responsive Design**: Adapts to different screen sizes for accessibility on various devices.

## How It Works

1. Visit the website at [redirect-confirmer.vercel.app](https://redirect-confirmer.vercel.app/).
2. Append the intended redirect path to the URL (e.g., `https://redirect-confirmer.vercel.app/example-path`).
3. The website processes and confirms the redirect behavior based on the appended path.
4. The displayed card allows users to:
   - Confirm and continue to the destination URL.
   - Go back to the previous page.

### Technical Details

- **Frontend**:
  - Built with HTML, CSS, and JavaScript.
  - Utilizes Material Icons and Roboto font for a clean and modern interface.
- **Custom Theme Management**:
  - Light and dark themes are toggleable and persist via `localStorage`.
- **Error Handling**:
  - Displays a friendly message if no URL is provided or if the URL is invalid.
- **URL Validation**:
  - Ensures that the appended path is a valid URL before attempting to redirect.

### Key Components

- **Main Card**: A central UI element that displays the confirmation prompt.
- **Dynamic URL Handling**: Extracts and validates the destination URL from the appended path.
- **Theme Toggle Button**: A fixed-position button that allows users to switch between themes.

## Usage Scenarios

- Debugging and testing URL redirects during website development.
- Verifying redirect rules and behavior after deploying updates.
- Ensuring user-friendly navigation across your web pages.

## Deployment Details

- Hosted on **Vercel** for high availability and performance.
- Leverages a custom `404.html` page to manage redirect validation.

## Get Started

Ready to test your redirects? Visit the tool here: [redirect-confirmer.vercel.app](https://redirect-confirmer.vercel.app/).

## Contributing

Contributions are welcome! If you have ideas for improvements or encounter issues, feel free to submit an issue or a pull request in this repository.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

For questions or support, please reach out through the repository's issue tracker.
