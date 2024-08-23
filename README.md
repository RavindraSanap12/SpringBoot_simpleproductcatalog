## Run the Spring Boot Application

### 1. Run as a Spring Boot App

- **Step 1**: Right-click the main application class, usually named `ProductCatalogApplication.java` (the one annotated with `@SpringBootApplication`).
- **Step 2**: Select `Run As` > `Spring Boot App`.
- **Step 3**: Check the Console:
  - In the Eclipse console, you should see logs indicating that the application has started successfully, like:
    ```
    Started ProductCatalogApplication in X seconds
    ```

### 2. Access the API Endpoints

#### Add a Product
- **Method**: `POST`
- **URL**: `http://localhost:8085/api/add`
- **Body**: JSON

#### Update a Product
- **Method**: `PUT`
- **URL**: `http://localhost:8085/api/update/{id}`
- Replace `{id}` with the product ID you want to update.

#### Get All Products
- **Method**: `GET`
- **URL**: `http://localhost:8085/api/getall`
