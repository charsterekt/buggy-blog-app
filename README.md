# Buggy: A full stack Blog app with a dedicated CMS.

In retrospect, the name Buggy might cause some confusion when someone comes to my GitHub. Although I don't currently blog, I have considered it in the past, and writing and maintaining a dev blog could be interesting. And in that case, I'd be sure to use a blog I made myself, and I would have no other name than Buggy :)

A bit more about the blog itself, the whole project runs on Next.js. It was my first experience using this framework and I was very pleased with how much of the process is simplified in comparison to bootstrapping a project using create-react-app. I think my favourite feature has to be file/folder based routing instead of the mess one has to deal with in a pure React app. The baked in functionality to make your own APIs within the project is also absolutely stellar. The frontend itself is still made using React though, and I decided to try out Tailwind CSS to see what all the hype is about. Safe to say i probably won't be going back to regular CSS, Tailwind is absolutely amazing. I also tried out GraphQL for storing and retreiving data, which was a good learning experience. The CMS is a platform called GraphCMS which is very streamlined and easy to use and complements the app very well. Anyone with access to the CMS can create and publish articles to the blog, and there are plenty of custom fields to differentiate the authors. Comments submitted to blog posts also have to be approved through the CMS so it is safe from spam and the content is filtered. The blog itself has all the features expected of a modern blog. The project was inspired by JSMYT as a means to learn new things and can definitely be improved upon in the future, especially with some aspects of the responsive design.

The blog has been deployed through Vercel, the natural choice when using Next.js. It is also my first time trying out Vercel over Netlify and Heroku for hobby deployment. The app can be found <a href="https://buggy-topaz.vercel.app/">here.</a>

------

# Next.js + Tailwind CSS Example

This example shows how to use [Tailwind CSS](https://tailwindcss.com/) [(v3.0)](https://tailwindcss.com/blog/tailwindcss-v3) with Next.js. It follows the steps outlined in the official [Tailwind docs](https://tailwindcss.com/docs/guides/nextjs).

## Preview

Preview the example live on [StackBlitz](http://stackblitz.com/):

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-tailwindcss)

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss&project-name=with-tailwindcss&repository-name=with-tailwindcss)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).
