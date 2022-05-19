Regex Pattern for Email Verification

```javascript
/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/
```

#### List of Valid Email Addresses

- email@example.com
- firstname.lastname@example.com
- email@subdomain.example.com
- firstname+lastname@example.com
- email@123.123.123.123
- email@[123.123.123.123]
- "email"@example.com
- 1234567890@example.com
- email@example-one.com
- _______@example.com
- email@example.name
- email@example.museum
- email@example.co.jp
- firstname-lastname@example.com


#### Example of invalid email id

- mysite.ourearth.com [@ is not present]
- mysite@.com.my [ tld (Top Level domain) can not start with dot "." ]
- @you.me.net [ No character before @ ]
- mysite123@gmail.b [ ".b" is not a valid tld ]
- mysite@.org.org [ tld can not start with dot "." ]
- .mysite@mysite.org [ an email should not be start with "." ]
- mysite()*@gmail.com [ here the regular expression only allows character, digit, underscore, and dash ]
- mysite..1234@yahoo.com [double dots are not allowed]


#### List of Strange Valid Email Addresses

- much.”more\ unusual”@example.com
- very.unusual.”@”.unusual.com@example.com
- very.”(),:;<>[]”.VERY.”very@\\ "very”.unusual@strange.example.com
- file_downloadDownload the validation code from here.

