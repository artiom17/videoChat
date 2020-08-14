# videoChat

npm init -y

npm i express ejs socket.io

npm i uuid

npm i --save-dev nodemon

npm run devStart (devStart это название указанное в package.json и можно выбрать любое название)

npm i -g peer

peerjs --port 3001
Если выдает ошибку внутри папки пишем Set-ExecutionPolicy RemoteSigned


Для того чтобы выложить делаем:

npm install -g pm2

оно работает в фоновом режиме

pm2 start server.js (server.js это название файла)

npm install pm2-windows-startup -g

pm2-startup install
pm2 save
