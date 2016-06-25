# cfaspnet
Push a sample demo .NET code to cloud foundry

# Pre-requisites
Cloud Foundry cli installed
Access to Cloud Foundry service

# Step 1
git clone https://github.com/kdiwakarsh/cfaspnet.git

# Step 2
cd cfaspnet

# Step 3

cf push <app_name> -b https://github.com/cloudfoundry-community/dotnet-core-buildpack.git

Replace <app_name> with a appname.

# Step 4

Browse the app. Browser should show 

Hello from ASP.NET core!




