# capkit

The CapKit CLI is a command-line tool that simplifies the process of configuring Capacitor with SvelteKit. With CapKit, you can quickly set up Capacitor for your SvelteKit app, making it easy to build and deploy native mobile applications as well as progressive web apps.

## Installation

To get started with the CLI you can simply go into your existing sveltekit project and run:
```bash
npx capkit init
```

After doing so you will be prompted will multiple questions that you can answer to get the most ideal configuration.

## Usage

To help improve the integration more the capkit CLI adds two scripts to your package.json.

### Development

When working with native applications and using their respective IDE's (Android Studio or Xcode) you can enable hot reloading by running:
```bash
npm run dev:cap
```

If you are solely focusing on creating a progressive web app you can run:
```bash
npm run dev
```

### Build

When building to native platforms you can use:
```bash
npm run build:cap
```

If you are solely focusing on building a progressive web app you can run:
```bash
npm run build
```
