# D0b0.Plugin.Analytics.ApplicationInsights

## How to install plugin?
In order to install the plugin you need to copy directory `./D0b0.Plugin.Analytics.ApplicationInsights` to directory `./Plugins/` in your nopCommerce project.

## Configuration
### 1. Create an Application Insights resource
1. Sign in to the [Microsoft Azure portal](https://portal.azure.com). (Need to [sign up](https://azure.microsoft.com/pricing/free-trial/)?)
2. Create a new Application Insights resource. (Click **New -> Monitoring + management -> Application Insights**). Select the ASP.NET application type.
3. In your new resource, open the **Essentials** drop-down so that you can copy the Instrumentation Key - you'll need it shortly. 

### 2. Add the instrumentation key. 
Open `appsettings.json` in the project and replace dumy key '11111111-2222-3333-4444-555555555555' with your key.

### 3. Build project
Open nopCommerce solution and build it.

## Links
- https://docs.microsoft.com/en-us/azure/application-insights
- https://github.com/Microsoft/ApplicationInsights-aspnetcore
