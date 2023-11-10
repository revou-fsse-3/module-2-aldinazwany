This is **README** file

# My Landing Website - My Course
Layout: https://wonderful-sprite-177a55.netlify.app/

## **Task**
1. Deploy a website about things that you built and deployed on Netlify
2. The deployment must be auto deploy from your project's main branch using github Action
3. Your portofolio website can be accessed by custom domain.
4. Documented on a readme with screenshots.
5. Readme must explain about:
- Netlify sign up process and connect netlify to your github project
- Auto deployment on Github with Netlify
- How to connect your custom domain and DNS

## **Screenshot**
**A. Netlify sign up process** 
1. Access netlify website (app.netlify.com) and select sign up with email or sign up with Github if you already have the account


![Myimage](./assets2/1.1%20Sign%20up%20process.JPG)

2. If you choose sign up with email, please enter your email address and make the password. However, you can also choose to sign up with github if you already have the account. Make sure you input the same email addresses.

![Myimage](./assets2/1.2%20Sign%20up%20using%20email.JPG)

**B. Connect netlify to your github project and auto deployment on Github with Netlify**

1. After you login, choose add new site and select 'import an existing project
'
![Myimage](./assets2/2.1%20Import%20project.JPG)


2. Select deploy with Github

![Myimage](./assets2/2.2%20Deploy%20with%20Github.JPG)

3. You will be redirected to github login, once you are in, you will be validated. Please choose revou-fsse-3 and select the respective module


![Myimage](./assets2/2.3%20Choose%20Revou%20and%20selected%20module.JPG)

4. Now step to setup the basic info and type your assignment week and ends with /. Go to deploy button on the bottom

![Myimage](./assets2/2.4.1%20Select%20and%20fill%20data.JPG)

![Myimage](./assets2/2.4.2%20Select%20and%20fill%20data.JPG)

5. Deploying process

![Myimage](./assets2/2.4.3%20Deploying.JPG)

6. Deploying in progress

![Myimage](./assets2/2.4.4%20Deploy%20in%20Progress.JPG)

7. Deploying Succeed

![Myimage](./assets2/2.4.5%20Deployed%20success.JPG)


**C. How to connect your custom domain and DNS**

1. Make sure you already buy external domain. In this example, I already bought domain from niagahoster. Please ensure it is already active.

![Myimage](./assets2/3.1%20Niagahoster%20active.JPG)

![Myimage](./assets2/3.2%20Niagahoster%20status.JPG)

2. On netlify website, please select desired project in 'sites' menu

![Myimage](./assets2/4.1%20Go%20to%20site%20configuration.JPG)

3. Go to domain management section and click add domain alias. Copy your domain in niagahoster (i.e Aldin.tech) then click verify --> adding domain. Below screenshot is the process after clicking these steps. 

4. To use Netlify DNS, go to your domain registrar and change your domain’s name servers to the following custom hostnames assigned to your DNS zone.

![Myimage](./assets2/4.4%20Domain%20DNS.JPG)

5. On domain's name servers (in this case is Niagahoster), please go to DNS/Namaservers sections and copy all custom hostnames assigned to DNS zone in the Netlify. 

![Myimage](./assets2/4.5%20Change%20Nameserver%20in%20niagahoster.JPG)

6. All process are done. This domain is waiting for external DNS propagation that can take up to 24 hours).

7. Once done, you can go to your custom link by clicking 'site overview' and select your projects and select your domain's link.

![Myimage](./assets2/4.6%20Go%20to%20your%20custom%20link.JPG)

8. You will be redirected to your website.

![Myimage](./assets2/4.7%20Redirect%20to%20website.JPG)

Thank you