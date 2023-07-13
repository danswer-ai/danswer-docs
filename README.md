<h2 align="center">
<a href="https://www.danswer.ai/"> <img width="50%" src="https://github.com/danswer-owners/danswer/blob/1fabd9372d66cd54238847197c33f091a724803b/DanswerWithName.png?raw=true)" /></a>
</h2>

# Danswer Docs
This repo generates the setup guide for Danswer found at [https://docs.danswer.dev/](https://docs.danswer.dev/).

It uses Mintlify which is a no-code documentation generation tool.
Instructions on setting up local preview are included below.

More info on Mintlify found [here](https://mintlify.com/).

### Set up Mintlify
Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally.

To install, use the following command (requires node >= v19.0.0)
```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)
```
mintlify dev
```

### Publishing Changes
Changes are automatically deployed to production after merging to main.

### Troubleshooting
- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
- Mintlify Docs - https://mintlify.com/docs/introduction
