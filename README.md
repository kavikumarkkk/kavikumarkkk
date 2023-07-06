

![svg](https://raw.githubusercontent.com/yoshi389111/github-profile-3d-contrib/main/docs/demo/profile-night-view.svg)

example: night green version

![svg](https://raw.githubusercontent.com/yoshi389111/github-profile-3d-contrib/main/docs/demo/profile-night-green.svg)

example: night rainbow version

![svg](https://raw.githubusercontent.com/yoshi389111/github-profile-3d-contrib/main/docs/demo/profile-night-rainbow.svg)

example: git block version

![svg](https://raw.githubusercontent.com/yoshi389111/github-profile-3d-contrib/main/docs/demo/profile-gitblock.svg)

### step 4. Add image to README.md

Add the path of the generated image to the readme file.

e.g.

```md
![](./profile-3d-contrib/profile-green-animate.svg)
```

## How to use (local)

Set the `GITHUB_TOKEN` environment variable to the value of "personal access token".

```shell-session
export GITHUB_TOKEN=XXXXXXXXXXXXXXXXXXXXX
```

Run it with your GitHub user specified.

```shell-session
node_modules/.bin/ts-node src/index.ts USER_NAME
```

or

```shell-session
npm run build
node . USER_NAME
```

## Licence

MIT License

(C) 2021 SATO, Yoshiyuki