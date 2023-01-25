# httprobe tool manual install and setup
## Before install you need to install go language on your system.
## Follow my instruction

#### update your system
    sudo apt update -y

#### install go language
    sudo apt install golang -y

#### Go to `/opt/` directory
    cd /opt/

#### Cloning Repository && changing dir
    sudo git clone https://github.com/tomnomnom/httprobe.git && cd httprobe

#### Setup `main.go` file
    sudo go build main.go