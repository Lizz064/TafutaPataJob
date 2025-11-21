# React Login and Registration example with JWT and HttpOnly cookie

**Author:** Elizabeth Mijide
Deployment
tafuta-pata-p96a7tjpz-lizz064s-projects.vercel.app


**Email:** [elizabeth.mijide@example.com](mailto:elizabeth.mijide@example.com)

> *Replace the email above with your real email before publishing.*

---

Build React JWT Authentication and Authorization example using React Hooks, React Router, Axios and Bootstrap (without Redux):

* JWT Authentication Flow for User Signup & User Login
* Project Structure for React Authentication (without Redux) with React Router & Axios
* Creating React Components with Form Validation using Formik and Yup
* React Pages for accessing protected Resources (Authorization)
* Dynamic Navigation Bar in React App

## About

This project demonstrates a lightweight approach to authentication in a React application using JSON Web Tokens (JWT) stored in an **HttpOnly cookie**. It includes examples for signup, login, protected routes, and how to connect to various back-end implementations.

## Live references & tutorials

For more detail, please visit the original tutorials used as references:

* [React Login and Registration example with JWT](https://bezkoder.com/react-login-example-jwt-hooks/)
* [React + Redux: Login and Registration example with JWT](https://www.bezkoder.com/redux-toolkit-auth/)

### Back-end examples referenced

* Spring Boot + H2: [https://bezkoder.com/spring-boot-security-jwt/](https://bezkoder.com/spring-boot-security-jwt/)
* Spring Boot + MySQL/PostgreSQL: [https://bezkoder.com/spring-boot-login-example-mysql/](https://bezkoder.com/spring-boot-login-example-mysql/)
* Spring Boot + MongoDB: [https://bezkoder.com/spring-boot-mongodb-login-example/](https://bezkoder.com/spring-boot-mongodb-login-example/)
* Node Express + MySQL/PostgreSQL: [https://bezkoder.com/node-js-express-login-example/](https://bezkoder.com/node-js-express-login-example/)
* Node Express + MongoDB: [https://bezkoder.com/node-js-express-login-mongodb/](https://bezkoder.com/node-js-express-login-mongodb/)

### Fullstack examples

* React + Spring Boot: [https://bezkoder.com/spring-boot-react-jwt-auth/](https://bezkoder.com/spring-boot-react-jwt-auth/)
* React + Node.js Express: [https://bezkoder.com/react-express-authentication-jwt/](https://bezkoder.com/react-express-authentication-jwt/)

---

## Project setup

In the project directory, you can run:

```bash
npm install
# or
yarn install
```

### Compiles and hot-reloads for development

```bash
npm start
# or
yarn start
```

Open [http://localhost:8081](http://localhost:8081) to view it in the browser.

The page will reload if you make edits.

---

## Environment variables

Create a `.env` file in your front-end (if needed) and add any variables required for the app (for example API base URL):

```
REACT_APP_API_BASE_URL=http://localhost:8080
```

> Adjust ports and URLs according to the back-end you run locally.

---

## Backend quick-start (examples)

If you use the Node/Express example referenced in the links above, run the server and make sure it listens on the port your front-end expects (commonly `8080` or `3000`). When using Spring Boot examples, review the project README from the referenced posts for DB setup (H2, MySQL, PostgreSQL, MongoDB).

---

## Features

* Signup and Login forms with validation (Formik + Yup)
* JWT issuance on successful authentication
* JWT stored in HttpOnly cookie to improve XSS resistance
* Protected routes (React Router) that require a valid cookie/token
* Role-based UI (basic example showing/hiding nav links)

---

## Project structure (example)

```
/src
  /components
  /pages
  /services
  App.js
  index.js
```

---

## Useful commands

* `npm start` — start dev server
* `npm run build` — create production build

---

## Related posts & extras

* [In-depth Introduction to JWT-JSON Web Token](https://bezkoder.com/jwt-json-web-token/)
* [React Hooks CRUD example with Axios](https://bezkoder.com/react-hooks-crud-axios-api/)
* [React Pagination using Hooks example](https://bezkoder.com/react-pagination-hooks/)
* [React Hooks File Upload example](https://bezkoder.com/react-hooks-file-upload/)

---

## Author / Contact

**Elizabeth Mijide**
Email: [elizabeth.mijide@example.com](mailto:elizabeth.mijide@example.com)

*Replace the email above with your preferred contact email before publishing this README.*

---

## License

This project is open-sourced — add a license (MIT, Apache, etc.) if you wish.

---

## Notes

* I have personalized this README with your name and a placeholder email. If you want me to insert a specific email, GitHub handle, project description, or tweak any sections (shorter/longer, add badges, add screenshots), tell me what to replace and I will update it.
