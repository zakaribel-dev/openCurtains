Curtain Control with Flask and Raspberry Pi
This project uses Flask to control a motorized curtain via a Raspberry Pi.

Prerequisites
Raspberry Pi with Raspberry Pi OS
Connected servomotor
Python 3
Installation
Clone the Repository


git clone https://github.com/zakaribel-dev/openCurtain.git
cd openCurtain
Create a Virtual Environment


python3 -m venv venv
source venv/bin/activate
Install Dependencies



pip install -r requirements.txt
Configuration
Edit openCurtain.py to adjust the GPIO pin numbers to your configuration.

Run the Server
bash
Copier le code
python openCurtain.py
Access the Routes
Open the Curtain: http://<RaspberryPiAddress>:5000/open
Close the Curtain: http://<RaspberryPiAddress>:5000/close
