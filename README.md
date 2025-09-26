2. cookie_session_auth source code
   
a. node app.js

b. register

Mở Postman chọn phương thức POST và nhập url: http://localhost:3000/auth/register

Chọn Body -> raw(Json)

Nhập {"username": "admin", "password": "12345"} và chọn Send

Kết quả : "User registered successfully!"

<img width="1501" height="882" alt="image" src="https://github.com/user-attachments/assets/2840c00c-09a8-4865-829c-361fdcc3cc3a" />

Check in database
<img width="1766" height="1000" alt="image" src="https://github.com/user-attachments/assets/792c7013-0629-4bc9-a628-53184a97f8d4" />

<img width="1765" height="875" alt="image" src="https://github.com/user-attachments/assets/2d6d6803-8ed5-46c4-9a96-076caedd027c" />

c. login
Mở Postman chọn phương thức POST và nhập url: http://localhost:3000/auth/login
<img width="1817" height="885" alt="image" src="https://github.com/user-attachments/assets/daffac1e-3736-4c7b-95c0-c4576f76aa61" />

Check in database
<img width="1782" height="871" alt="image" src="https://github.com/user-attachments/assets/821794cf-e1ac-4a32-b799-3a0c04060da6" />

d. go to profile
<img width="1351" height="913" alt="image" src="https://github.com/user-attachments/assets/b077bd46-69e1-44e3-8a1c-48303b43e0d2" />

e. go to logout and check cookie is deleted in database
<img width="1297" height="928" alt="image" src="https://github.com/user-attachments/assets/96ee71ac-25e1-486b-a234-366c1f488d44" />

Check in database
<img width="1778" height="852" alt="image" src="https://github.com/user-attachments/assets/30176671-f499-4b08-b533-af1c0b0c55b0" />


