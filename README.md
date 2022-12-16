# ExpressJS REST API with MongoDB using SOLID Design Principles

API Endpoints

| Methods | Urls                | Description             |
| ------- | ------------------- | ----------------------- |
| POST    | /api/v1/user/login  | User Login              |
| POST    | /api/v1/user/signup | User SignUp             |
| POST    | /api/v1/product/    | Create a New Product    |
| GET     | /api/v1/product/    | Get All Products        |
| GET     | /api/v1/product/:id | Get Product By ID       |
| PUT     | /api/v1/product/:id | Update Product Using ID |
| DELETE  | /api/v1/product/:id | Delete Product Using ID |

## Quick Start

Clone the repo.

```bash
git clone https://github.com/pisothyi/expressjs-rest-api-mongodb.git
cd expressjs-rest-api-mongodb
```

Create the .env file.

```bash
PORT=3002
DB_URL="mongodb://localhost/apiDb"
SECRET_KEY="SECRETKEY"
```

Install the dependencies.

```bash
npm install
```

To start the express server, run the following.

```bash
npm run dev
```
