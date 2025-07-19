# Full API Flow: Create → Get → Delete (GoRest)

---

## 1. Create User (POST)
- URL: https://gorest.co.in/public/v2/users
- Tests: 
- Pre‑request Script

```javascript

 pm.test("Status 201", () => pm.response.to.have.status(201));
```
- Screenshot: ![POST.png] (https://github.com/Arhuba/QA-Project/blob/main/docs/img/postman-post-runner.png)

---

## 2. Get User (GET)
- URL: https://gorest.co.in/public/v2/users
- Tests: 
- Pre‑request Script

```javascript

 pm.test("Status 200", () => pm.response.to.have.status(200));
```
- Screenshot: ![GET.png] (https://github.com/Arhuba/QA-Project/blob/main/docs/img/postman-get-runner.png)

---

## 3. Delete User (DELETE)
- URL: https://gorest.co.in/public/v2/users
- Tests: 
- Pre‑request Script

```javascript

 pm.test("Status 204", () => pm.response.to.have.status(204));
```
- Screenshot: ![DELETE.png] (https://github.com/Arhuba/QA-Project/blob/main/docs/img/postman-gorest-full-flow.png)


