<h2 align="center">
<a href="https://www.onyx.app/">

  
  ![logotype](https://github.com/user-attachments/assets/ebfa90a2-2516-4d0f-8a60-9a188a051783)

</a>

</h2>

# Onyx Docs

This repo generates the docs and setup guide for [Onyx](https://github.com/onyx-dot-app/onyx) found at [https://docs.onyx.app/](https://docs.onyx.app/).

It uses Mintlify which is a no-code documentation generation tool.
Instructions on setting up local preview are included below.

More info on Mintlify found [here](https://mintlify.com/).

To make changes, check out `mint.json`, it should be fairly straightforward hopefully!

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
