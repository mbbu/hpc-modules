## SPAdes 

SPAdes – St. Petersburg genome assembler – is an assembly toolkit containing various assembly pipelines. This manual will help you to install and run SPAdes. SPAdes version 3.13.1 was released under GPLv2 on April 11, 2019 and can be downloaded from http://cab.spbu.ru/software/spades/. 

## Basic Information
Installed: September, 2019

Updated: NA

Link: http://cab.spbu.ru/software/spades/

## Usage
You can check the available versions using:
`module avail spades`

Then you can load the required version using:
`module load spades/3.13.0`

## Installation
Install instructions available from: http://cab.spbu.ru/software/spades/

```
sudo mkdir -p /opt/apps/spades/3.13.0

sudo chown caleb /opt/apps/spades/3.13.0

cd /tmp

wget http://cab.spbu.ru/files/release3.13.1/SPAdes-3.13.1-Linux.tar.gz

tar xf SPAdes-3.13.1-Linux.tar.gz

cd SPAdes-3.13.1-Linux

mv * /opt/apps/spades/3.13.0

sudo chown -R root:root /opt/apps/spades/3.13.0
```
