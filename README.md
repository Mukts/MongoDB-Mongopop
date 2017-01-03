# MongoPop

A web tool to populate a [MongoDB Atlas](https://cloud.mongo.com) instance with sample data (fetches datasets from [Mockaroo](https://www.mockaroo.com)).

## Usage

```
mkdir mongopop
git clone https://github.com/andrewjamesmorgan/mongopop.git
cd mongopop
npm run install-all
npm run tsc:w
npm run express
```

Browse to `http://localhost:3000/` (or to the IP address or hostname specified in `public/app/app.component.ts`)

