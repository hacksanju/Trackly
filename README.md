# Trackly
What is Trackly?

Trackly is a tool that can remotely capture the exact GPS coordinates of a target device using a PHP server, and can also grab basic information about the system and ISP. This tool can be very helpful in information gathering. you can get following information of the target device

    Longitude
    Latitude
    Device Model
    Operating System
    Number of CPU Cores
    Screen Resolution
    User agent
    Public IP Address
    Browser Name
    ISP Information

Features

The tool offers a wide range of features and functionality, including:

    Capture Exact GPS Location
    Automated Data Collection
    User-friendly Interface

This Tool Tested On :

    Kali Linux
    Windows(WSL)
    Ubuntu

Installing and requirements

This tool require PHP for webserver, wget & unzip for download and extract cloudflare. First run following command on your terminal

apt-get -y install php unzip git wget

Installing (Kali Linux):

git clone https://github.com/hacksanju/Trackly
cd Trackly
bash trackly.sh
