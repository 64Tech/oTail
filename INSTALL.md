# How to install oTail

## Download
```
git clone https://github.com/64Tech/oTail.git
```

## Install

oTrail requires a working MySQL Database to store the passwords, hostnames, ip addresses, etc. in.

```
mysql -p
create database otail;
```

After creating the database, we can run the table generator.

```
./create-table.sh
```

## Use
Now we have to create a new vHost for Apache/ Nginx pointing to the proper directory with PHP Support and
visit the page.
