kali does not provide the compose.yaml
this must be run with docker run

firsat you pull

docker pull kalilinux/kali-last-release

then you run

docker run --tty --interactive kalilinux/kali-rolling


once in you need to run 
    sudo apt update && apt -y install kali-linux-headless

