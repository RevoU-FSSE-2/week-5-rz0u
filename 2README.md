## Deploying a Website with Netlify and Buying a Domain from Niagahoster and setting up DNS with Cloudfare

### Step 1: Sign up for Netlify

![Signing Up To Netlify](Assets-Documentation/sign-up-netlify.png)

1. Visit the [Netlify](www.netlify.com) website
2. Click on "Sign Up"
3. Choose a Sign-up Method
- If signing up with a third-party account:
   - Click on the corresponding button (e.g., "Continue with GitHub").
   - You'll be redirected to the authentication page of the selected platform.
   - Log in to your account and authorize Netlify to access your account information.
- If signing up with an email and password:
   - Fill in the required fields, including your full name, email address, and a secure password.
   - Optionally, you may see additional fields, such as a team name or a referral code.
   - Review and agree to the Netlify terms of service and privacy policy.
4. Complete the Sign-up Process
- If signing up with a third-party account:
   - Netlify will create an account for you using your existing third-party account credentials.
   - You may need to authorize Netlify to access certain account information or repositories.
- If signing up with an email and password:
   - Netlify will send you a verification email to the email address you provided during sign-up.
   - Open your email inbox and locate the email from Netlify.
   - Click on the verification link within the email to confirm your account.
5. Set Up Your Netlify Account
6. Explore Netlify Features

### Step 2: Create a New Site

![New Website to Deploy](Assets-Documentation/new-website.png)

1. After signing in to Netlify, click on the "New site from Git" button on the Netlify dashboard.
2. Choose your preferred Git platform (GitHub, GitLab, or Bitbucket) or select "Continuous Deployment" if you prefer another Git provider or a local repository.
3. Authenticate and authorize Netlify to access your Git repository.
4. Select the repository that contains the website you want to deploy.
5. Configure the basic settings for your site, such as the branch to deploy, build command, and publish directory.
6. Click on the "Deploy site" button to initiate the deployment process.

### Step 3: Buy a Domain from Niagahoster

![Checking and Buying Domain from Niagahoster](Assets-Documentation/niagahoster-domain.png)

1. Visit the [Niagahoster](https://www.niagahoster.co.id/) website.
2. Use the domain search feature on the Niagahoster homepage to check the availability of your desired domain name.
3. Once you find an available domain, select it and proceed to the domain registration page.
4. Follow the steps to complete the domain registration process, providing the necessary details such as your personal information and contact details.
5. During the checkout process, select the desired domain registration period and any additional services you may need.
6. Proceed to make the payment to finalize the domain purchase.

### Step 4: Configure Custom Domain

![Adding Custom Domain](Assets-Documentation/add-domain-name.png)

1. Once your site is deployed, navigate to the Netlify dashboard.
2. Select your site from the list of deployed sites.
3. In the site settings, click on "Domain settings" or "Settings" followed by "Domain management."
4. Click on "Add custom domain" to configure a custom domain for your website.
5. Enter the desired domain name you want to use (e.g., `www.example.com`) and click on "Verify."
6. Netlify will provide you with DNS configuration instructions. Keep this information handy as you'll need it in the next step.

### Step 5: Sign up for Cloudflare and Add Your Domain

![Getting Cloudfare nameserver's](Assets-Documentation/cloudfare-nameservers.png)

1. Visit the [Cloudflare](https://www.cloudflare.com/) website.
2. Click on the "Sign Up" button to create a Cloudflare account.
3. Follow the prompts to add your website/domain to Cloudflare.
4. Cloudflare will scan your DNS records. Ensure that the records match the ones provided by Netlify in Step 3.
5. Once the scan is complete, Cloudflare will provide you with new nameservers for your domain.

### Step 6: Update Nameservers in Niagahoster

![Niagahoster's nameservers Change](Assets-Documentation/update-nameservers.png)

1. Log in to your Niagahoster account.
2. Locate the domain management section and access the nameserver settings.
3. Replace the existing nameservers with the new nameservers provided by Cloudflare.
4. Save the changes. This update may take some time to propagate across the internet.

### Step 7: Set Up Cloudflare DNS Settings

![Setting Up DNS](Assets-Documentation/dns-records.png)

1. Go back to the Cloudflare dashboard.
2. In Cloudflare, select your website/domain from the list of added sites.
3. Navigate to the DNS settings.
4. Verify that the DNS records match the ones provided by Netlify in Step 3.
5. If any records are missing, add them accordingly.
6. Save the DNS settings.

### Step 8: Wait for DNS Propagation

After updating the DNS settings, it may take some time for the changes to propagate across the internet. DNS propagation can vary and may take up to 24-48 hours, although it often happens much faster.

### You Can Visit the Finished Product Here
- [**https://thedroidyourelookingfor.site**](https://thedroidyourelookingfor.site)
- [**www.thedroidyourelookingfor.site**](https://www.thedroidyourelookingfor.site)
- [**https://rayhanzou-week4-assignment.netlify.app**](https://rayhanzou-week4-assignment.netlify.app)
