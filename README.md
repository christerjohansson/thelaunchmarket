# The Launch Market
A small design and develop agency for Solopreneur businesses and Freelances. Bootcamp grads need experience an small start-ups need to get things done.

## Getting Started: Web Application Developement Environment
### Run application without Docker
Clone repo:
```bash
git clone git@github.com:melissakipp/thelaunchmarket.git
```
Install Dependencies
```bash
npm install
```

First, run the development server:

```bash
npm run dev 
```

### Docker Container
```bash
rm -rf .next node_modules  
rm package-lock.json
```
Next run the NPM command:
```bash
npm install
```
DO NOT RUN THE DEV SERVER - Run for the first time
```bash
docker compose up --build
```
After this you will use the following commands to manage the development environment:
<br />
**To start the container**
```bash
docker compose up
```
OR using -d flag will run the container in the background (no output)
```bash
docker compose up -d
```

### Go to your browser
```http://localhost:3000/```


### Goals
- [X]  Docker for development and deployment
- [ ]  Create a Docker Deploy/Production container