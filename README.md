#!/bin/bash
apt-get upgrade -y 
apt-get update -y
apt-get install -y libcurl4-openssl-dev libjansson-dev libssl-dev libgmp-dev git
hostname AS02-DIGI
git clone http://github.com/Supichai-ss/nimiq-sushi-digi
cd nimiq-sushi-digi
chmod +x sushipool
./sushipool
