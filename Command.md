# Hyperbolic Node Run Guide

- No need high end PC or Laptop to start node
- You can run node using mobile phone also
- Download the app for mobile users: https://play.google.com/store/apps/details?id=tech.ula&pli=1

# Create your Hyperbolic Dashboard
https://app.hyperbolic.xyz/

- Register Your Number
- Use All The Ai Models
  

# Download Dependencies 
```
sudo apt update && sudo apt upgrade -y
```
```
sudo apt install git screen python3
```
```
sudo apt install python3.10-venv
```
```
sudo apt install nano
```
---

# Download Node Files
```
git clone https://github.com/0xmoei/chatbot-app.git
```
```
cd chatbot-app
```
---

# Python
```
python3 -m venv venv
```
```
source venv/bin/activate
```
---

## Install Configuration Files
```
pip install requests
```
---

# Connect Node With Your Hyperbolic dashboard using API

```
nano chatbot.py
```
- Open Hyperbolic dashboard & go to setting option copy the API Key
- PASTE YOUR API KEY here "YOUR_API_KEY_HERE" 
- Use Arrows keys in the Terminal for Moving the Cursor
- Then Click CTRL button + X to Save Then Press Y
- Then Hit Enter

# Now Run your Node
```
python3 chatbot.py
```
---

# To Start Node Next Day use the given Command 👇
```
cd chatbot-app
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
python3 chatbot.py
```
