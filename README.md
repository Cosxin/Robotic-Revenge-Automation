﻿# Robotic-Revenge-Automation

This tool was originally used to spam back a spammer. Ethical use only.

<img src="https://github.com/Cosxin/Robotic-Revenge-Automation/tree/master/MB/example.gif" width="300" height="300" />

# Rules

### Socially Responsible Robot
Filling in random phone number/email address is strictly prohibited. To test, use an automated service numbers and no-reply email addresses.

### Equal Opportunity Robot
Always shuffle the mburl.csv before executing the scripts so that every dealer get a chance to be employed.
# Usage

1. Get UiPath
2. Modify Config.json
3. Click Run in UiPath

### Config.json
You know what to do:
```json
{
  "firstName": "",
  "lastName": "",
  "cellphone": "",
  "prefPhone": false,
  "customText": "",
  "email": "",
  "skipN": N,
  "limitN": N
}
```
### mburl.csv

This is the file that contains all the links to the local mb websites.  By setting *skipN* in Config.json, you skip the first N rows from this file. The *limitN* will stop the scripts after sending to N dealers.

### Other dealers

In development, Toyota next
