Alert Bounties
AlertBounties is a TypeScript Node.js project designed to keep you informed about new bounties on Algora Console. It utilizes Puppeteer for web scraping and Resend for email notifications.

How it Works
The script automatically scrapes new bounties from Algora Console every 25 minutes (customizable) and sends email notifications to the user. Stay ahead in the bounty hunting game with timely updates!

Technologies Used
Scraping: Puppeteer
Language: TypeScript, Node.js
Email Service: Resend
Getting Started
To use AlertBounties, follow these steps:

Fork this repository.

Obtain your Resend API key from Resend API Keys and your Algora Console session token.

Copy .env.example to .env

  cp .env.example .env
Add the following secrets to environment variables:

RESEND_API_KEY: Your Resend API key.
SESSION_TOKEN: The value of the '__Secure-next-auth.session-token' cookie from Algora Console.
USER_EMAIL: Your Resend login email (this email is used to receive updates).
Add the RESEND_API_KEY, SESSION_TOKEN and USER_EMAIL secret to your forked repository by following the steps outlined in the GitHub Actions documentation.

Contributing
Contributions are welcome! Feel free to open issues or pull requests.

If you find this project helpful, don't forget to star the repository!

Happy bounty hunting! 🚀
