# HotelManager

HotelManager is an application which objective is to allow Hotel owners to have control over their bookings aswell as have control over their employees. Live version here: [HotelManager](https://hotel-manager-app.netlify.app)

Links to repositories:
 [Frontend](https://github.com/RicardoCastelbon/u09-frontend-HotelManager)<br />
 [Backend](https://github.com/RicardoCastelbon/u09-backend-HotelManager)

## Table of Contents

* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Page and Routes](#[page-and-routes])
* [Features](#features)
* [Test](#test)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)

## General Information
The app porpuse is to be able to manage booking and personal of your business.


## Technologies Used
- React.js - version 18
- Node.js - version 16
- Express - version 4
- MongoDB - version 5
- Mongoose - version 6
- TypeScript - version 4


## Setup

1. Start by cloning the repository.
2. Install the dependencies in both frontend and backend folders:

```
npm install
```

3. Create a .env file in the frontend folder root with the following:

```
REACT_APP_API_URL = http://localhost:5000
```

4. Create a .env file in the backend folder root with the following:

```
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = Thecodeforjwt
JWT_LIFETIME = 1d
REQUEST_URL = http://localhost:3000
```

5. Start the react and node server with:

```
npm start
```

6. React runs at: http://localhost:3000/. Node runs at http://localhost:5000


## Page and Routes

| Page                                                                                                             | Items                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| /landing <br /> /bookings <br /> /add-booking <br /> /settings                                                                | <br /> <br /> Start page                                                                                                                               |
| /login POST <br /> /register POST <br /> /bookings GET POST PATCH DELETE <br /> /employees GET POST PATCH DELETE | login user <br /> register user <br /> CRUD bookings <br /> CRUD EMPLOYEES |

## Features

- Register and Login User

- Create, see, update and delete your Bookings

- As an admin create, see, update and delete employees

## Documentation

- Link to SiteMap

- Link to google document

- [Prototyping in Figma](https://www.figma.com/file/dOlEtZQwfJ3tQEaqL7Muzz/HotelManager?node-id=0%3A1)


## Contact

Created by:

[@RicardoCastelbon](https://github.com/RicardoCastelbon)


## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.

Feel free to contact!
