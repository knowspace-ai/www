# Knowspace website starter

## Getting Started

This website is based on Hugoplate by https://zeon.studio

### Prerequisites

To start using this template, you need to have some prerequisites installed on your machine.

- [Hugo Extended v0.124+](https://gohugo.io/installation/)
- [Node v20+](https://nodejs.org/en/download/)
- [Go v1.22+](https://go.dev/doc/install)

### Dependencies

Install all the dependencies using the following command.

```bash
npm install
```

### Development

Start the development server using the following command.

```bash
npm run dev
```

## Customization

This template has been designed with a lot of customization options in mind. You can customize almost anything you want, including:

### Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

###  Social Links

You can change the social links from the `data/social.json` file. Add your social links here, and they will automatically be displayed on the site.


## Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere.

### Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

