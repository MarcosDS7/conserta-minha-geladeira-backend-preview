![.NET 8](https://img.shields.io/badge/.NET-8.0-blueviolet?logo=dotnet&logoColor=white)
![Entity Framework Core](https://img.shields.io/badge/Entity%20Framework%20Core-6.0-green?logo=nuget&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange?logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-API%20Docs-brightgreen?logo=swagger&logoColor=white)
![SQL Server](https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-Payments-blue?logo=stripe&logoColor=white)



# SaaS - Conserta Minha Geladeira

A SaaS platform developed to connect **customers** who need refrigerator repair with **specialized technicians** quickly, securely, and via geolocation.

##

The objective of this project is to **create an intelligent service intermediation system,** where:

-  **Technicians** can register for free, and pay for **highlighted** plans to appear in the top positions. 
-  **Customers** can request services for free and pay to **prioritize their requests** in the listing.
-   The system automatically connects customers and technicians **based on geographic proximity** (postal code / coordinates).

<sub>The SaaS was designed to be scalable, with a modular architecture and continuous integration between the front-end, back-end, and database.</sub>

##

#### Planning  

```
1. Planning and Concept
   ├── Market research
   ├── Definition of the real problem
   ├── Personas
   │     ├── Customer persona
   │     └── Technician persona
   ├── User journey analysis
   └── Requirements
         ├── Functional requirements
         └── Non-functional requirements
```

##

![Idea](https://img.shields.io/badge/idea-%F0%9F%92%A1-yellow?style=flat-square)

<img width="1002" height="482" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516475427-19583063-9c5d-4244-933f-da6a06874966.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0NzU0MjctMTk1ODMwNjMtOWM1ZC00MjQ0LTkzM2YtZGE2YTA2ODc0OTY2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWRlNTkwNWU1MGU4OWU1N2RjMzM1MDNjZjliYWQ1OGUyOTk0ZTVmNThjMzNmMzBhZmIyNWIyOGIyMWZjNjBkNzgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.pDKHZJPATrHb92idTFNSA030vXWZHJjm5d7x2a6UDG4" />

##

![Requirements](https://img.shields.io/badge/Requirements-%E2%9A%94%EF%B8%8F-blue?style=flat-square)

<img width="1002" height="792" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516476759-6ebbf3e6-683a-4a7a-b5ec-0feb08cf7b97.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0NzY3NTktNmViYmYzZTYtNjgzYS00YTdhLWI1ZWMtMGZlYjA4Y2Y3Yjk3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg0NzU4MzgwY2VjN2U0ZmM3MDAwZGJiNDg5MzA3ZWJmNjNhY2JiOTZmODFhYmMxNDc5YzViYjk5ZTY1MjVmMGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.U1E6FhEG1Y5MDqBUjZXrfVZ4OBGIOSWcf9I9pBkB7N8" />

##

![Flow](https://img.shields.io/badge/Flow-%E2%9C%94%EF%B8%8F-green?style=flat-square)

<img width="996" height="849" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516483992-ae725630-9085-4752-bf37-13dbec496fe4.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0ODM5OTItYWU3MjU2MzAtOTA4NS00NzUyLWJmMzctMTNkYmVjNDk2ZmU0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdmZWQyMTcwMzNmYjVjNjA0N2M5ZjI3ODE5OGU2ZjA5YjZhZWYzNDQwZTQ0MDU5NmE5NDM4OWQ3ZWQ1NmRlY2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.0ClGIo5UAtYMg_boKYIvzsoJDlsI5NfmDHuIMWK9Zys" />

## 

![UML Class Diagram](https://img.shields.io/badge/UML_Class_Diagram-%F0%9F%93%A6-blueviolet?style=flat-square)

<img width="818" height="901" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516484518-6b54aaf5-eac0-4211-99b8-4e417f44724c.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0ODQ1MTgtNmI1NGFhZjUtZWFjMC00MjExLTk5YjgtNGU0MTdmNDQ3MjRjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTk5NGU0NWQ3YzQ3MGI3MDcwYWRlMmY0ZmZkNzM4ZWNjNDNhM2U1MGZlZTNiMGU1NGFjZWU1NTEzNTY1ZDc5OWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.u-M4aD-SDOPn4SvULS6gSL6fznTPVwuquwwFqGNN47E" />

##

![UI Design](https://img.shields.io/badge/UI_Design-%F0%9F%8E%A8-pink?style=flat-square)

<img width="673" height="861" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516485302-50b72a97-f3ba-4e58-9e61-e9aef7e80104.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0ODUzMDItNTBiNzJhOTctZjNiYS00ZTU4LTllNjEtZTlhZWY3ZTgwMTA0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgyYWE3ZmVmODk2YzRmMTcxNTExYzg3NGZkOWY1MjdkOGQ4MTk1YmRmNTBjOGViZDZkZDgzYjFmZmI2ZjNlN2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.wXvALVnKLEnS8nAfoJrgoJCq3UKEyF-qJYIa4-Jazac" />

##

![Swagger](https://img.shields.io/badge/Swagger-%F0%9F%8C%90-blue?style=flat-square)

<img width="2920" height="3924" alt="image" src="https://private-user-images.githubusercontent.com/61913052/516487206-82918467-85c7-4d1b-908c-f1d463df15b0.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NjM1ODUwODgsIm5iZiI6MTc2MzU4NDc4OCwicGF0aCI6Ii82MTkxMzA1Mi81MTY0ODcyMDYtODI5MTg0NjctODVjNy00ZDFiLTkwOGMtZjFkNDYzZGYxNWIwLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTExMTklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUxMTE5VDIwMzk0OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTA3N2FiMGFjNzBjNzQ1NDYwZDM3YzY1MDkyYWM5MjIyOTljMWVmMTJjOTE5M2FiMzlhZDdjY2Q4NGI3YTkwZTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.CfHutN-7vwGqQyvsF54U6dLSd8cvSM6Y3F8NdraOWck" />

##

![Folder Architecture](https://img.shields.io/badge/Folder_Architecture-%F0%9F%93%81-blue?style=flat-square)

```
├── Controllers
├── Data
├── Dtos
│   ├── Auth
│   ├── Common
│   ├── Payments
│   ├── Ratings
│   └── Services
├── Extensions
├── Helpers
│   └── Common
│       └── Query
├── Interfaces
├── Migrations
├── Models
├── obj
├── Properties
├── Repository
├── Services
```

##

VERSION
 _1.1.1_
##

Contributors

[![Marcos Souza](https://img.shields.io/badge/Marcos_Souza-Author-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/marcos-souza-front-end-ui-ux-design/)
