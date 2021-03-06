# How to access Azure Machine Learning Studio

Azure Machine Learning Studio is an Azure resources, and as such they are defined within a resource group in an Azure subscription, along with other related Azure resources that are required to support the workspace

![mlresources](../Images/azure-machine-learning-resources.png)

The Azure resources created alongside studio include:

* A storage account - used to store files used by the workspace as well as data for experiments and model training.
* An Application Insights instance, used to monitor predictive services in the workspace.
* An Azure Key Vault instance, used to manage secrets such as authentication keys and credentials used by the workspace.
* A container registry, created as-needed to manage containers for deployed models.

## Connect and explore Azure Machine Learning Studio

You can manage some studio assets in the Azure portal, but for data scientists, this tool contains lots of irrelevant information and links that relate to managing general Azure resources. Azure Machine Learning studio provides a dedicated web portal for working with your studio.
There are 2 options while connecting via web portal:
* Option 1 - Accessing Azure Machine Learning Studio through Azure Portal
* Option 2 - Accessing Azure Machine Learning Studio diretly from Azure ML Studio web link

The next steps will show, for each option, how the user can connect:

**Option 1 - Accessing Azure Machine Learning Studio through Azure Portal**

1. Access Azure Portal using the following: https://portal.azure.com/#home

![azportal](../Images/azure-portal.PNG)

2. If your browser didn't saved your connection details you will be prompted to fill with your credentials.

![azportalcredentials](../Images/azure-login-screen.PNG)

3. Once in Azure portal, on the top search option write Subscriptions and press enter. Then select the resource Subscriptions.

![subscriptionssearch](../Images/azure-subscription-search.PNG)

4. Select the subscription you need to work on. In order to see all subscriptions your user has access to please unckeck the option: _Show only subscriptions selected in the global subscription filter_

![subscriptions](../Images/Subscriptions%20Azure.PNG)

5. Open the resource group your studio is attached to.

![rg](../Images/resource-groups.PNG)

6. Click on the Azure Machine Learning Studio resource you want to work.

![resource](../Images/MachineLearning.PNG)

7. Click on _Open Studio_.

![openstudio](../Images/LauchStudio.PNG)

8. You will be redirected to the Azure Machine Learning studio interface - this is where you can all the studio assets.

![studionotoggle](../Images/ML%20Studio%20-%20no%20toogle.PNG)

9. In Azure Machine Learning studio, toggle the ☰ icon at the top left to show and hide the various pages in the interface. You can use these pages to manage the resources in your studio.

![studiotoggle](../Images/ML%20Studio.PNG)
 
 **Note:** Once you start using the resource, it will show up in the Azure Home Page recent resources. This will mean that you can skip steps 2 to 5 and only do 1, 6, 7, 8, and 9.
 
 ![recent](../Images/Recent_Resources.PNG)
 

**Option 2 - Accessing Azure Machine Learning Studio diretly from Azure ML Studio web link**

1. In a browser tab, open https://ml.azure.com. 

![directlink](../Images/directlink.PNG)

2. If prompted, sign in using your Microsoft account. 

![azportalcredentials](../Images/azure-login-screen.PNG)

3. Select your Azure subscription and workspace.

![azdirectcredentials](../Images/directsignincredentias.PNG)

4. You will be redirected to the Azure Machine Learning studio interface - this is where you can all the studio assets.

![studionotoggle](../Images/ML%20Studio%20-%20no%20toogle.PNG)

5. In Azure Machine Learning studio, toggle the ☰ icon at the top left to show and hide the various pages in the interface. You can use these pages to manage the resources in your studio.

![studiotoggle](../Images/ML%20Studio.PNG)
