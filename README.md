# Crema

dotnet core 3 포팅중

실행은 되나 정상적인 기능은 안됨.

## clone repository

```plain
git clone https://github.com/s2quake/crema.git --recursive
```

## Development Environment

### [Microsoft Visual Studio Community 2019](https://visualstudio.microsoft.com/ko/downloads/)

### [Microsoft Visual Studio Code](https://code.visualstudio.com/)

### [.NET Core 3.1](https://dotnet.microsoft.com/download/dotnet-core/3.1)

## Clone and Build (.NET Core 3.1)

```powershell
# clone
git clone https://github.com/s2quake/crema --recursive
# change directory
cd crema
# build
dotnet build ./JSSoft.Crema/crema.sln --framework netcoreapp3.1
```

## Run Server (.NET Core 3.1)

```powershell
# run server
dotnet run --project ./JSSoft.Crema/server/JSSoft.Crema.ApplicationHost --framework netcoreapp3.1
```

## Run Client (.NET Core 3.1)

```powershell
# run server
dotnet run --project ./JSSoft.Crema/client/JSSoft.Crema.ApplicationHost --framework netcoreapp3.1
```

## server - console

![Alt text](./cremaserver.png)

## server - application

![Alt text](./cremaserverApp.png)

## client - application

![Alt text](./crema.png)

## client - Console

![Alt text](./cremaconsole.png)
