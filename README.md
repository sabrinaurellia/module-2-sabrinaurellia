# Serendipia - Online Shop Deployment Documentation

## Netlify Deployment Process

### Day 1: Register on Netlify
1. Go to [Netlify](https://www.netlify.com/).
2. Create an account using GitHub account, or any other available method.
3. Once registered, sign in to Netlify dashboard.

### Day 2: Connect Netlify with GitHub Project
1. In Netlify dashboard, click on **"New site from Git"**.
2. Choose **GitHub** as the Git provider and authorize Netlify to access repositories.
3. Select the **module-2-sabrinaurellia** repository from GitHub.
4. Once connected, Netlify will automatically build and deploy the project.
5. Test the deployment by visiting the live URL provided by Netlify.

### Day 3: Domain Registration and DNS Configuration
1. **Buy a domain** from a domain registrar like **Niagahoster**
2. **Configure DNS**:
   - Go to the **DNS settings** of domain registrar.
   - Set the **DNS records** to point to **Netlify's DNS servers**.
3. In Netlify, go to **Site Settings** > **Domain Management** to find the **DNS information** required to link the domain.

#### Example DNS Configuration:
- **CNAME record**: Point custom domain to Netlify subdomain.

### Day 4: Create Documentation for the Deployment Process
1. Update this **README.md** file to document all steps of the process, including the Netlify setup, domain registration, and DNS configuration.
2. Ensure to include screenshots and any additional details required to explain the deployment process.


- [Web deployment](https://serendipiaid.netlify.app/)
---

## Resources

- [Netlify Documentation](https://docs.netlify.com/)
- [Domain Setup Instructions](https://docs.netlify.com/domains-https/custom-domains/)

## Final Steps
- Once the site is deployed on Netlify and connected to a custom domain, ensure the site is functioning correctly.
- Provide a **live URL** of the deployed website in this README.
- Capture screenshots of the deployment process to include in the documentation.

### Troubleshooting
- If you're unable to connect the repository to Netlify, ensure that you have the necessary permissions (admin access to the GitHub repository).
- If the domain isn't showing the correct content, double-check DNS settings in both domain registrar and Netlify.

---

### Summary of the Deployment Steps:
1. Register on Netlify.
2. Connect GitHub repository to Netlify.
3. Set up a custom domain and DNS management.
4. Document the full process with screenshots and explanations.

