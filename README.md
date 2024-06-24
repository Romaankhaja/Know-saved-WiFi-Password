# WiFi-Password-generate
This Python script utilizes subprocess module to interact with Windows netsh command-line utility for WiFi management. It retrieves and displays WiFi profiles and passwords stored on a Windows system.

Features:
get_wifi_profiles(): Fetches all WiFi profiles stored on the system.
get_wifi_password(profile): Retrieves the plaintext password for a given WiFi profile.
main(): Executes the script, printing each WiFi profile along with its corresponding password.
Usage:
Ensure Python is installed on your Windows machine.
Run the script to see a list of WiFi profiles and their passwords (if available).
Requirements:
Python 3.x
Windows operating system (as it relies on netsh command)
This script is designed for educational purposes or for retrieving forgotten WiFi passwords from your own Windows machine. Caution: Ensure you have the necessary permissions to access WiFi profile information.


