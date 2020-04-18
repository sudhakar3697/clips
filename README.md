# Awesome Web Technology

#### General (Refer the Computer Science section also)

* Internet (IP, DNS, Proxy, domain)
* World Wide Web
* Client-Server Architecture vs Peer-Peer (P2P)
* Web Page vs Website vs Web Server vs Web browser
* Static Websites vs Dynamic Websites
* HTTP/S Protocol (Request Methods, Headers, Cache, Cookies, Compression, CORS, CSP, Response codes), FTP.
* Browsers (Rendering Engines-Blik, Gecko, Webkit, JavaScript Engines-V8, SpiderMonkey, JavascriptCore)
* Browser Search Engines (Google)
* Character Encodings (UTF, ASCII)
* Licenses (Open Source vs Closed Source, CC, MIT, Apache, GPL, LGPL)
* [Semantic Versioning](https://semver.org/)
* UI/UX (Prototype/ Wireframes)
* API
* Web Standards (W3C, WHATWG, ECMAScript, TC39)
* Internationalization(i18n), Localization
* [Polyfill](https://developer.mozilla.org/en-US/docs/Glossary/Polyfill)
* Environment Variables
* Regular Expressions
* Splash screen
* Input validation
* [12 Factors](https://en.wikipedia.org/wiki/Twelve-Factor_App_methodology)
* Data exchange formats (JSON, XML, Protobuf (Protocol Buffers by Google))
* CDN (Content Delivery Network)

#### [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* HTML5, Semantics, Accessibility(A11y)
* [Vector graphics to the Web (SVG)](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web)
* [Document structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

#### [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling (UI/UX) 
* CSS3, Responsive Web Design (Media Queries, Relative units), Animations, UI-Lazy loading
* CSS Box model, Grid, Flexbox
##### CSS Pre-processors (SASS)
##### CSS Frameworks/Libraries
* [Bootstrap](https://getbootstrap.com/)
* [Ant Design](https://ant.design/)
* [Tailwind CSS](https://tailwindcss.com/)
##### CSS Architecture (BEM)

#### JavaScript
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* Module system (CommonJS vs AMD vs UMD vs ESM)
* ESNext (ECMAScript - Rest/Spread, Destructuring, Template Literals, let/const, for-await, for-of)
* script async vs defer
* Async programming (Callbacks, Promises, Async/Await, Error handling)
* OOP (Objects, Prototypes, Classes)
* Understanding functions, context and binding in JavaScript
* Events

#### Web/Browser APIs (DOM, BOM)
* DOM Manipulation
* Device APIs
* Communication APIs
* Data management APIs
* Fetch
* AJAX (XMLHttpRequest)
* Cookies vs Sessions
* Intersection Observer
* WebXR, WebUSB, WebBluetooth, WebAuth, Creds, Native FS, Share)
* Graphics (2D (Canvas, SVG), 3D (WebGL), Video/Audio, WebRTC)

#### Vanilla JS vs. jQuery vs. Modern Frontend Frameworks
* DOM vs virtual DOM vs shadow DOM
* JSX

#### Web Components (HTML Templates, Custom elements, Shadow DOM)

#### Front End Frameworks (SPA)
* [React](https://reactjs.org/)
* [Svelte](https://svelte.dev/) or Angular or Vue.

#### CSS in JS
* Styles components
* CSS modules

#### State management
* [Redux](https://redux.js.org/)

#### Router

#### JavaScript Flavors, Polyfills, Transpilers, Compilers
* [TypeScript](https://www.typescriptlang.org/)
* [Babel](https://babeljs.io/)

### Progressive Web Apps 
* App shell
* Latest Web APIs (Refer the Web/Browser API section)
* Server-Sent Events (SSE) 
* Web sockets 
* Service workers (Workbox)
* Push notifications
* WebAPK, Trusted Web Activity (TWA)
* [Single Page Apps (SPA) vs MPA (traditional)](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/choose-between-traditional-web-and-single-page-apps)
* [CSR / SSR (Next.js, sapper) / Hydration, Pre-Rendering](https://www.toptal.com/front-end/client-side-vs-server-side-pre-rendering)

### JAMStack (Static site generator,..)
* GatsbyJS

#### [WebAssembly](https://webassembly.org/)
* WASM
* WASI (Lucet, wasmer, wasmtime), https://bytecodealliance.org

#### Module bundler, Minification, Obfuscation
* [Webpack](https://webpack.js.org/)

#### Package Manager
* [npm](https://www.npmjs.com/)

#### Task runner 
* [npm-scripts](https://docs.npmjs.com/misc/scripts)

#### Linter
* [ESLint](https://eslint.org/)

#### Formatter
* [Prettier](https://prettier.io/)

<hr/>

#### Server Side Languages
* [Node.js](https://nodejs.org/) (Event Loop, Modules, Native node modules (N-API))
* [Deno](https://deno.land/)

### Back End Frameworks
* [Express.js](https://expressjs.com/) (Middlewares, Sessions, Streaming the response from Node.js Server)

#### Relational DB (SQL)
* [PostgreSQL](https://www.postgresql.org/)
* [SQLite](https://www.sqlite.org/index.html)

#### ORM ([Sequelize](https://sequelize.org/)) & Query builders ([Knex](http://knexjs.org/))

#### NoSQL DB
* [MongoDB](https://www.mongodb.com/) & MongoDB Atlas

#### Graph DB
* dgraph or Neo4j

#### Caching (Server-side)
* Redis, MemCached

#### Serverless
* Functions (AWS Lambda/ Azure functions/ Google Cloud functions)
* Databases (Firebase cloud firestore, Amazon aurora, Azure Data lake, Google cloud datastore)

#### API
* REST API
* [GraphQL](https://graphql.org/)
* [JSON API](https://jsonapi.org/) ❌

#### API Clients
* [Curl](https://curl.haxx.se/)
* [Insomnia](https://insomnia.rest/)
* [Postman](https://www.getpostman.com/)

#### Authentication / Authorization
* Basic
* Token Auth
* JWT
* OAuth 2.0
* OpenID Connect
* Single Sign-On (Kerberos, SAML)
* Certificates

#### Message Brokers
* RabbitMQ or Kafka

#### Search Engine
* ElasticSearch

##### Search Engine Optimization (SEO)
* SEO Friendly URLs (Slug)

#### Test (Unit vs functional vs integration) & Optimization
* Jest, Enzyme, Cypress
* Lighthouse, DevTools

#### Documentation
* Markdown
* [JSDoc](https://github.com/jsdoc/jsdoc)
* Swagger (https://app.swaggerhub.com/)

#### Security
* https://infosec.mozilla.org/guidelines/web_security
* [OWASP](https://cheatsheetseries.owasp.org/cheatsheets/Index.html) (SQL injection, XSS, Broken auth/session management, CSRF)
* HTTPS, Transport Layer Security (TLS)
* Content-Security-Policy (CSP)
* CORS
* Subresource Integrity (SRI)
* Hash passwords (~~MD5~~, ~~SHA-1~~, Use Argon2, PBKDF2, scrypt or bcrypt)
* [Hashing vs Encryption vs Encoding](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)

#### Performance (Loading vs Rendering)
* Measuring performance (RAIL)
* Tools (Lighthouse, WebPageTest, PageSpeed Insights, Chrome dev tools) 
* Code splitting, Lazy loading
* instant loading with the PRPL pattern

#### Deployment (Hosting)

* Source code protection
* pkg
* Docker, Kubernetes, Unikernels
* Web Servers (Apache, Nginx)
* https (letsencrypt)
* netlify, Github pages
* GIT
* Tunnels (Ngrok)
* Proxy, VPN
* CDN
* CMS
* Logging (morgan, winston)
* Load balancing
* Backups

#### Developer Tools & Utilities, Code editor vs IDE
* [VS Code](https://code.visualstudio.com/)
* [nodemon](https://nodemon.io/)
* [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
* [Node.js Debugging](https://nodejs.org/de/docs/guides/debugging-getting-started/)
* [Node.js profiling](https://nodejs.org/en/docs/guides/simple-profiling/)

#### Programming Paradigms (OOP, functional, reactive)
* OOP (Polymorphism, Inheritance, Encapsulation, Abstraction, Aggregation and Composition)

#### Architectural styles (Monolith, Microservices, Serverless, Event Sourcing, CQRS)

#### Design patterns (Creational vs Structural vs Behavioral)

#### Architectural patterns (MVC, MVVM, MVP, Flux, Redux)

#### Design principles (SOLID, YAGNI, KISS, DIY, SSOT, SoC, TDA, DRY)

#### Browser Extensions

#### Misc

* [Web Scrapping](https://pusher.com/tutorials/web-scraper-node)
* [Bot](https://en.wikipedia.org/wiki/Internet_bot)
* [Web Hooks](https://en.wikipedia.org/wiki/Webhook)
* [Web bundle](https://web.dev/web-bundles/)
* [gRPC](https://grpc.io/)
* [QUIC](https://en.wikipedia.org/wiki/QUIC)
* HTTP/2, HTTP/3

#### Mobile App Development using Web Technologies
* [React Native](https://facebook.github.io/react-native/). For alternatives [ReactNative-alternatives](https://github.com/sudhakar3697/ReactNative-alternatives)

#### Desktop App Development using Web Technologies
* [electron](https://electronjs.org/). For alternatives [electron-alternatives](https://github.com/sudhakar3697/electron-alternatives)

#### [Developing Games](https://wiki.developer.mozilla.org/en-US/docs/Games)

#### Computer Science
* [Map of Computer Science](https://www.youtube.com/watch?v=SzJ46YA_RaA)
* Programming (Binary, Pointers, Dynamic memory allocation, Memory leak, Garbage collection, Recursion, Concurreny, Parallelism, Multi-threading, Asynchronous, Compile vs interpret vs transpile, JIT, AOT, Exception Handling )
* Software Engineering (SDLC, UML, Blackbox vs Whitebox Testing)
* Operating Systems (Boot process, System Calls, Process, Threads, CPU Scheduling, IPC, Concurrency, Synchronization, Deadlock, Memory management, Disk management, File systems)
* Database Systems (ER model, Normalization, Indexing, Query Optimization,Transactions, ACID, Replication, Sharding)
* Computer Networks, Data Communication (OSI Layer, ISP) & Informaion Security (cryptography- encryption, Hash, TLS, Digital signatures,certificates, Firewalls)
* Computer Organization & Architecture, Digital electronics (Combinational vs Sequential circuits), Microprocessors (ASM), Microcontrollers (Memory hierarchy, Number System)
* Data Science (Big data, Artificial Intelligence/Machine Learning)
* Data Structures
* Algorithms (Searching, Sorting, Hashing)
* Algorithm Design Techniques (Greedy, Divide & Conquery, Dynamic programming)
* Asymptotic worst case time and space complexity analysis
* Theory of Computation, Compiler design (Optional)
* Distributed Systems
* Cloud Computing & Virtualization
* Internet of Things (Optional)
* Mathematics, Statistics (As applicable to CS)

#### References
* [roadmap.sh](https://roadmap.sh)
* [Front-end Masters](https://frontendmasters.com/books/front-end-handbook/2019/)
* [web-skills](https://andreasbm.github.io/web-skills/?compact)
