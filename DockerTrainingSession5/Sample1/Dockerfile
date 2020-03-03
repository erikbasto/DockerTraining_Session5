#Sample project using a manual dockerfile and file publishing

FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-nanoserver-1903 
COPY ./bin/Release/netcoreapp3.1/publish/ app/
ENTRYPOINT ["dotnet", "app/Sample1.dll"]