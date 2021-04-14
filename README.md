# readme

## bash

### commands

- `pwd` = print current directory/path
- `cd` = navigate to path
- `ls` = print directory content
- `mv` = move resource to new path
- `rm` = remove resource
- `touch` = create new file
- `cat` = print resource content
- `mkdir` = create new directory

## csharp

### scopes

- `namespace`
- `class, struct, interface, enum`
- `constructor, method, finalizer/destructor`
- `block`

### modifiers

- `static` = singular instance created at application start, can change value at runtime
- `const` = singular instance at application start, cannot change value at runtime
- `readonly` = singular instance at construction, cannot change at runtime after set
- `virtual` = a representative structure that an be used as-is or tranformed for specific use
- `override` = a transformation of a dynamic/virtual structure for specification
- `abstract` = a descriptive strucutre to represent an idea, defining a signature for implementation
- `sealed` = not available for specification (inheritance)
- `new` = allow for specificication on any structure that is not explicity virtual/abstract/sealed

### access modifiers

- `public` = accessible from any assembly (namespace)
- `private` = accessible within its own structure/scope
- `protected` = accessible from any assembly with constraint of inheritance tree/family tree
- `internal` = accessible within the assembly scope
- `internal protected` = use in libraries
- `private protected` = use in libraries

## dotnet

### commands

- `dotnet new`, `dotnet new console`, `dotnet new gitignore`
- `dotnet run` = code execution
- `dotnet build` = code compilation
- `dotnet --help`

## git

### commands

- `git init` = initialize local repository
- `git add <path>` = select resources to track
- `git commit` = save for tracking
- `git log` = print history of commits
- `git status` = current state of repository
- `git remote` = configure remote server
- `git config` = configure user information
- `git --help` = print help menu
- `git push` = sync local server to remote server
- `git pull` = sync remote server to local server
- `git clone` = initialize remote repository to local server
