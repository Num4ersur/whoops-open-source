# Whoops Project

This is the GitHub repository for the **Whoops Project**.

## Description

The **Whoops Project** is a project that involves video playback and overlays. It provides a video player with an overlay that displays error messages and system information in case of playback issues.

## Translated README.md

- [English](README.md)
- [Spanish (Español)](https://github.com/Num4ersur/whoops-open-source/blob/main/es/README_SPANISH.md)
  
## Important Note

When using this project, please consider the following:

- Secret videos are named as `secret_xx_{LANGUAGE}.mp4`, where `{LANGUAGE}` should be replaced with the appropriate language code.
- Do not modify or rename the language folders. These folders are necessary for the page to detect different supported languages.

## Usage

To use the **Whoops Project**, follow these steps:

1. Clone the repository: `git clone https://github.com/Num4ersur/whoops-open-source.git`
2. Open the `index.html` file in a web browser that supports video playback.

## Hosting the Project

You can host the **Whoops Project** on various platforms:

- **Glitch**: Remix the project on Glitch by visiting [https://glitch.com/edit/#!/import/git?url=https://github.com/Num4ersur/whoops-open-source.git](https://glitch.com/edit/#!/import/git?url=https://github.com/Num4ersur/whoops-open-source.git).
- **Replit**: Remix the project on Replit by visiting [https://replit.com/github/Num4ersur/whoops-open-source](https://replit.com/github/Num4ersur/whoops-open-source).
- **Neocities**: Please note that Neocities may require a paid plan for video uploads. To host using Neocities:
  1. Download the project ZIP file from GitHub.
  2. Log in to your NeoCities account.
  3. Upload the ZIP file or extract it to your NeoCities site.
  4. Important: Be aware that video uploads may require a paid plan as NeoCities free tier may not support video uploads.
- **Tinkerhost / Infinity Free**:
  1. Download the project ZIP file from the GitHub repository.
  2. Log in to your Tinkerhost or Infinity Free account.
  3. Access the "MY Accounts" section.
  4. Connect to the FTP of your account using FTP programs like [FileZilla](https://filezilla-project.org/), [Cyberduck](https://cyberduck.io/), or [WinSCP](https://winscp.net/eng/index.php).
  5. Upload the project files into the `.htdocs` folder.
  6. Caution: Using Tinkerhost or Infinity Free's free plan has a limit of 50,000 hits. Exceeding this limit could lead to your website being suspended for 24 hours. You can check your hit count by accessing the "Control Panel" of your account.
  7. Warning: If Tinkerhost / Infinity Free detects your website as a video-sharing platform, they may suspend your site. If you encounter such issues, consider reaching out to the [support team of Infinity Free](https://forum.infinityfree.net/) or [Tinkerhost](https://community.tinkerhost.net/).
  8. Final Warning: Do not use the online FTP provided by Tinkerhost / Infinity Free as it might cause issues. Instead, consider using FTP programs like [FileZilla](https://filezilla-project.org/), [Cyberduck](https://cyberduck.io/), or [WinSCP](https://winscp.net/eng/index.php).
  - **Vercel**: Deploy the project on Vercel by following these steps:
  1. Clone the repository: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Install Vercel CLI (if not installed): `npm install -g vercel`
  3. Navigate to the project folder: `cd whoops-open-source`
  4. Deploy the project using Vercel: `vercel`
- **Netlify**: Deploy the project on Netlify by following these steps:
  1. Clone the repository: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Sign up for a Netlify account if you don't have one.
  3. Connect your GitHub account to Netlify.
  4. Create a new site from Git and select your GitHub repository.
  5. Configure the build settings and deploy the site.
- **GitHub Pages**: Host the project on GitHub Pages by following these steps:
  1. Push your changes to the `gh-pages` branch of your repository.
  2. Go to the repository's Settings > Pages.
  3. Select the `gh-pages` branch as the source and save.
- **Ngrok** (Warning: Reveals your public IP): Make the project public using Ngrok and Python's web server:
  1. Clone the repository: `git clone https://github.com/Num4ersur/whoops-open-source.git`
  2. Navigate to the project folder: `cd whoops-open-source`
  3. Start a web server with Python:
     - **Windows**: Run `python -m http.server` in the Command Prompt.
     - **macOS / Linux**: Open a terminal and run `python3 -m http.server`.
  4. Download and configure Ngrok from [https://ngrok.com/download](https://ngrok.com/download):
     - **Windows**: Download the ZIP file and extract it.
     - **macOS / Linux**: Download the file and move the executable to an accessible location.
  5. Run Ngrok to expose the server:
     - **Windows**: Run `ngrok http 8000` in the Command Prompt.
     - **macOS / Linux**: Open a terminal and run `./ngrok http 8000`.
  6. Warning: Visiting the Ngrok URL will reveal your public IP. Consider using a VPN for added security.
## Recommended VPNs for Added Security

To enhance your online security and privacy while hosting your project, consider using a Virtual Private Network (VPN). Here are a couple of options:

- **Paid VPNs**:
  - ExpressVPN: Offers strong encryption and a wide range of server locations. [Website](https://www.expressvpn.com/)
  - NordVPN: Known for its robust security features and large server network. [Website](https://nordvpn.com/)

- **Free VPNs**:
  - ProtonVPN: Provides a limited free plan with secure encryption and no data caps. [Website](https://protonvpn.com/)
  - Windscribe: Offers a free plan with a generous data allowance and strong privacy features. [Website](https://windscribe.com/)

Remember that while free VPNs are a good starting point, paid VPNs generally offer more advanced features and stronger security. Choose the one that best fits your needs and budget.

Please note that using a VPN is just one of the measures to protect your online privacy. Always ensure you are using secure practices when hosting with ngrok.



## Contributing

We welcome contributions to the **Whoops Project**! If you want to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m "Add your changes"`
4. Push to your forked repository: `git push origin feature/your-feature`
5. Create a pull request to the main repository.

## Issues

If you encounter any issues while using the **Whoops Project**, please report them on our [Discord server](https://discord.gg/zgzh6REz2d).

## License

This project is licensed under the [MIT License](LICENSE).

---

**Note:** This project uses HTML, CSS, and JavaScript to create a video player with an overlay for error messages and system information. The video player automatically loads and plays videos, but it also checks for compatibility with the browser. Please follow the hosting instructions above if you wish to deploy the project on different platforms.
