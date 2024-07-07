- Checkout this repo
- switch to branch `test-2`
- run `npx storybook@next init --skip-install`

And you will get this error:

```
Error: Cannot find @storybook\svelte\package.json, Error: Cannot find module '@storybook\svelte\package.json'
Require stack:
- C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs
- C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\bin\index.cjs
    at Module._resolveFilename (node:internal/modules/cjs/loader:1048:15)
    at Function.resolve (node:internal/modules/helpers:136:19)      
    at getRendererDir (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:60:11624)  
    at templatePath (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:2146)     
    at copyTemplateFiles (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:3340)
    at async baseGenerator (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:108:782)
    at async generator15 (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:133:3110)
    at async installStorybook (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:145:4887)
    at async doInitiate (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:155:894) 
    at async withTelemetry (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\@storybook\core\dist\core-server\index.cjs:188662:12)

TypeError: (0 , import_get_npm_tarball_url.default) is not a function
    at resolveUsingBranchInstall (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:60:11070)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async getRendererDir (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:60:11763)
    at async templatePath (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:2140)
    at async copyTemplateFiles (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:3334)
    at async baseGenerator (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:108:782)
    at async generator15 (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:133:3110)
    at async installStorybook (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:145:4887)
    at async doInitiate (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:155:894) 
    at async withTelemetry (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\@storybook\core\dist\core-server\index.cjs:188662:12)
    at getRendererDir (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:60:11916)  
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async templatePath (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:2140)
    at async copyTemplateFiles (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:62:3334)
    at async baseGenerator (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:108:782)
    at async generator15 (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:133:3110)
    at async installStorybook (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:145:4887)
    at async doInitiate (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:155:894) 
    at async withTelemetry (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\@storybook\core\dist\core-server\index.cjs:188662:12)
    at async initiate (C:\Users\manue\AppData\Local\npm-cache\_npx\eb8bf615e50a412a\node_modules\storybook\dist\generate.cjs:180:214) 
```
