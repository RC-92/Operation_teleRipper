# Purpose
Operation_TeleRipper allows users to download videos shared on a Private/Public Telegram channel automatically even if download is disabled on the channel 

# Pre-Requisites
- Telegram Account
- Telegram API credentials
(Refer to Appendix: Setting up Telegram API for information on obtaining telegram API credentials)

# Scripts:
|-- listChannel.py
|-- download_videos.py

# Usage

## Get Channel ID
1. Clone the repository
2. In listChannel.py, replace the following accordingly
   API_ID = xxxxx
   API_HASH = 'xxxxx'
to get the values from Telegram API
3. Run lischannel.py
4. A list of containing Channel name with channel ID will be generated

## Download videos from specified channel 
1.  From the generated list of channels, copy the channel id of the channel you wish to rip videos from 
2. Replace the following values in download_videos.py
   API_ID = xxxxx
   API_HASH = 'xxxxx'
(get the values from Telegram API)
   CHANNEL = Replace with the channel id extracted from the previous script. 
Note: Channel ID must begin with -100
5. Run download_videos.py

