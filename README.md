sudo apt update
sudo apt install -y git curl
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs
node -v
npm -v
git clone https://github.com/btc-vision/OP_20.git
cd OP_20
nano src/contracts/MyToken.ts