# Online Map Services in Blazor Maps component

## Overview

This sample demonstrates how to integrate multiple online map service providers using the Syncfusion [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-map) component. The application renders map tiles from [OpenStreetMap (OSM)](https://www.openstreetmap.org/), [Bing Maps](https://www.microsoft.com/en-us/maps), [Mapbox](https://www.mapbox.com/maps), [TomTom](https://www.tomtom.com/en_us/drive/maps-services/maps/), and [Esri](https://www.esri.com/en-us/home) by configuring provider-specific tile URLs within Maps layers. The sample serves as a reference for developers who need to switch between different online map providers while continuing to use a consistent Syncfusion Maps API and user experience. It also highlights how external tile services can be combined with map customizations such as navigation lines, annotations, and additional map layers.

## Key Features

- Demonstrates rendering maps using OpenStreetMap (OSM), Bing Maps, Mapbox, TomTom, and Esri providers.
- Uses the Maps layer `UrlTemplate` configuration to load map tiles from external services.
- Shows how third-party tile services can be displayed within the Syncfusion Maps component.
- Demonstrates provider-specific map rendering while maintaining a unified map interface.
- Supports integration of additional map features such as markers, sublayers, annotations, and navigation lines on top of online maps.
- Requires provider-specific API keys for Bing Maps, Esri, Mapbox, and TomTom services.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework
- Valid API keys for Bing Maps, Esri, Mapbox, and TomTom map services when using those providers

## How to run the project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `OnlineMapService.sln` solution file.
3. Restore all NuGet packages.
4. Set the `OnlineMapService` project as the startup project if required.
5. Add valid provider keys for Bing Maps, Esri, Mapbox, and TomTom in the corresponding `UrlTemplate` configurations used by the sample.
6. Build the solution.
7. Run the application using `Ctrl+F5`.
8. Open the local application URL displayed by ASP.NET Core after startup.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the directory containing `OnlineMapService.csproj`.

```bash
dotnet restore
dotnet run
```

5. Configure the required API keys for applicable map providers.
6. Open the local URL displayed in the terminal after the application starts.


## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to online tile layers and map providers, visit https://blazor.syncfusion.com/documentation/maps/providers
- [Easily Visualize Online Maps in a Blazor Application](https://www.syncfusion.com/blogs/post/easily-visualize-online-maps-in-a-blazor-application.aspx)


## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
