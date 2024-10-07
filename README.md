## sample-multiapp-nextjs

This project is a proof of concept (POC) for deploying two NextJS applications within a single monorepo.

### How to Use

After cloning the repo, to run application one,
```
cd apps/app_one
npm install
npm run dev
```
Navigate to localhost:3000 and you should see something like

<img width="1728" alt="Screenshot 2024-10-07 at 8 39 30 AM" src="https://github.com/user-attachments/assets/dfb1ef52-b0e0-477c-af5c-f7abf5ba50fb">

To run application two,

```
cd apps/app_two
npm install
npm run dev
```

Navigate to localhost:3000 and you should see something like

<img width="1727" alt="Screenshot 2024-10-07 at 8 40 47 AM" src="https://github.com/user-attachments/assets/596ffef3-fdbc-41e4-8849-48f8e07094db">

