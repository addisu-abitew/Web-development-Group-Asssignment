# Web-development-Group-Asssignment
# Ecommerce Website
## Group members
| No | Name | ID |Section|
| ------ | ------ | ------ |------ |
|1| Semir Hamid | UGR/9690/13| 1|
|2 |Hayat Shifa | UGR/9771/13| 1|
|3| Bilen Mehalek | UGR/0252/13| 1|
|4| Addisu Abitew | UGR/7259/13| 3|
|5| Selam Yemiru | UGR/4870/13| 3|

# Frontend Specification
## Boostrap 
## Html
## css

#Backend Specification
## Nestjs
## Prisma
## Postgressql


# Why we used postgressql/ Relational DB
## Since ecommerce sites handles well-structured data. As the tables standardise the data, a relational database makes it easier to store, update and retrieve specific datasets using SQL queries. This data can be more easily formed into accurate reports as it’s all in one format. In a non-relational database, the data is unstructured, which can make it difficult to make sweeping changes to it or make accurate queries.

## This is referred to as normalisation, and helps to reduce data deduplication. This term means that redundant data is eliminated as much as possible.
The relational database model is mature and widely recognised, so from a practicality perspective, it’s generally easier for developers to work with..
It helps to visualise the data and its relationships, as well as gather results from it. However, it comes with drawbacks.



##
## Installation Instructions
Yarn package manager package available (https://www.nuget.org/packages/Postgres.BackupandRestoreDatabase)
```
Install-Package Postgres.BackupandRestoreDatabase -Version 1.4.1
```
dotnet cli:
```
dotnet add package Postgres.BackupandRestoreDatabase --version 1.4.1
```


# Nestjs


## Before getting started

Make sure you have installed [Nostjs @latest]([https://nodejs.org/en/](https://docs.nestjs.com/)) on your machine. You can use [

## Getting started

You can setup this project using npm or yarn package managers.

> I would recommend to installed or enabled [yarn](https://yarnpkg.com/getting-started) 1.22.15 or higher on your machine.

### Clone repo

```bash
git clone https://github.com/semirhamid/Web-development-Group-Asssignment.git
#or
git clone https://github.com/semirhamid/Web-development-Group-Asssignment.git
```

### Navigate to cloned repo

```bash
cd backend
```

### Install dependencies

```bash
yarn install
#or
npm install
```

### Start development server

```bash
yarn start:dev
#or
npm run dev
```

Open [http://localhost:3000](http://localhost:1756) with your browser to see the result.

### Build for production

```bash
yarn build
#or
npm run build
```

### Start preview server after build

```bash
yarn start
#or
npm run start
```

Open [http://localhost:3000](http://localhost:1756) with your browser to see the result.

### Run release

Follow the [Conventional Commits Specification](https://www.conventionalcommits.org/en/v1.0.0/) in your repository. And when you're ready to release, run below scripts.

```bash
yarn release
#or
npm run release
```

## Learn More

To learn more about Next.js, ESLint, Prettier, StyleLint and lint-staged, take a look at the following resources:

* [Nestjs Documentation](https://docs.nestjs.com/) - Learn about Next.js features and API
* [Prettier Setup](https://prettier.io/docs/en/install.html) - Learn about how to setup prettier
* [Prettier Integrations](https://prettier.io/docs/en/related-projects.html) - Learn about how to setup prettier with other tools
* [ESLint Setup](https://eslint.org/docs/user-guide/getting-started) - Learn about how to ESLint
* [StyleLint Setup](https://stylelint.io/user-guide/get-started) - Learn about how to setup StyleLint
* [Lint Staged Setup](https://github.com/okonet/lint-staged) - Learn about how to setup lint-staged
* [Standard Version](https://github.com/conventional-changelog/standard-version) - Learn about how to setup standar version
