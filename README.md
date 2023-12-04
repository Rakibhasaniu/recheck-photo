Reasons of recheck:-

1.  Here I give some photo that shows my code working properly(from my point of view).

2.  there will be problem in req body structure. Firstly, I send data from postman in below format:

        {
            "userData":{
                "userId": "number",
                "username": "string",
                "password": "string",
                "fullName": {
                    "firstName": "string",
                    "lastName": "string"
                },
                "age": "number",
                "email": "string",
                "isActive": "boolean",
                "hobbies": [
                    "string",
                    "string"
                ],
                "address": {
                    "street": "string",
                    "city": "string",
                    "country": "string"
                }
            }
        }

But I saw in your requirement document that req body structure must be like below :

    {
        "userId": "number",
        "username": "string",
        "password": "string",
        "fullName": {
            "firstName": "string",
            "lastName": "string"
        },
        "age": "number",
        "email": "string",
        "isActive": "boolean",
        "hobbies": [
            "string",
            "string"
        ],
        "address": {
            "street": "string",
            "city": "string",
            "country": "string"
        }
    }

So , I design my application to receive data from postman without "userData" . Format is shown in photos.

3. Joi validation is also done in above format.(without "userData")

My honourable examiner , please recheck my assignment considering the above reasons. If there still any confussion, fault and error , give your valuable feedback with specific reasons. Your feedback will help me to fullfil my assignment goal with 100% accuracy.

Plz, response me as soon as possible sothat I can accurate my application before 15th Dec.
