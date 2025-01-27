v# NodeJS Study Guide

Table of Contents
=================

- [Learn NodeJS](#learn-nodejs)
- [Coding standards](#coding-standards)
- [NodeJS frameworks](#nodejs-frameworks)
- [Performance Optimizations](#performance-optimizations)
- [Nodejs Architecture](#nodejs-architecture)
- [NodeJS with Typescript](#nodejs-with-typescript)
- [Projects](#projects)
- [MERN](#mern)
- [Nodejs with Nginx](#nodejs-with-nginx)
- [Nodejs Logging](#nodejs-logging)
- [Nodejs Error Handling](#nodejs-error-handling)
- [Tips and tricks](#tips-and-tricks)
- [Micro services](#micro-services)
- [NodeJS pattern](#nodejs-pattern)
- [NodeJS cheatSheet](#nodejs-cheatsheet)
- [NodeJS Interview](#nodejs-interview)
- [NestJS](#nestjs)
- [NodeJS Unit testing](#nodejs-unit-testing)
- [NodeJS with Typescript](#nodejs-with-typescript)
- [NodeJS best practices](#nodejs-best-practices)
- [API practices](#api-practices)
- [Package Manager](#package-manager)
- [NodeJS tools](#nodejs-tools)
- [NodeJS security](#nodejs-security)
- [NodeJS Migration](#nodejs-migration)
- [NodeJS deployment](#nodejs-deployment)
- [NodeJS with GraphQL](#nodejs-with-graphql)
- [NodeJS with Redis](#nodejs-with-redis)
- [NodeJS Auth](#nodejs-auth)
- [NodeJS with MongoDB](#nodejs-with-mongodb)
- [NodeJS Guide](#nodejs-guide)
- [NodeJS Queue](#nodejs-queue)
- [NodeJS library](#nodejs-library)
- [NodeJS Steaming](#nodejs-steaming)
- [NodeJS Serverless](#nodejs-serverless)
- [NodeJS documentation](#nodejs-documentation)

## Learn NodeJS
- [https://javascript.plainenglish.io/core-concepts-of-node-js-in-just-6-min-c4702fcc55a7](https://javascript.plainenglish.io/core-concepts-of-node-js-in-just-6-min-c4702fcc55a7)<br>
- [https://dev.to/geraldmuvengei06/how-use-environment-variables-env-in-expressjs-3bpc](https://dev.to/geraldmuvengei06/how-use-environment-variables-env-in-expressjs-3bpc)<br>
- [https://enlear.academy/nodejs-backpressuring-in-streams-52638f505e1b](https://enlear.academy/nodejs-backpressuring-in-streams-52638f505e1b)<br>
- [https://blog.logrocket.com/creating-custom-repl-node-js/](https://blog.logrocket.com/creating-custom-repl-node-js/)<br>
- [https://enlear.academy/reactjs-what-is-a-component-state-props-lifecycle-b2ed60adca1f](https://enlear.academy/reactjs-what-is-a-component-state-props-lifecycle-b2ed60adca1f)<br>
- [https://www.freecodecamp.org/news/nodejs-eventloop-tutorial/](https://www.freecodecamp.org/news/nodejs-eventloop-tutorial/)<br>
- [https://www.javacodegeeks.com/session-management-in-node-js.html](https://www.javacodegeeks.com/session-management-in-node-js.html)<br>
- [https://dev.to/altamashali/nodejs-event-loop-in-action-d5o](https://dev.to/altamashali/nodejs-event-loop-in-action-d5o)<br>
- [https://dev.to/codesphere/getting-started-with-web-sockets-in-nodejs-49n0](https://dev.to/codesphere/getting-started-with-web-sockets-in-nodejs-49n0)<br>
- [https://blog.bitsrc.io/node-js-event-loop-and-multi-threading-e42e5fd16a77](https://blog.bitsrc.io/node-js-event-loop-and-multi-threading-e42e5fd16a77)<br>
- [https://dev.to/nickytonline/what-are-your-go-to-nodejs-resources-3mma](https://dev.to/nickytonline/what-are-your-go-to-nodejs-resources-3mma)<br>
- [https://helewud.com/how-to-build-an-authorization-system-with-jwt-using-nodejs](https://helewud.com/how-to-build-an-authorization-system-with-jwt-using-nodejs)
- [https://devdojo.com/dastasoft/intro-to-mongodb-and-mongoose-how-every-web-developer-can-become-fullstack-with-nodejs](https://devdojo.com/dastasoft/intro-to-mongodb-and-mongoose-how-every-web-developer-can-become-fullstack-with-nodejs)
- [https://towardsdev.com/node-js-event-loop-3ee5b841adda](https://towardsdev.com/node-js-event-loop-3ee5b841adda)<br>
- [https://mudit.hashnode.dev/backend-development-is-not-hard](https://mudit.hashnode.dev/backend-development-is-not-hard)<br>
- [https://blog.devgenius.io/node-js-modeling-relationalship-between-connected-data-mongodb-9dc208a950e6](https://blog.devgenius.io/node-js-modeling-relationalship-between-connected-data-mongodb-9dc208a950e6)<br>
- [https://www.freecodecamp.org/news/introduction-to-nodejs/](https://www.freecodecamp.org/news/introduction-to-nodejs/)<br>
- [https://medium.com/@gustavoinzunza/how-to-set-up-node-and-tailwind-with-docker-step-by-step-e40a4cff05b3](https://medium.com/@gustavoinzunza/how-to-set-up-node-and-tailwind-with-docker-step-by-step-e40a4cff05b3)<br>
- [https://towardsdev.com/await-without-async-in-nodejs-2af573c81aa2](https://towardsdev.com/await-without-async-in-nodejs-2af573c81aa2)<br>
- [https://towardsdev.com/package-json-package-lock-json-1ea34560f555](https://towardsdev.com/package-json-package-lock-json-1ea34560f555)<br>
- [https://www.freecodecamp.org/news/apis-for-beginners/](https://www.freecodecamp.org/news/apis-for-beginners/)<br>
- [https://www.freecodecamp.org/news/message-queues-in-distributed-systesms/](https://www.freecodecamp.org/news/message-queues-in-distributed-systesms/)<br>
- [https://mojoauth.com/blog/best-practices-for-jwt-tokens/](https://mojoauth.com/blog/best-practices-for-jwt-tokens/)<br>
- [https://latesthackingnews.com/2023/02/23/top-7-reasons-why-use-node-js-in-your-next-web-development-project/](https://latesthackingnews.com/2023/02/23/top-7-reasons-why-use-node-js-in-your-next-web-development-project/)<br>
- [https://snyk.io/blog/node-js-multithreading-worker-threads-pros-cons/](https://snyk.io/blog/node-js-multithreading-worker-threads-pros-cons/)<br>
- [https://www.builder.io/blog/nodejs-module-exports-vs-exports](https://www.builder.io/blog/nodejs-module-exports-vs-exports)<br>
- [https://javascript.plainenglish.io/nodejs-developer-roadmap-2023-4e2fccc0ff54](https://javascript.plainenglish.io/nodejs-developer-roadmap-2023-4e2fccc0ff54)<br>
- [https://betterprogramming.pub/execution-types-models-in-node-js-46f70d71abb](https://betterprogramming.pub/execution-types-models-in-node-js-46f70d71abb)<br>
- [https://blog.francescociulla.com/nodejs-development-setup](https://blog.francescociulla.com/nodejs-development-setup)<br>
- [https://devhoangkien.com/node-js-19-a-whimsical-adventure-through-async-magic-and-javascript-enchantment-b338ebcea5ad](https://devhoangkien.com/node-js-19-a-whimsical-adventure-through-async-magic-and-javascript-enchantment-b338ebcea5ad)<br>
- [https://www.builder.io/blog/visual-guide-to-nodejs-event-loop](https://www.builder.io/blog/visual-guide-to-nodejs-event-loop)<br>
- [https://www.freecodecamp.org/news/how-to-build-a-command-line-application-with-nodejs/](https://www.freecodecamp.org/news/how-to-build-a-command-line-application-with-nodejs/)<br>
- [https://www.thisdot.co/blog/state-of-nodejs-wrap-up](https://www.thisdot.co/blog/state-of-nodejs-wrap-up)<br>
- [https://www.youtube.com/watch?v=GDe8DFZcgoI&list=PLSJnlFr3D-mEn4JLpA4F7UCAX_e5Nmx3q](https://www.youtube.com/watch?v=GDe8DFZcgoI&list=PLSJnlFr3D-mEn4JLpA4F7UCAX_e5Nmx3q)<br>
- [https://javascript.plainenglish.io/nodejs-developer-roadmap-2023-4e2fccc0ff54](https://javascript.plainenglish.io/nodejs-developer-roadmap-2023-4e2fccc0ff54)<br>
- [https://medium.com/@tony.infisical/why-you-should-stop-using-env-files-in-node-js-f62fffecf5a3](https://medium.com/@tony.infisical/why-you-should-stop-using-env-files-in-node-js-f62fffecf5a3)<br>
- [https://www.freecodecamp.org/news/get-started-with-nodejs/](https://www.freecodecamp.org/news/get-started-with-nodejs/)<br>
- [https://medium.com/@kalkidant/7-node-js-best-practices-2023-37063634eef](https://medium.com/@kalkidant/7-node-js-best-practices-2023-37063634eef)<br>
- [https://www.30secondsofcode.org/articles/s/cors-explained/](https://www.30secondsofcode.org/articles/s/cors-explained/)<br>
- [https://medium.com/@tony.infisical/guide-to-nodes-crypto-module-for-encryption-decryption-65c077176980](https://medium.com/@tony.infisical/guide-to-nodes-crypto-module-for-encryption-decryption-65c077176980)<br>
- [https://compile7.org/decompile/how-event-loop-works-in-nodejs/](https://compile7.org/decompile/how-event-loop-works-in-nodejs/)<br>
- [https://reflectoring.io/organize-code-with-nodejs-tutorial/]([)](https://reflectoring.io/organize-code-with-nodejs-tutorial/)<br>
- [https://www.freecodecamp.org/news/what-exactly-is-node-guide-for-beginners/](https://www.freecodecamp.org/news/what-exactly-is-node-guide-for-beginners/)<br>
- [https://amplication.com/blog/using-parallel-processing-in-nodejs-and-limitations](https://amplication.com/blog/using-parallel-processing-in-nodejs-and-limitations)<br>
- [https://tsh.io/blog/why-use-nodejs/](https://tsh.io/blog/why-use-nodejs/)<br>
- [https://robiul.dev/what-is-nodejs-exactly-real-world-example](https://robiul.dev/what-is-nodejs-exactly-real-world-example)<br>
- [https://www.freecodecamp.org/news/what-is-node-js-explained/](https://www.freecodecamp.org/news/what-is-node-js-explained/)<br>
- [https://code.likeagirl.io/what-is-node-js-a-beginners-guide-32f50da3b072](https://code.likeagirl.io/what-is-node-js-a-beginners-guide-32f50da3b072)<br>
- [https://www.thisdot.co/blog/building-a-multi-response-streaming-api-with-node-js-express-and-react/](https://www.thisdot.co/blog/building-a-multi-response-streaming-api-with-node-js-express-and-react/)<br>
- [https://dzone.com/articles/a-comprehensive-exploration-of-nodejs-a-practical](https://dzone.com/articles/a-comprehensive-exploration-of-nodejs-a-practical)<br>
- [https://itnext.io/evolution-of-server-side-javascript-314a8d408da4](https://itnext.io/evolution-of-server-side-javascript-314a8d408da4)<br>
- [https://reflectoring.io/tutorial-nodejs-rate-limiter/?ref=dailydev](https://reflectoring.io/tutorial-nodejs-rate-limiter/?ref=dailydev)<br>
- [https://www.sitepoint.com/fetch-api-node-deno-bun/?utm_source=rss&ref=dailydev](https://www.sitepoint.com/fetch-api-node-deno-bun/?utm_source=rss&ref=dailydev)<br>
- [https://blog.appsignal.com/2023/11/08/how-to-use-timeouts-in-nodejs.html?ref=dailydev](https://blog.appsignal.com/2023/11/08/how-to-use-timeouts-in-nodejs.html?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/javascript-concepts-to-know-before-learning-node-js/](https://www.freecodecamp.org/news/javascript-concepts-to-know-before-learning-node-js/)<br>
- [https://www.freecodecamp.org/news/crud-api-with-node-js-express-mongodb/?ref=dailydev](https://www.freecodecamp.org/news/crud-api-with-node-js-express-mongodb/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/how-to-work-with-files-in-node-js/](https://www.freecodecamp.org/news/how-to-work-with-files-in-node-js/)<br>
- [https://coinsbench.com/understanding-nodes-a-beginners-guide-a89172a04bfe](https://coinsbench.com/understanding-nodes-a-beginners-guide-a89172a04bfe)<br>
- [https://medium.com/@manikmudholkar831995/the-v8-javascript-engine-d1434ca77c96](https://medium.com/@manikmudholkar831995/the-v8-javascript-engine-d1434ca77c96)<br>
- [https://www.devsecurely.com/blog/2024/06/cors-the-ultimate-guide?ref=dailydev](https://www.devsecurely.com/blog/2024/06/cors-the-ultimate-guide?ref=dailydev)<br>
- [https://blog.platformatic.dev/introducing-the-node-application-platform?ref=dailydev](https://blog.platformatic.dev/introducing-the-node-application-platform?ref=dailydev)<br>
- [https://pavel-romanov.com/understanding-nodejs-buffer?ref=dailydev](https://pavel-romanov.com/understanding-nodejs-buffer?ref=dailydev)<br>
- [https://medium.com/@modywmbadr/how-dynamic-array-works-in-node-js-3d4e15c9ce73](https://medium.com/@modywmbadr/how-dynamic-array-works-in-node-js-3d4e15c9ce73)<br>
- [https://blog.platformatic.dev/handling-environment-variables-in-nodejs?ref=dailydev](https://blog.platformatic.dev/handling-environment-variables-in-nodejs?ref=dailydev)<br>
- [https://jsdev.space/files-dirs-nodejs/?ref=dailydev](https://jsdev.space/files-dirs-nodejs/?ref=dailydev)<br>
- [https://blog.appsignal.com/2024/12/11/a-deep-dive-into-commonjs-and-es-modules-in-nodejs.html?ref=dailydev](https://blog.appsignal.com/2024/12/11/a-deep-dive-into-commonjs-and-es-modules-in-nodejs.html?ref=dailydev)<br>
- [https://www.youtube.com/playlist?list=PLjFTSVBcNC2q2rxyts8sN4leF2CFrhg1S](https://www.youtube.com/playlist?list=PLjFTSVBcNC2q2rxyts8sN4leF2CFrhg1S)<br>
- [https://leapcell.io/blog/inside-nodejs-event-loop-deep-dive?ref=dailydev](https://leapcell.io/blog/inside-nodejs-event-loop-deep-dive?ref=dailydev)<br>
- [https://marvinh.dev/blog/modern-way-to-write-javascript-servers/?ref=dailydev](https://marvinh.dev/blog/modern-way-to-write-javascript-servers/?ref=dailydev)<br>


## Coding standards
- [https://github.com/a8hok/NodeJS-interview.git](https://github.com/a8hok/NodeJS-interview.git)<br>
- [https://css-tricks.com/how-to-implement-logging-in-a-node-js-application-with-pino-logger/](https://css-tricks.com/how-to-implement-logging-in-a-node-js-application-with-pino-logger/)<br>
- [https://bestcodingpractices.dev/catalog/62a710375029ab9ca974ab6b](https://bestcodingpractices.dev/catalog/62a710375029ab9ca974ab6b)<br>
- [https://medium.com/bitsrc/nodejs-design-patterns-must-know-8ef0a73b3339](https://medium.com/bitsrc/nodejs-design-patterns-must-know-8ef0a73b3339)<br>


## NodeJS frameworks
- [https://devdojo.com/chapagainashik/stripe-checkout-with-nextjs](https://devdojo.com/chapagainashik/stripe-checkout-with-nextjs)<br>
- [https://snyk.io/blog/comparing-node-js-web-frameworks/](https://snyk.io/blog/comparing-node-js-web-frameworks/)<br>
- [https://dev.to/rahulladumor/10-trending-nodejs-libraries-and-frameworks-to-boost-your-web-development-3aa5](https://dev.to/rahulladumor/10-trending-nodejs-libraries-and-frameworks-to-boost-your-web-development-3aa5)<br>
- [https://blog.bitsrc.io/top-5-nodejs-frameworks-in-2024-32c7fe9d49c6](https://blog.bitsrc.io/top-5-nodejs-frameworks-in-2024-32c7fe9d49c6)<br>
- [https://dev.to/encore/nodejs-frameworks-roundup-2024-elysia-hono-nest-encore-which-should-you-pick-19oj?ref=dailydev](https://dev.to/encore/nodejs-frameworks-roundup-2024-elysia-hono-nest-encore-which-should-you-pick-19oj?ref=dailydev)<br>
- [https://blog.stackademic.com/top-10-backend-frameworks-ranked-the-good-the-bad-and-the-ugly-aa0d06186293](https://blog.stackademic.com/top-10-backend-frameworks-ranked-the-good-the-bad-and-the-ugly-aa0d06186293)<br>
- [https://leapcell.io/blog/mastering-express-js-deep-dive?ref=dailydev](https://leapcell.io/blog/mastering-express-js-deep-dive?ref=dailydev)<br>


## Performance Optimizations
- [https://blog.joshsoftware.com/2021/09/11/performance-optimizations-in-nodejs%F0%9F%92%81/](https://blog.joshsoftware.com/2021/09/11/performance-optimizations-in-nodejs%F0%9F%92%81/)<br>
- [https://blog.devgenius.io/5-tips-to-speed-up-your-node-js-performance-1166451308b4](https://blog.devgenius.io/5-tips-to-speed-up-your-node-js-performance-1166451308b4)<br>
- [https://www.digitalocean.com/community/tutorials/how-to-scale-node-js-applications-with-clustering](https://www.digitalocean.com/community/tutorials/how-to-scale-node-js-applications-with-clustering)<br>
- [https://devhoangkien.com/interview-questions-related-to-optimizing-application-performance-in-node-js-40ad0aea91d](https://devhoangkien.com/interview-questions-related-to-optimizing-application-performance-in-node-js-40ad0aea91d)<br>
- [https://medium.com/@codeeverywhere/5-tips-to-speed-up-your-node-js-performance-8977153490c1](https://medium.com/@codeeverywhere/5-tips-to-speed-up-your-node-js-performance-8977153490c1)<br>
- [https://medium.com/@ben.dev.io/best-practices-for-building-large-scale-node-js-applications-b45ab29b757a](https://medium.com/@ben.dev.io/best-practices-for-building-large-scale-node-js-applications-b45ab29b757a)<br>
- [https://amplication.com/blog/7-tips-to-build-scalable-nodejs-applications](https://amplication.com/blog/7-tips-to-build-scalable-nodejs-applications)<br>
- [https://medium.com/@kalkidant/7-node-js-best-practices-2023-37063634eef](https://medium.com/@kalkidant/7-node-js-best-practices-2023-37063634eef)<br>
- [https://dzone.com/articles/nodejs-architectural-gems-and-best-practices-for-d](https://dzone.com/articles/nodejs-architectural-gems-and-best-practices-for-d)<br>
- [https://tsh.io/blog/simple-guide-concurrency-node-js/](https://tsh.io/blog/simple-guide-concurrency-node-js/)<br>
- [https://medium.com/javarevisited/optimizing-node-js-performance-tips-and-tricks-4052a0d43f88](https://medium.com/javarevisited/optimizing-node-js-performance-tips-and-tricks-4052a0d43f88)<br>


## Nodejs Architecture
- [https://itnext.io/clean-architecture-making-node-js-api-shine-38134b8f9b5c](https://itnext.io/clean-architecture-making-node-js-api-shine-38134b8f9b5c)<br>
- [https://dev.to/altamashali/deep-dive-into-nodejs-architecture-5190](https://dev.to/altamashali/deep-dive-into-nodejs-architecture-5190)<br>
- [https://betterprogramming.pub/clean-node-js-architecture-with-nestjs-and-typescript-34b9398d790f](https://betterprogramming.pub/clean-node-js-architecture-with-nestjs-and-typescript-34b9398d790f)<br>
- [https://malikatique.medium.com/node-js-code-architecture-for-scalable-projects-bc0b5f2da74a](https://malikatique.medium.com/node-js-code-architecture-for-scalable-projects-bc0b5f2da74a)<br>
- [https://blog.lorensr.me/building-reliable-distributed-systems-in-node-aff92fa45ad8](https://blog.lorensr.me/building-reliable-distributed-systems-in-node-aff92fa45ad8)<br>
- [https://temporal.io/blog/building-reliable-distributed-systems-in-node](https://temporal.io/blog/building-reliable-distributed-systems-in-node)<br>
- [https://adventures.nodeland.dev/archive/security-releases-in-the-nodejs-ecosystem-fastify/](https://adventures.nodeland.dev/archive/security-releases-in-the-nodejs-ecosystem-fastify/)<br>
- [https://amplication.com/blog/nodejs-asynchronous-flow-control-and-event-loop](https://amplication.com/blog/nodejs-asynchronous-flow-control-and-event-loop)<br>
- [https://dev.to/sasithwarnakafonseka/nodejs-architectural-patterns-with-examples-1335](https://dev.to/sasithwarnakafonseka/nodejs-architectural-patterns-with-examples-1335)<br>
- [https://nextcodeblock.com/posts/api-architectural-styles/](https://nextcodeblock.com/posts/api-architectural-styles/)<br>
- [https://semaphoreci.com/blog/securing-nodejs](https://semaphoreci.com/blog/securing-nodejs)<br>
- [https://medium.com/@manikmudholkar831995/event-loop-in-nodejs-999f6db7eb04](https://medium.com/@manikmudholkar831995/event-loop-in-nodejs-999f6db7eb04)<br>
- [https://developers.redhat.com/blog/2021/03/08/introduction-to-the-node-js-reference-architecture-part-1-overview?ref=dailydev#](https://developers.redhat.com/blog/2021/03/08/introduction-to-the-node-js-reference-architecture-part-1-overview?ref=dailydev#)<br>
- [https://www.platformatichq.com/node-principles?ref=dailydev](https://www.platformatichq.com/node-principles?ref=dailydev)<br>


## NodeJS with Typescript
- [https://towardsdev.com/creating-a-gateway-service-with-node-js-typescript-and-fastify-54cb9c17b0e1](https://towardsdev.com/creating-a-gateway-service-with-node-js-typescript-and-fastify-54cb9c17b0e1)<br>
- [https://itnext.io/modern-node-part-1-architecting-and-scaffolding-a-typescript-express-api-22e87fee054c](https://itnext.io/modern-node-part-1-architecting-and-scaffolding-a-typescript-express-api-22e87fee054c)<br>
- [https://dev.to/macmacky/get-better-with-typescript-using-express-3ik6](https://dev.to/macmacky/get-better-with-typescript-using-express-3ik6)<br>
- [https://dev.to/nayanpatil1998/how-to-create-an-api-using-nodejs-express-and-typescript-89d](https://dev.to/nayanpatil1998/how-to-create-an-api-using-nodejs-express-and-typescript-89d)<br>
- [https://vicman.hashnode.dev/setting-up-node-application-with-typescript](https://vicman.hashnode.dev/setting-up-node-application-with-typescript)<br>
- [https://dev.to/about14sheep/streaming-data-from-aws-s3-using-nodejs-stream-api-and-typescript-3dj0](https://dev.to/about14sheep/streaming-data-from-aws-s3-using-nodejs-stream-api-and-typescript-3dj0)<br>
- [https://betterprogramming.pub/handling-class-libraries-in-node-js-with-and-without-typescript-39b73b2186b6](https://betterprogramming.pub/handling-class-libraries-in-node-js-with-and-without-typescript-39b73b2186b6)<br>
- [https://rohitpaulscodism.hashnode.dev/mastering-nodejs-streams-with-typescript-a-complete-guide?ref=dailydev](https://rohitpaulscodism.hashnode.dev/mastering-nodejs-streams-with-typescript-a-complete-guide?ref=dailydev)<br>
- [https://jsdev.space/howto/env-ts-zod?ref=dailydev](https://jsdev.space/howto/env-ts-zod?ref=dailydev)<br>


## Projects
- [https://dev.to/anderrv/web-scraping-with-javascript-and-node-js-2d](https://dev.to/anderrv/web-scraping-with-javascript-and-node-js-2d)<br>
- [https://dev.to/sm0ke/node-js-react-soft-dashboard-free-version-1k5g](https://dev.to/sm0ke/node-js-react-soft-dashboard-free-version-1k5g)<br>
- [https://towardsdatascience.com/building-a-real-time-web-app-in-nodejs-express-with-socket-io-library-d9b50aded6e6](https://towardsdatascience.com/building-a-real-time-web-app-in-nodejs-express-with-socket-io-library-d9b50aded6e6)<br>
- [https://dev.to/koladev/authentication-and-authorization-with-jwts-in-node-expressjs-5a9a](https://dev.to/koladev/authentication-and-authorization-with-jwts-in-node-expressjs-5a9a)<br>
- [https://devdojo.com/teri/how-to-build-a-web-scraper-with-nodejs](https://devdojo.com/teri/how-to-build-a-web-scraper-with-nodejs)<br>
- [https://javascript.plainenglish.io/google-api-authentication-using-oauth2-0-and-passport-js-in-nodejs-7b2d9b73c513](https://javascript.plainenglish.io/google-api-authentication-using-oauth2-0-and-passport-js-in-nodejs-7b2d9b73c513)<br>
- [https://www.bezkoder.com/node-express-sequelize-postgresql/](https://www.bezkoder.com/node-express-sequelize-postgresql/)<br>
- [https://kirablog.hashnode.dev/rest-api-using-nodejs](https://kirablog.hashnode.dev/rest-api-using-nodejs)<br>
- [https://reactjsexample.com/docker-tutorial-nodejs-express-mongodb-react-redis-nginx/](https://reactjsexample.com/docker-tutorial-nodejs-express-mongodb-react-redis-nginx/)<br>
- [https://blog.avneesh.tech/building-a-crud-api-with-nodejs-and-mongodb](https://blog.avneesh.tech/building-a-crud-api-with-nodejs-and-mongodb)<br>
- [https://dev.to/nerdjfpb/how-to-build-simple-crud-restful-api-with-nodejs-expressjs-and-mongodb-in-2022-4756](https://dev.to/nerdjfpb/how-to-build-simple-crud-restful-api-with-nodejs-expressjs-and-mongodb-in-2022-4756)<br>
- [https://reactjsexample.com/a-fullstack-web-application-built-using-mern-stack-mongodb-express-react-nodejs/](https://reactjsexample.com/a-fullstack-web-application-built-using-mern-stack-mongodb-express-react-nodejs/)<br>
- [https://devdojo.com/usmanwrites/build-a-whatsapp-api-using-node-express](https://devdojo.com/usmanwrites/build-a-whatsapp-api-using-node-express)<br>
- [https://redis.com/blog/how-to-build-a-music-sharing-app-using-nodejs-and-redis/](https://redis.com/blog/how-to-build-a-music-sharing-app-using-nodejs-and-redis/)<br>
- [https://towardsdev.com/creating-a-nodejs-restful-api-without-expressjs-part-1-123933e7141a](https://towardsdev.com/creating-a-nodejs-restful-api-without-expressjs-part-1-123933e7141a)<br>
- [https://www.freecodecamp.org/news/build-a-realtime-chat-app-with-react-express-socketio-and-harperdb/](https://www.freecodecamp.org/news/build-a-realtime-chat-app-with-react-express-socketio-and-harperdb/)<br>
- [https://www.telerik.com/blogs/modern-apis-fastify-node](https://www.telerik.com/blogs/modern-apis-fastify-node)<br>
- [https://dev.to/permify/build-a-team-permissions-system-in-nodejs-app-using-auth0-and-permify-part-1-52bo](https://dev.to/permify/build-a-team-permissions-system-in-nodejs-app-using-auth0-and-permify-part-1-52bo)<br>
- [https://hackernoon.com/building-a-simple-telegram-bot-with-nodejs-and-grammy?source=rss](https://hackernoon.com/building-a-simple-telegram-bot-with-nodejs-and-grammy?source=rss)<br>
- [https://www.freecodecamp.org/news/how-to-build-a-command-line-application-with-nodejs/](https://www.freecodecamp.org/news/how-to-build-a-command-line-application-with-nodejs/)<br>
- [https://dzone.com/articles/your-go-to-guide-to-develop-cryptocurrency-blockch](https://dzone.com/articles/your-go-to-guide-to-develop-cryptocurrency-blockch)<br>
- [https://dev.to/francescoxx/build-a-crud-rest-api-in-javascript-using-nodejs-express-postgres-docker-jkb](https://dev.to/francescoxx/build-a-crud-rest-api-in-javascript-using-nodejs-express-postgres-docker-jkb)<br>
- [https://blog.erickwendel.com.br/implementing-the-websocket-protocol-from-scratch-using-nodejs](https://blog.erickwendel.com.br/implementing-the-websocket-protocol-from-scratch-using-nodejs)<br>
- [https://deno.com/blog/build-api-express-typescript](https://deno.com/blog/build-api-express-typescript)<br>
- [https://towardsdev.com/custom-api-server-with-basic-crud-apollo-graphql-mongodb-8c107523a09a](https://towardsdev.com/custom-api-server-with-basic-crud-apollo-graphql-mongodb-8c107523a09a)<br>
- [https://blog.logrocket.com/best-node-js-web-scrapers-use-case/](https://blog.logrocket.com/best-node-js-web-scrapers-use-case/)<br>
- [https://dev.to/wesleymreng7/uploading-multiple-files-at-the-same-time-using-multithreading-in-nodejs-3ib4](https://dev.to/wesleymreng7/uploading-multiple-files-at-the-same-time-using-multithreading-in-nodejs-3ib4)<br>
- [https://reflectoring.io/tutorial-graphql-apollo-server-nodejs-mongodb/](https://reflectoring.io/tutorial-graphql-apollo-server-nodejs-mongodb/)<br>
- [https://blog.javascripttoday.com/blog/build-a-rest-api-in-javascript/](https://blog.javascripttoday.com/blog/build-a-rest-api-in-javascript/)<br>
- [https://blog.javascripttoday.com/blog/creating-a-url-shortener-with-node/](https://blog.javascripttoday.com/blog/creating-a-url-shortener-with-node/)<br>
- [https://rapidapi.com/blog/nodejs-express-rest-api-example/](https://rapidapi.com/blog/nodejs-express-rest-api-example/)<br>
- [https://blog.erickwendel.com.br/how-to-create-e2e-tests-in-nodejs-with-no-frameworks-step-by-step](https://blog.erickwendel.com.br/how-to-create-e2e-tests-in-nodejs-with-no-frameworks-step-by-step)<br>
- [https://antman-does-software.com/implementing-the-outbox-pattern-in-nodejs-and-postgres](https://antman-does-software.com/implementing-the-outbox-pattern-in-nodejs-and-postgres)<br>
- [https://dev.to/pavanbelagatti/build-a-real-time-chat-application-with-socketio-and-nodejs-with-automated-testing-38h8](https://dev.to/pavanbelagatti/build-a-real-time-chat-application-with-socketio-and-nodejs-with-automated-testing-38h8)<br>
- [https://www.thisdot.co/blog/implementing-a-task-scheduler-in-node-using-redis](https://www.thisdot.co/blog/implementing-a-task-scheduler-in-node-using-redis)<br>
- [https://www.freecodecamp.org/news/how-to-use-elastic-beanstalk-to-deploy-node-js-app/](https://www.freecodecamp.org/news/how-to-use-elastic-beanstalk-to-deploy-node-js-app/)<br>
- [https://www.freecodecamp.org/news/how-to-work-with-files-in-node-js/](https://www.freecodecamp.org/news/how-to-work-with-files-in-node-js/)<br>
- [https://levelup.gitconnected.com/api-development-with-nodejs-express-and-typescript-from-scratch-dto-interface-and-54ebab8c447e](https://levelup.gitconnected.com/api-development-with-nodejs-express-and-typescript-from-scratch-dto-interface-and-54ebab8c447e)<br>
- [https://www.freecodecamp.org/news/build-a-secure-server-with-node-and-express/](https://www.freecodecamp.org/news/build-a-secure-server-with-node-and-express/)<br>
- [https://hackernoon.com/web-scraping-using-a-headless-browser-in-nodejs?source=rss](https://hackernoon.com/web-scraping-using-a-headless-browser-in-nodejs?source=rss)<br>
- [https://code.tutsplus.com/token-based-authentication-with-angularjs-nodejs--cms-22543t](https://code.tutsplus.com/token-based-authentication-with-angularjs-nodejs--cms-22543t)<br>
- [https://hackernoon.com/creating-a-nodejs-server-with-postgres-and-knex-on-express?source=rss](https://hackernoon.com/creating-a-nodejs-server-with-postgres-and-knex-on-express?source=rss)<br>
- [https://hackernoon.com/how-to-extract-and-generate-json-data-with-gpts-langchain-and-nodejs?source=rss](https://hackernoon.com/how-to-extract-and-generate-json-data-with-gpts-langchain-and-nodejs?source=rss)<br>
- [https://hackernoon.com/build-a-personal-shopping-assistant-using-brainjs-and-nodejs?source=rss](https://hackernoon.com/build-a-personal-shopping-assistant-using-brainjs-and-nodejs?source=rss)<br>
- [https://blog.javascripttoday.com/blog/web-scraping-bright-data-nodejs/](https://blog.javascripttoday.com/blog/web-scraping-bright-data-nodejs/)<br>
- [https://www.freecodecamp.org/news/nodejs-tutorial-build-a-task-manager-cli-tool/](https://www.freecodecamp.org/news/nodejs-tutorial-build-a-task-manager-cli-tool/)<br>
- [https://www.freecodecamp.org/news/build-an-online-image-to-pdf-converter-with-html-css-js-nodejs/](https://www.freecodecamp.org/news/build-an-online-image-to-pdf-converter-with-html-css-js-nodejs/)<br>
- [https://alexmaina.hashnode.dev/sending-emails-using-resend?ref=dailydev](https://alexmaina.hashnode.dev/sending-emails-using-resend?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/build-a-custom-api-gateway-with-node-js/?ref=dailydev](https://www.freecodecamp.org/news/build-a-custom-api-gateway-with-node-js/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/create-crud-api-project/](https://www.freecodecamp.org/news/create-crud-api-project/)<br>
- [https://www.cerbos.dev/blog/node-js-authorization?ref=dailydev](https://www.cerbos.dev/blog/node-js-authorization?ref=dailydev)<br>
- [https://www.sitepoint.com/sending-email-using-node-js/?ref=dailydev](https://www.sitepoint.com/sending-email-using-node-js/?ref=dailydev)<br>
- [https://dev.to/silentwatcher_95/legendary-emails-in-node-js-with-mjml-4gp9?ref=dailydev](https://dev.to/silentwatcher_95/legendary-emails-in-node-js-with-mjml-4gp9?ref=dailydev)<br>
- [https://github.com/JawherKl/graphql-nodejs-ecom?ref=dailydev](https://github.com/JawherKl/graphql-nodejs-ecom?ref=dailydev)<br>

## MERN
- [https://dev.to/crackingdemon/register-and-login-system-in-mern-stack-1n98](https://dev.to/crackingdemon/register-and-login-system-in-mern-stack-1n98)<br>
- [https://dev.to/collins87mbathi/building-a-dating-app-with-mern-478h](https://dev.to/collins87mbathi/building-a-dating-app-with-mern-478h)<br>
- [https://dev.to/ronyfr3/web-push-notification-using-react-and-node-js-oc9](https://dev.to/ronyfr3/web-push-notification-using-react-and-node-js-oc9)<br>
- [https://systemweakness.com/secure-database-connection-in-nodejs-application-3c3979566741](https://systemweakness.com/secure-database-connection-in-nodejs-application-3c3979566741)<br>
- [https://levelup.gitconnected.com/build-an-autocomplete-search-project-using-elasticsearch-fastapi-and-angular-part-i-backend-741a8cddde8f](https://levelup.gitconnected.com/build-an-autocomplete-search-project-using-elasticsearch-fastapi-and-angular-part-i-backend-741a8cddde8f)<br>
- [https://www.javacodegeeks.com/2023/05/node-js-execution-type-models.html](https://www.javacodegeeks.com/2023/05/node-js-execution-type-models.html)<br>
- [https://dev.to/itsfarhankhan28/user-authentication-in-mern-stack-part-1-4bj3](https://dev.to/itsfarhankhan28/user-authentication-in-mern-stack-part-1-4bj3)<br>
- [https://www.freecodecamp.org/news/simplify-your-file-upload-process-in-express-js/](https://www.freecodecamp.org/news/simplify-your-file-upload-process-in-express-js/)<br>
- [https://awstip.com/mean-stack-on-aws-5462948185a7](https://awstip.com/mean-stack-on-aws-5462948185a7)<br>
- [https://dev.to/idurar/building-an-invoice-pdf-system-with-reactjs-redux-and-nodejs-5g1a](https://dev.to/idurar/building-an-invoice-pdf-system-with-reactjs-redux-and-nodejs-5g1a)<br>
- [https://awstip.com/the-backend-part-of-mnnn-stack-mongodb-nestjs-nextjs-and-nodejs-6bde9adfedd9](https://awstip.com/the-backend-part-of-mnnn-stack-mongodb-nestjs-nextjs-and-nodejs-6bde9adfedd9)<br>
- [https://www.freecodecamp.org/news/full-stack-project-tutorial-create-a-notes-app-using-react-and-node-js/](https://www.freecodecamp.org/news/full-stack-project-tutorial-create-a-notes-app-using-react-and-node-js/)<br>
- [https://awstip.com/building-a-scalable-mern-stack-application-on-aws-using-a-three-tier-architecture-0b12dea74713](https://awstip.com/building-a-scalable-mern-stack-application-on-aws-using-a-three-tier-architecture-0b12dea74713)<br>

## Nodejs with Nginx
- [https://blog.logrocket.com/how-to-run-a-node-js-server-with-nginx/](https://blog.logrocket.com/how-to-run-a-node-js-server-with-nginx/)<br>

## Nodejs Logging
- [https://blog.logrocket.com/comparing-node-js-logging-tools/](https://blog.logrocket.com/comparing-node-js-logging-tools/)<br>
- [https://blog.appsignal.com/2021/09/01/best-practices-for-logging-in-nodejs.html](https://blog.appsignal.com/2021/09/01/best-practices-for-logging-in-nodejs.html)<br>
- [https://hackernoon.com/the-10-best-nodejs-logging-libraries?source=rss](https://hackernoon.com/the-10-best-nodejs-logging-libraries?source=rss)<br>
- [https://betterstack.com/community/guides/logging/logging-framework/?ref=dailydev](https://betterstack.com/community/guides/logging/logging-framework/?ref=dailydev)<br>
- [https://blog.platformatic.dev/handling-environment-variables-in-nodejs?ref=dailydev](https://blog.platformatic.dev/handling-environment-variables-in-nodejs?ref=dailydev)<br>
- [https://www.youtube.com/watch?v=I2mWnh66Bkg&t=3s](https://www.youtube.com/watch?v=I2mWnh66Bkg&t=3s)<br>

## Nodejs Error Handling
- [https://blog.logrocket.com/error-handling-node-js/](https://blog.logrocket.com/error-handling-node-js/)<br>
- [https://medium.com/ovrsea/power-up-your-node-js-debugging-and-error-handling-with-the-new-error-cause-feature-4136c563126a](https://medium.com/ovrsea/power-up-your-node-js-debugging-and-error-handling-with-the-new-error-cause-feature-4136c563126a)<br>
- [https://blog.shiftleft.io/node-js-vulnerability-cheatsheet-447b0c9bdb99](https://blog.shiftleft.io/node-js-vulnerability-cheatsheet-447b0c9bdb99)<br>
- [https://www.builder.io/blog/debug-nodejs](https://www.builder.io/blog/debug-nodejs)<br>
- [https://blog.appsignal.com/2023/03/15/how-to-build-an-error-handling-layer-in-nodejs.html](https://blog.appsignal.com/2023/03/15/how-to-build-an-error-handling-layer-in-nodejs.html)<br>
- [https://blog.openreplay.com/an-introduction-to-debugging-in-nodejs/](https://blog.openreplay.com/an-introduction-to-debugging-in-nodejs/)<br>
- [https://pprathameshmore.medium.com/error-handing-in-express-js-node-js-based-application-0da14e13fa63](https://pprathameshmore.medium.com/error-handing-in-express-js-node-js-based-application-0da14e13fa63)<br>

## Tips and tricks
- [https://javascript.plainenglish.io/node-js-backend-engineers-best-practices-overview-for-beginner-to-advance-caae74b53df](https://javascript.plainenglish.io/node-js-backend-engineers-best-practices-overview-for-beginner-to-advance-caae74b53df)<br>
- [https://dzone.com/articles/creating-a-secure-rest-api-in-nodejs-1](https://dzone.com/articles/creating-a-secure-rest-api-in-nodejs-1)<br>
- [https://dev.to/amoled27/best-practices-for-nodejs-development-5ao5](https://dev.to/amoled27/best-practices-for-nodejs-development-5ao5)<br>
- [https://faun.pub/best-practices-for-better-restful-api-a54b4e374cab](https://faun.pub/best-practices-for-better-restful-api-a54b4e374cab)<br>
- [https://blog.appsignal.com/2022/03/09/a-complete-guide-to-nodejs-process-management-with-pm2.html](https://blog.appsignal.com/2022/03/09/a-complete-guide-to-nodejs-process-management-with-pm2.html)<br>
- [https://dev.to/imaroof07/an-ideal-rest-api-best-practices-4k89](https://dev.to/imaroof07/an-ideal-rest-api-best-practices-4k89)<br>
- [https://infosecwriteups.com/ssrf-server-side-request-forgery-2865e87efc3](https://infosecwriteups.com/ssrf-server-side-request-forgery-2865e87efc3)<br>
- [https://amplication.com/blog/understanding-and-preventing-memory-leaks-in-nodejs](https://amplication.com/blog/understanding-and-preventing-memory-leaks-in-nodejs)<br>
- [https://github.com/goldbergyoni/nodebestpractices?ref=dailydev#readme](https://github.com/goldbergyoni/nodebestpractices?ref=dailydev#readme)<br>


## Micro services
- [https://fauna.com/blog/how-to-build-microservices-with-node-js](https://fauna.com/blog/how-to-build-microservices-with-node-js)<br>
- [https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker](https://www.digitalocean.com/community/tutorials/how-to-build-a-node-js-application-with-docker)
- [https://redis.com/blog/graphql-and-redis/](https://redis.com/blog/graphql-and-redis/)<br>
- [https://medium.com/@akinnurun.samuel/writing-a-microservice-using-node-js-14ce992c2003](https://medium.com/@akinnurun.samuel/writing-a-microservice-using-node-js-14ce992c2003)<br>

## NodeJS pattern
- [https://dev.to/fyapy/repository-pattern-with-typescript-and-nodejs-25da](https://dev.to/fyapy/repository-pattern-with-typescript-and-nodejs-25da)<br>
- [https://itnext.io/decoupling-the-crazy-taming-your-application-services-with-pub-sub-outbox-patterns-and-nodejs-9b00b47de373](https://itnext.io/decoupling-the-crazy-taming-your-application-services-with-pub-sub-outbox-patterns-and-nodejs-9b00b47de373)<br>
- [https://www.codeflashbacks.com/announcing-the-enterprise-node-js-service-template/](https://www.codeflashbacks.com/announcing-the-enterprise-node-js-service-template/)<br>

## NodeJS cheatSheet
- [https://devdojo.com/devbookmark/the-nodejs-ultimate-beginner-to-pro-cheatsheet-in-2021](https://devdojo.com/devbookmark/the-nodejs-ultimate-beginner-to-pro-cheatsheet-in-2021)<br>
- [https://morioh.com/p/7e75bc6e5041](https://morioh.com/p/7e75bc6e5041)<br>
- [https://www.javacodegeeks.com/node-js-cheatsheet.html?ref=dailydev](https://www.javacodegeeks.com/node-js-cheatsheet.html?ref=dailydev)<br>

## NodeJS Interview
- [https://www.edureka.co/blog/interview-questions/top-node-js-interview-questions-2016/](https://www.edureka.co/blog/interview-questions/top-node-js-interview-questions-2016/)<br>
- [https://codedamn.com/problem-list/nodejs?utm_source=email-inbox&utm_medium=email&utm_campaign=14may](https://codedamn.com/problem-list/nodejs?utm_source=email-inbox&utm_medium=email&utm_campaign=14may)<br>
- [https://hackernoon.com/nodejs-background-jobs-for-modern-developers-interview-with-startups-of-the-year-nominee-defer?source=rss](https://hackernoon.com/nodejs-background-jobs-for-modern-developers-interview-with-startups-of-the-year-nominee-defer?source=rss)<br>

## NestJS
- [https://blog.logrocket.com/full-stack-app-tutorial-nestjs-react/](https://blog.logrocket.com/full-stack-app-tutorial-nestjs-react/)<br>
- [https://dev.to/fekabas/learning-to-build-an-api-in-nestjs-node-typescript-3i1o](https://dev.to/fekabas/learning-to-build-an-api-in-nestjs-node-typescript-3i1o)<br>
- [https://www.paulsblog.dev/use-nestjs-mongodb-and-docker-to-create-an-url-shortener/](https://www.paulsblog.dev/use-nestjs-mongodb-and-docker-to-create-an-url-shortener/)<br>
- [https://hackernoon.com/5-steps-for-dockerizing-nestjs-with-prisma?source=rss](https://hackernoon.com/5-steps-for-dockerizing-nestjs-with-prisma?source=rss)<br>
- [https://betterprogramming.pub/nestjs-the-good-the-bad-and-the-ugly-d51aea04f267](https://betterprogramming.pub/nestjs-the-good-the-bad-and-the-ugly-d51aea04f267)<br>
- [https://dev.to/krtirtho/nestjs-the-framework-of-nodejs-part-3-database-integration-typeorm-4gab](https://dev.to/krtirtho/nestjs-the-framework-of-nodejs-part-3-database-integration-typeorm-4gab)<br>
- [https://faun.pub/nodejs-framework-express-vs-nestjs-which-one-will-work-best-for-your-project-bb0131c5cd83](https://faun.pub/nodejs-framework-express-vs-nestjs-which-one-will-work-best-for-your-project-bb0131c5cd83)<br>
- [https://blog.logrocket.com/build-project-using-angular-nestjs/](https://blog.logrocket.com/build-project-using-angular-nestjs/)<br>
- [https://blog.logrocket.com/understanding-guards-nestjs/](https://blog.logrocket.com/understanding-guards-nestjs/)<br>
- [https://planetscale.com/blog/build-a-user-management-api-with-nestjs-mysql](https://planetscale.com/blog/build-a-user-management-api-with-nestjs-mysql)<br>
- [https://blog.logrocket.com/exploring-nestjs-middleware-benefits-use-cases/](https://blog.logrocket.com/exploring-nestjs-middleware-benefits-use-cases/)<br>
- [https://dev.to/francescoxx/typescript-crud-rest-api-using-nestjs-typeorm-postgres-docker-and-docker-compose-33al](https://dev.to/francescoxx/typescript-crud-rest-api-using-nestjs-typeorm-postgres-docker-and-docker-compose-33al)<br>
- [https://amplication.com/blog/working-with-microservices-with-nestjs](https://amplication.com/blog/working-with-microservices-with-nestjs)<br>
- [https://devhoangkien.com/optimizing-application-performance-with-node-js-typescript-and-nest-js-tips-and-tricks-fb45ed87ebee](https://devhoangkien.com/optimizing-application-performance-with-node-js-typescript-and-nest-js-tips-and-tricks-fb45ed87ebee)<br>
- [https://dev.to/samchon/nestia-boost-up-your-nestjs-server-much-faster-and-easier-maximum-20000x-faster-59o5](https://dev.to/samchon/nestia-boost-up-your-nestjs-server-much-faster-and-easier-maximum-20000x-faster-59o5)<br>
- [https://hashnode.knulst.de/use-nestjs-mongodb-and-docker-to-create-an-url-shortener](https://hashnode.knulst.de/use-nestjs-mongodb-and-docker-to-create-an-url-shortener)<br>
- [https://www.tomray.dev/resources/nestjs-first-principles/part-1?ck_subscriber_id=2227267103&utm_campaign=Landing%20Page%20or%20Form%20-%204864903&utm_medium=email&utm_source=convertkit](https://www.tomray.dev/resources/nestjs-first-principles/part-1?ck_subscriber_id=2227267103&utm_campaign=Landing%20Page%20or%20Form%20-%204864903&utm_medium=email&utm_source=convertkit)<br>
- [https://aws.plainenglish.io/deploy-nestjs-application-into-aws-elastic-beanstalk-c5474e19a6b4](https://aws.plainenglish.io/deploy-nestjs-application-into-aws-elastic-beanstalk-c5474e19a6b4)<br>
- [https://www.permit.io/blog/how-to-protect-a-url-inside-a-nestjs-app-using-rbac-authorization](https://www.permit.io/blog/how-to-protect-a-url-inside-a-nestjs-app-using-rbac-authorization)<br>
- [https://www.tomray.dev/resources/nestjs-first-principles/part-1?ck_subscriber_id=2227267103&utm_campaign=Landing%20Page%20or%20Form%20-%204864903&utm_medium=email&utm_source=convertkit](https://www.tomray.dev/resources/nestjs-first-principles/part-1?ck_subscriber_id=2227267103&utm_campaign=Landing%20Page%20or%20Form%20-%204864903&utm_medium=email&utm_source=convertkit)<br>
- [https://hackernoon.com/the-complete-guide-to-deploying-nestjs-application-on-render?source=rss](https://hackernoon.com/the-complete-guide-to-deploying-nestjs-application-on-render?source=rss)<br>
- [https://awstip.com/understanding-nestjs-architecture-f257d054211d](https://awstip.com/understanding-nestjs-architecture-f257d054211d)<br>
- [https://medium.com/@dev.muhammet.ozen/advanced-transaction-management-with-nestjs-typeorm-43a839363491](https://medium.com/@dev.muhammet.ozen/advanced-transaction-management-with-nestjs-typeorm-43a839363491)<br>
- [https://www.freecodecamp.org/news/message-queues-with-rabbitmq-in-nest-js/?ref=dailydev](https://www.freecodecamp.org/news/message-queues-with-rabbitmq-in-nest-js/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/how-to-add-filtering-sorting-limiting-pagination-to-nestjs-app/?ref=dailydev](https://www.freecodecamp.org/news/how-to-add-filtering-sorting-limiting-pagination-to-nestjs-app/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/how-to-use-nodemailer-in-nestjs/?ref=dailydev](https://www.freecodecamp.org/news/how-to-use-nodemailer-in-nestjs/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/how-to-setup-typeorm-datasource-nestjs-app/?ref=dailydev](https://www.freecodecamp.org/news/how-to-setup-typeorm-datasource-nestjs-app/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/how-to-setup-typeorm-datasource-nestjs-app/](https://www.freecodecamp.org/news/how-to-setup-typeorm-datasource-nestjs-app/)<br>
- [https://itnext.io/building-microservices-with-nestjs-tcp-and-typescript-dda33aad8b89](https://itnext.io/building-microservices-with-nestjs-tcp-and-typescript-dda33aad8b89)<br>
- [https://medium.com/@zigbalthazar/implement-retry-pattern-in-nest-js-2ad505324960](https://medium.com/@zigbalthazar/implement-retry-pattern-in-nest-js-2ad505324960)<br>
- [https://coinsbench.com/building-a-balancer-price-retrieval-api-with-nestjs-5ad53e72e2cf](https://coinsbench.com/building-a-balancer-price-retrieval-api-with-nestjs-5ad53e72e2cf)<br>
- [https://www.freecodecamp.org/news/build-a-crud-rest-api-with-nestjs-docker-swagger-prisma/](https://www.freecodecamp.org/news/build-a-crud-rest-api-with-nestjs-docker-swagger-prisma/)<br>
- [https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8](https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8)<br>
- [https://medium.com/@swapnilsuman65/generate-pdfs-dynamically-in-nodejs-nestjs-398fe3617a4a](https://medium.com/@swapnilsuman65/generate-pdfs-dynamically-in-nodejs-nestjs-398fe3617a4a)<br>
- [https://medium.com/@abeythilakeudara3/nestjs-framework-fundamentals-part-01-7e2fa9e91bad](https://medium.com/@abeythilakeudara3/nestjs-framework-fundamentals-part-01-7e2fa9e91bad)<br>
- [https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8](https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8)<br>
- [https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8](https://blog.stackademic.com/mastering-microservices-in-nestjs-powerful-design-patterns-for-flexibility-resilience-and-64309ae219e8)<br>
- [https://www.freecodecamp.org/news/comprehensive-nestjs-course/](https://www.freecodecamp.org/news/comprehensive-nestjs-course/)<br>
- [https://dev.to/rayenmabrouk/best-tech-stack-for-startups-in-2025-5h2l](https://dev.to/rayenmabrouk/best-tech-stack-for-startups-in-2025-5h2l)<br>


## NodeJS Unit testing
- [https://github.com/goldbergyoni/javascript-testing-best-practices?utm_campaign=javascript-and-node-testing-best-practic](https://github.com/goldbergyoni/javascript-testing-best-practices?utm_campaign=javascript-and-node-testing-best-practic)<br>
- [https://semaphoreci.com/blog/unit-tests-nodejs-jest](https://semaphoreci.com/blog/unit-tests-nodejs-jest)<br>
- [https://dzone.com/articles/web-application-testing-tutorial-a-comprehensive-g](https://dzone.com/articles/web-application-testing-tutorial-a-comprehensive-g)<br>
- [https://circleci.com/blog/mocking-api-requests-with-mirage/](https://circleci.com/blog/mocking-api-requests-with-mirage/)<br>
- [https://developers.redhat.com/articles/2023/07/27/introduction-nodejs-reference-architecture-testing](https://developers.redhat.com/articles/2023/07/27/introduction-nodejs-reference-architecture-testing)<br>
- [https://blog.appsignal.com/2024/10/16/best-testing-practices-in-nodejs.html?ref=dailydev](https://blog.appsignal.com/2024/10/16/best-testing-practices-in-nodejs.html?ref=dailydev)<br>

## NodeJS with Typescript
- [https://itnext.io/simple-cqrs-in-nodejs-with-typescript-6da6d3e8a420](https://itnext.io/simple-cqrs-in-nodejs-with-typescript-6da6d3e8a420)<br>
- [https://deno.com/blog/build-api-express-typescript-pt2](https://deno.com/blog/build-api-express-typescript-pt2)<br>
- [https://wundergraph.com/blog/the-backend-for-frontend-pattern-using-nextjs](https://wundergraph.com/blog/the-backend-for-frontend-pattern-using-nextjs)<br>
- [https://dev.to/wizdomtek/typescript-express-building-robust-apis-with-nodejs-1fln](https://dev.to/wizdomtek/typescript-express-building-robust-apis-with-nodejs-1fln)<br>
- [https://medium.com/before-semicolon/how-to-setup-a-typescript-nodejs-server-2023-16f3874f2ce5](https://medium.com/before-semicolon/how-to-setup-a-typescript-nodejs-server-2023-16f3874f2ce5)<br>
- [https://losikov.medium.com/part-1-project-initial-setup-typescript-node-js-31ba3aa7fbf1](https://losikov.medium.com/part-1-project-initial-setup-typescript-node-js-31ba3aa7fbf1)<br>

## NodeJS best practices
- [https://systemweakness.com/why-helmet-js-is-essential-for-securing-your-express-js-application-416e0044fc2](https://systemweakness.com/why-helmet-js-is-essential-for-securing-your-express-js-application-416e0044fc2)<br>
- [https://blog.javascripttoday.com/blog/node-js-server-vulnerabilities/](https://blog.javascripttoday.com/blog/node-js-server-vulnerabilities/)<br>

## API practices
- [https://mojoauth.com/blog/rest-api-authentication/](https://mojoauth.com/blog/rest-api-authentication/)<br>
- [https://nerdleveltech.com/a-full-guide-understand-everything-about-apis-with-examples/](https://nerdleveltech.com/a-full-guide-understand-everything-about-apis-with-examples/)<br>
- [https://blog.logrocket.com/communicating-between-node-js-microservices-with-grpc/](https://blog.logrocket.com/communicating-between-node-js-microservices-with-grpc/)<br>
- [https://www.strongdm.com/blog/api-security](https://www.strongdm.com/blog/api-security)<br>
- [https://blog.bytebytego.com/p/ep49-api-architectural-styles](https://blog.bytebytego.com/p/ep49-api-architectural-styles)<br>
- [https://blog.logrocket.com/using-helmet-node-js-secure-application/](https://blog.logrocket.com/using-helmet-node-js-secure-application/)<br>
- [https://cerbos.dev/blog/should-you-choose-grpc-over-rest-when-designing-your-apis](https://cerbos.dev/blog/should-you-choose-grpc-over-rest-when-designing-your-apis)<br>
- [https://www.freecodecamp.org/news/public-apis-for-developers/](https://www.freecodecamp.org/news/public-apis-for-developers/)<br>
- [https://dzone.com/articles/the-ultimate-api-development-guide-strategy-tools](https://dzone.com/articles/the-ultimate-api-development-guide-strategy-tools)<br>
- [https://unzip.dev/0x012-trpc/](https://unzip.dev/0x012-trpc/)<br>
- [https://www.telerik.com/blogs/11-api-security-best-practices-secure-business](https://www.telerik.com/blogs/11-api-security-best-practices-secure-business)<br>
- [https://amplication.com/blog/rest-vs-grpc-whats-the-difference](https://amplication.com/blog/rest-vs-grpc-whats-the-difference)<br>
- [https://betterprogramming.pub/build-faster-and-easier-apis-with-user-sessions-b73b8902222d](https://betterprogramming.pub/build-faster-and-easier-apis-with-user-sessions-b73b8902222d)<br>
- [https://www.freecodecamp.org/news/use-apis-to-practice-coding-skills/](https://www.freecodecamp.org/news/use-apis-to-practice-coding-skills/)<br>
- [https://www.freecodecamp.org/news/build-consume-and-document-a-rest-api/](https://www.freecodecamp.org/news/build-consume-and-document-a-rest-api/)<br>
- [https://blog.bytebytego.com/p/api-design](https://blog.bytebytego.com/p/api-design)<br>
- [https://medium.com/api-center/api-documentation-rules-192c127cf401](https://medium.com/api-center/api-documentation-rules-192c127cf401)<br>
- [https://mehranjnf.medium.com/preventing-cross-site-request-forgery-csrf-in-node-js-82a989a41642](https://mehranjnf.medium.com/preventing-cross-site-request-forgery-csrf-in-node-js-82a989a41642)<br>
- [https://medium.com/api-center/api-design-practice-7fce69e6336c](https://medium.com/api-center/api-design-practice-7fce69e6336c)<br>
- [https://blog.postman.com/how-to-choose-between-rest-vs-graphql-vs-grpc-vs-soap/](https://blog.postman.com/how-to-choose-between-rest-vs-graphql-vs-grpc-vs-soap/)<br>
- [https://www.apriorit.com/dev-blog/776-cloud-api-scaling](https://www.apriorit.com/dev-blog/776-cloud-api-scaling)<br>
- [https://www.wallarm.com/what/api-security-tutorial](https://www.wallarm.com/what/api-security-tutorial)<br>
- [https://brainhub.eu/library/api-expressjs-and-hadron](https://brainhub.eu/library/api-expressjs-and-hadron)<br>
- [https://blog.bytebytego.com/p/the-foundation-of-rest-api-http](https://blog.bytebytego.com/p/the-foundation-of-rest-api-http)<br>
- [https://www.freecodecamp.org/news/api-integration-patterns/?ref=dailydev](https://www.freecodecamp.org/news/api-integration-patterns/?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/master-api-testing-with-postman/](https://www.freecodecamp.org/news/master-api-testing-with-postman/)<br>
- [https://www.freecodecamp.org/news/what-are-api-gateways/](https://www.freecodecamp.org/news/what-are-api-gateways/)<br>
- [https://www.freecodecamp.org/news/api-documentation-best-practices-course/](https://www.freecodecamp.org/news/api-documentation-best-practices-course/)<br>
- [https://www.youtube.com/watch?v=_gQaygjm_hg](https://www.youtube.com/watch?v=_gQaygjm_hg)<br>
- [https://blog.amigoscode.com/p/api-development-roadmap-for-developers?r=22x1kh&ref=dailydev&triedRedirect=true](https://blog.amigoscode.com/p/api-development-roadmap-for-developers?r=22x1kh&ref=dailydev&triedRedirect=true)<br>
- [https://www.freecodecamp.org/news/learn-how-to-secure-api-servers/](https://www.freecodecamp.org/news/learn-how-to-secure-api-servers/)<br>
- [https://dev.to/msnmongare/best-practices-for-naming-api-endpoints-2n5o?ref=dailydev](https://dev.to/msnmongare/best-practices-for-naming-api-endpoints-2n5o?ref=dailydev)<br>
- [https://www.thoughtworks.com/insights/blog/rest-api-design-resource-modeling?ref=dailydev](https://www.thoughtworks.com/insights/blog/rest-api-design-resource-modeling?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/api-documentation-best-practices-course/](https://www.freecodecamp.org/news/api-documentation-best-practices-course/)<br>
- [https://newsletter.techworld-with-milan.com/p/how-to-learn-api?ref=dailydev](https://newsletter.techworld-with-milan.com/p/how-to-learn-api?ref=dailydev)<br>
- [https://www.freecodecamp.org/news/api-testing-with-postman-a-step-by-step-guide-using-the-spotify-api/?ref=dailydev](https://www.freecodecamp.org/news/api-testing-with-postman-a-step-by-step-guide-using-the-spotify-api/?ref=dailydev)<br>
- [https://newsletter.techworld-with-milan.com/p/how-to-learn-api?ref=dailydev](https://newsletter.techworld-with-milan.com/p/how-to-learn-api?ref=dailydev)<br>
- [https://implementing.substack.com/p/how-to-make-the-best-use-of-api-pagination?ref=dailydev&triedRedirect=true](https://implementing.substack.com/p/how-to-make-the-best-use-of-api-pagination?ref=dailydev&triedRedirect=true)<br>
- [https://blogs.halodoc.io/improving-api-latency-guide/?ref=dailydev](https://blogs.halodoc.io/improving-api-latency-guide/?ref=dailydev)<br>
- [https://levelup.gitconnected.com/api-design-101-from-basics-to-best-practices-a0261cdf8886](https://levelup.gitconnected.com/api-design-101-from-basics-to-best-practices-a0261cdf8886)<br>
- [https://pixel506.com/insights/how-much-traffic-can-nodejs-handle?ref=dailydev](https://pixel506.com/insights/how-much-traffic-can-nodejs-handle?ref=dailydev)<br>
- [https://blog.openreplay.com/how-to-debug-api-issues-with-jwt-decoders/?ref=dailydev](https://blog.openreplay.com/how-to-debug-api-issues-with-jwt-decoders/?ref=dailydev)<br>

## Package Manager
- [https://howtocrackit.com/pnpm-vs-npm-and-yarn-why-you-should-switch-and-how-to-do-it/](https://howtocrackit.com/pnpm-vs-npm-and-yarn-why-you-should-switch-and-how-to-do-it/)<br>

## NodeJS tools
- [https://brainhub.eu/library/node-js-tools-for-developers](https://brainhub.eu/library/node-js-tools-for-developers)<br>

## NodeJS security
- [https://www.telerik.com/blogs/all-you-need-to-know-cors-errors](https://www.telerik.com/blogs/all-you-need-to-know-cors-errors)<br>
- [https://tsh.io/blog/dependency-injection-in-node-js/](https://tsh.io/blog/dependency-injection-in-node-js/)<br>
- [https://amplication.com/blog/how-to-use-dependency-injection-with-nodejs](https://amplication.com/blog/how-to-use-dependency-injection-with-nodejs)<br>
- [https://blog.openreplay.com/securing-front-end-apps-with-cors-and-csp/](https://blog.openreplay.com/securing-front-end-apps-with-cors-and-csp/)<br>
- [https://reflectoring.io/tutorial-nodejs-rate-limiter/?ref=dailydev](https://reflectoring.io/tutorial-nodejs-rate-limiter/?ref=dailydev)<br>
- [https://dev.to/mohammadfaisal/nodejs-security-best-practices-34ck?ref=dailydev](https://dev.to/mohammadfaisal/nodejs-security-best-practices-34ck?ref=dailydev)<br>
- [https://www.strongdm.com/blog/api-security-best-practices?ref=dailydev](https://www.strongdm.com/blog/api-security-best-practices?ref=dailydev)<br>
- [https://developer.mozilla.org/en-US/blog/securing-apis-express-rate-limit-and-slow-down/?ref=dailydev](https://developer.mozilla.org/en-US/blog/securing-apis-express-rate-limit-and-slow-down/?ref=dailydev)<br>
- [https://medium.com/@modywmbadr/securing-node-js-in-production-f11822ab20b7](https://medium.com/@modywmbadr/securing-node-js-in-production-f11822ab20ab7)<br>
- [https://www.toptal.com/nodejs/secure-rest-api-in-nodejs?ref=dailydev](https://www.toptal.com/nodejs/secure-rest-api-in-nodejs?ref=dailydev)<br>

## NodeJS Migration
- [https://blog.appsignal.com/2023/06/28/migrate-your-express-application-to-fastify.html](https://blog.appsignal.com/2023/06/28/migrate-your-express-application-to-fastify.html)<br>

## NodeJS deployment
- [https://aws.plainenglish.io/upload-images-on-aws-s3-using-node-js-c3d3b9e81ddc](https://aws.plainenglish.io/upload-images-on-aws-s3-using-node-js-c3d3b9e81ddc)<br>
- [https://aws.plainenglish.io/deploy-node-js-server-to-aws-ec2-with-docker-78687493b53](https://aws.plainenglish.io/deploy-node-js-server-to-aws-ec2-with-docker-78687493b53)<br>
- [https://blog.risingstack.com/how-to-debug-a-node-js-app-in-a-docker-container/?ref=dailydev](https://blog.risingstack.com/how-to-debug-a-node-js-app-in-a-docker-container/?ref=dailydev)<br>

## NodeJS with GraphQL
- [https://medium.com/neo4j/improving-a-node-js-graphql-server-performance-645a4ae711c3](https://medium.com/neo4j/improving-a-node-js-graphql-server-performance-645a4ae711c3)<br>
- [https://www.freecodecamp.org/news/graphql-queries-for-everyone/](https://www.freecodecamp.org/news/graphql-queries-for-everyone/)<br>
- [https://javascript.plainenglish.io/an-introduction-to-federated-graphql-and-wundergraph-cosmo-b802599a338c](https://javascript.plainenglish.io/an-introduction-to-federated-graphql-and-wundergraph-cosmo-b802599a338c)<br>

## NodeJS with Redis
- [https://www.freecodecamp.org/news/how-to-use-queues-in-web-applications/](https://www.freecodecamp.org/news/how-to-use-queues-in-web-applications/)<br>
- [https://blog.bytebytego.com/p/a-crash-course-in-redis](https://blog.bytebytego.com/p/a-crash-course-in-redis)<br>
- [https://blog.bytebytego.com/p/the-6-most-impactful-ways-redis-is?ref=dailydev](https://blog.bytebytego.com/p/the-6-most-impactful-ways-redis-is?ref=dailydev)<br>
- [https://awstip.com/unlock-the-power-of-redis-part-1-55ccdf43d8f0](https://awstip.com/unlock-the-power-of-redis-part-1-55ccdf43d8f0)<br>
- [https://implementing.substack.com/p/implement-leaderboard-with-redis-sorted-sets?ref=dailydev](https://implementing.substack.com/p/implement-leaderboard-with-redis-sorted-sets?ref=dailydev)<br>

## NodeJS Auth
- [https://hackernoon.com/a-practical-guide-to-implementing-user-authentication-using-javascript-and-express?source=rss](https://hackernoon.com/a-practical-guide-to-implementing-user-authentication-using-javascript-and-express?source=rss)<br>
- [https://www.permit.io/blog/authentication-vs-authorization?ref=dailydev](https://www.permit.io/blog/authentication-vs-authorization?ref=dailydev)<br>
- [https://www.permit.io/blog/differences-between-oauth-vs-jwt?ref=dailydev](https://www.permit.io/blog/differences-between-oauth-vs-jwt?ref=dailydev)<br>
- [https://arindam1729.hashnode.dev/jwt-authentication-in-nodejs?ref=dailydev](https://arindam1729.hashnode.dev/jwt-authentication-in-nodejs?ref=dailydev)<br>
- [https://ssojet.com/blog/navigating-the-world-of-jwt-a-comprehensive-guide/?ref=dailydev](https://ssojet.com/blog/navigating-the-world-of-jwt-a-comprehensive-guide/?ref=dailydev)<br>
- [https://medium.com/@iamprovidence/authentication-history-basic-digest-cookie-session-token-jwt-api-key-55d6c21be90b](https://medium.com/@iamprovidence/authentication-history-basic-digest-cookie-session-token-jwt-api-key-55d6c21be90b)<br>
- [https://www.syncfusion.com/blogs/post/secure-jwt-storage-best-practices?ref=dailydev](https://www.syncfusion.com/blogs/post/secure-jwt-storage-best-practices?ref=dailydev)<br>
- [https://blog.logrocket.com/understanding-jwt-oauth-bearer-tokens/?ref=dailydev](https://blog.logrocket.com/understanding-jwt-oauth-bearer-tokens/?ref=dailydev)<br>
- [https://hackernoon.com/build-a-login-and-logout-api-using-expressjs-nodejs?ref=dailydev](https://hackernoon.com/build-a-login-and-logout-api-using-expressjs-nodejs?ref=dailydev)<br>
- [https://neon.tech/blog/wtf-are-jwts?ref=dailydev](https://neon.tech/blog/wtf-are-jwts?ref=dailydev)<br>
- [https://www.cerbos.dev/blog/role-based-access-control-best-practices?ref=dailydev](https://www.cerbos.dev/blog/role-based-access-control-best-practices?ref=dailydev)<br>
- [https://medium.com/procedureflow-engineering/building-api-authentication-at-procedureflow-4d1fe78bb293](https://medium.com/procedureflow-engineering/building-api-authentication-at-procedureflow-4d1fe78bb293)<br>

## NodeJS with MongoDB
- [https://blog.appsignal.com/2023/08/09/how-to-use-mongodb-and-mongoose-for-nodejs.html](https://blog.appsignal.com/2023/08/09/how-to-use-mongodb-and-mongoose-for-nodejs.html)<br>
- [https://awstip.com/deploy-node-js-with-mongodb-app-on-aws-5b20ac4418f9](https://awstip.com/deploy-node-js-with-mongodb-app-on-aws-5b20ac4418f9)<br>
- [https://blog.openreplay.com/mongoose--simplifying-mongodb-for-node/?ref=dailydev](https://blog.openreplay.com/mongoose--simplifying-mongodb-for-node/?ref=dailydev)<br>

## NodeJS Guide
- [https://hackernoon.com/file-based-routing-in-nodejs-a-brief-guide?source=rss](https://hackernoon.com/file-based-routing-in-nodejs-a-brief-guide?source=rss)<br>

## NodeJS Queue
- [https://javascript.plainenglish.io/message-queue-in-nodejs-with-bullmq-and-redis-ec7af00c075](https://javascript.plainenglish.io/message-queue-in-nodejs-with-bullmq-and-redis-ec7af00c075)<br>
- [https://www.digitalocean.com/community/tutorials/publish-subscribe-pattern-in-node-js?ref=dailydev](https://www.digitalocean.com/community/tutorials/publish-subscribe-pattern-in-node-js?ref=dailydev)<br>

## NodeJS library
- [https://www.freecodecamp.org/news/learn-bun-a-faster-node-js-alternative/?ref=dailydev](https://www.freecodecamp.org/news/learn-bun-a-faster-node-js-alternative/?ref=dailydev)<br>
- [https://newsletter.systemdesigncodex.com/p/polling-vs-webhooks?ref=dailydev](https://newsletter.systemdesigncodex.com/p/polling-vs-webhooks?ref=dailydev)<br>
- [https://www.codu.co/articles/simple-node-cron-example-in-node-js-s3slkm5p?ref=dailydev](https://www.codu.co/articles/simple-node-cron-example-in-node-js-s3slkm5p?ref=dailydev)<br>
- [https://javascript.plainenglish.io/mastering-package-json-the-heart-of-every-node-js-project-b665a9cb82ab](https://javascript.plainenglish.io/mastering-package-json-the-heart-of-every-node-js-project-b665a9cb82ab)<br>
- [https://medium.com/@surajAherrao/scheduling-tasks-with-cron-jobs-in-node-js-85680383a659](https://medium.com/@surajAherrao/scheduling-tasks-with-cron-jobs-in-node-js-85680383a659)<br>

## NodeJS Steaming
- [https://dev.to/bsorrentino/how-to-stream-data-over-http-using-node-and-fetch-api-4ij2?ref=dailydev](https://dev.to/bsorrentino/how-to-stream-data-over-http-using-node-and-fetch-api-4ij2?ref=dailydev)<br>
- [https://pavel-romanov.com/exploring-the-core-concepts-of-nodejs-readable-streams?ref=dailydev](https://pavel-romanov.com/exploring-the-core-concepts-of-nodejs-readable-streams?ref=dailydev)<br>

## NodeJS Serverless
- [https://www.freecodecamp.org/news/serverless-node-js-tutorial/](https://www.freecodecamp.org/news/serverless-node-js-tutorial/)<br>

## NodeJS documentation
- [https://blog.openreplay.com/document-your-api-with-swagger/?ref=dailydev](https://blog.openreplay.com/document-your-api-with-swagger/?ref=dailydev)<br>
- [https://rapidapi.com/courses](https://rapidapi.com/courses)<br>

## NodeJS github
- [https://github.com/alirezanqp/nodejs-backend-roadmap](https://github.com/alirezanqp/nodejs-backend-roadmap)<br>
- [https://github.com/saifaustcse/nodejs-developer-roadmap](https://github.com/saifaustcse/nodejs-developer-roadmap)<br>
- [https://github.com/aliyr/Nodejs-Developer-Roadmap](https://github.com/aliyr/Nodejs-Developer-Roadmap)<br>
- [https://github.com/DhanushNehru/Ultimate-NodeJs-Resources?ref=dailydev](https://github.com/DhanushNehru/Ultimate-NodeJs-Resources?ref=dailydev)<br>

## NodeJS youtube
- [https://www.youtube.com/watch?v=dQV0xzOeGzU](https://www.youtube.com/watch?v=dQV0xzOeGzU)<br>
- [https://www.youtube.com/watch?v=m6T7Bi8OEvc](https://www.youtube.com/watch?v=m6T7Bi8OEvc)<br>

## NodeJS ORM
- [https://blog.logrocket.com/drizzle-vs-prisma-which-orm-is-best/?ref=dailydev](https://blog.logrocket.com/drizzle-vs-prisma-which-orm-is-best/?ref=dailydev)<br>

## NodeJS sockets
- [https://kumneger.vercel.app/blog/server-sent-events-explained](https://kumneger.vercel.app/blog/server-sent-events-explained)<br>

## Backend Essientials
- [https://blog.stackademic.com/essential-skills-every-back-end-developer-needs-4474809e14d0](https://blog.stackademic.com/essential-skills-every-back-end-developer-needs-4474809e14d0)<br>

## Node Ops
- [https://www.freecodecamp.org/news/containerize-a-nodejs-application-using-docker/?ref=dailydev](https://www.freecodecamp.org/news/containerize-a-nodejs-application-using-docker/?ref=dailydev)<br>
