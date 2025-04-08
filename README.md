🎮 Steam Profile Avatar Downloader :

This Python script allows you to download the real, high-resolution avatar from any public Steam profile using the Steam ID. It uses web scraping with requests and BeautifulSoup to extract the actual avatar image via OpenGraph tags.

✅ Features:

Downloads full-size Steam profile pictures.

Simple and clean code using standard libraries.

Helpful output messages for clarity.

🛠️ Requirements :
Make sure you have the required Python packages:
pip install requests beautifulsoup4

🚀 How to Use :
Clone or download this repository:
git clone https://github.com/your-username/steam-avatar-downloader.git
cd steam-avatar-downloader
Open the steam_avatar.py file.

Replace the steamid in the URL with the actual Steam ID64 of the user:
url = "https://steamcommunity.com/profiles/76561197960435530/"
Run the script:
python steam_avatar.py
The real full-size avatar will be saved as:
real_steam_avatar.jpg

🔍 Example
Replace:
url = "https://steamcommunity.com/profiles/steamid/"
With:
url = "https://steamcommunity.com/profiles/76561198006409530/"


⚠️ Notes

Works only with public profiles.

Does not work with custom URLs (like steamcommunity.com/id/yourname) — you must use the numeric Steam ID64.

For best results, verify the ID on https://steamid.io.
