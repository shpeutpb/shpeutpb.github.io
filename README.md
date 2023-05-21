## Installation

* Install Go and Git(64-bit)*

**1. Install Hugo**

To use this theme you will first need to have Hugo installed. Please follow the official [installation guide](https://gohugo.io/getting-started/installing/)

> ⚠️ **Note:** Check your Hugo version - **Hugo Extended** is required!

This theme uses [Hugo Pipes](https://gohugo.io/hugo-pipes/scss-sass/) to compile SCSS and minify assets which means if you are not using the Hugo extended version this theme will not work. To check your version of Hugo, run `hugo version`. Make sure you see **/extended** after the version number, for example _Hugo Static Site Generator v0.51/extended darwin/amd64 BuildDate: unknown_ You do not need to use version v0.51 specifically, it just needs to have the _/extended_ part.

**2. Create a new Hugo site**

This will create a fresh Hugo site in the folder `mynewsite`.

```
hugo new site mynewsite
```

**3. Install the theme**

Download or git clone this theme into the sites themes folder `mynewsite/themes`. You should end up with the following folder structure `mynewsite/themes/devfest-theme-hugo`

```
cd mynewsite
git clone https://github.com/shpeatutpb/devfest-theme-hugo.git themes/devfest-theme-hugo
```

**4. Copy the example content**

Copy the entire contents of the `mynewsite/themes/devfest-theme-hugo/exampleSite/` folder to root folder of your Hugo site, ie `mynewsite/`. To copy the files using terminal, make sure you are still in the projects root, ie the `mynewsite` folder.

```
cp -a themes/hugo-winston-theme/exampleSite/. .
```

**6. Run Hugo**

After installing the theme for the first time, generate the Hugo site.

You run this command from the root folder of your Hugo site ie `mynewsite`

```
hugo
```

For local development run Hugo's built-in local server.

```
hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.
