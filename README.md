## Product에 대한 CRUD 메소드를 제공하는 REST API 구현

  - #### **프로젝트 구조**
    <img src = "https://user-images.githubusercontent.com/56067179/85832115-70aec480-b7ca-11ea-8eaa-c4edc64c0d82.png" width="15%"><br/>

  - #### **Database - data.sql를 이용하여 미리 10개의 Product 생성**<br/>
      <img src = "https://user-images.githubusercontent.com/56067179/85833174-452cd980-b7cc-11ea-86e3-71457605a562.png" width="40%"><br/>

  - #### **Postman - API 요청/응답 메시지**
    - **Create/Add (POST)**
      - **POST** http://localhost:9090/api/v1/products
      <img src = "https://user-images.githubusercontent.com/56067179/85832113-70162e00-b7ca-11ea-8964-d27220c4b265.png" width="80%"><br/>

    - **Retrieve/Get (GET)**
      - **GET** http://localhost:9090/api/v1/products
      <img src = "https://user-images.githubusercontent.com/56067179/85832109-6ee50100-b7ca-11ea-9c75-b222404e90a4.png" width="80%"><br/>

      - **GET** http://localhost:9090/api/v1/products/{id}
      <img src = "https://user-images.githubusercontent.com/56067179/85832112-6f7d9780-b7ca-11ea-9b2d-8fe6208d9046.png" width="80%"><br/>

      - **GET** http://localhost:9090/api/v1/products/category/{category}
      <img src = "https://user-images.githubusercontent.com/56067179/85832111-6f7d9780-b7ca-11ea-8a30-64a3639eb1a5.png" width="80%"><br/>

    - **Update (PUT)**
      - **PUT** http://localhost:9090/api/v1/products/{id}
      <img src = "https://user-images.githubusercontent.com/56067179/85832116-70aec480-b7ca-11ea-967d-706fea482588.png" width="80%"><br/>

    - **Delete (DELETE)**
      - **DELETE** http://localhost:9090/api/v1/products/{id}
      <img src = "https://user-images.githubusercontent.com/56067179/85832107-6ee50100-b7ca-11ea-9a72-f3ecf6951b10.png" width="80%"><br/>

      - **After Delete**<br/>
      <img src = "https://user-images.githubusercontent.com/56067179/85832105-6e4c6a80-b7ca-11ea-95da-3a957535c699.png" width="80%"><br/>

  - #### **Actuator**
    - **mappings - Product REST API의 URL Mapping 정보**
      - http://localhost:9090/actuator/mappings
      <img src = "https://user-images.githubusercontent.com/56067179/85832100-6d1b3d80-b7ca-11ea-8e62-5f2d7540eb40.png" width="80%"><br/>
