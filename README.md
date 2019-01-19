# TodGru.com

All things todgru!

Website written in markdown. Based on Jekyll template from [Solo](http://chibicode.github.io/solo).

# Local development

From project directory, type `jekyll serve`

# Upload

Upload to S3 using: <https://github.com/jamestalmage/s3-static-site-uploader>

Make sure to cd into the `_site` directory where the HTML files have been generated. Run `s3-upload` from there.

# PDF

A pdf converter plugin is available but needs work. Not quit working yet. More info [here](https://github.com/pdfkit/pdfkit/blob/master/README.md), [here](https://gist.github.com/kristianmandrup/5280569), and [here](https://jekyllrb.com/docs/plugins/#converters).

I ended up using this website as I only needed to convert a single file to a pdf. <http://www.markdowntopdf.com/>.
