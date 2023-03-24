#Specifichiamo l'immagine base da modificare
FROM mcr.microsoft.com/dotnet/aspnet:7.0 AS runtime
#settiamo la working directory all'interno dell'immagine
WORKDIR /app
#copiamo tutto quello che e' presente nella cartella dove sta questo Dockerfile e la copiamo nella cartella "/app" settata sopra
COPY . .
#Lanciamo il comando sulla dll richiesta
ENTRYPOINT ["dotnet", "WebAPI.dll"]
