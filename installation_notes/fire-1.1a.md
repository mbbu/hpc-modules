## FIRE

FIRE is a universal framework for regulatory element discovery across all genomes and data-types.

## Basic Information

Installed: March 2019
Updated: NA
Link: https://tavazoielab.c2b2.columbia.edu/FIRE/

## Usage

You can check the available versions using:
`module avail fire`

Then you can load the required version using:
`module load fire/1.1a`

## Installation

Install instructions available from https://tavazoielab.c2b2.columbia.edu/FIRE/tutorial.html

```
mv FIRE-1.1a.zip /tmp

cd /tmp

unzip FIRE-1.1a.zip

cd FIRE-1.1a

sudo mkdir -p /opt/apps/fire/1.1a

sudo chown caleb /opt/apps/fire/1.1a/

bash configure --prefix=/opt/apps/fire/1.1a

sed -i 's/prefix = \/usr\/local/prefix = \/opt\/apps\/fire\/1.1a/' Makefile
make clean
make
make install

sudo chown -R root:root /opt/apps/fire/1.1a
```
