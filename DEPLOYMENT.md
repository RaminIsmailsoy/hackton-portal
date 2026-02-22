# Deployment Instructions for hackton-portal

## Step 1: Prerequisites
- Ensure you have Node.js installed on your server.
- Install Yarn or npm for managing packages.

## Step 2: Clone the Repository
Run the following command to clone the repository onto your server:
```bash
git clone https://github.com/RaminIsmailsoy/hackton-portal.git
```

## Step 3: Navigate to the Project Directory
Change into the project directory:
```bash
cd hackton-portal
```

## Step 4: Install Dependencies
Use Yarn or npm to install the necessary dependencies:
```bash
npm install
# or
yarn install
```

## Step 5: Build the Project
Build the project using the following command:
```bash
npm run build
# or
# yarn build
```

## Step 6: Start the Server
Start the server using:
```bash
npm start
# or
# yarn start
```

## Step 7: Access the Application
Open your web browser and go to http://your-server-ip:3000 to access the application.

## Step 8: Additional Configuration (Optional)
- Configure environment variables as necessary.
- Set up a reverse proxy (e.g., using Nginx) if needed.

## Step 9: Monitor the Application
- Monitor the logs for any issues.
- Ensure your server has enough resources to run the application smoothly.

## Conclusion
You now have the hackton-portal running on your server!