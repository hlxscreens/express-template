# Express Project Template
Welcome to our Express Integration with AEM Franklin GitHub repository! This template is a robust solution crafted to simplify the intricate process of setting up the integration between Express and Adobe Experience Manager (AEM) Franklin. With pre-configured settings and optimized Express routes, the template ensures a seamless flow of channels between the two platforms. The middleware provided facilitates efficient channel propagation from Express to AEM Franklin, promoting accurate and timely updates. Built for scalability, this template can effortlessly handle a growing number of channels without compromising performance. 

## Environments
- Preview: https://main--express-template--hlxscreens.hlx.page/
- Live: https://main--express-template--hlxscreens.hlx.live/

## Installation

```sh
npm i
```

## Tests

```sh
npm test
```

## Local development

1. Create a new repository based on the `helix-project-boilerplate` template and add a mountpoint in the `fstab.yaml`
1. Add the [helix-bot](https://github.com/apps/helix-bot) to the repository
1. Install the [Helix CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/helix-cli`
1. Start Franklin Proxy: `hlx up` (opens your browser at `http://localhost:3000`)
1. Open the `{repo}` directory in your favorite IDE and start coding :)
