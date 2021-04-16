# Vue JS (Raspberry Pi)

Mettre en place **Vue.js** sur Raspberry Pi.


___
___

## Installation & Configuration

1. Standalone

```html
<script src="https://unpkg.com/vue"></script>
```

2. NPM vue-cli

```bash
sudo apt-get install nodejs npm

# Si ça marche pas :
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
```

```bash
sudo npm install -g n
sudo n stable
sudo npm i npm@latest -g
sudo npm i -g @vue/cli
sudo npm i -g @vue/cli-init
vue init webpack tpvuejs
cd tpvuejs
npm install
npm run lint
npm run dev
```
