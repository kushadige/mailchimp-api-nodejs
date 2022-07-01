# Mailchimp API implementation with Node.js

It allows you to collect users email addresses and put them to Mailchimp Audience List that you specified. 

Used modules
* Express
* Body-Parser
* Request
* Https (Internal)

Styled with Bootstrap 5

---

## User Guide

1. Sign up https://mailchimp.com/

2. Get Audience ID from: Audience -> Settings -> Audience name and defaults -> Audience ID

3. Get API Key from: youradminpanel/account/ -> Extras -> API keys -> Create A Key

4. Put the values you get to the related fields in app.js:
```javascript
const LIST_ID = '<your_audience_id>'; 
const YOUR_API_KEY = '<your_api_key>';
```

## Images

