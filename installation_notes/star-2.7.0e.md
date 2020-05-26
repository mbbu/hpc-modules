## STAR

STAR (Spliced Transcripts Alignment to a Reference) is an RNA-seq aligner. 

## Basic Information

Updated: March, 2019
Link: https://github.com/alexdobin/STAR

## Usage
You can check the available versions using:
`module avail star`

Then you can load the required version using:
`module load star/2.7.0e`

## Installation
```
cd /tmp
wget https://github.com/alexdobin/STAR/archive/2.7.0e.tar.gz
tar xf 2.7.0e.tar.gz
sudo mkdir /opt/apps/star/2.7.0e/bin
sudo cp -rv STAR-2.7.0e/bin/Linux_x86_64/STAR* /opt/apps/star/2.7.0e/bin

```
