# DA.KOREAN 

### About project

"DA.KOREAN" is a website for learning Korean.

The app allows to:

- **sign in** or **sign up** on website;
- **buy** courses, calligraphy pages (test mode);
- **mailing** newsletters after subscribing in the form of a footer;
- **add**, **change**, **delete** courses and calligraphy pages from admin page;


Main page:

<img src="https://github.com/BentonFraizer/DA.KOREAN/blob/main/.github/workflows/main_page.png" width="769" />

Courses page: 

<img src="https://github.com/BentonFraizer/DA.KOREAN/blob/main/.github/workflows/courses_page.png" width="769" />

Callygraphy page: 

<img src="https://github.com/BentonFraizer/DA.KOREAN/blob/main/.github/workflows/calligraphy_page.png" width="769" />

### Stack 
- React 
- TypeScript
- React Router v.6
- Redux
- Redux Toolkit
- Express
- PostgreSQL
- Sequelise

### ⚙️ How To Run Locally

1. download and install PostgreSQL from [official website](https://www.postgresql.org/download/)

2. clone repo with:
```
git clone git@github.com:BentonFraizer/DA.KOREAN.git
```
3. go into the **client** folder with:
```
cd DA.KOREAN/client/
```
4. install all dependencies with:
```
npm install
```
5. run in the **dev** mode with:
```
npm start
```
6. go into the **server** folder with:
```
cd DA.KOREAN/server/
```
7. install all dependencies with:
```
npm install
```
8.1 copy file .env.example, rename to .env

8.2 change DATABASE_URL. For example:

from
```
DATABASE_URL = postgres://login:password@ip:port/bd_name
```
to
```
DATABASE_URL = postgres://postgres:postgres@localhost:5432/da_korean
```
9. create a database with:
```
npm run dbr
```
10. run in the **dev** mode with:
```
npm run dev
```
If you encounter an error you should change in "scripts" /client/package.json folder one row

from
``` 
  "start": "DISABLE_ESLINT_PLUGIN=true BROWSER=none react-scripts start",
```
to
``` 
  "start": "react-scripts start",
```


