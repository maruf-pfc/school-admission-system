# school-admission-system

## Requirements

- .NET 10 SDK
- Node.js 22.12+ (or 20.19+) and npm

## Server

```sh
dotnet run --project server/SchoolAdmission.Api.csproj --launch-profile http
```

The ASP.NET Core Web API runs at http://localhost:5030.
The template endpoint is `GET /weatherforecast`.

## Client

```sh
cd client
npm install
npm run dev
```

The React 19 + TypeScript app uses Vite and runs at http://localhost:5173.

## Build checks

```sh
dotnet build server/SchoolAdmission.Api.csproj
npm --prefix client run build
npm --prefix client run lint
```
