# Generating PDFs for the website

0. install [`website2pdf`](https://github.com/jgazeau/website2pdf) globally `npm install -g website2pdf`
1. enable `@import "pdf";` in `lol.scss`
2. run `hugo serve`
3. open a new terminal window and run this command:

```sh
website2pdf --marginTop 50px --marginBottom 50px --marginLeft 40px --marginRight 40px --display-header-footer --safe-title --template-dir="pdf" --output-dir ./temp
```

4. Manually rename the files and put them in `static/pdf`
