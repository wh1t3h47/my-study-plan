# my-study-plan

This is a comprehensive list of what technologies I studied after I started my career as a programmer and what I plan to study in the future.

## This is not everything
> There's a lot more that I have studied in the past years before creating this repository, if you wish to check out more about what I know, please have a look at [my website](https://invalid.com) and also at [wh1t3h47/coding-interview-university](https://github.com/wh1t3h47/coding-interview-university) .


# Subjects:

## Programming:

- ### JavaScript
  > - [x] https://css-tricks.com/breaking-performance-api/
  > - [x] https://developer.mozilla.org/en-US/docs/Web/API/Resource_Timing_API
  - #### Design Patterns:
    > - [x] [Async Lazy initializer pattern](https://advancedweb.hu/the-async-lazy-initializer-pattern-in-javascript/)
      > - Async Lazy Initializer Pattern is a pattern that invokes an asynchronous function only once and only when it's needed, it can still have memoization and is cache-able;
  - #### ES6
    > - [x] https://wanago.io/2018/03/19/prototype-the-big-bro-behind-es6-class/
    > - [x] https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
  - #### Frameworks
    > #### Vue
    > - [x] https://www.youtube.com/watch?v=4deVCNJq3qc
    > - [ ] https://medium.com/vue-mastery/how-to-create-vue-js-transitions-6487dffd0baa
    > - [x] https://www.vuemastery.com/blog/Reactivity-Vue2-vs-Vue3/
    > - [x] https://vue-loader.vuejs.org/guide/scoped-css.html
    > #### Vue/ Nuxt
    > - [x] https://medium.com/vue-mastery/10-reasons-to-use-nuxt-js-for-your-next-web-application-522397c9366b
    > - [ ] https://nuxtjs.org/examples/routes-transitions/
    > - [x] https://nuxtjs.org/guides/features/deployment-targets/
    > - [ ] https://nuxtjs.org/faq/github-pages
    > #### Vue/ Vuetify
    > - [x] https://vuetifyjs.com/en/introduction/why-vuetify/#feature-guides
    > - [X] https://vuetifyjs.com/en/components/toolbars/
    > #### React
    > > - [X] https://ui.dev/react-router-v5-animated-transitions/
    > > - This video explains how to use CSSTransitions to animate react router, it is the best approach as it works well with Redirect and route
    > #### React/ Redux
    > > - [x] https://redux.js.org/introduction/getting-started
    > > - This document gives an introduction about Redux, demonstrating how to install/ setup Redux with create-react-app and also showing a basic example of a reducer function, with it's core pattern (having the dispatcher, a switch and actions).
    > #### Jest
    > - [x] https://wanago.io/2018/08/27/testing-javascript-tutorial-types-of-tests-of-unit-testing-with-jest/
  - ### Node
    > #### Guides
    > - [x] https://nodejs.org/en/docs/guides/getting-started-guide/
    > - [x] https://nodejs.org/en/docs/guides/debugging-getting-started/
    > #### Node + TypeScript + Mongoose
    > - [x] https://wanago.io/2018/12/03/typescript-express-tutorial-routing-controllers-middleware/
    > - [x] https://wanago.io/2018/12/10/express-mongodb-typescript-env-var/
    > - [x] https://wanago.io/2018/12/17/typescript-express-error-handling-validation/
    > - [x] https://wanago.io/2018/12/24/typescript-express-registering-authenticating-jwt/
    > - [x] https://wanago.io/2018/12/31/mongodb-relationships-documents-typescript-express-tutorial-5/
    > - [x] https://wanago.io/2019/01/07/mongodb-aggregation-basic-data-processing-typescript-express-tutorial-6/
    > - [ ] https://wanago.io/2019/01/14/express-postgres-relational-databases-typeorm/
    > - [ ] https://wanago.io/2019/01/21/typescript-express-tutorial-8-types-of-relationships-with-postgres-and-typeorm/
    > - [ ] https://wanago.io/2019/01/28/typeorm-migrations-postgres/
    > - [ ] https://wanago.io/2019/02/04/typescript-express-testing/
    > - [ ] https://wanago.io/2019/07/22/nodejs-two-factor-authentication/
    > - [ ] https://wanago.io/2019/10/14/typescript-express-ci-cd-pipeline-travis-heroku/
    > - [x] https://wanago.io/2020/02/10/typescript-express-tutorial-13-using-mongoose-virtuals-to-populate-documents/
    > - [x] https://wanago.io/2020/04/20/typescript-express-tutorial-code-optimization-mongoose-lean/
    > - [x] https://wanago.io/2020/04/27/typescript-express-put-vs-patch-mongodb-mongoose/
    > - [x] [How to use async file-based caching or zip-based caching](https://advancedweb.hu/how-to-implement-a-persistent-file-based-cache-in-node-js/)
      > - File based caching is useful when you need the result to survive across reboots. It is very powerful and can be used in conjunction with Async Lazy Initializer design pattern, but it has a drawback: Cache-based errors can survive reboots! So it must be implemented with care
    > - #### Mongoose
    > - [x] https://mongoosejs.com/docs/tutorials/virtuals.html
    > - [x] [https://www.youtube.com/watch?v=7kmttmmlygc](MongoDB blind SQL injection with express and Mongoose)
      > - Blind SQL injection is possible in implementations of NodeJS and express where use input in a REST request is not type-consistent. This happens because of an error in mongoose find function's design, where it allows a key to be either a string (which is normally okay) or an object that might do priviledged operations; This is a form of the confused deputy problem, in which type confusion is contained

- ### MongoDB
  > - [x] https://docs.mongodb.com/manual/reference/operator/aggregation/group/#accumulator-operator

- ### CSS

- ### HTML
  > - [x] https://developer.mozilla.org/pt-BR/docs/Molla/Mobile/Viewport_meta_tag

- ### Python

- ### C


## Computer Science:

## Information Security:
> - [x] [Confused Deputy Problem](https://en.wikipedia.org/wiki/Confused_deputy_problem)
> - [x] [Off-By-One Error/ Memory Corruption](https://en.wikipedia.org/wiki/Off-by-one_error)
> - [x] [Hacking sudoedit](https://www.youtube.com/watch?v=zdzcTh9kUrc) This video is part of the series where liveoverflow hacks into sudoedit, reproducing its vulnerability. In this video, he explains what is the issue: This one I have seen before - An escape character skipping the Nullbytes goes way past where it was supposed to land. This bug doesn't need to be necessarily a 0x5c character (`\`), but could be any character, specially if the code being examined implements a custom protocol. To find bugs like those, you can test the last byte before the end of the input string and fuzz it. I learnt to use AFL in this small series and fuzzed pidgin with it. At the time I messed with AFL, I didn't knew about [preeny](https://github.com/zardus/preeny) and used an ineffective approach that would fuzz pidgin through dbus commands. The problem with that approach was that it became very hard to determine what caused the crash, I didn't know if it was my wrapper to send dbus commands, dbus itself or pidgin receiving the message that caused 5 unique crashes, but after studying more about AFL and why they discourage fuzzing servers and GUI programs that way, I gave up with that approach and started studying more about it, eventually learning another smarter way to do this, by using preeny or altering the source code and wrapping it 
