# espWebServerTypingHelper

memudahkan anda dalam mengetik local web server yang tertanam pada microcontroller ESP
pilih file HTML anda dan aplikasi ini akan mengkonversinya supaya lebih mudah dalam copy-paste

# contoh file sebelum dikonversi

<title>web server</title>

# contoh file setelah dikonversi

server.send(200, "text/plain", "	<title>web server</title>");
