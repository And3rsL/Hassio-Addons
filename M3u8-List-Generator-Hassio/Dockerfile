FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS base
WORKDIR /app
EXPOSE 80

COPY /publish .
ENTRYPOINT ["dotnet", "M3UF.dll"]