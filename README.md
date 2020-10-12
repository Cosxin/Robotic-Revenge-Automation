# Robotic-Spammer-Automation

Send a phone number and an email address to every dealer in the U.S. This tool was originally used to spam a spammer. Ethical use only.

# Rules

### Socially Responsible Robot
Do not use random numbers!!! To test, use an automated service numbers and no-reply email addresses.

### Equal Opportunity Robot
Always shuffle the mburl.csv before executing the scripts so that every dealer get a chance to be employed.



### Config.json

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

In development
