xmpp-client fork build instructions
=================

    git clone git@github.com:twstrike/xmpp-client.git
    cd xmpp-client
    direnv allow

    ln -s /YourRepoPathOf/otr3 $GOPATH/src/github.com/twstrike/otr3

run test:

build otr3 if it's changed:

    go install $GOPATH/src/github.com/twstrike/otr3

run all test in xmpp-client:

    go test ./...
