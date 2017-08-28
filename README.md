# Muse-Witness-Monitor
Monitor your missed blocks & public seednode availability for [the Muse Blockchain](https://github.com/themuseblockchain/Muse-Source) and get notifications on Telegram

This python3 script provides the monitoring of 2 core witness tasks and reports via a telegram bot API call the following:

**1. Monitor missing blocks**
Whenever a new block is missed you will get a notification. This part of the script can (and will) be extended towards automated switching to the backup witness signing key once a threshold is passed.

**2. Monitor the availability of your public seednode**
By utilizing the telnet library the script tries to connect to the given seednode and will report on time-out or errors.

## Dependencies
- [Steem-Python by @furion](https://github.com/steemit/steem-python) and the Telnet lib.
- A telegram bot token so you can receive notifications
- You need to have and set a https mused url before this script works (currently provided via blckchnd)

*If you have any remarks/feedback or questions, please let me know! If you find this script useful, feel free to support my witness activities by voting for me on Muse username: `roelandp`.*
