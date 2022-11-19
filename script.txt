#!/bin/bash

apt update
apt install apache2 -y

echo "<html>
<head>
  <title>GlobalLogic</title>
</head>
<body>
  <p> Oleh Lozhynskiy </p>
</body>
</html>" > /var/www/html/index.html