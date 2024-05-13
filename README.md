# Adding Detox to App

1. Install Docker CLI global not mandatory

   ```bash
   npm install detox-cli --global
   ```

2. Install Jest to app and install types if needed

   ```bash
   npm install jest --save-dev
   ```

   types

   ```bash
   npm install @types/jest --save-dev
   ```

3. Install Detox to dev dependencies of project

   ```bash
   npm install detox --save-dev
   ```

   After installation use following command to generate config files and sample test cases.

   ```bash
   detox init
   ```

   This will generate following files in app workspace.

   ```bash
   Created a file at path: .detoxrc.js
   Created a file at path: e2e/jest.config.js
   Created a file at path: e2e/starter.test.js
   ```

   - .detoxrc.js – Detox config file;
   - e2e/jest.config.js – Jest configuration;
   - e2e/starter.test.js – dummy first test.

[official project setup documentation](https://wix.github.io/Detox/docs/introduction/project-setup)
