```markdown
# Uso de appsettings.*.json por entorno {#uso-de-appsettingsjson-por-entorno  data-source-line="224"}

ASP.NET Core carga la configuración así:

1. `appsettings.json` (base)
2. `appsettings.{Environment}.json` (ej: `appsettings.Development.json`)
3. Variables de entorno

Lo específico del entorno sobrescribe lo general.

## Secciones típicas {#secciones-típicas  data-source-line="234"}

- `Logging`
- `ConnectionStrings`
- Configuración custom, por ejemplo `CustomLogging`, `FeatureFlags`, etc.

``` {data-source-line="240"}

_(Puedes complementar con lo que tú ya tengas documentado.)_