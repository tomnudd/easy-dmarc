# nextjs-template

This is a template repository for when I want to produce a something using Next.js

## Tailwind CSS

This does not need any additional configuration, but this site uses [Tailwind CSS](https://tailwindcss.com/), this makes styling elements simpler.

Additional styles can be configured in `/styles/index.css` and Tailwind Plugins can be installed in `tailwind.config.js`

## Code formatting

Again this doesn't need any additional configuration, but can be configured if you wish, for code formatting and linting I have

-   `.eslintrc.js`
-   `.prettierrc.json`

These configure ESLint and Prettier respectively, ensure that whatever configuration you choose doesn't cause conflicts, such as using tabs in ESLint and spaces in prettier.

## Vercel Hosting
This site will use hosting from Vercel. This can be configured in `vercel.json` a notable key to change is `alias`, this will allow for setting a custom domain
