Link Sharing App, Live link: https://link-share-application.vercel.app

## Getting Started

#### 1. First, clone this project:

```bash
git clone https://github.com/sifathme/link-sharing-app.git
```

#### 2. Go inside it:

```bash
cd link-sharing-app
```

#### 3. install dependencies:

```bash
yarn
# or
yarn install
# or
npm install
```

#### 4. add Environment Variables:

`.env.local` and `.env` files is required, Please copy and paste `.env.local.example` and `.env.example` files and rename, and add required variables.

or

You can visit this [link](https://sifathme.notion.site/Link-Sharing-App-11f73be9627480f893a4f7a404d8b0d8) for [`Environment Variables`](https://sifathme.notion.site/Link-Sharing-App-11f73be9627480f893a4f7a404d8b0d8)

#### 5. Run Prisma command:

```bash
yarn db:prisma
# or
npm run db:prisma
```

#### 6. Run the development server:

```bash
yarn dev
# or
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

### For Production:

#### 1. Run the build command:

```bash
yarn build:prod
# or
npm run build:prod
```

#### 2. Start the production server:

```bash
yarn start
# or
npm start
```
