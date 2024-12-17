# Finance Management

1. **Add daily expenses**
2. **Set a monthly budget limit**
3. **View expenses for a specific date**
4. **View overall monthly expenses**
5. **View overall yearly expenses**

- **Backend (REST API):** Spring Boot 2.1.4
  - Spring Boot Web
  - Spring Data
  - Spring DevTools
  - Swagger for API documentation
- **Database:** MongoDB
- **Frontend (UI):** Angular 7

### Backend Setup (Spring Boot API)

1. Clone the repository.
2. Open a terminal in the `Expense-Manager-API` directory.
3. Run `mvn clean install` to build the project.
4. Navigate to the `target` directory.
5. Deploy the API with the command:  
   `java -jar Expense-Manager-API-0.0.1-SNAPSHOT.jar`
6. Access the API documentation at:  
   http://localhost:8089/ExpenseManager/swagger-ui.html

### Frontend Setup (Angular UI)

1. Open a terminal in the `Expense-Manager-UI` directory.
2. Run `npm install` to install dependencies.
3. Start the UI with:  
   `npm start`
4. Open the application at:  
   http://localhost:4200/ExpenseManager/
