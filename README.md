# React-Django Recipe App

https://intense-forest-38655-411c6c58cdb1.herokuapp.com/recipes

<img width="1091" alt="Screen Shot 2024-07-22 at 1 48 49 PM" src="https://github.com/user-attachments/assets/94b0b151-aad6-4202-b7ae-8de41d106917">

<img width="1109" alt="Screen Shot 2024-07-22 at 1 48 59 PM" src="https://github.com/user-attachments/assets/f844b20b-7470-4326-8996-f3ac2b90ce95">

## Architecture Overview


Components: React components are the lego blocks that represent the UI and handle user interactions application. State in this application is managed within created components.
Routing: React Router handles the navigation and conditional rendering between different views or pages in the application.
Service: Axios calls to Django backend handled by RecipeService file.


### Deployment and Hosting
Frontend Deployment: The finished React app is built into a static “dist” file using the Vite framework build tool. This “dist” file can be deployed purely as a frontend through static hosting service. For this project, an AWS s3 bucket deployment demonstrates this purely frontend dynamic. 
