[![Netlify Status](https://api.netlify.com/api/v1/badges/e9f165ee-578e-4d47-b2f9-27d34d45a6ea/deploy-status)](https://app.netlify.com/sites/netlify-backend/deploys)

<p> -> endpoints : student , institute , course , teacher</p>
<p>deployment procedure:
<ol><li>follow this folder structure </li>
<li>add script : "scripts": {
    "build": "netlify deploy --prod"
  },
 </li>
  <li>add enviroment vairables : netlify env:set VAR_NAME value
</li>
  <li>Run deploy command after api tests : npm run build</li>
</ol>
</p>
