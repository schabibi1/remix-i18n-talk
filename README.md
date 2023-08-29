# Remix & Storyblok i18n folder-level talk resource repo

![Blog](https://res.cloudinary.com/dsmeebz8b/image/upload/v1651070686/Remix%20workshop/Screenshot_2022-04-27_at_16.44.03_cv5f0c.png)

This repository is a Remix [Storyblok](https://www.storyblok.com) i18n talk repo.

We have a starter template that you can use from our [5 minute tutorial](https://www.storyblok.com/tp/headless-cms-remix) if you want to start from a scratch.

## Requirements

To use this project you need a Storyblok account. If you don't have one yet you can register at [Storyblok](https://www.storyblok.com). It's free.

## How to get started?

Read the [Remix tutorial](https://www.storyblok.com/tp/headless-cms-remix) about connecting Storyblok with Remix.

### 1. Fork the repo

### 2. Install all dependecies

```sh
npm i
```

### 3. Create a space at Storyblok

### 4. Adding the Access token

Exchange the preview token of your new space with the `accessToken` in `app/root.jsx`.

### 5. Run your project

Set the preview domain in <strong>Storyblok</strong> to `http://localhost:3000/`

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.
#### Using a Template

When you ran `npx create-remix@latest` there were a few choices for hosting. You can run that again to create a new project, then copy over your `app/` folder to the new project that's pre-configured for your target server.

```sh
cd ..
# create a new project, and pick a pre-configured host
npx create-remix@latest
cd my-new-remix-app
# remove the new project's app (not the old one!)
rm -rf app
# copy your app over
cp -R ../my-old-remix-app/app app
```

## Resources

- [Remix Docs](https://remix.run/docs)
- [Storyblok Tutorial](https://www.storyblok.com/tp/headless-cms-remix)