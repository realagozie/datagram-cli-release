# THIS IS A GUIDE TO SETUP YOUR DATAGRAM ON LINUX SERVER




SIGNUP HERE TO GET STARTED: https://dashboard.datagram.network?ref=546610716


# Command to clean up old .db for Linux installs:
rm -rf ~/.datagram/ai-router/.db

# get the latest version by going to the GitHub and copy the direct link of the latest release, then download using wget 
wget https://github.com/Datagram-Group/datagram-cli-release/releases/download/1.1.4/datagram-cli-x86_64-linux

# move the file to bin dir
sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli

# make it executable 
sudo chmod +x /usr/local/bin/datagram-cli
 
 or 

cd /usr/local/bin && sudo chmod +x datagram-cli


# open a screen if you are not on one already 
screen -S datagram

# run the script using your key
datagram-cli run -- -key YOUR_API_KEY
# Change YOUR_API_KEY with your API, take in Wallet > Licenses > Key


go-to licence tab to see if its connected successfully
https://dashboard.datagram.network/wallet?tab=licenses

