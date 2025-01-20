# Shopping Site  

Welcome to the Shopping Site project! Follow the steps below to set up and run the application locally.  

## Prerequisites  

- **Node.js** (Ensure Node.js is installed on your machine. [Download Node.js](https://nodejs.org))  
- **Angular CLI** (Install globally if not already installed):  
  ```bash  
  npm install -g @angular/cli  
  ```  

## Setup Instructions  

### 1. Clone the Repository  
Clone the project to your local machine and navigate to the project directory:  
```bash  
git clone <repository-url>  
cd <project-directory>  
```  

### 2. Install Dependencies  
Run the following command to install all required dependencies:  
```bash  
npm install  
```  

### 3. Additional Setup  

#### Install `node-sass`  
If `node-sass` is not already installed, run:  
```bash  
npm install node-sass  
```  

#### Resolve `@angular-devkit/build-angular` Issue  
If you encounter an issue with the Angular Devkit builder, install the required package:  
```bash  
npm install @angular-devkit/build-angular  
```  

#### Resolve `AngularGettingStarted` Issues  
If you face any issues with Angular dependencies, run:  
```bash  
npm install  
```  

### 4. Setting Up the Mock Server  
To set up and run the mock server:  
1. Navigate to the `mock-server` folder:  
   ```bash  
   cd mock-server  
   ```  
2. Install dependencies:  
   ```bash  
   npm install  
   ```  
3. Start the server:  
   ```bash  
   npm start  
   ```  

## Running the Application  

### Development Server  
1. Run the Angular development server:  
   ```bash  
   ng serve  
   ```  
2. Open your browser and navigate to:  
   ```
   http://localhost:4200/  
   ```  
   The app will automatically reload whenever you make changes to the source files.  

## Troubleshooting  
- If you encounter any errors, ensure all dependencies are installed by running:  
  ```bash  
  npm install  
  ```  
