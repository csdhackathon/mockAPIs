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
Example mailerIds for Shipping API : 93-804-9376, 26-450-8961, 18-937-0363, 16-277-1231, 04-924-9982, 90-163-5830, 63-024-8608, 14-893-6235, 09-469-1042 

Example mailerIds for Address API : 58-583-2808, 35-958-4207, 58-587-7382, 95-106-6036, 92-058-9178, 12-911-1509, 01-146-0978, 05-576-6194, 32-153-5613, 40-843-4823, 45-034-7046, 74-168-4830 


# To Access API through cURL
```
> curl -H 'X-Api-Key: TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb' 'https://api-qa.fusion.pitneycloud.com/fusionapi/address?mailerId=95-106-6036'

> curl -H 'X-Api-Key: TAHb4BcUUe4IZX8D9dFOb8D4vjRXk1195QhfqNXb' 'https://api-qa.fusion.pitneycloud.com/fusionapi/shipping?mailerId=26-450-8961'
```
