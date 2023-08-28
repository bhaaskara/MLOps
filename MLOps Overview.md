# MLOps Concepts

## MLOps Componenets
![](Pasted%20image%2020230825193405.png)

**Use case discovery:**
- Collaboration between business and data scientists to define a business problem and translate that into a problem statement
- Objectives solvable by ML with associated relevant KPls (Key Performance Indicator).

**Data Engineering:**
- Collaboration between data engineers and data scientists to acquire data from various sources
- Prepare the data (processing/validation) for modeling.

**Machine Learning pipeline:**
- This stage is designing and deploying a pipeline integrated with CI/CD.
- Data scientists use pipelines for multiple experimentation and testing.
- The platform keeps track of data and model lineage and associated KPls across the experiments.

**Production deployment:**
- This stage accounts for secure and seamless deployment into a production server of choice, be it public cloud, on-premise, or hybrid.

**Production monitoring:**
- This stage includes both model and infrastructure monitoring.
- Models are continuously monitored using configured KPls like changes in input data distribution or changes in model performance.

## Automated ML pipelines VS CI/CD ML Pipelines
![](Pasted%20image%2020230825195143.png)

## Different roles involved in MLOps
A single person cannot answer all the above questions. Hence, a matured ML team   
typically consists of the following:

![](Pasted%20image%2020230825201544.png)
- Data Analysts 
   Uses tools like: Excel, SQL, Data visulization tools (Power BI, Tableu) 
- Data Engineers   
   Uses tools like: Spark, Hadoop, ETL tools
- Data Scientist   
- Research/Applied Scientists
   Creates new algorithms for ML models, mostly leading edge orgs will have these roles.
- ML Engineers   
   Works closely with Data engineers and the scientists
- DevOps Teams
   in MLOps these people are called ML engineers.
   Responsible for CI/CD pipeline creation, ML model deployments
- Developers
   Works on front end app by integrating all the above parts.

# MLOps VS DevOps
![](Pasted%20image%2020230825202654.png)

# Different tools for MLOps

## MLOps on cloud

## Tools
- Version control: Git, Gitlab
- CI/CD: Jenkins, Gitlab, Github actions

**MLOps pipeline**
![](Pasted%20image%2020230825203749.png)
- Kubernetes
- Model management
  MLFlow (machine learning model registry)
- Data versioning
	- DVC (Data version control)
	- Git large file storage (alternative to DVC)
- Feature Store (schema registry)
	- Amazon sagemaker feature maker
	- Vertex AI feature store (GCP)
	- FEAST (open source)
- Cloud ML services
	- Amazon sage maker
	- Vertex.ai (GCP)
	- Azure machine learning
- Kubeflow (opensource to create pipelines on k8s clusters)
- Model Monitoring
	- AWS model monitoring
	- Azure model monitoring 
	- GCP model monitoring
	- Evidently AI (opensource model monitoring tool)
- AutoML tools (subscription based tools)
	- Iguazio
	- DOMINO
	- Valohai
	- neptune.ai
## Post-deployment challenges
- Software engineering related
- ML related
- Challenges when deploying machine learning to edge devices
- 

# Q&A
AI ops or MLOps ?
  as a it operations guy which is good for me AIOPS or MLOPS ?
  https://chat.openai.com/share/247a628f-a8ce-4df9-a781-1749b62fce8e

 
