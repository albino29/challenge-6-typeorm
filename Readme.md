<h1 align="center">
  <img src="public/logo.svg"/>
</h1>

<h2 align="center">
  Backend
</h2>

---

## 🚀 About
GoStack Bootcamp **Challenge 6**: practicing typescript.
<br /> This is my solving of this challenge

---

## 🛣 Available routes

| Resource               | Method          | Description                                                               |
| ---------------------- | --------------- | ------------------------------------------------------------------------- |
| `/transactions/import` | [`POST`]        | Import an [csv](src/__tests__/import_template.csv) file with transactions |
| `/transactions`        | [`GET`, `POST`] | List / Add new transaction                                                |
| `/transactions/:id`    | `DELETE`]       | Delete transaction                                                        |

---

## 💻 Running

```bash
$ git clone https://github.com/albino29/challenge-6-typeorm
$ cd challenge-6-typeorm
$ yarn
$ yarn dev:server
```

### 🧪 Running tests

```bash
$ yarn test
```
<img src="public/tests.png"/>

> All scripts can be found at [package.json](./package.json)

---

