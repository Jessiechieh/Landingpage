# Chippewa
Say hello to Chippewa, an eclectic, patterned site template.

[Papaya](https://www.papayatemplates.com)
[@jrdnbwmn](https://www.twitter.com/jrdnbwmn)

Demo images from [Unsplash](https://unsplash.com/).
Icons from [Entypo](http://entypo.com/).

## Instructions
For local development, run `npm install` on the main directory and then `gulp` to get BrowserSync going along with all the Gulp tasks (see [Pear](https://github.com/jrdnbwmn/Pear)).

Development files are in `src`. Everything is compiled into `dist`—that’s where all your final files reside.

## GitHub Pages
This repo includes a GitHub Actions workflow that deploys the `dist` folder to GitHub Pages on every push to `main`.

To publish:
1. Push to the `main` branch.
2. In the GitHub repo settings, enable Pages and select **GitHub Actions** as the source.
3. The site will be available at the Pages URL shown in the workflow run.
