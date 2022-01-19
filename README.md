<h1 align="center">
  <img src="./azure-data-lake.png" width="900px"/><br/><br/>
  Azure Data Lake ETL Pipeline
</h1>
<p align="center">This is a <b>Big Data</b> Enterprise ETL Pipeline desinged for <b>Azure Data Lake</b></p>

<br/>
<hr/>

## <p align="center">⚡️ How it Works</p>

<br/>
<p>
<b>For Batch processing:</b>

<ul>
<li> Azure Data Factory ingests data from multiple sources. </li>
<li> The data is processed using an Azure data processing solution such as Azure DataBricks or Azure HDInsight. </li>
<li> The Processed data is stored in Azure Dedicated SQL Pool (formerly Azure SQL DataWarehouse). </li>
<li> The data is ready for consumption/presentation. </li>
<li> The data can also be used in more advanced ML Model training. </li>
</ul>


<b>For Real Time processing:</b>

<ul>
<li> Real time data is ingested by Azure Event Hub. </li>
<li> This data is sent to Azure Stream Analytics for processing. </li>
<li> The processed data is ready for consumption/presentation. </li>
<li> The data can also be sent to Azure Data Lake for further processing. </li>
</ul>

</p>

<br/>
<hr/>

## <p align="center"> 📄 Details</p>

### 🛠 Services Used

<br/> 

###### `Data Ingestion`


|                                                        |        Service       |                  Description                                                                                                                                                                                                           |
| ------------------------------------------------------ | -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/Data-Factory.svg" width="50px" />   | `Azure Data Factory` |  [Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/) is Azure's cloud ETL service for scale-out serverless data integration and data transformation.                                                            |
|  <img src="./icons/IoT-Hub.svg" width="50px" />        |       `IOT Hub`      |  [Azure IOT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) is Microsoft's Internet of Things connector to the cloud.                                                                                                        |
|  <img src="./icons/Logic-Apps.svg" width="50px" />     |     `Logic Apps`     |  [Azure Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview) is a cloud-based platform for creating and running automated workflows that integrate your apps, data, services, and systems                |
|  <img src="./icons/Function-Apps.svg" width="50px" />  |   `Function Apps`    |  [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview) is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure.  |

<br/>

###### `Data Lake (Raw Data)`

|                                                                |          Service        |                  Description                                                                                                                                                                                       |
| -------------------------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/Data-Lake-Store-Gen1.svg" width="50px" />   | `Azure Data Lake Store` |  [Azure Data Lake Storage](https://azure.microsoft.com/en-us/services/storage/data-lake-storage/#documentation) is a secure cloud platform that provides scalable, cost-effective storage for big data analytics.  |


<br/>

###### `Processing`

|                                                                |          Service            |                  Description                                                                                                                                                                      |
| -------------------------------------------------------------- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/Azure-Databricks.svg" width="50px" />       | `Azure DataBricks`          |  [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks) is a data analytics platform optimized for the Microsoft Azure cloud services platform. |
|  <img src="./icons/HD-Insight-Clusters.svg" width="50px" />    | `Azure HD Insight`          |  [Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-overview) is a managed, full-spectrum, open-source analytics service in the cloud for enterprises.                  |
|                                                                | `Azure Data Lake Analytics` |  [Azure Data Lake Analytics](https://docs.microsoft.com/en-us/azure/data-lake-analytics/) allows you to run big data analysis jobs that scale to massive data sets.                               |
             
<br/>

###### `Data Warehouse (Processed Data)`

|                                                                |          Service              |                  Description                                                                                                                                                                                                                                             |
| -------------------------------------------------------------- | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/SQL-Elastic-Pools.svg" width="50px" />      | `Azure Dedicated SQL Pool`    |                  [Azure Dedicated SQL pool](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-overview-what-is) (formerly SQL DW) refers to the enterprise data warehousing features that are available in Azure Synapse    |
|  <img src="./icons/Azure-Synapse-Analytics.svg" width="50px" />| `Azure Synapse Analytics`     |                  [Azure Synapse Analytics](https://docs.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-overview-what-is) is an analytics service that brings together enterprise data warehousing and Big Data analytics.             |


<br/>

###### `Advanced Machine Learning`

|                                                                   |          Service                |                  Description                                                                                                                                                                                                                                       |
| ----------------------------------------------------------------- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/Machine-Learning-Studio.svg" width="50px" />   | `Azure Machine Learning Studio` |     [Azure Machine Learning Studio](https://docs.microsoft.com/en-us/azure/machine-learning/overview-what-is-machine-learning-studio) is a GUI-based integrated development environment for constructing and operationalizing Machine Learning workflow on Azure.  |

<br/>

###### `Messaging`


|                                                        |        Service       |                  Description                                                                                                                                                                                       |
| ------------------------------------------------------ | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/Event-Hubs.svg" width="50px" />     | `Azure Event Hub`    |   [Azure Event Hub](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-about) is a big data streaming platform and event ingestion service. It can receive and process millions of events per second.    |

<br/>

###### `Streaming`


|                                                               |        Service           |                  Description                                                                                                                                                                                                                                                                        |
| ------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/Stream-Analytics-Jobs.svg" width="50px" /> | `Azure Stream Analytics` |    [Azure Stream](https://docs.microsoft.com/en-us/azure/stream-analytics/stream-analytics-introduction) Analytics is a real-time analytics and complex event-processing engine that is designed to analyze and process high volumes of fast streaming data from multiple sources simultaneously.   |

<br/>

###### `Authentication, Authorization & Security`


|                                                                 |        Service           |                  Description                                                                                                                                                                                                                                       |
| --------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/Key-Vaults.svg" width="50px" />              | `Azure Key Vault`        |    [Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts) is a cloud service for securely storing and accessing secrets.                                                                                                       |
|  <img src="./icons/Policy.svg" width="50px" />                  | `Azure Policy`           |    [Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/overview) helps to enforce organizational standards and to assess compliance at-scale.                                                                                                  |
|  <img src="./icons/Azure-Active-Directory.svg" width="50px" />  | `Azure Active Directory` |    [Azure Active](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis) Directory (Azure AD) is Microsoft’s cloud-based identity and access management service, which helps your employees sign in and access resources.   |
|  <img src="./icons/Azure-Defender.svg" width="50px" />         | `Microsoft Defender for Cloud`  |    [Microsoft Defender for Cloud](https://docs.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction) is a tool for security posture management and threat protection.                                                                |

<br/>

###### `Monitoring`


|                                                               |        Service           |                  Description                                                                                                                                             |
| ------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/SAP-Azure-Monitor.svg" width="50px" />     | `Azure Monitor`          |   [Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) helps you maximize the availability and performance of your applications and services   |

<br/>

###### `Provisioning`


|                                                               |        Service                     |                  Description                                                                                                                                                                                        |
| ------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       | `Azure Resource Manager Templates` |   [ARM templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview) are a form of infrastructure as code, a concept where you define the infrastructure that needs to be deployed.  |

<br/>
<hr/>



### 💽 Accepted Data Input Types 

<br/>


###### `Data Input Types`


|                                                           |        Service                     |                  Description                                                                                                                                                                                                                                                                                                                                                        |
| --------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/spreadsheet.svg" width="50px" />       |         `Structured Data`          |    [Structured data](https://www.ibm.com/cloud/blog/structured-vs-unstructured-data), typically categorized as quantitative data — is highly organized and easily decipherable by machine learning algorithms. Structured Query Language (SQL) is the programming language used to manage structured data                                                                           |
|  <img src="./icons/binary-file.svg" width="50px" />       |        `Unstructured Data`         |    [Unstructured data](https://www.ibm.com/cloud/blog/structured-vs-unstructured-data), typically categorized as qualitative data, cannot be processed and analyzed via conventional data tools and methods. Since unstructured data does not have a predefined data model, it is best managed in non-relational (NoSQL) databases or data lakes (in its raw form).                 |
|  <img src="./icons/xml.svg" width="50px" height="50px"/>  |      `Semi-Structured Data`        |    [Semi-structured data](https://en.wikipedia.org/wiki/Semi-structured_data) is a form of structured data that does not obey the tabular structure of data models associated with relational databases or other forms of data tables, but nonetheless contains tags or other markers to separate semantic elements and enforce hierarchies of records and fields within the data.  |

<br/>
<hr/>



### 🔍 Supported Analysis Types

<br/>

###### `Analysis Types`


|                                                               |        Service                     |                  Description                                                                                                                                                                     |
| ------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  <img src="./icons/HD-Insight-Clusters.svg" width="50px" />   |         `Azure HDInsight`          |                  Azure HDInsight, supports multiple open-source frameworks such as Hadoop, Apache Spark, Apache Hive, LLAP, Apache Kafka, Apache Storm, R, and more, in your Azure environment.  |
|  <img src="./icons/Azure-Databricks.svg" width="50px" />      |        `Azure DataBricks`          |                  Azure DataBricks supports multiple open source frameworks such as Apache Spark, and Apache Kafka. It also enables collaborative work for teams.                                 |


<br/>
<hr/>


### 🔗 Networking Services Used

<br/>

###### `Networking`


|                                                               |        Service                      |                  Description                                                                                                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  <img src="./icons/Virtual-Networks.svg" width="50px" />      |          `Azure VNET`               |    [Azure Virtual Network (VNet)](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview) is the fundamental building block for your private network in Azure. VNet enables many types of Azure resources, such as Azure Virtual Machines (VM), to securely communicate with each other, the internet, and on-premises networks.    |
|  <img src="./icons/Private-Link.svg" width="50px" />          |      `Azure Private DNS`            |    [Azure Private DNS](https://docs.microsoft.com/en-us/azure/dns/private-dns-overview) provides a reliable and secure DNS service for your virtual network.                                                                                                                                                                                                  |



## <p align="center">✌️ Info</p>


Created by [Brave Okafor](https://github.com/braveokafor) for [Tynes.science](https://tynes.science/).
