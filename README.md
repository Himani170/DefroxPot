<div align="center"><p>
    <h1>DefroxPot</h1>
    <img style="filter: brightness(200%)" src="https://user-images.githubusercontent.com/122822828/216810369-34904b5a-d063-48a9-a87d-11caf293243b.png" width="50%"><br>
    <img src="https://forthebadge.com/images/badges/made-with-python.svg">
    <img src="https://forthebadge.com/images/badges/built-with-love.svg">
    <br><br>
    <a href="https://github.com/TeamDefronix/Cyberonix/releases/latest">
      <img alt="Latest release" src="https://img.shields.io/github/v/release/TeamDefronix/Cyberonix?style=for-the-badge&logo=starship&color=C9CBFF&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://github.com/TeamDefronix/Cyberonix/pulse">
      <img alt="Last commit" src="https://img.shields.io/github/last-commit/TeamDefronix/Cyberonix?style=for-the-badge&logo=starship&color=8bd5ca&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://github.com/TeamDefronix/Cyberonix/blob/main/LICENSE">
      <img alt="License" src="https://img.shields.io/github/license/TeamDefronix/Cyberonix?style=for-the-badge&logo=starship&color=ee999f&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://github.com/TeamDefronix/Cyberonix/stargazers">
      <img alt="Stars" src="https://img.shields.io/github/stars/TeamDefronix/Cyberonix?style=for-the-badge&logo=starship&color=c69ff5&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://github.com/TeamDefronix/Cyberonix/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/TeamDefronix/Cyberonix?style=for-the-badge&logo=bilibili&color=F5E0DC&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://github.com/TeamDefronix/Cyberonix">
        <img alt="Repo Size" src="https://img.shields.io/github/repo-size/TeamDefronix/Cyberonix?color=%23DDB6F2&label=SIZE&logo=codesandbox&style=for-the-badge&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=niteshlike123">
      <img alt="follow on Twitter" src="https://img.shields.io/twitter/follow/niteshlike123?style=for-the-badge&logo=twitter&color=8aadf3&logoColor=D9E0EE&labelColor=302D41" />
    </a>
    <a href="https://discord.gg/defronix">
      <img alt="Discord" src="https://img.shields.io/discord/1072407436348112896?style=for-the-badge&logo=starship&color=c69ff5&logoColor=D9E0EE&labelColor=302D41"/>
    </a>
  </p>
  <p align="center">
    <img src="https://stars.medv.io/TeamDefronix/Cyberonix.svg", title="commits"/>
  </p>

<h1 align="left">Description</h1>

<p align="left">
     DefroxPot is a honeypot project designed to detect, monitor, and analyze malicious activity in a controlled environment. This project aims to provide cybersecurity enthusiasts and professionals with a powerful tool to study attack patterns, improve defensive strategies, and enhance security awareness.
</p>


---

**[<kbd> <br> Categories <br> </kbd>][Variants]** 
**[<kbd> <br> Install <br> </kbd>][Install]**
**[<kbd> <br> Dependencies <br> </kbd>][Dependencies]** 
**[<kbd> <br> Usage <br> </kbd>][Usage]** 
**[<kbd> <br> ScreenShots <br> </kbd>][ScreenShots]** 
**[<kbd> <br> Contributors <br> </kbd>][Contributors]**

---

[Variants]: ##Variants
[Install]: ##Installation
[Dependencies]: ##Dependencies
[Usage]: ##Usage
[ScreenShots]: ##ScreenShots
[Contributors]: ##Contributors

</div>

## Variants

### Web Honeypot

The Web Honeypot simulates a vulnerable website to attract and analyze web-based attacks.

#### Features

**Web Logging**
- Records all HTTP requests and responses
- Logs IP addresses, session details, user agents, user IDs, and paths visited
- Captures keystrokes through the website

**File Analysis**
- Analyzes files uploaded by attackers to check for malicious content
- Extracts metadata from the uploaded files

**Dashboard**
- Provides a dashboard for real-time monitoring

### Network Honeypot

The Network Honeypot mimics a network environment to detect, log and analyze network-based attacks.

#### Features

**Network Logging**
- Captures and logs all network traffic
- Records IP addresses and authentication attempts via FTP or SSH services (whichever you run)

**Deceptive Environment**
- Creates a deceptive environment to trap attackers
- Simulates various network services to attract malicious activity

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/repo/HoneyGuard.git
    cd honeypot
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure the honeypot:**
      ```bash
    python manage.py migrate
    python manage.py createsuperuser
    ```
    **Note**: `python manage.py createsuperuser` is required to create for managing the DefroxPot tool

4. **Start the honeypot:**
   
    ```bash
    python manage.py runserver
    ```
   You will receive a URL with port 8000. Open this URL in your browser to access the admin panel.
   
## Dependencies
- Apart from what is in `requirements.txt` ExifTool is also required to extract metadata from images. You can visit the official website [https://exiftool.org]
- Virus total has been used to check malicious content if uploaded by an attacker [https://www.virustotal.com]

## Usage
### Website
- Navigate to the `Setup` tab and launch the web setup. You will receive a URL with port 5000 that is intended to be accessed by an attacker.
- `File Analysis`, `Photo`, `Keylogger` and `Website` tabs belong to Web honeypot. You can navigate to check logs.

### Network
- Navigate to the `Setup` tab and launch the network setup. The `ssh` and `ftp` will be started that is intended to be accessed by an attacker.
- `Network` tabs belong to network honeypot. You can navigate to check logs.

## Screenshots


## Contacts

<p align="left">
<a href="https://github.com/TeamDefronix"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/Github.svg" width="64" height="64" alt="Github Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/> <a href="https://www.facebook.com/defronix"><img src="https://raw.githubusercontent.com/gauravghongde/social-icons/master/SVG/Color/Facebook.svg" width="64" height="64" alt="Facebook Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/> <a href="https://twitter.com/teamdefronix"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/Twitter.svg" width="64" height="64" alt="Twitter Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/>
<a href="https://instagram.com/teamdefronix"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/Instagram.svg" width="64" height="64" alt="Instagram Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/>
<a href="https://whatsapp.com/channel/0029VaGltobEKyZ8eX8Ki82w"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/WhatsApp.svg" width="64" height="64" alt="WhatsApp Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/>
<a href="https://youtube.com/@defronix"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/Youtube.svg" width="64" height="64" alt="Youtube Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/>
<a href="https://www.linkedin.com/company/defronix/"><img src="https://github.com/gauravghongde/social-icons/raw/master/SVG/Color/LinkedIN.svg" width="64" height="64" alt="LinkedIN Logo"/></a> <img src="assets/misc/transparent.png" height="1" width="5"/>
</p>

## Support

<p><a href="https://www.buymeacoffee.com/metaxone" target="_blank"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Buymeacoffee" /></a></p><br><br><br>
<p><a href="https://paypal.me/niteshsinghhacker" target="_blank"> <img align="left" src="https://raw.githubusercontent.com/andreostrovsky/donate-with-paypal/master/blue.svg" height="70" width="210" alt="Donate with paypal" /></a></p><br><br><br>
<p><a href="https://tools.apgy.in/upi/Nitesh+Singh/niteshkumar5@ybl/" target="_blank"> <img align="left" style="border-radius:8px" src="https://user-images.githubusercontent.com/122822828/216837693-3480fcd2-b4fc-40ff-94f8-c5d7d4b82ad5.png" height="50" width="210" alt="Donate with paypal" /></a></p><br><br><br>
<p><a href="https://razorpay.me/@technicalnavigator" target="_blank"> <img align="left" src="https://user-images.githubusercontent.com/122822828/216838288-a946ef91-f215-4286-926f-afa71d0c3760.png" height="50" width="210" alt="Donate with paypal" /></a></p><br><be>
<br>
  
*This tool is currently a prototype and can be further improved. If you have more context or specific improvements in mind, I can tailor the sentence further to fit your needs*
<div align="center">
    <h1 id="Contributors">Thanks To All Contributors</h1>

<a href="https://github.com/TeamDefronix/Cyberonix/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=TeamDefronix/Cyberonix" />
</a>
</div>
