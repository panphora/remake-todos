# Get started

1. `npm install`
2. `npm run dev`
3. [enable livereload browser extension](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en)

**Note:** The only things you should have to edit to get started in Remake.js are the templates and JSON files in the `./templates` folder. The pages are defined in `./templates/pages`. They're automatically rendered based on the route that's defined in their `./templates/pages/{pageName}/config.json` file. A good practice is to split your sub-templates off into partials and include them in the `./templates/partials` directory in their own folder. You can then reference them from your page templates. Also, these partial templates will be automatically rendered for you when you use Remake's `data-i-new` attribute, rendering them with the data specified in their `./templates/partials/{partialName}/data.json`.

# Warning

- This app doesn't implement real user accounts (they're just simulated). You need to implement user accounts that have their own data yourself or wait for a version of Remake that has real user accounts built in. However, if you just want to play around with Remake.js, this is the perfect project to start with.
