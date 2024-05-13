1. Install the Erlang VM on windows
2. Install the corresponding Elixir distribution on windows
3. Install asdf to manage elixir versioning
	- Currently this isn't possible on windows, so version management must be done manually. Real bummer.
4. (Optional) Install postgresSQL for windows
5. Install Node.js and Yarn for Phoenix Frontend
6. Install the hex package manager `min local.hex`
	- Enable remote signed packages on windows `Set-ExecutionPolicy RemoteSigned`
7. Installing phoenix `mix archive.install hex phx_new`