# A statically generated blog example using Next.js and spurtcms

![Screenshot of spurtCMS using Presentation Tool to do Visual Editing](https://www.spurtcms.com/spurtcms-starter-template.jpg)

This starter is a statically generated blog that uses Next.js App Router for the frontend and [spurtcms][https://demo.spurtcms.com/dashboard/] to handle its content. It comes with a native spurtcms that offers features like real-time collaboration and visual editing with live updates using [https://spurtcms.com/documentation].

The Studio connects to spurtcms, which gives you hosted content APIs with a flexible query language, on-demand image transformations, powerful patching, and more. You can use this starter to kick-start a blog or learn these technologies.

## Features

- Smooth admin login and intuitive dashboard.
- Quick navigatgion to channels, members, spaces from dashboard.
- Easy Admin Profile Update.
- Manage roles and assigning of permisions.
- Effortless team creation.
- Multilingual support.
- Customization of email templates
- Create and manage content
- Member management and member access
- Simple space creation



## Admin Panel Demo

### [https://nextjs-starter-theme.vercel.app/](https://nextjs-starter-theme.vercel.app/)




## Deploy your own

Use the Deploy Button below, you'll deploy the example using 

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fspurtcms%2Fnextjs-starter-theme)

## Configuration


## Step 1. spurtCMS Admin Setup

Setup SpurtCMS Admin Console for Manage or Populate content

spurtCMS prioritizes user-friendly administration, offering powerful tools for content creation, management, and defining CMS workspaces. Administrators have precise control over member access, ensuring streamlined member management. Dynamic channel management allows effective content structuring, enhancing the overall user experience. Administrators effortlessly create and manage channels and spaces, providing a comprehensive, user-centric content management solution for personalized and organized web
environments.

![Screenshot of spurtCMS]()


First,you need to set up spurtCMS Admin Application.There are many solutions for insallation.
Please refer [(https://www.spurtcms.com/documentation/cms-admin)] 

But,you can quick start with using CLI

```bash
sudo snap install spurtcms
```
```bash
spurtcms -i admin
```
```bash
sudo ./spurtcms-admin.sh
```
```bash
sudo systemctl start spurtcms-admin.service
```
```bash
sudo systemctl stop spurtcms-admin.service
```
## Step 2. GraphqlAPI Setup
To initiate the set up process please refer
[(https://www.spurtcms.com/documentation/grapql-api-setup)]

or using CLI
```bash
spurtcms -i graphql
```

```bash
sudo ./spurtcms-api.sh
```

```bash
sudo systemctl start spurtcms-api.service
```

```bash
sudo systemctl stop spurtcms-api.service
```
## Step 3. Set up environment variables
Open .env and set  NEXT_PUBLIC_SPURTCMS_NEXTJS_STARTER_THEME_BASEURL  to  be the URL to your GraphQL endpoint in spurtCMS. 

Your env should look like this:

```bash
NEXT_PUBLIC_SPURTCMS_NEXTJS_STARTER_THEME_BASEURL=""
```
```bash
NEXT_PUBLIC_SPURTCMS_NEXTJS_STARTER_THEME_TOKEN=""
```
## Step 4. Run Next.js in development mode
```bash
npm install 
```
```bash
npm run dev
```
Your blog should be up and running on [http://localhost:3000!](http://localhost:3000!)


## Step 5. Run Next.js in production mode
```bash
npm run prod
```


## Feedback and Questions
If you have feedback or questions about this starter, please use the Github Issues on this repo, [(https://github.com/spurtcms/nextjs-starter-theme/issues)]

or Send Email to us [(support@spurtcms.com)]

