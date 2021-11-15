# How to install the project
## Clone the website with ssh
` git clone git@github.com:IIM-Creative-Technology/nextjs-devops-romain_valla_iwm1.git`

## Install dependencies
```npm install or yarn install```

## Build project
``next build``

## Start project
```npm start```

# How it works
- When you push something on a branch that is not ```main``` the pipeline process multiple check and deploy a preproduction website.
- If you push on ```main``` the pipeline will automatically deploy a production website
  - I'm using Vercel as host.

# Explanation in French
- J'ai décider d'utiliser Vercel pour ça simplicité et son intégration avec Github. J'ai notamment utilisé le projet d'example d'une boutique afin de réalisé ce projet. Afin de configurer Vercel j'ai du générer trois secrets dans github pour la clé API, le nom du projet générer avec la commande ```npm install -g vercel``` puis après avoir suivis les instructions j'ai utilisé cette commande afin de générer un environement Vercel `vercel`.






[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fcommerce&project-name=commerce&repo-name=commerce&demo-title=Next.js%20Commerce&demo-description=An%20all-in-one%20starter%20kit%20for%20high-performance%20e-commerce%20sites.&demo-url=https%3A%2F%2Fdemo.vercel.store&demo-image=https%3A%2F%2Fbigcommerce-demo-asset-ksvtgfvnd.vercel.app%2Fbigcommerce.png&integration-ids=oac_MuWZiE4jtmQ2ejZQaQ7ncuDT)
