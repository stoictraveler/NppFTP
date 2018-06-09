# NppFTP
Plugin for Notepad++ allowing FTP, FTPS, FTPES and SFTP communications, with hotfix on wine

- Further information could be found at [NppFTP](http://ashkulz.github.io/NppFTP/)

- Build HowTo [BUILDING.md](https://github.com/ashkulz/NppFTP/blob/master/BUILDING.md)

- [Added by stoictraveler] If NppFTP is used together with Notepad++ on wine, the plugin could freeze after 5 mins of inactivity due to ssh connection timeout. This fork fixes the issue by forcing to reconnect every time a QueueOperation is performed. It should work on macports wine-crossover and Ubuntu 16.04 with wine 3.9. 

Build Status
------------

[![Appveyor build status](https://ci.appveyor.com/api/projects/status/github/ashkulz/nppftp?branch=master&svg=true)](https://ci.appveyor.com/project/ashkulz/nppftp)
[![Travis build status](https://travis-ci.org/ashkulz/NppFTP.svg?branch=master)](https://travis-ci.org/ashkulz/NppFTP)
[![GitHub release](https://img.shields.io/github/release/ashkulz/NppFTP.svg)](https://github.com/ashkulz/NppFTP/releases)
