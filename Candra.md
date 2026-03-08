pkg update && pkg upgrade -y
pkg install nodejs python git -y

git clone https://github.com/... (atau buat folder manual)
cd mybot

npm init -y
npm install @whiskeysockets/baileys pino qrcode-terminal

# buat file tokens.txt & claim.py seperti di atas
# edit OWNER di bot.js