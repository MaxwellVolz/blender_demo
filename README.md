# Setup

## VSCode


## Installing Node.js and npm
Node.js comes with npm (Node Package Manager) bundled, which means installing Node.js will also install npm.

1. Visit the [Node.js website](https://nodejs.org/).
2. Download the installer for your operating system (choose LTS version recommended for most users).
3. Run the installer and follow the prompts to install Node.js and npm.

Verify Install with:

```bash
node -v
npm -v
```

## Convert a model

1. In Blender Export to `.glb`
2. Copy to `/public`

```bash
npx gltfjsx public/globe.glb
```

1. Move the `Globe.jsx` -> `/models`
2. Edit the `Globe.jsx`:

```js
export default function Model(props) {
```

