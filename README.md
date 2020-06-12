# BlazorAuth

A sample showing how to add ASP.NET Core Identity auth options to the basic Blazor app.

## Features

- Adds ASP.NET Core Identity with Default UI for login, etc.
- Demonstrates use of `AuthorizeView`
- Demonstrates use of `CascadingAuthenticationState` in `App.razor`
- Demonstrates adding role support to app in `Startup.cs`
- Demonstrates use of Claims
- Demonstrates using Claims to drive Policies
- Use of [Authorize] attribute in Razor Server pages

## Related Docs

- [ASP.NET Core Blazor authentication and authorization](https://docs.microsoft.com/en-us/aspnet/core/security/blazor/?view=aspnetcore-3.1)
- [Role-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/roles?view=aspnetcore-3.1)
- [Claims-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/claims?view=aspnetcore-3.1)

## Related Stack Overflow Questions

- [Why is ASP.NET Core Identity User.IsInRole always returns false](https://stackoverflow.com/questions/53271496/asp-net-core-identity-2-user-isinrole-always-returns-false)
- [Persisting Claims across requests](https://stackoverflow.com/questions/25292137/persisting-claims-across-requests)
- [How can I get a list of policies from asp.net core auth](https://stackoverflow.com/questions/42811753/how-can-i-get-the-list-of-policies-from-asp-net-core-authentication)

## Other Resources

- [Accessing and Extending Authorization Claims in ASP.NET Core and Blazor](https://visualstudiomagazine.com/articles/2019/11/01/authorization-claims.aspx)
- [Custom authorisation policies and requirements in ASP.NET Core](https://andrewlock.net/custom-authorisation-policies-and-requirements-in-asp-net-core/)
