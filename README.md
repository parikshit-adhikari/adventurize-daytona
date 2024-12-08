# Sample Javascript/Reactjs/Nodejs

Adventurize is a web-app that allows users to search for different locations to visit.

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  

2. **Create the Workspace**:  
   ```bash  
   daytona create https://github.com/parikshit-adhikari/adventurize.git 
   ```  

3. **Start the Application**:  

###### Prerequisites

Before running adventurize, you will need an OpenAI API key from Gemini Services and Weather API from OpenWeatherMap. You can obtain an API key by registering on the their respective platform.

###### Setup
1. Navigate to backend side by:

   ```bash
   cd backend
   ``` 

2. Navigate to frontend side by:

   ```bash
   cd frontend
   ``` 

3. Setting up .env file for API Keys 

- Create a .env file inside backend directory

  ```bash
  # inside .env file
  API_KEY=******************************* # Your key
  WEATHTER_API=******************************* # Your key from open weather map
  ```
###### Usage

Run the application by executing both frontend and backend side code:

For backend side:

```bash
node app.js 
```

For backend side:

```bash
npm run dev
```

## ✨ Features  
- Get weather information
- Toggle between light and dark Theme
- Engaging descriptions regarding locations to visit
- Browse locations by category

## Dependencies

- Flagsmith
- Gemini API
- Open Weather Map  
- cors
- Other dependencies listed in `package.json` (Check out for both frontend and backend side!)

