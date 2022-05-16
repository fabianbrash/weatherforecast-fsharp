# Accelerator Log

## Options
```json
{
  "applicationName" : "Sample",
  "projectName" : "weatherforecast-fsharp"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.fs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Program.fs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Sample.fsproj matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Startup.fs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.fs matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug appsettings.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md, Sample.fsproj, config/**, catalog/**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.fs didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug Program.fs didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, Sample.fsproj, config/**, catalog/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Sample.fsproj matched [README.md, Sample.fsproj, config/**, catalog/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Startup.fs didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.fs didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, Sample.fsproj, config/**, catalog/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, Sample.fsproj, config/**, catalog/**] -> excluded
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [README.md, Sample.fsproj, config/**, catalog/**] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[2] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0].<combo>.transformations[2].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [Sample->Sample]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [Sample.fsproj]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.fs didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Program.fs didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Sample.fsproj matched [Sample.fsproj] -> included
┃ ┃ ┃ ┃ ┃ Debug Startup.fs didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.fs didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml didn't match [Sample.fsproj] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (RewritePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'Sample.fsproj' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.fsproj, folder=null, filename=Sample.fsproj, g0=Sample.fsproj, g1=null, g2=Sample.fsproj, g3=Sample.fsproj, g4=.fsproj} and was rewritten to 'Sample.fsproj'
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md, config/*.yaml, catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Controllers/WeatherForecastController.fs didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Program.fs didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Properties/launchSettings.json didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md, config/*.yaml, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug Sample.fsproj didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Startup.fs didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug WeatherForecast.fs didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug appsettings.Development.json didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug appsettings.json didn't match [README.md, config/*.yaml, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [README.md, config/*.yaml, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [README.md, config/*.yaml, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [sample-app->weatherforecast-fsha...(truncated)]
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
