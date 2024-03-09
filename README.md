# wec-nitk-website-backend
The backend for hosting the CMS for the Web Club Website.


#### node js :v20.11
#### postgres:14.0(recommended)

---
### Here is the database schema for the website

https://dbdiagram.io/d/Web-Club-Website-Schema-65b7eacbac844320aef8b83b

![Web Club Website Schema](https://github.com/WebClub-NITK/wec-nitk-website-backend/assets/90238207/32a96487-5e08-4bdd-a6df-e1c4be13c872)


### Local Setup using docker

1. Clone the repository
2. Make the postgres container using the following command
```bash
docker start --name wec-postgres -p 5432:5432 -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -d postgres:14-bookworm
```
3. Run the server using `npm run develop`