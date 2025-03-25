
<p align="center">
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMDA0bGZkem4ydWZ5N3RuOHZ1NW9zcWEydzR4Z3Azd3hhaXl1YmR0eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o6vXZwXqTK4186JBC/giphy.gif", width="300", height="300">
</p>

<h1 align="center">DEDSEC_WEBTRACE</h1>
<h4 align="center">all-in-one website tracking toolkit designed to help expose and track scammers.</h4>

### DESCRIPTION

WEBTRACE is a powerful, all-in-one website tracking toolkit designed to help expose and track scammers. It seamlessly integrates tracking scripts into any webpage, allowing you to gather valuable data on suspicious individuals in real time.

With WEBTRACE, you can collect critical details such as IP addresses, browser information, geolocation, and even capture camera snapshots—helping investigators, ethical hackers, and researchers identify and analyze scam operations more effectively.

This tool automatically converts any website into a tracker that collects visitor information, including:

  * IP Address
  * Browser Information
  * Device & OS Details
  * Screen Size & Resolution
  * Referrer URL
  * WebRTC Local IP
  * Geolocation (GPS)
  * Camera Snapshots (10 Shots)

Once a scammer opens the converted page, it gathers and stores their details without requiring interaction.
How It Works

  * Place your project (the target website files [index.php, style.css]) inside the MYPAGE folder.
  * Run the tool, and it will inject tracking scripts into the website.
  * Deploy the modified website, and it will start tracking visitors automatically.
  * Track Scammer: Send the link to the scammer, and the tool will log their details.
  * View Captured Data: Logs are stored in .info, and camera snapshots are saved in the images folder inside your project.

## Features
  * Stealth Mode – Runs in the background when the page is loaded.
  * Real-Time Tracking – Captures user details and location.
  * Camera Capture – Takes 10 snapshots if the user allows camera access.
  * Automatic Integration – No manual editing required.

## Create an API Key
1. Create Temporary Email [Tempmail](https://www.emailnator.com/) (Optional)
1. Register a [T.LY Account](https://t.ly/register)
2. Create an [API Token](https://t.ly/settings#/api)

### INSTALLATION
    git clone https://github.com/0xbitx/DEDSEC_WEBTRACE.git
    cd DEDSEC_WEBTRACE
    python3 -m pip install tabulate tqdm
    chmod +x dedsec_webtrace 
    ./dedsec_webtrace


### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  
## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.

## Contributing

Pull requests are welcome! Feel free to improve the tool and submit changes.
