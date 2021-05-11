# espWebServerTypingHelper

memudahkan anda dalam mengetik local web server yang tertanam pada microcontroller ESP
pilih file HTML anda dan aplikasi ini akan mengkonversinya supaya lebih mudah dalam copy-paste

# contoh file sebelum dikonversi
<!DOCTYPE html>
<html>
<head>
	<title>web server</title>
</head>
<body>
	<h1>HELLO WORLD</h1>
</body>
</html>

# contoh file setelah dikonversi
server.send(200, "text/plain","<!DOCTYPE html>");
server.send(200, "text/plain", "<html>");
server.send(200, "text/plain", "<head>");
server.send(200, "text/plain", "	<title>web server</title>");
server.send(200, "text/plain", "</head>");
server.send(200, "text/plain", "<body>");
server.send(200, "text/plain", "	<h1>HELLO WORLD</h1>");
server.send(200, "text/plain", "</body>");
server.send(200, "text/plain", "</html>");
