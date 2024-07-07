<!--
**khqnn/khqnn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


<div id="header" align="center">
  <img src="https://media.giphy.com/media/gjrYDwbjnK8x36xZIO/giphy.gif" width="100"/>

  <div id="badges">
  <a href="https://www.linkedin.com/in/khaqan-ashraf/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:eng.khaqan@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://github.com/khqnn/">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="github"/>
  </a>
</div>

<img src="https://komarev.com/ghpvc/?username=khqnn&style=flat-square&color=blue" alt=""/>

<h1>
  Hey there 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/> 
  I engineer the software solutions
  
</h1>


</div>

<div align="center">
  <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
</div>


---

### 🔥 My Stats 

[![GitHub Streak](https://streak-stats.demolab.com?user=khqnn&theme=dark)](https://git.io/streak-stats)

<!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=khqnn&hide=contribs,prs) -->

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=khqnn&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)


---

#  I'm Khaqan Ashraf, a Senior Software Engineer based in Lahore, Pakistan.

## 🎓 Education
- **MS in Data Science**  
  Information Technology University Lahore

- **BS in Computer Science**  
  Government College University Lahore


## 💻 Technical Skills
- **Languages:** JavaScript, TypeScript, SQL, Python, Java
- **Frameworks:** Node, ExpressJs, NestJs, ReactJs
- **Technologies:** AWS, Docker, GraphQL
- **Databases:** MySQL, Postgres, MongoDB, DynamoDB, Apache Cassandra

## 🛠️ Tools and Technologies
- **Development Tools & IDEs:** VS Code
- **DevOps:** Docker, Jenkins, GitHub Actions
- **Cloud Platforms:** AWS (Lambda, EC2, ECR, S3, DynamoDB, API Gateway)
- **Version Control:** Git, GitHub, Bitbucket
- **Project Management:** Jira, Asana
- **Web Servers:** Nginx
- **Monitoring:** Newrelic, CloudWatch
- **Other:** Sonar, Memcache, Redis

## 📜 Certificates
- **Data Engineer Certificate | Mangtas 2023**
- **Machine Learning, Data Science, and Deep Learning with Python | Udemy 2022**

## 🔭 Research Projects
Master's Thesis: Automated Pest Detection in Crops using Deep Learning
- **Abstract:**  
  Crops are a vital part of the economy and livelihood, making crop protection crucial. In this research, we explored the application of deep learning techniques for automating the detection of pests in crops. Using the IP102 dataset and ensemble pre-trained deep CNN models, we developed a weighted ensemble technique with learnable parameters. Additionally, we utilized pretrained vision transformers to classify stem rust, leaf rust, and healthy wheat from a small dataset sourced from the ICLR challenge. Through experimentation with CNN architectures and ViT models, we demonstrated the effectiveness of large-scale pretrained vision transformers on small datasets, outperforming state-of-the-art CNN architectures. Our research highlights the importance of leveraging pretrained models and the transferability of features learned from ImageNet21 in agricultural applications.

- **Key Contributions**  
  * Developed a weighted ensemble technique with learnable parameters for pest detection.
  * Demonstrated the effectiveness of pretrained vision transformers on small agricultural datasets.
  * Achieved competitive performance in the ICLR challenge through the use of ViT models pretrained on ImageNet21.

- **Learnings**  
  * Pretrained vision transformers are effective for small datasets in agricultural contexts.
  * Features learned from ImageNet21 are transferable to diverse datasets, such as wheat plant images.

## 📦 Packages/Libraries
stealth25519 Python Package
- **Description:**  
  The Stealth25519 Python package provides functionality for the generation, verification, and signing of stealth addresses using the standard ed25519 algorithm with the ECDH protocol.

- **Features**  
  * The sender can generate a stealth address using the public view and spend key of the recipient.
  * The recipient can use their public spend key and private view key to identify transactions intended for them.
  * The recipient can sign transactions for all transactions that belong to them.
  * The signature generated by the recipient can be verified by anyone with the stealth address public key.

- **Code Example**  
  
  ```python
  from stealth25519.generator import StealthAddressGenerator

  public_spend_key_bytes = bytes.fromhex('18a498c68461e39dd180745e5aa1faacbc9b8a5f74a7eb25b5038b66db0a4af6')
  public_view_key_bytes = bytes.fromhex('b52c33b513c26e17b7105cb1ed1c7022ef00f3967aaac0ff8bd9d15ccee4d94e')

  public_spend_key = PublicKey(public_spend_key_bytes)
  public_view_key = PublicKey(public_view_key_bytes)

  generator = StealthAddressGenerator(public_spend_key, public_view_key, hash_function = sha512)
  stealth_address = generator.generate()
  print('Stealth Address\n', stealth_address)
  ```

- **Documentation:** [stealth25519](https://pypi.org/project/stealth25519/)
- **Source code:** [stealth-py](https://github.com/khqnn/stealth-py)



<!-- 

feedback:
1. claim ownership of the projects delivered individualy (update role and respnsibilites)
2. add more graphics in projects
3. add more code snippets


Projects:
1. nitro (metaverse game project, blockchain, nodejs backend with typescript, dynamodb, reactjs, docker, ec2, lambda)
2. techpurview (society management system, nodejs backend, postgres, nextjs, aws ec2, docker)
3. tossdown (multivendor ecommerce engine, nodejs, codeigniter, php, mysql, lambda)
4. alpolink (dump exams selling, php, codeigniter, mysql)
5. aangan (multivendar ecommerce for Pakistani women handcraft items, php, wordpress)
6. information reterieval system (corpora, support vector machine, python, jupyter notebook, cassandra)
7. clause generation (llm, prompt engineering, huggingface, quantization, gpu, Llama)
8. stealth addresses (x25519, ed25519, stealth address generation, signature and verification)
9.  smart contracts (erc20, erc721, contracts deployment, hardhat)
10. prdocuts pair (a priori algo)
11. reporting system (multitenant reports, data cubes, slices)
12. location wise clustering (kibana and elasticsearch)
13. searching service (migration of data from mysql to elasticsearch)
14. kidsafe (app for youtube videos for kids using youtube apis)
15. funding metrics (loan, installments, collection, react native, nodejs, salesforce, firestore, firebase auth, gcp)
16. lead management system (lead ingestion, campaign, lead life cycle, nodejs, nextjs, docker, docker-compose)
17. sales predictions (yearly, quarterly sales etc, data collection from relation database, data preprocessing, heatmap)
18. notifications service (1k notifications per minute, fcm, cassandra, retry, recuring and one-time)
19. scrappers (products scrapping from shopify site, python, beautifulsoap, selenium)

Problems:
1. nodejs scaling (event loop blocking, load testing)
2. 302 redirection (old slugs, json in mysql)
3. llms (quantization, prompts)
4. optimization (mysql queries)
5. assets reterival (blockchain)

Presentations:
1. jwt security, access management
2. api gateway


Project: techpurview
Description: 
Challenges Faced: 
Solutions Implemented: 



-->


##  Projects

<div id="nitro-img" align="center">
  <img src="https://i.ytimg.com/vi/7ZyDbpt-7p4/maxresdefault.jpg" />
</div>

### Nitro

- **Description**  
  Nitro is a metaverse game project integrating blockchain technology. It features a Node.js backend with TypeScript and DynamoDB for data storage. The frontend is developed using React.js, and deployment is managed using Docker containers on AWS EC2 instances and Lambda functions.

- **Role and Responsibilities**  
  As the lead software engineer, my responsibilities included designing the backend architecture, implementing new features, and providing support for existing features.

- **Challenges Faced**  
  1. ***Slow Query Performance with Dynamodb***  
  <b>Challenge: </b> Initial queries to DynamoDB were slow, impacting overall application performance.  
  <b>Solution: </b> Conducted a comprehensive analysis of the query patterns and identified inefficient scan operations. I then restructured the data model to better align with access patterns, created composite indexes to support complex queries, and optimized the use of partition keys to evenly distribute the data load. Implemented batch operations to reduce the number of read requests and improve throughput.

  2. ***High Latency in Asset Retrieval from the Blockchain***  
     <b>Challenge: </b> Retrieving assets from the blockchain was slow, causing delays in game interactions.  
     <b>Solution: </b> Implemented a caching layer using Redis to store frequently accessed assets, significantly reducing retrieval times. Additionally, I set up asynchronous processes to prefetch and update the cache with the latest assets, ensuring that the most current data was available with minimal delay. Employed background jobs using AWS Lambda functions to handle periodic asset updates.

  3. ***Scalability Issues with Backend Services***  
     <b>Challenge: </b> The backend services experienced performance bottlenecks under high user load.  
     <b>Solution: </b>  Designed and implemented a microservices architecture to distribute the load across multiple services. Used Docker containers to isolate and scale services independently. Implemented auto-scaling groups on AWS EC2 instances to dynamically adjust resources based on traffic. Enhanced inter-service communication using AWS SQS to manage message queues and ensure reliable data exchange.
  

- **[site](https://www.nitroleague.com/)**



### TechPurview

<div id="techpurview-img" align="center">
  <img width="1024" alt="techpurview" src="https://github.com/khqnn/khqnn/assets/56000386/41c0c3d3-4803-451e-9df9-8acb20fd2908">
</div>

- **Description**  
  TechPurview is a society management system built with a Node.js backend and PostgreSQL database. The frontend is developed using Next.js, and the application is deployed on AWS EC2 instances using Docker containers.enhancements.

- **Role and Responsibilities**  
  As the lead software engineer, my responsibilites including the architecting the backend infrastructure to develop, integrate, deploy and delivering the complete proejct.
<!--  As the lead software engineer, my responsibilities included architecting the backend infrastructure, implementing database connectivity, and coordinating with the frontend team for UI/UX enhancements. -->
  
- **Challenges Faced**
  1. ***Managing Multiple Connections to the Database***  
     <b>Challenge: </b>Handling multiple connections to the PostgreSQL database led to potential performance issues and resource wastage.  
     <b>Solution: </b>Implemented the singleton design pattern to ensure that only one instance of the database connection is initiated and served for all requests. This optimized resource usage and improved overall system performance.
     
  2. ***Ensuring Data Consistency and Integrity***  
     <b>Challenge: </b>Maintaining data consistency and integrity across multiple transactions was challenging, especially with concurrent database operations.  
     <b>Solution: </b>Implemented transaction management using PostgreSQL’s ACID properties to ensure data consistency and integrity. Used connection pooling to manage concurrent connections efficiently and avoid deadlocks. Applied proper indexing and optimized SQL queries to enhance database performance.
     
  3. ***Optimizing Query Performance***  
     <b>Challenge: </b>Some complex queries were slow, impacting the overall responsiveness of the system.  
     <b>Solution: </b>Conducted query performance analysis and optimization. Created necessary indexes to speed up frequently used queries. Refactored and optimized complex queries to reduce execution time. Implemented caching strategies using Redis to store the results of frequently accessed data, thereby reducing database load.
     
  4. ***Handling Session Management Securely***  
     <b>Challenge: </b>Managing user sessions securely to prevent unauthorized access and ensure data privacy.  
     <b>Solution: </b> Implemented secure session management using JWT (JSON Web Tokens) for authentication. Ensured that JWTs were securely signed and stored. Used HTTPS for all communication to protect data in transit. Regularly reviewed and updated security protocols to mitigate potential vulnerabilities.
     
  5. ***Coordinating Backend and Frontend Development***  
     <b>Challenge: </b>Ensuring seamless integration between the backend and frontend components, and maintaining consistent data flow.  
     <b>Solution: </b>Established clear communication protocols and API documentation to ensure that the backend services met the frontend requirements. Used tools like Swagger for API documentation and Postman for testing. Conducted regular integration testing and code reviews to ensure smooth and efficient collaboration between the backend and frontend teams.

- **[site](https://biz.techpurview.co/)**


### Tossdown

<div id="tossdown-img" align="center">
  <img width="1024" alt="tossdown" src="https://github.com/khqnn/khqnn/assets/56000386/10c4665a-97e4-46b8-8f0d-171f17c6b737">
</div>


- **Description**  
  Tossdown is a multivendor ecommerce engine developed using Node.js, CodeIgniter (PHP framework), and MySQL database. The backend is primarily implemented in Node.js, while certain functionalities are handled by serverless Lambda functions.

- **Role and Responsibilities**  
  As a senior software engineer on the Tossdown project, my responsibilities included optimizing performance, analyzing database queries, and implementing search functionalities.

- **Challenges Faced**
  1. ***Slow Performance of Certain Endpoints***  
     <b>Challenge: </b>Certain API endpoints were slow, impacting user experience and overall system efficiency.  
     <b>Solution: </b> Identified endpoints with poor performance by analyzing database queries and code execution. Used the "EXPLAIN" keyword to understand query execution plans and identify bottlenecks. Optimized MySQL queries by adding appropriate indexes, refactoring complex joins, and removing unnecessary iterations. Implemented caching strategies using Redis to store frequently accessed data, reducing the need for repetitive database queries.
     
  2. ***Redundant Search Results Affecting Search Accuracy and Relevance***  
     <b>Challenge: </b>Search results were often redundant and not accurately relevant to user queries.  
     <b>Solution: </b>Implemented a solution to periodically move data from MySQL to Elasticsearch, ensuring that product data is indexed and searchable with full-text search capabilities. This approach improved search accuracy and reduced redundant search results. Additionally, fine-tuned the Elasticsearch queries to include filtering, boosting, and sorting to enhance search relevance and user satisfaction.
     
  3. ***Handling High Traffic Loads and Ensuring Scalability***  
     <b>Challenge: </b>The system needed to handle high traffic loads, especially during peak times, without degrading performance.  
     <b>Solution: </b>Designed and implemented a scalable architecture using AWS services. Deployed backend services on AWS EC2 instances with auto-scaling groups to automatically adjust the number of instances based on traffic. Used AWS Lambda functions for certain functionalities to ensure efficient and scalable execution of tasks. Implemented a load balancer to distribute incoming requests evenly across instances, ensuring high availability and reliability.
     
  4. ***Maintaining Data Consistency Between MySQL and Elasticsearch***  
     <b>Challenge: </b>Ensuring that data remains consistent between MySQL and Elasticsearch during updates and deletions.  
     <b>Solution: </b>Implemented a change data capture (CDC) mechanism to track changes in the MySQL database and update Elasticsearch indices in real-time. Used AWS Lambda functions to process database change events and synchronize data between MySQL and Elasticsearch. This ensured that search results were always up-to-date and consistent with the database.
     
  5. ***Optimizing Code for Serverless Functions***  
     <b>Challenge: </b>Certain functionalities handled by serverless Lambda functions needed to be optimized for performance and cost-efficiency.  
     <b>Solution: </b>Refactored the code for serverless functions to minimize cold start latency and optimize execution time. Used environment variables and AWS Secrets Manager to manage configuration and secrets securely. Implemented monitoring and logging using AWS CloudWatch to track performance and identify areas for improvement. Fine-tuned resource allocation (memory and timeout settings) to balance cost and performance.

- **[site](https://tossdown.com/)**


### Alpolink

<div id="tossdown-img" align="center">
  <img width="1024" alt="alpolink" src="https://github.com/khqnn/khqnn/assets/56000386/b1682850-9cb2-4586-af01-6949c5f654e3">
</div>

- **Description**  
  Alpolink is a platform for selling exam dumps, developed using PHP and the CodeIgniter framework, with MySQL as the database management system.

- **Role and Responsibilities**  
  As a senior software engineer for Alpolink, my responsibilities included addressing architectural challenges and optimizing system performance.

- **Challenges Faced**  
  Architectural issue: Each website had its own frontend and database instance, leading to complexities in managing and maintaining multiple codebases and databases.

- **Solutions Implemented**  
  Implemented a unified backend architecture where a single backend serves multiple websites. This approach reduced complexity by consolidating codebases and databases, allowing for easier maintenance and scalability. Each site is now served by the same backend, streamlining operations and improving efficiency.

- **[site](https://www.certificationsbuzz.com/)**


### Aanganpk

<div id="aangan-img" align="center">
  <img width="1024" alt="aangan" src="https://github.com/khqnn/khqnn/assets/56000386/6b2bc488-3e4b-4a6a-9b4e-efa61e9d2c4a">
</div>

- **Description**  
  Aanganpk is a multivendor ecommerce platform specializing in Pakistani women's handcrafted items. The platform is built using WordPress with WooCommerce plugin, leveraging PHP for customizations and extensions.

- **Role and Responsibilities**  
  As a senior software engineer for Aanganpk, my responsibilities included addressing platform limitations and customizing functionalities to meet business requirements.

- **Challenges Faced**  
  Lack of reporting capabilities from the WooCommerce WordPress plugin, hindering the organization's ability to generate essential reports for business analysis and decision-making.

- **Solutions Implemented**  
  Updated the WooCommerce plugin code to retrieve and generate custom reports tailored to the organization's specific needs. This involved modifying the plugin codebase to extract and present relevant data in a format conducive to business insights and analysis.

- **[site](https://kaarvan.com.pk/portfolio-item/aanganpk-com/)**



### Information Retrieval System
- **Description**  
  The Information Retrieval System is designed to retrieve relevant documents from a corpora using machine learning techniques. It utilizes Support Vector Machine (SVM) algorithms for classification and is implemented in Python within Jupyter Notebook environment. Data is stored and managed in a Cassandra database.

- **Role and Responsibilities**  
  As the sole architect and developer of the Information Retrieval System, I assumed complete ownership of all project aspects. My role involved the design and implementation of sophisticated machine learning algorithms tailored for document classification and retrieval. This project epitomizes my capacity to conceive, execute, and refine complex technical solutions independently.

- **Challenges Faced**  
  Document and query indexing posed significant challenges in organizing and efficiently retrieving information from the corpora.

- **Solutions Implemented**  
  Implemented the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm for document and query indexing. This approach simplified the indexing process while improving retrieval effectiveness. The system achieved better evaluation metrics in terms of precision and recall, ensuring more accurate document retrieval.


### Clause Generation
- **Description**  
  The Clause Generation project focuses on generating legal clauses using advanced natural language processing techniques. It leverages Large Language Models (LLMs), prompt engineering methodologies, and the Hugging Face library for model training and inference. Quantization techniques are employed for model optimization, with GPU acceleration for faster computation. The project also utilizes Llama and Falcon frameworks for specific functionalities.

- **Role and Responsibilities**  
  As a senior software engineer for the Clause Generation project, my responsibilities included implementing and optimizing the clause generation pipeline, model training, and evaluation.

- **Challenges Faced**  
  The LLMs utilized in the project were too large to fit in the available GPU memory, posing challenges in model training and inference.

- **Solutions Implemented**  
  To address the GPU memory limitations, we conducted testing using EC2 g5.2xlarge instances, which provided sufficient resources for model training and inference. Additionally, for local development and testing, we implemented quantization techniques to optimize model size and memory usage. This allowed us to generate outputs using quantized LLMs and evaluate them based on syntax and semantic similarity metrics.


### Stealth Address Library
- **Description**  
  Stealth Addresses is a cryptographic project focused on generating secure and private addresses for transactions. It utilizes the x25519 algorithm for shared secret generation and the ed25519 algorithm for signature generation and verification.

- **Role and Responsibilities**  
  As the sole proprietor and developer of the Stealth Address Library project, I assumed full ownership and accountability throughout its lifecycle. Responsibilities encompassed every aspect, from conceptualization and design to implementation and refinement. This project epitomizes my capacity to initiate, execute, and deliver complex technical initiatives independently.

- **Challenges Faced**  
  Integrating the x25519 and ed25519 algorithms posed challenges due to their different purposes and implementations.

- **Solutions Implemented**  
  Implemented an initial stealth address generation mechanism using the shared secret methodology of x25519. Then, instead of using standard libraries for ed25519, a custom core implementation was developed based on RFC8032 specifications. Mathematics and cryptographic principles were utilized to generate stealth addresses seamlessly using the ed25519 algorithm, ensuring compatibility and security.


### Products Pair
- **Description**  
  Products Pair is a system designed to predict the probability of items being sold together. The Apriori algorithm is utilized to calculate these probabilities based on transactional data.

- **Role and Responsibilities**  
  As a senior software engineer for the Products Pair project, my responsibilities included designing and implementing the predictive algorithm and optimizing system performance.

- **Challenges Faced**  
  Implementing the Apriori algorithm was successful, but retrieving probabilities of product pairs from the transactional database each time resulted in high latency, impacting system performance.

- **Solutions Implemented**  
  Implemented a solution to periodically update data in a denormalized data store from the transactional database (MySQL). This denormalized data store contains pre-calculated probabilities of product pairs. By querying this denormalized database, the system achieves significantly lower latency, ensuring smooth and efficient operation.


### Reports management system
- **Description**  
  The Reporting System is designed to generate multitenant reports using data cubes and slices. It provides insights into various dimensions such as time, product, category, branch, and brand, catering to the diverse reporting needs of hundreds of clients. Reports can be saved and they're continuesly updated.

- **Role and Responsibilities**  
  As a senior software engineer for the Reporting System project, my responsibilities included designing and implementing the reporting functionalities, ensuring scalability and efficiency.

- **Challenges Faced**  
  Making reports generic for hundreds of clients posed a significant challenge, especially in calculating dimensions from transactional data for each client.

- **Solutions Implemented**  
  Implemented a solution to calculate dimensions for data cubes (e.g., time, product, category, branch, and brand) from transactional data. These dimensions are then pre-calculated and stored in cache (e.g., Memcached) for efficient retrieval. This approach significantly reduced the computational overhead and time required for generating reports, ensuring scalability and responsiveness.


### KidSafe
- **Description**  
  KidSafe is an application designed to provide a safe environment for children to watch YouTube videos. It utilizes the YouTube API to curate a selection of kid-friendly content.

- **Role and Responsibilities**  
  As a senior software engineer for the KidSafe project, my responsibilities included implementing features, integrating APIs, and ensuring child safety and usability.

- **Challenges Faced**  
  Initially, the app was designed to allow parents to manually select videos for their children, but this approach proved cumbersome. Integrating functionality to automatically include all videos from a YouTube channel posed a challenge, as the YouTube API does not provide direct access to fetch videos by channel name.

- **Solutions Implemented**  
  Developed a Python service to overcome the challenge by utilizing web scraping techniques with Beautiful Soup to fetch the YouTube channel ID using the channel name. Once the channel ID was obtained, the YouTube API was invoked recursively to fetch all videos associated with the channel. This solution provided a seamless way to include all videos from a specified YouTube channel in the KidSafe app, enhancing user experience and content accessibility for parents and children.


### Notifications Service
- **Description**  
  The Notifications Service is designed to deliver up to 1,000 notifications per minute efficiently. It utilizes Firebase Cloud Messaging (FCM) for message delivery, Cassandra for data storage, and supports features such as retry mechanisms and recurring/one-time notifications.

- **Role and Responsibilities**  
  As a senior software engineer for the Notifications Service project, my responsibilities included architecting the system, optimizing performance, and ensuring reliable delivery of notifications.

- **Challenges Faced**  
  The partition key was set as the job_id, and the sort key was the next notification trigger time. However, the presence of the same next notification trigger time in multiple partitions led to slower query performance, as queries for next jobs to be executed were scanned across all partitions.

- **Solutions Implemented**  
  To address the query performance issue, we redesigned the data model by setting the next notification timestamp as the partition key and the job_id as the sort key. This ensured that all notifications scheduled for the same time would be stored within the same partition. As a result, querying for next notifications to be triggered became more efficient, improving overall system performance and reducing latency.



### Google Map Scraper
- **Description**  
  The Google Map Scraper is a tool designed to extract information about stores from Google Maps based on location and store type. It is built using Python, with Beautiful Soup and Selenium utilized for web scraping.

- **Role and Responsibilities**  
  As the sole creator and developer of the Google Map Scraper, I orchestrated all facets of the project, from conceptualization to implementation. My responsibilities encompassed designing the scraping process, integrating essential web scraping libraries, and fine-tuning data extraction mechanisms. This project underscores my adeptness in independently driving and delivering complex technical solutions.

- **Challenges Faced**  
  The dynamic rendering of Google Maps posed challenges for web scraping, as Beautiful Soup could not access dynamically loaded content.

- **Solutions Implemented**  
  To overcome the limitation of Beautiful Soup, Selenium was employed to open a browser and wait for the complete rendering of the Google Maps webpage. Once the page was fully loaded, metadata for the stores (such as location and store type) was extracted using Selenium. Subsequently, Beautiful Soup was utilized to iterate through the metadata and extract detailed information for each store, including address, star ratings, phone numbers, and photos. This combined approach ensured comprehensive data extraction from Google Maps despite the dynamic rendering challenges.


