# Authorization Capability Query format spec

This repository contains the specification for the Authorization Capability
Query format. You can access the latest version of this 
specification here: 

**https://digitalbazaar.github.io/zcap-query-spec/**

## See Also

* [Authorization Capabilities for Linked Data](https://w3c-ccg.github.io/zcap-ld/)

## Editing and building the specification
The specification is built using [Bikeshed](https://tabatkins.github.io/bikeshed/).

That means: **do not edit `index.html` directly**. Only edit `index.bs`, and
generate the HTML using Bikeshed.

### Generating ReSpec HTML using `curl`

These instructions assume use of the `curl` command, but you can use any
equivalent "talk HTTP at a server" command you might have access to.

```
curl https://api.csswg.org/bikeshed/ -F file=@index.bs -F force=1 > index.html
```

