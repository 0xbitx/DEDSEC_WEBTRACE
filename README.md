
<p align="center">
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDA0bGZkem4ydWZ5N3RuOHZ1NW9zcWEydzR4Z3Azd3hhaXl1YmR0eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o6vXZwXqTK4186JBC/giphy.gif", width="300", height="300">
</p>

<h1 align="center">DEDSEC_WEBTRACE</h1>
<h4 align="center">all-in-one website tracking toolkit designed to help expose and track targets</h4>

### DESCRIPTION
WEBTRACE is a powerful, all-in-one website tracking toolkit designed to help expose and track targets. It seamlessly integrates tracking scripts into any webpage, allowing you to gather valuable data on suspicious individuals in real time.

With WEBTRACE, you can collect critical details such as IP addresses, browser information, geolocation, and even capture camera snapshots—helping investigators, ethical hackers, and researchers identify and analyze scam operations more effectively.

## Modes of Operation

### 1. Info Extractor Mode
This is the original tracking feature of WEBTRACE, allowing you to collect detailed visitor information with minimal interaction. Users may need to grant permissions for GPS location and camera access to capture that data.

### Features:
   * Stealth Mode – Runs in the background when the page is loaded.
   * Real-Time Tracking – Captures user details and location.
   * Camera Capture – Takes 10 snapshots if the user allows camera access.
   * URL Masking – Generates lookalike URLs to mimic legitimate pages, making links appear more convincing.
   * QR Code Generation – Creates a QR code linking to the page for easy scanning
   * Automatic Integration – No manual editing required.

### 2. Credential Extractor Mode
  This mode allows you to deploy phishing pages for credential harvesting. It includes templates for major platforms and supports OTP interception.
  ### Features:
  * Pre-Built Templates – Includes phishing pages for Facebook, Google, TikTok, and more.
  * OTP Interception – Captures login credentials even if the target enters a one-time password.
  * Automatic Template Deployment – Select the platform, and the tool auto-deploy the phishing page.
  * URL Masking – Generates lookalike URLs to mimic legitimate login pages, making phishing links appear more convincing.
  * QR Code Generation – Creates a QR code linking to the page for easy scanning
  * Credential Logging – Captures login credentials and stores them in .info

## How It Works

### Info Extractor Mode:
  * Place your project (the target website files [index.php, style.css]) inside the MYPAGE folder.
  * Run the tool, and it will inject tracking scripts into the website.
  * Deploy the modified website, and it will start tracking visitors automatically.
  * Send the link to the target, and the tool will log their details.
  * Logs are stored in .info, and camera snapshots are saved in the images folder inside your project.

### Credential Extractor Mode:
  * Select Credential Extractor Mode.
  * Choose a platform template (e.g., Facebook, Google, TikTok).
  * The tool automatically deploys the phishing page.
  * When the target enters their credentials, they are logged in .info.
  * If OTP is required, the tool captures and logs the OTP.

## Create an API Key
1. Create Temporary Email [Tempmail](https://www.emailnator.com/) (Optional)
1. Register a [T.LY Account](https://t.ly/register)
2. Create an [API Token](https://t.ly/settings#/api)

### INSTALLATION
    git clone https://github.com/0xbitx/DEDSEC_WEBTRACE.git
    pip3 install tqdm tabulate "qrcode[pil]"
    cd DEDSEC_WEBTRACE
    chmod +x dedsec-webtrace 
    ./dedsec-webtrace
    
    or
    
    sudo apt install ./dedsec-webtrace.deb
    dedsec-webtrace
  
### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.

