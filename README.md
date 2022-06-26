## API Testing Report
[![Netlify Status](https://api.netlify.com/api/v1/badges/ea4f8bbe-844f-4c6a-958a-6067316d9dfc/deploy-status)](https://app.netlify.com/sites/mahmud-restfulbooker/deploys)
#### [Booking](https://mahmud-restfulbooker.netlify.app/)
## Method
- POST
- GET
- PUT
- DELETE

## Command

1. **Newman Install:**

   - npm install -g newman

2. **Reporter Install:**

   - npm install -g newman-reporter-html
   - npm install -g newman-reporter-htmlextra

3. **Report Generate:**
   - newman run "..\CollectionName.json" -e "..\EnvironmentName.json" -r cli,html
   - newman run "..\CollectionName.json" -e "..\EnvironmentName.json" -r cli,htmlextra
