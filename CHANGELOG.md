# 0.4.0 - 2017/11/15
  * fix(https): instrument https.request in Node.js v9
  * refactor(http): log HTTP results in groups of 100 (#68)
  * fix(api): add language to APM Server requests (#64)
  * refactor(trans): set default transaction.result to success (#67)
  * refactor(config): rename timeout config options (#59)

# 0.3.1 - 2017/10/3
  * fix(parsers): don't log context.request.url.search as null (#48)
  * fix(parsers): separate hostname and port when parsing Host header (#47)

# 0.3.0 - 2017/9/20
  * fix(instrumentation): don't sample transactions (#40)
  * feat(graphql): include GraphQL operation name in trace and transaction names (#27)
  * feat(tls): add validateServerCert config option (#32)
  * feat(parser): support http requests with full URI's (#26)
  * refactor(\*): remove appGitRef config option
  * fix(instrumentation): fix setting of custom flushInterval
  * feat(elasticsearch): add simple Elasticsearch instrumentation
  * fix(\*): don't start agent if appName is invalid

# 0.2.0 - 2017/8/28
  * refactor(\*): support new default port 8200 in APM Server
  * refactor(\*): support new context.response status code format

# 0.1.1 - 2017/8/17
  * fix(instrumentation): don't fail when sending transactions to APM Server

# 0.1.0 - 2017/8/17
  * Initial release
