## whatsapp bot untuk membuat sticker dari image / video / gif

## usable commands? 
	.sp
	.stk

## cara menggunakan?
	.sp (untuk mengecek speed respon bot)
	.stk
		kirim gambar dengan caption .stk
		reply gambar yang sudah dikirim dengan .stk
		
## installasi?
```
sudo apt-get install -y mc
sudo apt-get -y update
sudo apt-get -y upgrade
sudo apt-get install -y curl
sudo apt-get install -y zip
sudo apt-get install -y unzip
curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt-get install -y nodejs
sudo apt-get install -y golang
sudo apt-get install -y gcc g++ make
sudo apt-get install -y python3-pip
sudo apt-get install -y git
sudo apt-get install -y python3-pafy
sudo apt-get install -y ffmpeg
sudo apt-get install -y imagemagick
sudo apt-get install -y gifsicle
sudo apt-get install -y tesseract-ocr
sudo apt-get install -y libtesseract-dev
sudo apt-get install -y libicu-dev libpango1.0-dev libcairo2-dev
sudo apt-get update && sudo apt-get install -yq gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget
sudo timedatectl set-timezone Asia/Jakarta
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt-get install -y ./google-chrome-stable_current_amd64.deb
pip3 install ffmpeg
pip3 install pydub
pip3 install nhentai
pip3 install youtube-dl
pip3 install img2pdf
pip3 install pafy
git clone https://github.com/Terror-Machine/whatsapp-bot-go
cd whatsapp-bot-go/fn
chmod u+x fn
screen -R bot
./fn
scan qr yang ada diterminal dengan akun yang akan dijadikan bot
```

## tambahan! PENTING WAJIB DIBACA!!!
buka file .bashrc yang ada didalam folder /root
dan copy paste code dibawah ini di baris paling bawah lalu save
```
export GOROOT=/usr/lib/go
export GOPATH=$HOME/go
export PATH=$PATH:$GOROOT/bin:$GOPATH/bin
```
