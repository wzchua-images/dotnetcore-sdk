FROM mcr.microsoft.com/dotnet/core/sdk:2.2
#Install OpenJDK 8 jre for sonarscanner
RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y openjdk-8-jre-headless

RUN dotnet tool install --global dotnet-sonarscanner 
ENV PATH="${PATH}:/root/.dotnet/tools"