# Install a webserver on Raspberry Pi.

Run this to get your system updated with latest sources & package versions.
```sudo apt-get update && sudo apt-get upgrade -y```

Now install nginx
```sudo apt-get install nginx -y```

And thats it, now you can put your HTML-Files into **/var/www/html**.
Dont forget to delete a file called index.nginx-*your os*.html, thats the example file.

Now you can access your website via your browser.
