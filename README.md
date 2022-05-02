# POC : SignarlR using Webpack Typescript AspNetCore 5

SignalR is a free and open-source software library for Microsoft ASP.NET that allows server code to send asynchronous notifications to client-side web applications. The library includes server-side and client-side JavaScript components. 

This projet is an implementation of SignalR using Visual Studio 2022, Typescript and Webpack.

This is the [official microsoft tutorial](https://docs.microsoft.com/fr-fr/aspnet/core/tutorials/signalr-typescript-webpack?view=aspnetcore-5.0&tabs=visual-studio).

## Prerequisite

- ASP.NET CORE 5
- NodeJS 16 LTS
- Npm 8

## Description

ASP.NET SignalR is a library for ASP.NET developers to add real-time web functionality to their applications. Real-time web functionality is the ability to have server-side code push content to the connected clients as it happens, in real-time.[1]

SignalR takes advantage of several transports, automatically selecting the best available transport given the client's and server's capabilities. SignalR takes advantage of WebSocket, an HTML5 API that enables bi-directional communication between the browser and server. SignalR will use WebSockets under the covers when it's available, and gracefully fall back to other techniques and technologies when it isn't, while the application code remains the same.[2][3]

SignalR also provides a simple, high-level API for doing server-to-client RPC (call JavaScript functions in a client's browser from server-side .NET code) in an ASP.NET application, as well as adding useful hooks for connection management, such as connect/disconnect events, grouping connections, authorization.