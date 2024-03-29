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

### Where are the HTML files stored?
`lib/controllers/name_html/home.html.heex`

### Adding a new Page?
1. Modify the router by adding a new router
2. Add a function to the controller to handle that route
3. Create an html page in the html folder matching the controller name
4. You can pass data to views from within the controller by passing it to the view in the render method
   - Uses the template engine eex
   - You can return JSON by using JSON instead of render
### Limitations
- The templating engine is not as powerful as using something like react
- Liveview is another alternative to keep all of the logic in the backend
### Database integration
- Build a scaffolding for the database
- Build a scaffolded model for a router by running 
	- `mix phx.gen.json Posts <name> Post body:string title:string`
	- The first post is the name of the context (model), Schema describes the structure (second), third (table name)
### Api scope
- Define a new scope under `"/api"`
- Define a pipe_through to pass data through middleware, etc `pipe_through :api`
- You can run migrations from within elixir to update the structure of the database
- Run migrations `mix ecto.migrate`



### Thoughts so far
1. Using elixir allows you to generate a lot of the code automagically which is nice. However, it does require you to understand both the CLI and the code that's generated for you
2. It appears that some basic planning of structure is required, and purely iterative design isn't possible



