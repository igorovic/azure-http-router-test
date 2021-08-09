# Reproduction steps

- npm install
- npm run start:azure
- call the api at => http://localhost:7071/api/

## The error in terminal

```
[2021-08-09T08:22:08.893Z] (node:2396) UnhandledPromiseRejectionWarning: TypeError: trouter_1.default is not a constructor
[2021-08-09T08:22:08.895Z]     at new AzureHttpRouter (C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\router\azure-http.router.js:12:15)
[2021-08-09T08:22:08.896Z]     at createApp (C:\Users\ig\DEV\azure-http-router-test\dist\src\main.azure.js:8:73)
[2021-08-09T08:22:08.898Z]     at AzureHttpAdapterStatic.<anonymous> (C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\azure-http.adapter.js:24:31)
[2021-08-09T08:22:08.899Z]     at Generator.next (<anonymous>)
[2021-08-09T08:22:08.901Z]     at C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\azure-http.adapter.js:8:71
[2021-08-09T08:22:08.903Z]     at new Promise (<anonymous>)
[2021-08-09T08:22:08.905Z]     at __awaiter (C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\azure-http.adapter.js:4:12)
[2021-08-09T08:22:08.909Z]     at AzureHttpAdapterStatic.createHandler (C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\azure-http.adapter.js:23:16)
[2021-08-09T08:22:08.911Z]     at AzureHttpAdapterStatic.handle (C:\Users\ig\DEV\azure-http-router-test\node_modules\@nestjs\azure-func-http\dist\azure-http.adapter.js:20:14)
[2021-08-09T08:22:08.913Z]     at Object.default_1 [as default] (C:\Users\ig\DEV\azure-http-router-test\dist\main\index.js:6:40)
```
