# Robotic-Revenge-Automation

Ever hated someone so much that you imagined one day you will revenge by giving his/her phone number to every dealer in the U.S.? That's what this script does. 

<img src="https://github.com/Cosxin/Robotic-Revenge-Automation/tree/master/MB/example.gif" width="100" height="100" />

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
{
  "firstName": "Elon",
  "lastName": "Musk",
  "cellphone": "8885183752",
  "prefPhone": false,
  "customText": "I am an asshole which makes me a great boss",
  "email": "Press@tesla.com",
  "skipN": 0,
  "limitN": 3
}

### mburl.csv

This is the file that contains all the links to the local mb websites.  By setting *skipN* in Config.json, you skip the first N rows from this file. The *limitN* will stop the scripts after sending to N dealers.

### Other dealers

In development
