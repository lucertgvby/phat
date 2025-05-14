# 📧 Phat: Email Header Analysis Tool

![Phat Logo](https://img.shields.io/badge/Phat-Email%20Header%20Analyzer-blue)

Welcome to the **Phat** repository! This graphical PowerShell application is designed to assist investigators, security analysts, and IT professionals in examining email headers for signs of phishing or spoofing. By parsing headers from `.eml` and `.msg` files, Phat highlights crucial fields and provides insights into SPF, DKIM, and DMARC results.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Supported Formats](#supported-formats)
- [Understanding Email Security](#understanding-email-security)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User-Friendly Interface**: A clean and intuitive graphical interface that simplifies the analysis process.
- **Header Parsing**: Efficiently parses `.eml` and `.msg` files to extract important header information.
- **Highlighting Key Fields**: Important fields such as "From," "To," "Subject," and "Received" are highlighted for easy reference.
- **Security Insights**: Provides detailed insights into SPF, DKIM, and DMARC results, helping you understand the legitimacy of an email.
- **Multi-Platform Support**: Runs on any system that supports PowerShell, making it versatile for different environments.

## Installation

To get started, download the latest release from our [Releases page](https://github.com/lucertgvby/phat/releases). Once downloaded, execute the installer to set up the application on your system.

## Usage

After installation, launch the application. You will see an interface where you can upload your `.eml` or `.msg` files. Follow these steps:

1. Click on the "Upload" button.
2. Select the email file you want to analyze.
3. View the parsed results displayed on the screen.
4. Check the highlighted fields and security insights for further analysis.

## How It Works

Phat operates by reading the email headers from the specified file formats. It utilizes PowerShell scripts to extract relevant information, which is then presented in an easy-to-read format. The application highlights important fields, allowing users to quickly assess the email's legitimacy.

## Supported Formats

Phat currently supports the following email formats:

- `.eml`: Standard format for email messages.
- `.msg`: Microsoft Outlook email message format.

## Understanding Email Security

### SPF (Sender Policy Framework)

SPF helps verify that the email comes from an authorized server. It prevents spoofing by checking the sender's IP address against a list of authorized IPs.

### DKIM (DomainKeys Identified Mail)

DKIM adds a digital signature to the email header. This signature verifies that the email content has not been altered during transit.

### DMARC (Domain-based Message Authentication, Reporting & Conformance)

DMARC builds on SPF and DKIM. It allows domain owners to set policies on how to handle emails that fail authentication checks.

## Contributing

We welcome contributions from the community! If you would like to contribute to Phat, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your forked repository.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, please reach out via GitHub issues or contact the maintainer directly at [maintainer@example.com](mailto:maintainer@example.com).

## Conclusion

Phat is a powerful tool for anyone looking to analyze email headers and enhance their understanding of email security. By leveraging this application, you can better protect yourself and your organization from phishing and spoofing attacks. 

Don't forget to check the [Releases page](https://github.com/lucertgvby/phat/releases) for the latest updates and versions!