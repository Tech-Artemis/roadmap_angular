## **Dependencies**

### **Frontend**
- [Ionic 6+](https://ionicframework.com/)
- [Angular 14+](https://angular.io/)
- [leaflet 1.7+](https://leafletjs.com/)
- [chartjs 3.5+](https://www.chartjs.org/)

# **SETUP**

## **Frontend (Part)**

### **1.1 navigate to `frontend/` directory.**

```
#  navigate to frontend 
$ cd frontend
```

### **1.2 Fill the desired environment variables:**  
- navigate to `frontend/src/environments`
- set values to variables (ex. api.url) 
```
  api: {
    url: 'http://localhost:8000/', <-- server URL
    mapKey: '', <-- Leaflet map key,
    googleAuthClientId: '', <-- google Auth CLient ID for Social signin
    webSocketUrl: 'ws://localhost:8000/websocket' <-- websocket URL
  }
```

### **2. then install dependencies & run ionic serve**

In terminal - command
```
# install dependencies
$ npm install

# serve frontend
$ ionic serve
```

<br>

### **2. then install dependencies & run dev**

In terminal - command
```
#  navigate to backend-fastify 
$ cd backend-fastify

# install dependencies
$ npm install

# start server
$ npm start

```

### **2.1 Database seeder(optional)**
- Make sure `.env` is configured & dependencies are installed
- Will populate database with dummy data.

```
$ npm run db:seeder
```

dummy user:
```
  fullName: "test tester",
  email: "test@email.com",
  password: "password"

  You can use this to signin.
```
## Routes
```
/docs/
/users/
/auth/
/properties/
/enquiries/
```
