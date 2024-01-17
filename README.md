# NdExTs Node Express Typescript

## Steps 

### Step 1: Initialize Project

- Open your terminal
- Clone the repo `git clone https://github.com/avinashadluri/NdExTs.git`
- Navigate by using `cd NdExTs` into the folder directory
- Install project dependencies by running `npm install`

### Step 2: Set Up Environment Variables

- Copy the .env.template file to a new file named .env
- You can use the following command: `cp .env.template .env`
- Ensure that the .env file contains the required environment variables as defined in .env.template

### Step 3: Available Scripts

Below are Scripts that can be ran and found in package.json file

- Development Mode: `npm run dev`
- Build Project: `npm run build`
- Production Mode: `npm run start` or `npm run docker:start`

## Source Folder Structure

```
.
├── common
│   ├── middleware
│   │   ├── compressFilter.ts
│   │   ├── errorHandler.ts
│   │   ├── index.ts
│   │   ├── rateLimiter.ts
│   │   └── requestLogger.ts
│   ├── models
│   │   └── serviceResponse.ts
│   └── utils
│       ├── compressFilter.ts
│       ├── envConfig.ts
│       └── responseHandler.ts
├── index.ts
├── modules
│   ├── healthCheck
│   │   ├── healthCheckController.ts
│   │   ├── healthCheckRoutes.ts
│   │   └── tests
│   │       └── healthCheckRoutes.test.ts
│   └── user
│       ├── tests
│       │   └── userRoutes.test.ts
│       ├── userController.ts
│       ├── userModel.ts
│       ├── userRepository.ts
│       ├── userRoutes.ts
│       └── userService.ts
└── server.ts

10 directories, 19 files
```
