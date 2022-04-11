# Project Setup

# Description

<h3> Image Processing API using : </h3>

      - Node.Js
      - sharp
      - Jasmine
      - prettier
      - eslint

# Running

<h2> Install dependencies </h2>

     npm install

<h2> Run development server </h2>

     npm run start

<h2> Testing  </h2>

     npm run test

<h2> Compile typescript to javascript </h2>

     npm run build

<h2> Linting </h2>

     npm run lint

<h2> Formatting code with Prettier </h2>

     npm run format

<h2> API endpoint </h2>

      **GET /api/images?filename=name&width=200&height=200**

- Put images in the images folder, and thumbnails will be in the thumbs folder



# Image Processing API

A nodejs API to resize images.

## Scripts

- To run prettier: npm run prettier
- To run lint: npm run lint
- To build: npm run build
- To run tests: npm run jasmine
- To build and run tests: npm run test
- To start production server: node .\build\
- To start development server: npm run start

## Endpoints

1. **GET /api/images?filename=name&width=200&height=200**

- Put images in the images folder, and thumbnails will be in the thumbs folder
