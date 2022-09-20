[√] Description :

Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.

[*]Announcent

This project is now a part of MaxPhisher. Further bug fixes and feature addition will be available in that

[+] Installation

Install dependencies (git, python, php ssh)

For Debian (Ubuntu, Kali-Linux, Parrot)

sudo apt install git python3 php openssh-client -y

For Arch (Manjaro)

sudo pacman -S git python3 php openssh --noconfirm

For Redhat(Fedora)

sudo dnf install git python3 php openssh -y

For Termux

pkg install git python3 php openssh -y

Clone this repository

git clone https://github.com/KasRoudra/PyPhisher

Enter the directory

cd PyPhisher

Install all modules

pip3 install -r files/requirements.txt

Run the tool

python3 pyphisher.py

Or, directly run

wget https://raw.githubusercontent.com/Mrsilent/PyPhisher/main/pyphisher.py && python3 pyphisher.py

Pip

pip3 install pyphisher [For Termux]

sudo pip3 install pyphisher [For Linux]

pyphisher

Docker

sudo docker pull kasroudra/pyphisher

sudo docker run --rm -it kasroudra/pyphisher

Options

usage: pyphisher.py [-h] [-p PORT] [-o OPTION] [-t TUNNELER]

                    [-r REGION] [-S SUBDOMAIN] [--noupdate]

options:

  -h, --help            show this help message and exit

  -p PORT, --port PORT  PyPhisher's server port [Default : 8080]

  -o OPTION, --option OPTION

                        PyPhisher's template index [Default : null]

  -t TUNNELER, --tunneler TUNNELER

                        Tunneler to be chosen while url shortening

  -r REGION, --region REGION

                        Region for ngrok and loclx [Default: auto]

  -S SUBDOMAIN, --subdomain SUBDOMAIN

                        Subdomain for ngrok and loclx [Pro Account]

                        (Default: null)

  --noupdate            Skip update checking

Features:

Multi platform (Supports most linux)

Easy to use

Possible error diagnoser

77 Website templates

Concurrent 4 tunneling (Ngrok, Cloudflared, Loclx and LocalHostRun)

Upto 8 links for phishing

OTP Support

Argument support

Credentials mailing

Built-in masking of URL

Custom masking of URL

URL Shadowing

Redirection URL settings

Portable file (Can be run from any directory)

Get IP Address and many other details along with login credentials

Relevant Tools by Me

CamHacker for image phishing

VidPhisher for video phishing

Requirements

Python(3)

requests

bs4

PHP

SSH

200MB storage

If not found, php and python modoules will be installed on first run

Tested on

Termux

Ubuntu

Kali-Linux

Arch

Fedora

Manjaro

Usage

Run the script

Choose a Website
