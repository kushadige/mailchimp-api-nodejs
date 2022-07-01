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

![home](https://user-images.githubusercontent.com/101992799/176957560-607561c8-cca2-4579-98b8-d9f887502b09.png)
![success](https://user-images.githubusercontent.com/101992799/176957568-698f5504-a110-4cf6-904e-2d472d3ed762.png)
![failure](https://user-images.githubusercontent.com/101992799/176964443-215d9324-ebc9-4b7e-bac0-27f80a89851b.png)
![contacts](https://user-images.githubusercontent.com/101992799/176957584-b42ce7e4-864f-424b-ac26-330881022fd6.png)
