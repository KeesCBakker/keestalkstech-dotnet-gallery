# KeesTalksTech Gallery Repository

This repository containers a lot of code samples for articles on my blog.
It is easier to keep the code up to date when all of the items are grouped.

## 1. Dependency injection (with IOptions) in Console Apps in .NET

When you are used to building web applications, you kind of get hooked to the 
ease of Dependency Injection (DI) and the way settings can be specified in a 
JSON file and accessed through DI (``IOptions<T>``). It's only logical to 
want the same features in your Console app.

- <a href="1.dependency-injection-with-ioptions-in-console-apps">1.dependency-injection-with-ioptions-in-console-apps</a>
- <a href="1.dependency-injection-with-ioptions-in-console-apps/README.md">README.md</a>
- <a href="1.dependency-injection-with-ioptions-in-console-apps/ConsoleApp.sln">ConsoleApp.sln</a>
- <a href="https://keestalkstech.com/2018/04/dependency-injection-with-ioptions-in-console-apps-in-dotnet/">Dependency injection (with IOptions) in Console Apps in .NET</a>


## 2. Simple JWT Access Policies for API security in .NET

Services can use their private key to communicate with our service.
We can configure the access for each issuer using standard .NET claims.

- <a href="2.simple-jwt-access-policies-for-api-security-in-net">2.simple-jwt-access-policies-for-api-security-in-net</a>
- <a href="2.simple-jwt-access-policies-for-api-security-in-net/README.md">README.md</a>
- <a href="2.simple-jwt-access-policies-for-api-security-in-net/JwtSecuredApi.sln">JwtSecuredApi.sln</a>
- <a href="https://keestalkstech.com/2024/11/simple-jwt-access-policies-for-api-security-in-net/">Simple JWT Access Policies for API security in .NET</a>

## 3. Options Injection

Options themselves can be collections as well. This
project shows how to use a `Dictionary<string, string>` and a
`List<string>` as base classes for options. Both are supported
by default.

- <a href="3.option-injection">3.option-injection</a>
- <a href="3.option-injection/README.md">README.md</a>
- <a href="3.option-injection/Ktt.OptionsApi.sln">Ktt.OptionsApi.sln</a>

## 4. .NET Console Application with injectable commands (System.CommandLine preview)

How to use `System.CommandLine` to build a CLI with commands and 
dependency injection.

- <a href="4.command-line-di-poc">4.command-line-di-poc</a>
- <a href="4.command-line-di-poc/README.md">README.md</a>
- <a href="4.command-line-di-poc/Ktt.MyCli.sln">Ktt.MyCli.sln</a>
