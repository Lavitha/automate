#!/bin/bash
export http_proxy="http://p12168:lavi*vk@netmon.iitb.ac.in:80/"
cd  scilab.in/textbook_companion/generate_book
now=$(date +"%Y-%m-%d-%S")
filename="my_program.$now.log"
# example filename: my_program.2012-01-23-47.log

find . -type f -size -51k > /home/lavitha/Desktop/Link-1/$filename

cd /home/lavitha/Desktop/Link-1/
mpack -s Log_report_`date +%d%b%Y` -d body_txt Script_Monitor.log lavita89@gmail.com
