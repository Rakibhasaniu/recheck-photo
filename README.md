Reasons of recheck:-

1.  Here I give some photo that shows my code working properly(from my point of view).

2.  there might be problem in req body structure I used. Firstly, I send data from postman in below structure where all data binded in "userData" object.

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

But I saw in your requirement document which said that req body structure must be like below where "userData" object is not necessary :

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

So , I design my application to receive data from postman without "userData" object . Format is shown in photos.

3. Joi validation is also done in above format.(without "userData")

My honourable examiner , please recheck my assignment considering the above reasons. If there still any confussion, fault and error , give your valuable feedback with specific reasons. Your feedback will help me to fullfil my assignment goal with 100% accuracy. I request you with honour , not to cut my marks. It's 48 out of 60 (80% , needed for backend path).

Plz, response me as soon as possible sothat I can accurate my application before 15th Dec.

I request you with honour , not to cut my marks .
