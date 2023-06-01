# Better Together.
A gallery meant to inspire.

## ════ ⋆★⋆ ════

## Touch the Color; See the Sound

 When unexpected sadness really hits home & it's difficult to shake it... always remember it's the smallest things that manage to melt my heart.
> Live demo can be found [here](https://image-gallery-eight-lac.vercel.app/)

## Tech Stack

- ![nextjs](https://camo.githubusercontent.com/8552f38715af0ea9f364801b055f7a2448812b49075860983d53a81414349623/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d4e6578742e6a7326636f6c6f723d303030303030266c6f676f3d4e6578742e6a73266c6f676f436f6c6f723d464646464646266c6162656c3d)

- ![typescript](https://camo.githubusercontent.com/773cfd323f61dbc7301a98e28c69fbd0f27f491272f4acf48106936ca1d14c47/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d5479706553637269707426636f6c6f723d333137384336266c6f676f3d54797065536372697074266c6f676f436f6c6f723d464646464646266c6162656c3d)

- ![tailwind](https://camo.githubusercontent.com/5d16e7fdd964ebca50ca82d6c8b081045630340427c463f4470050acd4e50ef3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d5461696c77696e642b43535326636f6c6f723d323232323232266c6f676f3d5461696c77696e642b435353266c6f676f436f6c6f723d303642364434266c6162656c3d)
- 
## Table of contents

> * [Title / Repository Name](#image-gallery)
>   * [Table of contents](#table-of-contents)
>   * [Installation](#installation)
>   * [Usage](#usage)
>     * [Screenshots](#screenshots)
>     * [Features](#features)
>   * [Code](#code)
>     * [Content](#content)
>     * [Requirements](#requirements)
>     * [Limitations](#limitations)
>     * [Build](#build)
>     * [Deploy (how to install build product)](#deploy-how-to-install-build-product)
>   * [License](#license)


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=<name-of-cloud>`

`CLOUDINARY_API_KEY=<your-api-key>`

`CLOUDINARY_API_SECRET=<secret-key>`

// optional

`CLOUDINARY_FOLDER=<specific-folder-name>`

## Configuration

Add the following variables to your .env.local or .env file. & if you deploy it, with Vercel for example, you can place these variables in the Envorpnment Variables part of the setup!

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="<Your Cloud Name>"

CLOUDINARY_API_KEY=<your-api-key>

CLOUDINARY_API_SECRET=<secret-key>

CLOUDINARY_FOLDER=<specific-folder-name>

## Installation

* From the command line: 
```
npm install @headlessui/react @heroicons/react cloudinary eslint-config-next framer-motion imagemin imagein-jpegtran next react react-dom react-hooks-global-state react-swipeable react-use-keypress
```

## Usage

### Screenshots

![App Screenshot](https://res.cloudinary.com/codelikeagirl29/image/upload/v1684422294/projects/Next-js-Conf-2022-Photos_zcmzzj.png)

### Features

## Code
![Vercel](http://therealsujitk-vercel-badge.vercel.app/?app=image-gallery-eight-lac.vercel.app)

### Build

    npm run build

### Deploy (how to install build product)

Direct to MP package if any. Otherwise provide steps to deploy on Nuxeo Platform:

 > Copy the built artifacts into `$NUXEO_HOME/templates/custom/bundles/` and activate the `custom` template.

## License

This example shows how to create an image gallery site using Next.js, [Cloudinary](https://cloudinary.com), and [Tailwind](https://tailwindcss.com).

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example) or view the demo [here](https://image-gallery-eight-lac.vercel.app/)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-cloudinary&project-name=nextjs-image-gallery&repository-name=with-cloudinary&env=NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME,CLOUDINARY_API_KEY,CLOUDINARY_API_SECRET,CLOUDINARY_FOLDER&envDescription=API%20Keys%20from%20Cloudinary%20needed%20to%20run%20this%20application.)

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example::

```bash
 npx create-next-app --example with-cloudinary nextjs-image-gallery
```

```bash
yarn create next-app --example with-cloudinary nextjs-image-gallery
```

```bash
pnpm create next-app --example with-cloudinary nextjs-image-gallery
```

## References

- Cloudinary API: https://cloudinary.com/documentation/transformation_reference
