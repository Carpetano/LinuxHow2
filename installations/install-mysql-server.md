# Install mysql-server

##### As usual make sure to update before installing new software

Install command:

```
sudo apt install mysql-server
```

Configure securely mysql-server's (optional, but it's recommended)

```
sudo mysql_secure_installation
```

Start the mysql service

```
sudo systemctl start mysql
```

Log in as root:
```
mysql -u root -p
```
