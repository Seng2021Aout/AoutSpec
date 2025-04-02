# Integrated Digital Trade

## Project Info
Team: Aout F18A<br/>
This is a guide for using our API through swagger [https://app.swaggerhub.com/apis-docs/JustinLi-357/Aout/1.0.0#/user%20end/getHealth](https://app.swaggerhub.com/apis-docs/JustinLi-357/Aout/1.0.0#/)

## API overview
We had 2 active management route

### Authentication and User Management
All the APIs is working in this route but we do not require auth to use our Despatch Advice Management as we dont have a active front end yet

```
POST /api/create-organisation
POST /api/signup
POST /api/login
POST /api/logout
```
### Despatch Advice Management
```
POST /api/despatch-advice
GET /api/despatch-advice-all
GET /api/despatch-advice-ids
GET /api/despatch-advice-info/{despatch_id}
PATCH /api/despatch-advice-save/{despatch_id}
DELETE /api/despatch-advice-delete/{despatch_id}
```

### System Status
```
GET /health
```

## Guide for testing
We strongly recommend testing from this order<br/>
System Status --> Despatch Advice Management --> Authentication and User Management(Optional)<br/>
<br/>
All the request body example is prefilled in Swagger doc you feel free to change it<br/>
<br/>
Feel free to message me in Discord(m1ple) if you have any question

