# shop_nodejs
#### Step 1: Update system
As a norm, we work on an updated system to ensure we don’t have dependency issues.

```
sudo apt update
sudo apt -y upgrade
```

####Step 2: Add Node.js APT Repository
All releases of Node.js are derivable from the official APT repository. However, this needs to be added to your system manually.

```
sudo apt update
sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```

#### Step 3: Install Node.js 12 on Ubuntu / Debian / Linux Mint
Node.js repository has been added, The next step is installation of Node.js 12 on Ubuntu / Debian / Linux Mint. Running the following commands is all that’s needed for the installation.

```
sudo apt -y install nodejs
```

You can as well install development tools used to build native addons:

```
sudo apt -y  install gcc g++ make
```
