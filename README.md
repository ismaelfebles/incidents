Node.js v.9.5.0


1) Clone the git repository

2) Within the "incidents" folder, execute the command "docker-compose build"

3) When finished, run the command "docker-compose up"

4) In your browser, navigate to "localhost:8000/incidents" to see it working!


PS: to run the tests, go to the ./incidents/dev/ folder and execute "npm test" or "npm run test-linux" (only for a linux environment)

PSS: Errors ocurred when compiling TS code are due to an issue regarding the use of the command "ts-node". TypeScript needs the packages @types/core-js@0.9.36 and @types/bluebird installed in order to execute the aforementioned command to run the source files (*.ts). These errors can be ignored since they do not affect the resulting files.