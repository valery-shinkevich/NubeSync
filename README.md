# NubeSync
NubeSync is a bi-directional offline data sync framework

## Features
* Fast operations based transmission of the changes to the server
* Incremental sync when downloading new and changed records from the server
* Automatic merge conflict resolution (last change wins) on per field basis is performed on the server
* Based on standard technologies (ASP.NET Core, SQLite, REST)
* Can be used in any .NET client app (Xamarin, Blazor, UWP, WPF, ...)
* Suitable for Flutter client apps
* Client side indexes and encryption are supported 
* Server side storage can use all Entity Framework Core compatible storages (e.g. Microsoft SQL, CosmosDB)
* NubeSync can be implemented as a successor to the Azure Mobile App Service offline sync capabilities

## Documentation & Getting Started
See the [Wiki page](https://github.com/stefffdev/NubeSync/wiki) for getting started and have a look at the [samples](https://github.com/stefffdev/NubeSync/tree/master/samples).
