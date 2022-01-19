<h1 align="center">
  <img src="./azure-data-lake.png" width="500px"/><br/>
  SlingShot Biz
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


### ⚙️ URL's & Ports

###### `url's`


|   Service   |                   Description                       |  URL             |    Port   |
| ----------- | --------------------------------------------------- | ---------------- | --------- |
| `wordpress` |                  WordPress URL                      | `localhost:80`   |    80     |
|   `mysql`   |                    MySQL URL                        | `localhost:3306` |   3306    |
| `phpmyadmin`|                 PHPMyAdmin URL                      | `localhost:8000` |   8000    |

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
