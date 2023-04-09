# Cyprus rocks static website

➡️ [DEMO](https://cyprusrocks.eu/)

# Getting started

    git clone git@gitlab.com:Snegovikufa/cyprusrockseu.git cyprusrockseu
    cd cyprusrockseu
    git submodule update --recursive
    npm install
    npm start

# Publishing

When deploying to services like Netlify or Vercel, use the following command for building your site:

    npm i && HUGO_ENVIRONMENT=production hugo --gc

