project_path: /web/_project.yaml
book_path: /web/tools/_book.yaml
description: A set of examples for the workbox modules.

{# wf_updated_on: 2017-10-14 #}
{# wf_published_on: 2017-10-14 #}

This page contains examples for some of the Workbox modules.

Workbox is a set of small modules that can be used on their own, but we've
also combined the most common pieces into one module, `workbox-sw`. This module
supports precaching, routing of fetch events, runtime caching and more.

## Example of workbox-sw

The `workbox-sw` example demonstrates a complete service worker
implementation, demonstrating the common parts of the API. It's an in-depth
exploration of everything you'd need to build a production-ready service worker.

<a href="https://workboxjs.org/examples/workbox-sw/" target="_blank">View Example</a>

## Lower Level Modules

As an alternative to using the full `workbox-sw` library, you can use these
smaller, standalone modules in your service worker.

### workbox-broadcast-cache-update

Uses the [broadcast channel API](https://developer.mozilla.org/en-US/docs/web/api/broadcast_channel_api) to let you know when two responses are different.

<a href="https://workboxjs.org/examples/workbox-broadcast-cache-update/index.html" target="_blank">View Example</a>

### workbox-cache-expiration

Takes care of expiring cached entries based on the maximum number or age of entries.

<a href="https://workboxjs.org/examples/workbox-cache-expiration/index.html" target="_blank">View Example</a>

### workbox-routing

Makes it easy to handle network requests using the response strategy of your choice.

<a href="https://workboxjs.org/examples/workbox-routing/index.html" target="_blank">View Example</a>

### workbox-runtime-caching

Implements common cache strategies, and provides hooks to extend the default behaviors.

<a href="https://workboxjs.org/examples/workbox-runtime-caching/index.html" target="_blank">View Example</a>

## Projects Using Workbox

Below are a list of example sites that are using the Workbox modules.

### iFixit PWA

A React-based web app using workbox-build in a gulp-based build process.

[View Demo](https://ifixit-pwa.appspot.com/) | [View Source](https://github.com/GoogleChrome/application-shell/tree/ifixit-pwa/ifixit-pwa)

### React HN

A React-based web app using workbox-cli in an npm scripts-based build process.

[View Demo](https://react-hn.appspot.com/) | [View Source](https://github.com/insin/react-hn)

### Next.js HN

A Next.js-based web app using custom service worker generation in an npm scripts-based build process.

[View Demo](https://next-hnpwa.now.sh/) | [View Source](https://github.com/codebusking/next-hnpwa-guide-kit)

### ShadowReader

A "vanilla" JS web app that uses workbox-build in a gulp-based build process.

[View Demo](https://amp.cards/) | [View Source](https://github.com/ampproject/amp-publisher-sample/tree/master/amp-pwa-reader)
