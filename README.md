# atlas-data-api-remix
A sample app to show case new [remix.run](https://remix.run/) JS framework with [MongoDB Atlas Data Rest API](https://www.mongodb.com/developer/quickstart/atlas_data_api_introduction/)

## Prerquisities

- [Get startd with Atlas](https://docs.atlas.mongodb.com/getting-started/) and prepare a cluster to work with.

- [Enable](https://docs.atlas.mongodb.com/api/data-api/) the DATA API and save the API key

- [Load sample data](https://docs.atlas.mongodb.com/sample-data/) set into the cluster (This application is using `sample_mflix` for its demo)

- Create a `.env` file in the main directory:
```
DATA_API_KEY=<API-KEY>
DATA_API_BASE_URL=<YOUR-ENDPOINT-URL>
```

## Development

Install:
```
npm install
```

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.

## Deployment

First, build your app for production:

```sh
npm run build
```

Then run the app in production mode:

```sh
npm start
```
