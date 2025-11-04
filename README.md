### 1️⃣ Racine de l’API
```bash
curl -X GET 'http://localhost:8082/api'
```
<img width="1022" height="412" alt="Screenshot from 2025-11-04 20-22-22" src="https://github.com/user-attachments/assets/e32a800d-29af-4927-9b42-5f641183f9d1" />

### 2️⃣ Tous les comptes
```bash
curl -X GET 'http://localhost:8082/api/comptes'
<img width="1910" height="1080" alt="Screenshot from 2025-11-04 20-23-36" src="https://github.com/user-attachments/assets/d9a0b07e-6ff0-4ed7-b629-f2c9ff361d8b" />

```

### 3️⃣ Comptes de type EPARGNE
```bash
curl -X GET 'http://localhost:8082/api/comptes/search/byType?t=EPARGNE'
<img width="1910" height="1080" alt="Screenshot from 2025-11-04 20-24-25" src="https://github.com/user-attachments/assets/431a7e2b-5eb6-4a76-8d0c-525112c4bd81" />

```

### 4️⃣ Projection "solde"
```bash
curl -X GET 'http://localhost:8082/api/comptes?projection=solde'
<img width="1910" height="1080" alt="Screenshot from 2025-11-04 20-24-48" src="https://github.com/user-attachments/assets/e3eab82f-f946-491d-97cd-03e73d843534" />

```

### 5️⃣ Projection "mobile"
```bash
curl -X GET 'http://localhost:8082/api/comptes?projection=mobile'
<img width="1910" height="1080" alt="Screenshot from 2025-11-04 20-25-26" src="https://github.com/user-attachments/assets/163b91af-71ef-4aec-a0bd-00c2ab95535d" />

```
