FROM mcr.microsoft.com/dotnet/sdk:5.0
SHELL ["pwsh", "-noninteractive", "-command"]
RUN Install-Module Pester -MaximumVersion 5.99.99 -Scope AllUsers -Force;Install-Module -Name PSPackageProject -Force
CMD ["/usr/bin/pwsh", "-nologo"]