# API Skill Assessment

Thank you for the opportunity to showcase my API development skills. Please reach out if you have any questions or have any trouble setting up the project. I've tried to be as thorough as possible, but I could certainly have missed something.

The SQL Test is also included in this project: [**SQL Test**](https://github.com/JonathanCrider/api-skill-assessment/blob/main/docs/SQLtest.md)

## Project setup

### Development Environment

To set up the development environment, you'll need to install the following tools:

1. **Node.js**  
   Node.js is a JavaScript runtime that allows you to execute JavaScript code server-side. You'll need it to run the server for this project.  
   - [Download and Install Node.js](https://nodejs.org/)  
   - [Node.js Documentation](https://nodejs.org/en/docs/)  

2. **NPM (Node Package Manager)**  
   NPM comes bundled with Node.js and is used to manage dependencies for your project. To verify if NPM is installed, run:  

   ```bash
   npm --version
   ```  

   - [NPM Documentation](https://docs.npmjs.com/)  

3. **SQLite**  
   SQLite is a lightweight, serverless database engine used in this project.
   - [Download SQLite](https://www.sqlite.org/download.html)  
   - [SQLite Documentation](https://www.sqlite.org/docs.html)  

### Download and run the project

```bash
git clone https://github.com/JonathanCrider/api-skill-assessment.git
cd api-skill-assessment
```

Be sure to create a `.env` file and include the following variables:

```bash
touch .env
```

```env
PORT=3001
OPENWEATHER_API_KEY=
STRIPE_SECRET_API_KEY=
X_API_KEY=
```

Install the dependencies and start the server locally:

```bash
npm i
npm run start:dev
```

## API Documentation

Once the server is running, you can open your browser to see the docs at the following URL (if your `.env` port is set to 3001):

[http://localhost:3001/docs](http://localhost:3001/docs)

They are also published at [https://jonathancrider.com/api-docs.html](https://jonathancrider.com/api-docs.html)

## API Package

Download the JSON and import into [Insomnia](https://insomnia.rest/):

[Insomnia JSON](https://github.com/JonathanCrider/api-skill-assessment/blob/main/docs/Insomnia-api-skill-assessment.json)
