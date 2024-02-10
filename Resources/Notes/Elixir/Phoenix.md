## Initalizing a Phoenix Project
1.  Loading and installing phoenix dependencies `mix phx.new <name>`

## File structure 
### ._build
When you run the application, build artifacts go here
### .elixir_ls
Setup and maintain elixir language server
### .formatter
Setup and configure `mix formatter` to format code
### mix.exs
This is the project file. This describes how to build the project. Dependencies and configurations are found here
- `mix deps.get` updates these
### assets
Front end oriented files
### config
Controls application specific configuration
### deps
A local copy of dependencies
### priv
Files and scripts not directly related to running your application. Migration files, etc.
### lib
Application code
### test
Where you write tests

### Where do we find what pages are available to be navigated to?
`lib/app_name_web/router.ex`





