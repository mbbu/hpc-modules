## ParDRe

ParDRe is a parallel tool to remove duplicate reads. 

## Basic Information

Installed: April 2019

Updated: NA

Link: https://sourceforge.net/projects/pardre/

## Usage

You can check the available versions using:
`module avail pardre`

Then you can load the required version using:
`module load pardre/1.1`

## Installation

Install instructions: https://sourceforge.net/projects/pardre/

```
sudo mkdir -p /opt/apps/pardre/rel2.2.5

sudo chown caleb /opt/apps/pardre/rel2.2.5

cd /tmp

wget https://liquidtelecom.dl.sourceforge.net/project/pardre/ParDRe-rel2.2.5.tar.gz

tar xf ParDRe-rel2.2.5.tar.gz

cd ParDRe-rel2.2.5/source

make

%TODO: Still to figure out the setup

mv pardre /opt/apps/pardre/1.1

sudo chown -R root:root /opt/apps/pardre/1.1
```
