<h1 align="center">
  <img src="./azure-data-lake.png" width="900px"/><br/><br/>
  Azure Data Lake
</h1>
<p align="center">This is a <b>Big Data</b> pipeline desinged for <b>Azure Data Lake</b></p>

<br/>
<hr/>

## <p align="center">⚡️ How it Works</p>

<br/>
<p align="center">
First of all, install the latest versions of [Docker](https://docs.docker.com/engine/install/) and install [Docker-Compose](https://docs.docker.com/compose/install/).  

</p>

<br/>

## <p align="center">✌️ Details</p>

### ⚙️ Services Used

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
|  <img src="./icons/Data-Lake-Store-Gen1.svg" width="50px" />   | `Azure DataBricks`          |  [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks) is a data analytics platform optimized for the Microsoft Azure cloud services platform. |
|  <img src="./icons/HD-Insight-Clusters.svg" width="50px" />    | `Azure HD Insight`          |  [Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-overview) is a managed, full-spectrum, open-source analytics service in the cloud for enterprises.                  |
|                                                                | `Azure Data Lake Analytics` |  [Azure Data Lake Analytics](https://docs.microsoft.com/en-us/azure/data-lake-analytics/) allows you to run big data analysis jobs that scale to massive data sets.                               |
             
<br/>

###### `Data Warehouse (Processed Data)`

|                                                                |          Service              |                  Description                        |
| -------------------------------------------------------------- | ----------------------------- | --------------------------------------------------- |
|  <img src="./icons/SQL-Data-Warehouses.svg" width="50px" />    | `Azure SQL (Data Ware House)` |                  WordPress URL                      |
|  <img src="./icons/Analysis-Services.svg" width="50px" />      | `Azure Analysis Service`      |                  WordPress URL                      |

<br/>

###### `Advanced Machine Learning`

|                                                                   |          Service                |                  Description                        |
| ----------------------------------------------------------------- | ------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Machine-Learning-Studio.svg" width="50px" />   | `Azure Machine Learning Studio` |                  WordPress URL                      |

<br/>

###### `Messaging`


|                                                        |        Service       |                  Description                        |
| ------------------------------------------------------ | -------------------- | --------------------------------------------------- |
|  <img src="./icons/Event-Hubs.svg" width="50px" />     | `Azure Event Hub`    |                  WordPress URL                      |

<br/>

###### `Streaming`


|                                                               |        Service           |                  Description                        |
| ------------------------------------------------------------- | ------------------------ | --------------------------------------------------- |
|  <img src="./icons/Stream-Analytics-Jobs.svg" width="50px" /> | `Azure Stream Analytics` |                  WordPress URL                      |

<br/>

###### `Authentication, Authorization & Security`


|                                                                 |        Service           |                  Description                        |
| --------------------------------------------------------------- | ------------------------ | --------------------------------------------------- |
|  <img src="./icons/Key-Vaults.svg" width="50px" />              | `Azure Key Vault`        |                  WordPress URL                      |
|  <img src="./icons/Policy.svg" width="50px" />                  | `Azure Policy`           |                    MySQL URL                        |
|  <img src="./icons/Azure-Active-Directory.svg" width="50px" />  | `Azure Active Directory` |                 PHPMyAdmin URL                      |
|  <img src="./icons/Security-Center.svg" width="50px" />         | `Azure Security Centre`  |                 PHPMyAdmin URL                      |

<br/>

###### `Monitoring`


|                                                               |        Service           |                  Description                        |
| ------------------------------------------------------------- | ------------------------ | --------------------------------------------------- |
|  <img src="./icons/SAP-Azure-Monitor.svg" width="50px" />     | `Azure Monitor`          |                  WordPress URL                      |

<br/>

###### `Provisioning`


|                                                               |        Service                     |                  Description                        |
| ------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       | `Azure Resource Manager Templates` |                  WordPress URL                      |

<br/>




### ⚙️ Accepted Data Input Types

<br/>

###### `Data Input Types`


|                                                               |        Service                     |                  Description                        |
| ------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |         `Structured Data`          |                  WordPress URL                      |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |       `Semi-Structured Data`       |                  WordPress URL                      |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |         `Unstructured Data`        |                  WordPress URL                      |

<br/>



### ⚙️ Supported Analysis Types

<br/>

###### `Analysis Types`


|                                                               |        Service                     |                  Description                        |
| ------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |         `Azure HDInsight`          |                  With HDInsight, you can use open-source frameworks such as Hadoop, Apache Spark, Apache Hive, LLAP, Apache Kafka, Apache Storm, R, and more, in your Azure environment.                      |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |       `Semi-Structured Data`       |                  WordPress URL                      |


<br/>

### ⚙️ Implementation / Provisioning

<br/>

###### `IAC`


|                                                               |        Service                      |                  Description                        |
| ------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |  `Azure Resource Manager Templates` |                  WordPress URL                      |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |              `Terraform`            |                  WordPress URL                      |

<br/>

### ⚙️ Networking Services Used

<br/>

###### `Networking`


|                                                               |        Service                      |                  Description                        |
| ------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------- |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |  `Azure VPC`                        |                  WordPress URL                      |
|  <img src="./icons/Resource-Groups.svg" width="50px" />       |              `Azure DNS`            |                  WordPress URL                      |



## ✌️ Info

Created by [Brave Okafor](https://github.com/braveokafor) for Johannes[]().
