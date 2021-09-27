# OpenWeather

## SETUP AND RUN GUIDELINE

### APPROACH
 - Following test cases, verify APIs for getting city and weather Verify
 - UI and UX of home page, search city page and display full weather   
   page

### TOOLS

 - Framework: Cypress
 - Report: Mochawesome
 - CI/CD: CircleCI
 - Design Pattern: Page Object Model
 - Repository:
   [https://github.com/lightsaberdtl/OpenWeather.git](https://github.com/lightsaberdtl/OpenWeather.git)

### SETUP AND RUN

### Local
 - Install Node.js and NPM
 - Clone this repository
 - Open terminal and go to your project path
 - Install Cypress
 - To run in Chrome: npm run test:chrome
 - To run in Firefox: npm run test:firefox
 - View report: Report is stored in OpenWeather\cypress\reports\mochareports

![image](https://user-images.githubusercontent.com/6335598/134640902-69e2da47-e4e1-4b39-a75b-6dbca30bf95b.png)

### CircleCI
 - Login CircleCI dashboard using your GitHub account: [https://app.circleci.com/](https://app.circleci.com/)
 - Check Organization Settings, make sure this setting is allowed
![image](https://user-images.githubusercontent.com/6335598/134641526-71d4d2ed-b017-4f3e-89ea-0a3427dd46a0.png)
 - Setup your clone project, choose config.yml from OpenWeather\.circleci
 - Or you can view mine at: [https://app.circleci.com/pipelines/github/lightsaberdtl/OpenWeather](https://app.circleci.com/pipelines/github/lightsaberdtl/OpenWeather)
 - Result:
![image](https://user-images.githubusercontent.com/6335598/134642860-cd93ec9c-7311-4c5b-8deb-4caecf83047d.png)

### TROUBLESHOOTING
 - If running in windows, sometimes the run will fail with this error: "The dictionary is not empty". **Solution:** Close your window explorer and run again

### ROOM FOR IMPROVEMENTS
 - Use tv4 to validate JSON schema
 - Use Eslint prettier to make code more structure and beatiful