### **📌 Installation & Deployment Steps for Shopify Volume Discount Function**  

1️⃣ **Install Shopify CLI**  
```sh
npm install -g @shopify/cli
```

2️⃣ **Create a New Shopify App (Remix-based)**  
```sh
shopify app init your-app-name --template remix
```
Navigate to the app directory:  
```sh
cd your-app-name
```
Install dependencies:  
```sh
npm install
```

3️⃣ **Generate the Discount Function**  
```sh
npm run shopify app generate extension
```
- Select **"Discount Function"**  
- Name it **"volume-discount"**  
- Choose **JavaScript** as the language  

4️⃣ **Build the App**  
```sh
npm run shopify app build
```

5️⃣ **Deploy the App**  
```sh
npm run shopify app deploy
```

6️⃣ **Run the App in Development Mode**  
```sh
npm run shopify app dev
```

---

Your Shopify Volume Discount Function is now installed, deployed, and ready for development! 🚀