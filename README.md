# DIDemo
This is a sample web api project used to study .Net Core DI Lifetimes

The web api has 3 api methods

1) Singleton/GetSingletonMessage
2) Transient/GetTransienMessage
3) Scoped/GetScopedMessage

The simple logic is to display datetime when the service was initialized on each request. Singleton and Transient lifetimes can be tested directly via api calls. Scoped lifetime can be studied by using the .net core console, since two different service requirements, one in the middle and one in api method call, write service instatiation information as a log in the console.
