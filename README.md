

- Install dependencies: `npm install` or `yarn`

- Start the server: `npm run dev` or `yarn dev`

- Views are on: `localhost:3000`

## Setup authentication (optional)

1. Sign in on **Zalter Dashboard** (https://dashboard.zalter.com) and create your **Zalter project**.

2. Open your project settings and activate **Email Magic Link** authentication.
This authentication method requires `redirect URIs` setup, so while in development you need to add `http://localhost:3000/sign-in/confirm`.
For production replace `localhost:3000` with your own domain.

3. Copy `.env.example` file and rename it to `.env`

4. Open `.env` file and enable the Zalter authentication, then set your own Zalter project ID.

```bash
NEXT_PUBLIC_ENABLE_ZALTER_AUTH="true"
NEXT_PUBLIC_ZALTER_PROJECT_ID="<your-project-id>"
```

For more information about Zalter Authentication access https://developer.zalter.com.

## File Structure

Within the download you'll find the following directories and files:

```
material-kit-react

┌── .env.example
├── .eslintrc.json
├── .gitignore
├── CHANGELOG.md
├── LICENSE.md
├── next.config.js
├── package.json
├── README.md
├── public
└── src
	├── __mocks__
	├── components
	├── icons
	├── lib
	├── theme
	├── utils
	└── pages
		├── 404.js
		├── _app.js
		├── _document.js
		├── account.js
		├── customers.js
		├── index.js
		├── index.js
		├── products.js
		├── register.js
		└── settings.js
		└── sign-in
			├── confirm.js
			└── index.js
```

## Resources

- More freebies like this one: <https://devias.io>

## Reporting Issues:

- [Github Issues Page](https://github.com/devias-io/react-material-dashboard/issues?ref=devias-io)

## License

- Licensed under MIT (https://github.com/devias-io/react-material-dashboard/blob/master/LICENSE.md)

## Contact Us

- Email Us: support@deviasio.zendesk.com
