# TomoChain ApiDocs

## Swagger to Slate

```bash
node widdershins --search true --language_tabs 'shell:cURL' 'node:request' 'go:GO' 'ruby:Ruby' 'python:Python' 'java:Java' --httpsnippet true --resolve true --summary swagger/swagger.json -o slate.md
```

Change the httpsnippet for javascript key to `node:request` . [(Read more)](https://github.com/Kong/httpsnippet/tree/master/src/targets)

Replace `request` to `Node.js` in `slate.md`

## Build

- Copy slate.md content to `apidocs/source/index.html.md` then

`node shins.js`

`node buildstyle.js`
