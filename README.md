# API Tests with Newman 🧪

This repository contains a collection of automated API tests executed using [Newman](https://www.npmjs.com/package/newman), the command-line runner for Postman collections.

## 📦 Prerequisites

Make sure the following tools are installed on your machine:

- [Node.js](https://nodejs.org/) (v18 or later)
- npm (comes bundled with Node.js)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/alem-x/alemx-newman.git
cd alemx-newman
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the API tests

```bash
npm run api-tests
```

This command will execute your Postman collection using Newman.

## 📁 Folder Structure

```
├── .github/workflows
│   └── ci.yml
├── Alemx.postman_collection.json       # Postman collections
├── .gitignore
├── package-lock.json                   
├── package.json
└── README.md
```

## 📝 Scripts

In the `package.json` file, the following script is defined:

```json
"scripts": {
  "api-tests": "newman run Alemx.postman_collection.json"
}
```

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
