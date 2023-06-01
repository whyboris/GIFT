# GIFT - Green Impact Fund for Transformation

Official repository for [greenimpactfund.de](https://www.greenimpactfund.de/)

## Developing

Built with _Hugo_

## PDF

To generate PDFs for the website:

0. install [`website2pdf`](https://github.com/jgazeau/website2pdf) globally `npm install -g website2pdf`
1. enable `@import "pdf";` in `lol.scss`
2. run `hugo serve`
3. open a new terminal window and run this command:

```sh
website2pdf --marginTop 50px --marginBottom 50px --marginLeft 40px --marginRight 40px --safe-title --output-dir ./temp
```

4. Manually rename the files and put them in `static/pdf`

## Thank you

- [Hugo](https://gohugo.io/) for being an amazing static website generator
