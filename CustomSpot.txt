### Spicetify

#### Install Spicetify:
Open powershell, and Copy Paste this:
iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex

##### Install Marketplace:
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex

### Block auto update
Open Command Prompt, then do these:

del "%localappdata%\Spotify\Update"
mkdir "%localappdata%\Spotify\Update"
icacls "%localappdata%\Spotify\Update" /deny "%username%":D
icacls "%localappdata%\Spotify\Update" /deny "%username%":R
