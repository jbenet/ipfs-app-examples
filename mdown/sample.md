# IPFS Markdown Reader

This simple app renders markdown ipfs files for easy viewing.
Many thanks to <a href="http://strapdownjs.com/">Strapdown.js</a>.

Check out examples:
- [IPFS Readme](mdown#/ipfs/QmfQ75DjAxYzxMP2hdm6o4wFwZS5t7uorEZ2pX9AKXEg2u)

Try it out!

## Write your own


Write your own markdown file:

```sh
> cat hello.md
# hello!

hello world.

![](/ipfs/QmRgpPeEDMTyyUqxdPj54AhnAxCPXRgwfbqZMBqsfiZWew/dominic.png)

Yep, images too!
```

Publish it:
```
> ipfs add hello.md
added QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7 hello.md
```

Craft the link:
```sh
# format
http://<http gateway>/<ipfs-path-to-markdown-viewer>/mdown#<ipfs-path-to-file>

# for example
http://localhost:8080/ipfs/QmWFyFpzG8M7Ck6YyHQgUiZLXT37JwQSUWvFhyoZ6m3jn5/mdown#/ipfs/QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7
```

- View it locally: [http://localhost:8080/ipfs/QmWFyFpzG8M7Ck6YyHQgUiZLXT37JwQSUWvFhyoZ6m3jn5/mdown#/ipfs/QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7](http://localhost:8080/ipfs/QmWFyFpzG8M7Ck6YyHQgUiZLXT37JwQSUWvFhyoZ6m3jn5/mdown#/ipfs/QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7)
- View it on the gateway: [http://gateway.ipfs.io/ipfs/QmWFyFpzG8M7Ck6YyHQgUiZLXT37JwQSUWvFhyoZ6m3jn5/mdown#/ipfs/QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7](http://gateway.ipfs.io/ipfs/QmWFyFpzG8M7Ck6YyHQgUiZLXT37JwQSUWvFhyoZ6m3jn5/mdown#/ipfs/QmQ59y7R9eBdmi75s5KobQNPmtMFigywQpjXTY5aHqyzL7)
