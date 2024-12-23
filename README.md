# Introducing the Scam Pop-Up Blocklist
Simply copy and paste the URL https://raw.githubusercontent.com/cubodebasura/scam-popup-blocklist/master/list.txt into your Pi-hole adlist config.
An experimental hourly updated list is also available at https://cretin.org/hourly.txt

## What does this list block?
This list mainly aims to block scam pop-ups (think "Windows virus! Call this toll-free number!").
It also blocks a few ConnectWise (ScreenConnect) servers that have been identified as belonging to scammers.

## How reliable is it?
The automated means some domains are added to here before the scammers even have a chance to deploy them.
It does appear to block more US-aimed Microsoft scams, but some others have been found too.
A solution is being worked on to find pop-ups targeting other countries, such as Australia, Ireland, UK, and New Zealand.
