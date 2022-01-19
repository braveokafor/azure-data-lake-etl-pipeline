<h1 align="center">
  <img src="./azure-data-lake.png" width="900px"/><br/>
  Azure Data Lake
</h1>
<p align="center">Automatically deploy a locally hosted <b>WordPress</b> site to <b>Google Kubernetes Engine</b>.<br/> 
<b>Local Orchestration</b> (Docker Compose), <b>Remote GCP Orchestration</b> (GKE)<br/>and <b>CI/CD</b> (CloudBuild).<br/>
<br/>
On push to this <b>GitHub</b> repo, a <b>CloudBuild</b> trigger redeploys the <b>WordPress</b> workload and clones this repo to <b>/var/www/html</b> on the WordPress GKE container.</p>


## ⚡️ Quick start

First of all, install the latest versions of [Docker](https://docs.docker.com/engine/install/) and install [Docker-Compose](https://docs.docker.com/compose/install/).  

### ⚙️ Clone GitHub Repo (git clone)

Clone GitHub repo to Local Computer.  
> 🔔 Make sure your GitHub account is authenticated, as this is a private repo.  

> To clone the GitHub repo, run:

```bash
git clone https://github.com/slingshotbiz/wp-start.git
```


### 🐳 Start WordPress on Local Computer (docker-compose up)

Navigate to the cloned GitHub folder.  

> To start the docker-compose environment, run:

```bash
docker-compose up -d
```

> If you get Admin access related errors, run:

```bash
sudo docker-compose up -d
```


### ⚙️ Services Used

###### `Data Ingestion`


|                                                        |        Service       |                  Description                        |
| ------------------------------------------------------ | -------------------- | --------------------------------------------------- |
|  <img src="./icons/Data-Factory.svg" width="50px" />   | `Azure Data Factory` |                  WordPress URL                      |
|  <img src="./icons/IoT-Hub.svg" width="50px" />        |       `IOT Hub`      |                    MySQL URL                        |
|  <img src="./icons/Logic-Apps.svg" width="50px" />     |     `Logic Apps`     |                 PHPMyAdmin URL                      |
|  <img src="./icons/Function-Apps.svg" width="50px" />  |   `Function Apps`    |                 PHPMyAdmin URL                      |

<br/>

###### `Data Lake (Raw Data)`

|                                                                |          Service        |                  Description                        |
| -------------------------------------------------------------- | ----------------------- | --------------------------------------------------- |
|  <img src="./icons/Data-Lake-Store-Gen1.svg" width="50px" />   | `Azure Data Lake Store` |                  WordPress URL                      |


<br/>

###### `Processing`


|        Service       |                   Description                       |
| -------------------- | --------------------------------------------------- |
|      `Azure Data Bricks`    |                  WordPress URL                      |
|      `Azure HD Insight`     |                    MySQL URL                        |
| `Azure Data Lake Analytics` |                 PHPMyAdmin URL                      |


|                                                                |          Service            |                  Description                        |
| -------------------------------------------------------------- | --------------------------- | --------------------------------------------------- |
|  <img src="./icons/Data-Lake-Store-Gen1.svg" width="50px" />   | `Azure Data Bricks`         |                  WordPress URL                      |
|  <img src="./icons/HD-Insight-Clusters.svg" width="50px" />    | `Azure HD Insight`          |                  WordPress URL                      |
|  <img src="" width="50px" />                                   | `Azure Data Lake Analytics` |                  WordPress URL                      |
             
<br/>

###### `Data Warehouse (Processed Data)`


|        Service       |                   Description                       |
| -------------------- | --------------------------------------------------- |
| `Azure SQL (Data Ware House)` |                  WordPress URL                      |
|   `Azure Analysis Service`    |                    MySQL URL                        |




### 🐳 Stop WordPress on Local Computer (docker-compose down)

Shut-down Docker containers.  

> To shutdown the docker-compose environment, run:

```bash
docker-compose down
```

### 🚚 Deploy to GKE (git commit)
To push modifications to GitHub (deploy to GKE), navigate to cloned folder.  

> To push modifications to GitHub repo:

```bash
git add *;
git commit -m "Modified wp-content";
git push;
```


## ✌️ Info

Created by [Brave Okafor](https://github.com/braveokafor) for [Slingshot Biz](https://github.com/slingshotbiz).
