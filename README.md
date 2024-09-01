# Next JS App
## SIH internal hackathon

An Web App created for generating Invoices and send those invoices back to customers via email

### What are the Features -
- User can `generate invoices` with Pre Loaded Template
- User can add multiple address for his organization
- User can `print` generated invoices 
- user can send invoices `via email` to customer email address 

### How to run locally
```bash
git clone https://github.com/MrVineetRaj/NextJs_SIH_internal.git
npm install 
```

#### Add Few enviornment Variables in 
`.env.local` file created in root directory of the project
```bash
JWT_SECRET=
EMAIL_USER=example@gmail.com
EMAIL_PASS=<Gmail PASS key>
```



```bash 
npm run dev
```

Now you can check the website on `http://localhost:
3000 `

Thankyou for using