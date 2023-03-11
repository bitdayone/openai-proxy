One-click deployment of the ChatGPT private proxy, power by Next.js

English | [简体中文](./README-CN.md)

## Deploy on Zeabur

The Zeabur is recommended, Specific operations are as follows

1. Fork this repository for your own repository

<img width="600" src="public/frok.png" alt="fork" />

2. Deploy your repo on [Zeabur](https://zeabur.com)

3. Add a new service on [Zeabur](https://zeabur.com) console

<img width="600" src="public/zeabur-console.png" alt="step 1"/>

4. select from source deploy

<img width="600" src="public/zeabur-console-1.png" alt="step 2"/>

5. select your forked repo

<img width="600" src="public/zeabur-console-2.png" alt="step 3"/>

6. select main and deploy

<img width="600" src="public/zeabur-console-3.png" alt="step 4"/>

7. After the deployment is successful, Generate domain on the setting tab

<img width="600" src="public/zeabur-console-4.png" alt="step 5"/>

8. Finally get your service

<img width="600" src="public/zeabur-console-5.png" alt="step 6"/>

## Deploy on Vercel

If you use Vercel deploy services, you must [custom domain name](https://vercel.com/docs/concepts/get-started/assign-domain), beacuse the [custom domain name](https://vercel.com/docs/concepts/get-started/assign-domain) is not affected by the GFW, Specific operations are as follows

<a href="https://vercel.com/import/project?template=https://github.com/imyuanx/chatgpt-proxy" target="_blank" rel="noopener noreferrer"><img src="https://vercel.com/button" alt="Deploy to Vercel"></a>

1. Click the deploy button at the top

<img width="600" src="public/vercel.png" alt="One-click deploy"/>

2. After deployment, the repository will be forked automatically for you, entering a custom repository name in the input field

<img width="600" src="public/vercel-deploy.png" alt="Deploy"/>

3. After successful deployment, get your service

<img width="600" src="public/vercel-success.png" alt="Alt text"/>

4. You must add a custom domain name for your service, otherwise you will not be able to access your service in the country

<img width="600" src="public/vercel-domain.png" alt="Domain"/>

## How to use

Whether you use Zeabur or Vercel, you will get the following proxy service after deployment

<img width="600" src="public/proxy.png" alt="Proxy service"/>

The address in the red box is fully forwarded to `https://api.openai.com` and is accessible within the country

You can use the proxy service in applications that support custom apis to invoke the "openai" interface domestically

Fro example, [openai-translator](https://github.com/yetone/openai-translator):

<img width="600" src="public/openai-translator.png" alt="Alt text"/>
