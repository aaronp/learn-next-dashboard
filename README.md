## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

# Learn More


## Vercel

    * [postgres](https://vercel.com/docs/storage/vercel-postgres/sdk)

## Data Visualisation
 * (Visx)[https://airbnb.io/visx/]
 * (Tremor)[https://www.tremor.so/]
 * (chartjs)[https://www.chartjs.org/]

## Data / Streaming
 * [streaming](https://nextjs.org/learn/dashboard-app/streaming)

## Accessibility
 * [learn more](https://web.dev/learn/accessibility/)
 * [here](https://nextjs.org/learn/dashboard-app/improving-accessibility)
 

## Authentication
 
  * see [here](https://nextjs.org/learn/dashboard-app/adding-authentication) for next-auth
  * [addint auth providers](https://nextjs.org/learn/dashboard-app/adding-authentication#adding-the-credentials-provider)
  * [OAuth provideres](https://authjs.dev/getting-started/authentication/oauth)

## Server Components

 "Security is a top priority for web applications, as they can be vulnerable to various threats. This is where Server Actions come in. They offer an effective security solution, protecting against different types of attacks, securing your data, and ensuring authorized access. Server Actions achieve this through techniques like POST requests, encrypted closures, strict input checks, error message hashing, and host restrictions, all working together to significantly enhance your app's safety."
 
 * [here](https://nextjs.org/learn/dashboard-app/mutating-data)
 * [form data](https://developer.mozilla.org/en-US/docs/Web/API/FormData) [methods](https://developer.mozilla.org/en-US/docs/Web/API/FormData/append)
 * [zod](https://zod.dev/) for schema validation
 * further [security reading](https://nextjs.org/blog/security-nextjs-server-components-actions)
 * [caching](https://nextjs.org/docs/app/building-your-application/caching)

# Routing

 * [route groups](https://nextjs.org/docs/app/building-your-application/routing/route-groups)
 * [page components' params and searchParams](https://nextjs.org/docs/app/api-reference/file-conventions/page)
 

## Metrics
 * [Cumulative Layout Shift](https://web.dev/articles/cls)

## Styling
 * [Tailwind](https://nextjs.org/learn/dashboard-app/css-styling) and [utility classes](https://tailwindcss.com/docs/utility-first)

    * [clsx](https://www.npmjs.com/package/clsx) and [here])(https://github.com/lukeed/clsx)
    * [styled-jsx](https://github.com/vercel/styled-jsx)
    * [styled components](https://github.com/vercel/next.js/tree/canary/examples/with-styled-components)
    * [emotion](https://github.com/vercel/next.js/tree/canary/examples/with-emotion)
 
### Images

 * [about next/image](https://nextjs.org/learn/dashboard-app/optimizing-fonts-images)

" It's good practice to set the width and height of your images to avoid layout shift, these should be an aspect ratio identical to the source image."

 * [avif](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#avif_image)
 * [webp](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#webp)

### Fonts
 * [Google Font](https://fonts.google.com/) [Subsets](https://fonts.google.com/knowledge/glossary/subsetting)

# Environment

I needed to install the latest node and n (node manager):

```sh
npm install -g n
sudo n latest
nvm use node
```
