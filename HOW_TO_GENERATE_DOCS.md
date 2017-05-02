## Building the docs

Plugin SDK docs are available at [https://nylas.github.io/nylas-mail/](https://nylas.github.io/nylas-mail/). Here's how you build them:

Until my patch gets merged, docs need to be built manually using mg's fork.

    git clone git@github.com:grinich/gitbook.git

    cd nylas-mail

    ./node_modules/.bin/gitbook alias ../gitbook latest

Then to actually build the docs:

    script/grunt docs

    ./node_modules/.bin/gitbook --gitbook=latest build . ./_docs_output --log=debug --debug

    rm -r docs_src/classes

If you want to preview the docs:

    pushd ./_docs_output; python -m SimpleHTTPServer; popd

Just want to publish everything? There's a helper script that does it for you:

    script/publish-docs
