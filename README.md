# Update NodeJS in Parrot OS

Default Nodejs in Parrot OS is v12, to update nodejs do the following

1. Remove preinstalled versino of nodejs and npm

`sudo apt purge --auto-remove nodejs npm`

2. Clean terminal and install npm

`sudo apt install npm`

That's it, now check version of nodejs and npm

`node -v && npm -v`
