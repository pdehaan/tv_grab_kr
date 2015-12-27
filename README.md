tv_grab_kr
==========

XMLTV grabber for NAVER TV편성표 (tvguide.naver.com)

Prerequisits
============

nodejs

Running
======= 

Usage: node tv_grab_kr.js [OPTION]
Options:
  -e, --exclude-channel=CH1,CH2,... specify the channels to be excluded by using comma separated list
  -g, --channel-group=GR1,GR2,...   select channel group
  -h, --help                        show usage information
  -l, --list-channel-group          list all available channel group
  -n, --days=X                      supply data for X days
  -o, --offset=X                    start with data for day today plus X days
  -w, --output=FILENAME             redirect xmltv output to the specified file
  -s, --sock=SOCKET                 redirect xmltv output to the specified XMLTV socket