# buildout

# install atom
# source: snapcrafters

# install chrome browser

# install brave browser
# source: snapcrafters

# install skype
# source: snapcrafters

# install slack
# source: snapcrafters

# install yadm
# nfo source: https://thelocehiliosan.github.io/yadm/
sudo apt-get install -y software-properties-common
sudo add-apt-repository -y ppa:flexiondotorg/yadm
sudo apt-get update
sudo apt-get -y install yadm

# install virtualbox
# get / add repo keys
wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -
# add repo
sudo sh -c 'echo "deb http://download.virtualbox.org/virtualbox/debian $(lsb_release -sc) contrib" >> /etc/apt/sources.list.d/virtualbox.list'
# remove old versions
sudo apt remove virtualbox*
# install prerequisites
sudo apt update
sudo apt-get -y install gcc make linux-headers-$(uname -r) dkms
# install virtualbox-5.2
sudo apt update
sudo apt-get install virtualbox-5.2

# install vagrant
sudo apt-get update
sudo apt-get install -y vagrant

# install docker
sudo apt-get update
sudo apt-get install -y docker

# install git
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install -y git 








#############################################################
# PENTESTING INSTALLS
#############################################################
# Information Gathering
#############################################################
# acccheck
# ace-voip
# Amap
# APT2
# arp-scan
# Automater
# bing-ip2hosts
# braa
# CaseFile
# CDPSnarf
# cisco-torch
# Cookie Cadger
# copy-router-config
# DMitry
# dnmap
# dnsenum
# dnsmap
# DNSRecon
# dnstracer
# dnswalk
# DotDotPwn
# enum4linux
# enumIAX
# EyeWitness
# Faraday
# Fierce
# Firewalk
# fragroute
# fragrouter
# Ghost Phisher
# GoLismero
# goofile
# hping3
# ident-user-enum
# InSpy
# InTrace
# iSMTP
# lbd
# Maltego Teeth
# masscan
# Metagoofil
# Miranda
# nbtscan-unixwiz
# Nikto
# Nmap
# ntop
# OSRFramework
# p0f
# Parsero
# Recon-ng
# SET
# SMBMap
# smtp-user-enum
# snmp-check
# SPARTA
# sslcaudit
# SSLsplit
# sslstrip
# SSLyze
# Sublist3r
# THC-IPV6
# theHarvester
# TLSSLed
# twofi
# Unicornscan
# URLCrazy
# Wireshark
# WOL-E
# Xplico

 













apt-get -f install kali_packages -y && wget http://www.morningstarsecurity.com/downloads/bing-ip2hosts-0.4.tar.gz && tar -xzvf bing-ip2hosts-0.4.tar.gz && cp bing-ip2hosts-0.4/bing-ip2hosts /usr/local/bin/
