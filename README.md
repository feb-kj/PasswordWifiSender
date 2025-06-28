# PasswordWifiSender
This PowerShell script is your ultimate tool for uncovering saved Wi-Fi networks and their passwords on a Windows machine. With just a few clicks, it scans, extracts, and formats the credentials of all stored Wi-Fi profiles. The gathered information is then seamlessly sent to a specified Discord channel via a webhook, making it perfect for keeping track of your network connections or recovering forgotten passwords.


PasswordWifiSender is a PowerShell script that retrieves the saved Wi-Fi profiles and their passwords from a Windows machine and sends them to a specified Discord channel via a webhook.  

## Features  
- Extracts all saved Wi-Fi profiles and their passwords (if available).  
- Sends the extracted information to a Discord channel using a webhook.  
- Outputs a clear and structured report of all Wi-Fi profiles and credentials.  

## Requirements  
- Windows operating system with PowerShell enabled.  
- Administrator privileges to run the script (required to access Wi-Fi profile data).  
- A Discord webhook URL for sending the data.  

## How to Use  

1. **Set Up a Discord Webhook**  
   - Go to the channel settings in Discord.  
   - Navigate to **Integrations > Webhooks** and create a new webhook.  
   - Copy the webhook URL.


  (Edit the Script: $webhookUrl = "INSERISCI_IL_TUO_URL_WEBHOOK_QUI")   

2. **Download the Script**  
   Clone or download this repository to your local machine.
