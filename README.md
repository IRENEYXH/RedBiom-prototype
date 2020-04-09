# RedBiom Web Prototype

> Redbiom is a microbiome caching layer, which allows users to rapidly query samples that contain a given feature, retrieve sample data and metadata, and search for samples that match specified metadata values or ranges (e.g., all samples with a pH of >7), implemented using an in-memory NoSQL database called Redis. By default, redbiom allows public anonymous sample access for over 100,000 publicly available samples in the Qiita database. At over 100,000 samples, the caching server requires only 35 GB of resident memory. We highlight how redbiom enables a new type of characterization of microbiome samples and provide tutorials for using redbiom with QIIME 2. redbiom is open source under the BSD license, hosted on GitHub, and can be deployed independently of Qiita to enable search of proprietary or clinically restricted microbiome databases. (Mcdonald, et al. 2019)


## Motivations
After researched on current command line tool and web interface, we found several limitations to the design that would lead to hidden features and furstrating user experience. Therefore, this web prototype is to improve the smoothness of searching process, provide more guidance, and encourage explorations in data.

![interface](https://github.com/IRENEYXH/RedBiom-prototype/blob/master/doc/prototype.png)

**[Design process doc](https://github.com/IRENEYXH/RedBiom-prototype/tree/master/doc)**


## Development

This prototype is built using [Vue.js](https://vuejs.org) and [Vega](https://vega.github.io/vega/)

### Vue.js setup

##### install vue
```
npm install vue
```

##### Project setup
```
npm install
```

##### Compiles and hot-reloads for development
```
npm run serve
```

##### Compiles and minifies for production
```
npm run build
```

##### Lints and fixes files
```
npm run lint
```

#### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
