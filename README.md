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

# extra discord task for Early Alpha Tester Role role
➖ Join Discord (https://discord.gg/datagramnetwork)

(new dev) fill this form to get early alpha testnet role https://docs.google.com/forms/d/e/1FAIpQLSevC3QjAx4xdNysKoRtCSR_5cAUtVBhoNu3XoCrQBIOYVQN8A/viewform


# NB
Just a reminder for everyone that the uptime points are only distributed every six hours or so on-average, with four check-in points on-chain per day. The time at which this happens for your individual node is randomized so that there isn't chain congestion with everyone hitting the chain at the same time. 
This means that for each six-hour period, there will be one distribution of uptime points for your node SOMEWHERE in that six hour window. Hypothetically, you could have the first uptime in minute 1 of your first six-hour window and minute 360 of your second window, meaning that you could have no points showing up for almost 12 hours. 
