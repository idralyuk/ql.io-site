This is the app used to run the site [http://ql.io](http://ql.io). You can run this locally.

    git clone git@github.com:ql-io/ql.io-site.git
    cd ql.io-site
    make install
    bin/start.sh

If you want this app to use a clone of `git@github.com:ql-io/ql.io.git` do the following before the
 above.

    git clone git@github.com:ql-io/ql.io.git
    cd ql.io
    make install
    cd ..
