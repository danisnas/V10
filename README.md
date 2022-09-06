apt update && apt upgrade

pkg install bash nodejs ffmpeg libwebp git mc yarn

git clone https://github.com/danisnas/V10.git

cd V10

yarn

rm -rf session.json

npm start

```

step 2 sdcard

termux-setup-storage

cd /sdcard

cd V10

npm start
