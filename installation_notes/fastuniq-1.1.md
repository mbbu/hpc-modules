
## FastUniq

FastUniq is an ultrafast de novo tool for removal of duplicates in paired short DNA sequence reads in FASTQ format.

## Basic Information

Installed: April 2019

Updated: NA

Link: https://sourceforge.net/projects/fastuniq/files/

## Usage

You can check the available versions using:
`module avail fastuniq`

Then you can load the required version using:
`module load fastuniq/1.1`

## Installation

Install instructions available from https://sourceforge.net/projects/fastuniq/files/

```
sudo mkdir -p /opt/apps/fastuniq/1.1

sudo chown caleb /opt/apps/fastuniq/1.1

cd /tmp

wget https://liquidtelecom.dl.sourceforge.net/project/fastuniq/FastUniq-1.1.tar.gz

tar xf FastUniq-1.1.tar.gz

cd FastUniq/source

make

mv fastuniq /opt/apps/fastuniq/1.1

sudo chown -R root:root /opt/apps/fastuniq/1.1
```
