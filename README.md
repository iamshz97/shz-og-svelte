# shz-svelte-og

Prerequisites

1. [Install Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=windows%2Cisolated-process%2Cnode-v4%2Cpython-v2%2Chttp-trigger%2Ccontainer-apps&pivots=programming-language-csharp])
2. Node v18.20.3

# To run the project via swa cli

`npm run build && xcopy /E /I "function-configs" ".\build\server" && swa start`

# To run the project via npm

`npm run dev`
