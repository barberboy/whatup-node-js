class: middle, center
highlightLanguage: javascript
highlightLines: true
highlightSpans: true

Whatup Node v4!
===============

---

## What is Node.js

- [Node.js](http://nodejs.org)
- Uses Chrome’s “V8” JavaScript engine
- Non-blocking event loop
- File and network IO
- [CommonJS Modules 1.1](http://wiki.commonjs.org/wiki/Modules/1.1)
- [npm package repository](npmjs.com)

---

## What’s new in Node.js v4

- [Announcement](https://nodejs.org/en/blog/release/v4.0.0/)
- [ES6 features](https://nodejs.org/en/docs/es6/)
- [Performance improvements (~25%)](http://apmblog.dynatrace.com/2015/09/05/all-you-need-to-know-about-node-js-4-0/)
- [Reduced memory consumption](https://github.com/nodejs/node/issues/2522#issuecomment-138501907)
- [ARM support in build and test infrastructure](https://github.com/nodejs/build)

---

## Why from 0.12.7 to 4.0.0?

Brief History:

- [io.js](http://blog.izs.me/post/104685388058/iojs) (fork)
- [Node Forward Technical Committee](http://nodeforward.org/)
- [Node.js Advisory Board](https://www.joyent.com/blog/node-js-advisory-board) by Joyent (temporary stop-gap)

---

## Node.js Foundation

[Node.js Foundation](https://nodejs.org/en/foundation/)

- [Completed the merge of io.js (v3.3) & node.js (v0.12.7) projects](https://github.com/nodejs/node/issues/978)
- [Hosted by Linux Foundation](http://www.linuxfoundation.org/news-media/announcements/2015/06/nodejs-foundation-advances-community-collaboration-announces-new)
- [Open governance model](https://github.com/nodejs/node/blob/master/GOVERNANCE.md#technical-committee)
- Guided by [Technical Steering Committee (TSC)](https://github.com/nodejs/node/blob/master/GOVERNANCE.md#technical-committee)
- [Long-term support process](https://github.com/nodejs/LTS/#nodejs-long-term-support-working-group) following [SemVer](http://semver.org/)
- [Enterprise members](https://nodejs.org/en/foundation/members/)

---

## Use Node.js v4

Migrating modules

- [Breaking changes](https://github.com/nodejs/LTS/wiki/Breaking-changes-between-v0.12-and-next-LTS-release)
  - [Between io.js versions](https://github.com/nodejs/node/wiki/Breaking-Changes)
  - [V8 API changes](https://docs.google.com/document/d/1g8JFi8T_oAE_7uAri7Njtig7fKaPDfotU6huOa1alds/edit?pli=1)
- [NAN (Native Abstractions for Node.js)](https://github.com/nodejs/nan)

Installing and running

- [nvm](https://github.com/creationix/nvm):  `nvm install stable`
- [node-bin](https://www.npmjs.com/package/node-bin): `npm install --save node-bin@latest`

---

## Stay in the loop

Official channels

- [Issues and discussions on GitHub](https://github.com/nodejs/node/issues)
- [#node.js IRC](http://webchat.freenode.net/?channels=node.js) [(archive)](http://logs.libuv.org/node.js/latest)
- [Official Node.js Twitter account](https://twitter.com/nodejs)
- [Technical Steering Committee members](https://nodejs.org/en/about/organization/)

Unofficial channels

- [Node Weekly](http://nodeweekly.com/) email newsletter
- [Planet Node](http://www.planetnodejs.com/) aggregator
- Podcasts
  - [NodeUp](http://nodeup.com/) podcast
  - [JavaScript Jabber](https://devchat.tv/js-jabber) podcast
- Conferences
  - [Nodevember](http://nodevember.org), November 14–15, Nashville TN
  - [Node.js Interactive](http://events.linuxfoundation.org/events/node-interactive), December 8–9, Portland, OR

---

## Additional reading

- [io.js by Isaac Z. Schlueter](http://blog.izs.me/post/104685388058/iojs)
- [Why io.js](http://www.infoworld.com/article/2855057/application-development/why-iojs-decided-to-fork-nodejs.html)
- [Node.js Foundation Announcement at Linux Foundation](http://www.linuxfoundation.org/news-media/announcements/2015/06/nodejs-foundation-advances-community-collaboration-announces-new)
- [Node.js and io.js Merge Under the Node Foundation](http://www.infoq.com/news/2015/05/nodejs-iojs)
- [V8 4.5 Release](http://v8project.blogspot.com/2015/07/v8-45-release.html)
- [Node.js 4.0 ES6 Compatibility](https://kangax.github.io/compat-table/es6/#node4)
- [7 Reasons to Upgrade to Node v4 Now](http://www.cli-nerd.com/2015/09/09/7-reasons-to-upgrade-to-node-v4-now.html)
- [Node.js v4.0.0—Node at its best](https://medium.com/@nodesource/node-js-v4-0-0-node-at-its-best-54a93fd2e0c6)
- [Today is one of those #Node days](https://developer.ibm.com/opentech/2015/06/16/today-one-node-days-gonna-awesome)
- [Nodebug.me](https://nodebug.me/)
