
# Environments en ASP.NET Core {#environments-en-aspnet-core  data-source-line="247"}

Valores más comunes:

- `Development`
- `Staging`
- `Production`

Se leen desde:

- Variable de entorno `ASPNETCORE_ENVIRONMENT`
- `launchSettings.json`
- Docker / docker-compose

## Métodos de ayuda {#métodos-de-ayuda  data-source-line="261"}

- `env.IsDevelopment()`
- `env.IsStaging()`
- `env.IsProduction()`

``` {data-source-line="267"}