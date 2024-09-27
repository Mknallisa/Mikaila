# Mikaila Lisa's Personal Website

Welcome to **Mikaila Lisa's** personal website repository, hosted on the **Internet Computer (ICP)**. This website serves as a personal space to showcase projects, share thoughts, and create a digital presence on the decentralized web. The project is built using **DFINITY SDK** and leverages the power of the ICP for hosting and security.

## Overview

This project is a simple static website built with HTML, CSS, and JavaScript, deployed on the Internet Computer. It provides a minimalistic and elegant personal homepage where Mikaila Lisa can introduce herself and showcase her projects.

### Features
- **Decentralized Hosting**: The website is hosted on the Internet Computer, making it resistant to centralized failures.
- **Simple and Clean Design**: The site uses basic HTML and CSS to create a welcoming and professional aesthetic.
- **Customizable**: You can easily update the content, style, or even add more functionalities like a blog or portfolio.
  
## Project Structure

The project consists of the following directories and files:

/src
 └── /mikaila_lisa_website_assets
     ├── index.html         # Main HTML file
     ├── styles.css         # Optional stylesheet (for future customization)
     └── script.js          # Optional JavaScript file (for future interactivity)
dfx.json                    # DFX configuration file


### Key Files

- **index.html**: Contains the main structure and content of the webpage.
- **styles.css**: (Optional) A CSS file to define the styles used across the site.
- **script.js**: (Optional) JavaScript file for handling any dynamic behavior (currently unused).

## Getting Started

To run and deploy this project on the Internet Computer, follow these steps:

### Prerequisites

Make sure you have the following installed:

- **DFINITY SDK**: [Install guide](https://internetcomputer.org/docs/current/developer-docs/setup/install)
- **Node.js**: (For any future frontend package management)

### Installation and Deployment

1. Clone the repository:
   ```bash
   git clone https://github.com/Mknallisa/Mikaila.git
   cd Mikaila
   ```

2. Start the local Internet Computer environment:
   ```bash
   dfx start
   ```

3. Deploy the website to the Internet Computer:
   ```bash
   dfx deploy
   ```

4. After the deployment, the website will be accessible at a URL similar to:
   ```
   https://<your-canister-id>.ic0.app
   ```

### Customization

- **Content**: Edit the `index.html` file in the `/src/mikaila_lisa_website_assets` directory to change the content.
- **Styling**: Modify or add styles in the `styles.css` file.
- **JavaScript Interactivity**: Add dynamic functionality by writing custom scripts in `script.js`.

## Roadmap

Future updates and possible features:
- **Blog Section**: Add a blog to share thoughts and updates.
- **Portfolio**: Showcase projects and past work in a more structured way.
- **Contact Form**: Allow visitors to contact Mikaila Lisa directly via the website.
- **More Themes**: Add multiple design themes for the website.

## Contributing

If you have suggestions for improving the website or want to contribute, feel free to fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add some feature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For any inquiries or questions, you can reach out to Mikaila Lisa via the contact form on the website (future feature) or via the repository's issue tracker.

---

**Mikaila Lisa** - Personal Website, Powered by the Internet Computer
