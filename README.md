# Mock-APIs

API(s) for getting address details and shipping details based on "mailerId" information.

## API URL

To access API

API Key to access API TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb

Put API key in header of request 

x-api-key : TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb

API endpoints
```
1.	https://api-qa.fusion.pitneycloud.com/fusionapi/shipping?mailerId={mailerId}

2.	https://api-qa.fusion.pitneycloud.com/fusionapi/address?mailerId={mailerId}
```
Example mailerIds for Shipping API : 85-868-1890, 31-969-9006, 88-484-2330, 21-507-7999, 89-953-6868, 52-214-3082, 16-247-2082, 86-839-2237, 93-197-5804, 41-299-2781, 04-562-5086, 16-924-5593, 74-061-2851, 

Example mailerIds for Address API : 96-076-3745, 84-598-1145, 47-250-3103, 36-905-8491, 53-854-4576, 88-542-6739, 05-675-7334, 95-205-6436, 43-448-6575, 78-695-7277, 47-948-3359, 51-382-9103, 56-641-7295, 58-654-3955, 


# To Access API through cURL
```
> curl -H 'X-Api-Key: TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb' 'https://api-qa.fusion.pitneycloud.com/fusionapi/address?mailerId=84-598-1145'

> curl -H 'X-Api-Key: TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb' 'https://api-qa.fusion.pitneycloud.com/fusionapi/shipping?mailerId=85-868-1890'
```
