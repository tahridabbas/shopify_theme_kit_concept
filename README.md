# shopify_theme_kit_concept
how to we install theme kit or theme tool kit on local environment using command line..
please follow the steps command line by which you can manipulate the theme of your store
step1: first you need to create a app through your store
step2: during creation of app you need to focus on permissions which is called read access,no access and read write access
after this completion you have to move ahead.
step3:after that If you have chocolatey installed you can install Theme Kit by running the following commands.
step4:choco install themekit
step5:if you don't have installed chocolatey you need to insatt first before running step4.
how we install let see
step6:run this below command to install chocolatey
step7:Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
stpe8:after complete process of chocolately installation you need to run below command
step9:choco install themekit
step10:run theme to check how many types of command is there
step11: run below command to download the shopify theme through app api using command line( once you have a theme id for the theme you want to setup on your local machine, you can run:)
step12:theme get --password=[your-api-password] --store=[your-store.myshopify.com] --themeid=[your-theme-id]
