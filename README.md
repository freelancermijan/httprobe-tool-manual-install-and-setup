<h2 align='center'>httprobe tool manual install and setup</h2>

### Before install you need to install go language on your system.
## Follow my instruction

#### update your system
    sudo apt update -y

#### install go language
    sudo apt install golang -y

#### Go to `/opt/` directory
    cd /opt/

#### Cloning Repository && changing dir
    sudo git clone https://github.com/tomnomnom/httprobe.git && cd httprobe

#### Setup `main.go` file & rename it into `httprobe`
    sudo go build main.go && sudo mv main httprobe

#### Go back to Home dir
    cd ..

#### Run this command
    sudo ln -s /opt/httprobe/httprobe /usr/bin/httprobe

#### It's Done. For testing run this command
    httprobe -h