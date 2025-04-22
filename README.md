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

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=khqnn&layout=compact&theme=vision-friendly-dark&size_weight=0.5&count_weight=0.5)](https://github.com/anuraghazra/github-readme-stats)


---

#  I'm Khaqan Ashraf, a Senior Software Engineer based in Lahore, Pakistan.

## 🎓 Education
- **MS in Data Science**  
  Information Technology University Lahore

- **BS in Computer Science**  
  Government College University Lahore

## 🧑‍💼 Designations/Roles
  - [LLM Trainer](#-as-an-llm-trainer) 🧠📚
  - [Data Scientist](#-as-a-data-scientist) 📊🧑‍🔬
  - [Backend Engineer](#-as-a-data-scientist) 🧑‍💻
  - [Blockchain Developer](#-as-a-data-scientist) 🔗💻

## 🏢 Companies/Organizations
  - Turing
  - Systems Ltd
  - Tkxel
  - tossdown
  - Hotwire Studios


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


## 🧠📚 As an LLM Trainer
  As an LLM Trainer, I specialize in designing, refining, and aligning large language models (LLMs) for safe, accurate, and context-aware outputs. My work bridges machine learning and software engineering, focusing on training models to solve domain-specific challenges (e.g., code generation, audio/visual understanding) while mitigating risks like harmful outputs or inefficiencies. Refer to the [LLM capabilities](#-llm-capabilities) section.



## 📊🧑‍🔬 As a Data Scientist
  As a Data Scientist, I partner with businesses to identify growth opportunities through machine learning. My work revolves around analyzing existing workflows, designing tailored ML solutions, and ensuring seamless integration of models into production systems—all while balancing technical feasibility, cost efficiency, and business impact. Refer to the [LLM capabilities](#-llm-capabilities) section.



## 🧑‍💻 As a Software Engineer
  As a versatile Full-Stack Software Engineer, I specialize in architecting and delivering high-performance, scalable solutions across diverse domains—from business intelligence platforms and telecom systems to blockchain-integrated metaverse games and AI/ML-driven tools. My expertise spans backend development (Node.js, Python, PHP), RESTful API design, database optimization (SQL, NoSQL), and cloud-native deployment (AWS, Docker). I’ve led end-to-end development of enterprise-grade applications, implementing MVC architectures, securing systems with JWT authentication, and optimizing performance through caching (Redis), parallel processing, and efficient query design. My work emphasizes scalability (microservices, monorepos), reliability (transaction management, CI/CD pipelines), and innovation (blockchain integration, LLM-driven tools), while solving complex challenges like high-concurrency data workflows, third-party API latency, and dynamic system scaling. I bridge technical rigor with business impact, ensuring solutions are both robust and aligned with user needs. Please refer to the [projects](#-projects) section. 



## 🔗💻 As a Blockchain Developer
  As a Blockchain Developer, I design, deploy, and integrate secure smart contracts into scalable systems, bridging decentralized technologies with traditional backend architectures. My work spans building blockchain-powered features for metaverse games (e.g., Nitro League) and maintaining a disciplined focus on continuous learning through challenges like the [100 Days of Blockchain](https://github.com/khqnn/chainlearning) commitment. Also, please refere to the [Nitro League](#nitro) and [Stealth Address Library](#stealth-address-library) project and Python package for [stealth addresses](#-packageslibraries)



## 💬🧠 LLM Capabilities


### Python Code Generation & Validation LLM
  *Developed a specialized LLM precision-tuned to generate, analyze, and correct Python code in response to user queries. As an LLM Trainer, I evaluated model outputs for accuracy, security, and efficiency, authored gold-standard code responses, and iteratively refined training datasets. Key contributions included identifying edge cases (e.g., recursion errors, insecure dependencies), implementing adversarial testing, and aligning outputs with real-world programming challenges to ensure robust, error-free code generation. The model now assists developers in writing secure, optimized Python scripts across diverse use cases.*


### JavaScript Code Generation & Validation LLM
  *Trained an LLM to generate, debug, and optimize JavaScript code for diverse use cases (web apps, APIs, Node.js). As an LLM Trainer, I curated datasets of real-world JS scenarios, authored high-quality code samples, and iteratively refined model outputs for accuracy and security. Key contributions included identifying and correcting edge cases (e.g., async/await pitfalls, callback hell), mitigating vulnerabilities (XSS, prototype pollution), and optimizing code efficiency (memory leaks, event-loop bottlenecks). The model now delivers production-ready JavaScript solutions aligned with modern best practices.*


### Multimodal Adversarial Testing for LLM Security
  *Spearheaded adversarial testing of a multimodal LLM to identify vulnerabilities in code generation triggered by image-based prompts. As an AI Security Specialist, I designed adversarial attacks by crafting deceptive prompts (e.g., generating malicious code snippets, unethical coding practices) from images, stress-testing the model’s alignment safeguards. Responsibilities included curating image-to-prompt attack vectors, analyzing harmful outputs (malware, SQL injection), and refining SFT datasets to mitigate risks. The project hardened the model’s resilience against coding-domain exploits, ensuring ethical and secure code generation.*


### Audio-Capable LLM Training via Synthetic SFT Datasets
  *Designed and executed a supervised fine-tuning (SFT) pipeline to train an LLM for multimodal audio tasks, including speech understanding, generation, and noise-resilient processing. As an Audio AI Trainer, I engineered text-based prompt-response pairs simulating real-world audio challenges (background noise, emotional tone variations, interruptions) to teach the model context-aware responses. Collaborated with audio engineers to convert these scenarios into synthetic training data (speech clips, sound effects), enabling the model to robustly parse and generate audio even in suboptimal conditions. Key outcomes included improved performance in noisy environments and nuanced paralinguistic comprehension.*


### Vision-Driven Function Calling for LLMs
  *Engineered an SFT pipeline to train an LLM in interpreting visual inputs and autonomously invoking external APIs/tools via structured JSON calls. As an AI Trainer, I designed multimodal prompts combining images (e.g., graphs, invoices, maps) with user queries, teaching the model to extract visual data (numbers, locations) and trigger context-aware tool usage (payment processing, weather APIs, live data fetching). Responsibilities included curating function schemas, validating JSON outputs against image context, and refining the model’s ability to chain API responses into coherent final answers. The system now solves complex, real-time tasks (e.g., “Calculate shipping costs from this warehouse photo”) beyond standard LLM capabilities.*



### Clause Generation
<!-- 
python
fastapi
docker
huggingface
ec2
api gateway


streaming
ci/cd
authorization
-->

- **Description**  
  The Clause Generation project focuses on generating legal clauses using advanced natural language processing techniques. It leverages Large Language Models (LLMs), prompt engineering methodologies, and the Hugging Face library for model training and inference. Quantization techniques are employed for model optimization, with GPU acceleration for faster computation. The project also utilizes Llama and Falcon frameworks for specific functionalities.

- **Role and Responsibilities**  
  As a senior software engineer for the Clause Generation project, my responsibilities included implementing and optimizing the clause generation pipeline, model training, and evaluation.

- **Challenges Faced**  
  1. ***LLMs too large for available GPU memory***  
     <b>Challenge: </b> The LLMs used in the project were too large to fit in the available GPU memory, which posed significant challenges in both model training and inference phases.  
     <b>Solution: </b> Conducted testing using EC2 g5.2xlarge instances, which provided sufficient GPU memory and computational power for efficient model training and inference. Implemented quantization techniques to reduce the model size, enabling it to fit within the available memory constraints. This involved converting the model to a lower precision format, significantly reducing the memory footprint without compromising performance.

  2. ***Maintaining model performance after quantization***  
     <b>Challenge: </b> Quantizing the model to fit within memory constraints could potentially degrade its performance, particularly in terms of accuracy and output quality.  
     <b>Solution: </b> Evaluated the performance of quantized models using syntax and semantic similarity metrics to ensure that the generated clauses maintained high-quality standards. Performed iterative fine-tuning and optimization to balance model size and performance, ensuring that the quantized models produced outputs comparable to their full-precision counterparts.

  3. ***Ensuring efficient prompt engineering***  
     <b>Challenge: </b> Effective prompt engineering is critical for guiding the LLMs to generate accurate and contextually appropriate legal clauses.  
     <b>Solution: </b> Developed and tested various prompt templates to determine the most effective configurations for eliciting high-quality clause generation from the LLMs. Conducted extensive experimentation with different prompt structures and contextual inputs, continuously refining the approach based on output quality and relevance.

  4. ***Integrating multiple frameworks (Llama and Falcon)***  
     <b>Challenge: </b> Utilizing multiple frameworks like Llama and Falcon for specific functionalities added complexity to the integration and coordination of different components within the project.  
     <b>Solution: </b> Designed a modular architecture that allowed for seamless integration of different frameworks, ensuring that each component could be developed and tested independently before integration. Conducted thorough interoperability testing to identify and resolve any compatibility issues between the frameworks, ensuring smooth and efficient operation of the entire clause generation pipeline.

  5. ***Managing computational resources for development and testing***  
     <b>Challenge: </b> Developing and testing the clause generation pipeline required significant computational resources, which could be challenging to manage, especially during local development.  
     <b>Solution: </b> Adopted a hybrid development environment where resource-intensive tasks were offloaded to cloud-based EC2 instances, while local development and testing utilized optimized, quantized models. Implemented a robust scheduling and resource management system to ensure efficient utilization of computational resources, minimizing downtime and maximizing productivity.




## 📁 Projects

### Competitor's app

<!-- 
python
flask
sql alchemy
pytest
docker
ec2
jwt
pandas
wsgi


ci/cd
rest apis
authorization
authentication
mvc
-->

- **Description**  
  Developed a business intelligence web application for a retail organization to analyze and compare sales performance across brands, stores, and regions. The application enables managers to track historical sales data (from previous years) and input current monthly/yearly sales figures, providing actionable insights into growth trends, competitor benchmarking, and store-level performance.

  
- **Role and Responsibilities**  
  - Designed sequence diagrams to model application workflows and ensure clarity in service interactions.
  - Structured the application using MVC architecture, separating models (SQLAlchemy), controllers (business logic), and views (API endpoints).
  - Built RESTful APIs to handle CRUD operations, user authentication, and data processing tasks.
  - Implemented JWT authentication and authorization to secure endpoints and manage user roles.
  - Processed and transformed large datasets using pandas DataFrames for analytics and reporting.
  - Integrated caching mechanisms (e.g., Redis) to store frequently accessed data, reducing database load by 30%.
  - Utilized SQLAlchemy ORM to define models, execute complex queries, and ensure database-agnostic operations.
  - Enforced data consistency through transaction management, database constraints, and atomic operations.
  - Developed isolated controllers to decouple business logic from data access layers, improving code testability.
  - Containerized the application using Docker and orchestrated multi-container environments for development and production.
  - Wrote unit and integration tests using pytest to achieve 95% code coverage and validate API reliability.
  - Deployed the application with WSGI (Gunicorn) and Nginx to ensure high performance under load.

  
- **Challenges Faced**  
  1. ***Ensuring Data Consistency Across Complex Workflows***  
  <b>Challenge: </b> Concurrent data updates and distributed transactions risked inconsistencies.  
  <b>Solution: </b> Implemented database transactions with SQLAlchemy’s session management and added retry logic for failed operations.

  2. ***Efficient Processing of Large Datasets***  
     <b>Challenge: </b> In-memory data processing with DataFrames caused performance bottlenecks.   
     <b>Solution: </b> Optimized DataFrame operations using chunking, indexing, and lazy loading, reducing memory usage by 25%.

  3. ***Testing Database-Dependent Workflows***  
     <b>Challenge: </b> Complex database interactions made tests slow and difficult to isolate.    
     <b>Solution: </b>  Leveraged pytest fixtures to mock SQLAlchemy sessions and create ephemeral test databases.
  


---


### DigiCelcom

<!-- 
nodejs
typescript
docker
ec2
jwt
sendgrid
puppeteer
mocha
nx console
redis
mysql
s3


ci/cd
rest apis
authorization
authentication
dependency injection
-->

<div id="nitro-img" align="center">
  <img src="https://github.com/user-attachments/assets/98a6e4fb-e4aa-42c7-82de-a21a2ed6873b" />
</div>

- **Description**  
  Developed a high-performance backend system for a telecom company’s mobile application, enabling users to manage telecom services seamlessly. The application supported critical functionalities such as SIM card ordering, prepaid/postpaid package purchases, wallet-based transactions, subscription management (add-ons, unsubscribing), and real-time due deductions. Designed to handle high concurrent traffic, the system integrated with payment gateways, telecom infrastructure APIs, and notification services while ensuring security, scalability, and reliability. Built using Node.js in a monorepo (managed via Nx Console), it employed Docker for containerization, Redis for caching, and MySQL for transactional data storage. Key features included PDF invoice generation, email notifications, and role-based access control.

  
- **Role and Responsibilities**  
  - Designed and developed RESTful APIs to support user workflows: SIM ordering, package selection, wallet transactions, and subscription management.
  - Integrated third-party APIs (e.g., payment gateways, SMS services, telecom provisioning systems) to validate transactions, activate services, and sync user data.
  - Secured endpoints using JWT-based authentication and Passport.js strategies, enforcing role-based access for users and admin roles.
  - Implemented the dependency injection design pattern to decouple service logic, enhancing testability and scalability across modules.
  - Built a modular monorepo with Nx Console to manage shared libraries, utilities, and microservices efficiently.
  - Developed an email service using SendGrid to notify users about order confirmations, payment receipts, and subscription updates.
  - Automated PDF invoice generation from HTML templates using Puppeteer, ensuring consistent branding and dynamic data rendering.
  - Optimized performance using Redis to cache frequently accessed data (e.g., package details, user balances) and rate-limit API requests.
  - Dockerized services for consistent deployment and orchestrated cloud storage of invoices/assets using AWS S3.
  - Wrote comprehensive test suites with Mocha to validate API logic, edge cases, and integration workflows.


  
- **Challenges Faced**  
  1. ***High Latency in Third-Party API Integrations***
    <b>Challenge: </b> Frequent delays and timeouts when interacting with external APIs affected user experience.  
    <b>Solution: </b>  Implemented Redis caching for frequently accessed data and optimized parallel API calls to reduce response times by 40%.

  2. ***Testing Complex Service Dependencies***
     <b>Challenge: </b> Testing interdependent services in a monorepo led to flaky tests and false positives.  
     <b>Solution: </b> Isolated test environments using Mocha hooks and Nx Console’s dependency graph to run targeted tests, ensuring reliability.

  3. ***Resource-Intensive PDF Generation***
     <b>Challenge: </b> Generating PDFs from dynamic HTML templates caused server bottlenecks.   
     <b>Solution: </b>  Offloaded PDF rendering to a dedicated service using Puppeteer and optimized HTML templates with precompiled layouts.
  


---


### Nitro

<!-- 
nodejs
typescript
docker
ec2
jwt
jest
redis
dynamodb
s3
solidity
hardhat
newrelic
keycloak
metamask


ci/cd
rest apis
authorization
authentication
dependency injection
chain of responsibility
decorator
-->

<div id="nitro-img" align="center">
  <img src="https://i.ytimg.com/vi/7ZyDbpt-7p4/maxresdefault.jpg" />
</div>

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

---

### WhatsApp Web Nativefier Linux App

<!-- 
linux
shell
Nativefier
nodejs


-->

<div id="techpurview-img" align="center">
  <img width="1785" alt="303564370-41c0c3d3-4803-451e-9df9-8acb20fd2908" src="https://github.com/user-attachments/assets/d2fd9347-181d-4397-abea-2e69c834c343">
</div>

- **Description**  
  WhatsApp Web Nativefier Linux App is a straightforward application that utilizes Nativefier to package WhatsApp Web as a native desktop application for Linux. By wrapping WhatsApp Web in a dedicated browser window with Nativefier, the app provides a seamless, standalone experience on Linux, mimicking a native application’s look and feel while maintaining the web-based functionality of WhatsApp.

- **Role and Responsibilities**  
  As the primary developer, my responsibilities included setting up and configuring Nativefier to create a dedicated application window for WhatsApp Web. I managed the customization of the app’s appearance and functionality to ensure an optimal user experience. This included configuring the app settings, testing across different Linux distributions, and addressing any compatibility issues.
  
- **Challenges Faced**  
  1. ***Customization of Nativefier Output***  
  <b>Challenge: </b> Achieving the desired appearance and functionality of the application through Nativefier’s default settings.  
  <b>Solution: </b> Customized the Nativefier build by modifying configuration options to adjust the window size, icon, and other visual aspects. Implemented additional scripts to handle specific user interface preferences and ensured that the application adhered to the visual standards expected from a native desktop app.

  2. ***Performance Optimization***  
     <b>Challenge: </b> Maintaining responsive performance while running WhatsApp Web within a Nativefier-generated application.   
     <b>Solution: </b> Implemented a caching layer using Redis to store frequently accessed assets, significantly reducing retrieval times. Additionally, I set up asynchronous processes to prefetch and update the cache with the latest assets, ensuring that the most current data was available with minimal delay. Employed background jobs using AWS Lambda functions to handle periodic asset updates.

- **[site](https://github.com/khqnn/linux-whatsapp)**

---

### TechPurview

<!-- 
nodejs
typescript
typeorm
docker
ec2
jwt
jest
redis
postgresql
s3


ci/cd
rest apis
authorization
authentication
dependency injection
chain of responsibility
decorator
-->

<div id="techpurview-img" align="center">
  <img width="1785" alt="303564370-41c0c3d3-4803-451e-9df9-8acb20fd2908" src="https://github.com/user-attachments/assets/0cd63094-8ecd-4ccb-bae3-b40439483033">
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

---

### Tossdown

<!-- 
nodejs
typescript
typeorm
docker
ec2
jwt
jest
redis
memcache
postgresql
mysql
dynamodb
elasticsearch
mongodb
s3
new relic
pandas
pusher


query optimization
ci/cd
rest apis
authorization
authentication
dependency injection
chain of responsibility
decorator
reports
data analysis
-->

<div id="tossdown-img" align="center">
  <img width="1181" alt="303564782-10c4665a-97e4-46b8-8f0d-171f17c6b737" src="https://github.com/user-attachments/assets/dda63277-4722-4762-96b0-0d0831c70253">
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

---

### Alpolink

<!-- 
nodejs
php
jwt
jest
redis
mysql
mongodb

query optimization
rest apis
authorization
authentication
-->

<div id="tossdown-img" align="center">
  <img width="1781" alt="303568944-b1682850-9cb2-4586-af01-6949c5f654e3" src="https://github.com/user-attachments/assets/42939368-e76e-4c2a-85ff-a5d4aa9fb98d">
</div>

- **Description**  
  Alpolink is a platform for selling exam dumps, developed using PHP and the CodeIgniter framework, with MySQL as the database management system.

- **Role and Responsibilities**  
  As a senior software engineer for Alpolink, my responsibilities included addressing architectural challenges and optimizing system performance.

- **Challenges Faced**  
  1. ***Architectural Complexity***  
     <b>Challenge: </b> Each website had its own frontend and database instance, leading to complexities in managing and maintaining multiple codebases and databases. This fragmented architecture resulted in higher operational overhead, difficulties in applying updates, and increased risk of inconsistencies.  
     <b>Solution: </b>Implemented a unified backend architecture where a single backend serves multiple websites. This approach consolidated the codebases and databases, reducing complexity. The unified backend enabled centralized management, allowing for easier maintenance and scalability. Updates and bug fixes could be applied universally, improving operational efficiency and consistency across the platform.

  2. ***Performance Optimization***  
     <b>Challenge: </b> The platform needed to handle a growing number of users and data without compromising speed and reliability. The initial architecture with multiple database instances led to inefficient resource usage and slower response times.  
     <b>Solution: </b> Optimized the system by consolidating the databases, which allowed for better indexing and query handling. Implemented caching mechanisms using Memcached to store frequently accessed data, reducing the load on the database and improving response times. Additionally, code optimization and load balancing techniques were applied to enhance overall system performance.

  3. ***Scalability***  
     <b>Challenge: </b> Ensuring the platform could scale efficiently to accommodate more websites and users without significant overhead in maintenance and resource allocation.  
     <b>Solution: </b> The unified backend architecture inherently provided a scalable solution. By managing a single codebase and database system, adding new websites to the platform became straightforward. Employed containerization Docker to automate deployments and manage resources dynamically. This ensured the platform could handle increased load and scale horizontally as needed, all while maintaining ease of maintenance and operational simplicity.

  4. ***Data Consistency and Integrity***  
     <b>Challenge: </b> Ensuring data consistency and integrity across multiple websites and a single backend can be challenging, especially during high traffic or concurrent access scenarios.  
     <b>Solution: </b> Implemented database transactions to ensure data consistency and integrity during multiple operations. Used MySQL’s ACID properties to maintain data accuracy and reliability. Applied data validation both at the application and database levels to prevent incorrect data entry.

  5. ***Deployment and CI/CD***  
     <b>Challenge: </b> Managing deployments and continuous integration/continuous deployment (CI/CD) for a platform serving multiple websites.  
     <b>Solution: </b> Set up a robust CI/CD pipeline using tools like Jenkins to automate testing, building, and deployment processes. Containerized the application using Docker, enabling consistent environments across development, testing, and production. 

  

- **[site](https://www.certificationsbuzz.com/)**


---

### Aanganpk

<!-- 
nodejs
php
wordpress
mysql

query optimization
rest apis
reports
-->

<div id="aangan-img" align="center">
  <img width="1349" alt="303569709-6b2bc488-3e4b-4a6a-9b4e-efa61e9d2c4a" src="https://github.com/user-attachments/assets/7372d9ad-0531-40dd-87b1-925a180e7013">
</div>

- **Description**  
  Aanganpk is a multivendor ecommerce platform specializing in Pakistani women's handcrafted items. The platform is built using WordPress with WooCommerce plugin, leveraging PHP for customizations and extensions.

- **Role and Responsibilities**  
  As a senior software engineer for Aanganpk, my responsibilities included addressing platform limitations and customizing functionalities to meet business requirements.

- **Challenges Faced**  
  1. ***Platform Limitations***  
     <b>Challenge: </b> WordPress and WooCommerce, while flexible, have inherent limitations in handling complex multi-vendor functionalities, which can affect performance and scalability.  
     <b>Solution: </b> Extended WooCommerce functionalities using custom PHP code to better handle multi-vendor operations. Developed custom plugins and utilized hooks and filters to tailor the platform to specific business needs without compromising performance. Optimized database queries and implemented caching mechanisms to enhance performance.

  2. ***Vendor Management***  
     <b>Challenge: </b> Managing multiple vendors with varying requirements and ensuring a smooth onboarding process was complex.  
     <b>Solution: </b> Created a customized vendor dashboard using PHP and WooCommerce hooks, providing vendors with tools to manage their products, orders, and profile. Implemented role-based access controls to ensure vendors could only access their own data. Developed comprehensive documentation and an onboarding guide to facilitate a smooth vendor setup process.

  3. ***Customization and Extensibility***  
     <b>Challenge: </b> The need for custom features not available in standard WooCommerce and WordPress plugins to meet specific business requirements.  
     <b>Solution: </b> Developed custom PHP plugins and extensions to add the required features. Used child themes and custom templates to modify the frontend appearance and functionality without affecting the core theme. Ensured all customizations adhered to WordPress coding standards for maintainability and compatibility with future updates.

  

- **[site](https://kaarvan.com.pk/portfolio-item/aanganpk-com/)**

---

### Information Retrieval System

<!-- 
python
pandas
numpy
cassandra
postgres

tf/idf
-->

- **Description**  
  The Information Retrieval System is designed to retrieve relevant documents from a corpora using machine learning techniques. It utilizes Support Vector Machine (SVM) algorithms for classification and is implemented in Python within Jupyter Notebook environment. Data is stored and managed in a Cassandra database.

- **Role and Responsibilities**  
  As the sole architect and developer of the Information Retrieval System, I assumed complete ownership of all project aspects. My role involved the design and implementation of sophisticated machine learning algorithms tailored for document classification and retrieval. This project epitomizes my capacity to conceive, execute, and refine complex technical solutions independently.

- **Challenges Faced**  
  1. ***Handling Large Datasets***  
     <b>Challenge: </b> Managing and processing large datasets efficiently to ensure timely document retrieval and accurate results.  
     <b>Solution: </b> Utilized the distributed nature of the Cassandra database to manage large datasets effectively. Implemented data partitioning and replication strategies to ensure high availability and fault tolerance. Leveraged batch processing and parallel computing techniques in Python to handle data preprocessing and feature extraction, significantly reducing processing time.

  2. ***Algorithm Optimization***  
     <b>Challenge: </b> Implementing and optimizing sophisticated machine learning algorithms like TF-IDF for document classification and retrieval.  
     <b>Solution: </b> Developed custom Python functions for TF-IDF calculation, ensuring they were optimized for performance. Applied dimensionality reduction techniques such as Singular Value Decomposition (SVD) to improve the efficiency and accuracy of the retrieval process. Regularly profiled and optimized the code to eliminate bottlenecks and improve overall performance.

  3. ***Precision and Recall Evaluation***  
     <b>Challenge: </b> Evaluating the effectiveness of the retrieval system in terms of precision and recall to ensure relevant documents are retrieved.  
     <b>Solution: </b> Designed and implemented evaluation metrics to measure the precision and recall of the retrieval system. Conducted extensive testing using a validation dataset to fine-tune the algorithms and improve retrieval accuracy. Used confusion matrices and ROC curves to visualize and analyze the performance, making data-driven decisions for further optimization.

  4. ***Data Storage and Management***  
     <b>Challenge: </b> Efficiently storing and managing a large volume of documents and metadata in a Cassandra database.  
     <b>Solution: </b> Designed a scalable schema in Cassandra tailored for efficient retrieval operations. Used Cassandra’s indexing and query capabilities to ensure fast and reliable access to documents. Implemented data consistency and integrity checks to maintain the quality of stored data.

  5. ***Scalability and Performance***  
     <b>Challenge: </b> Ensuring the system can scale to handle increasing volumes of data and user queries without degradation in performance.  
     <b>Solution: </b> Leveraged the distributed architecture of Cassandra to scale horizontally, adding more nodes as needed to handle increased load. Implemented load balancing techniques to distribute user queries evenly across the system, preventing bottlenecks and ensuring consistent performance. Continuously monitored system performance and made necessary adjustments to maintain efficiency.


---

### Stealth Address Library

<!-- 
python
ec25519
x25519
pypi

cryptography
web3
signing and verification
shared secrete
-->

- **Description**  
  Stealth Addresses is a cryptographic project focused on generating secure and private addresses for transactions. It utilizes the x25519 algorithm for shared secret generation and the ed25519 algorithm for signature generation and verification.

- **Role and Responsibilities**  
  As the sole proprietor and developer of the Stealth Address Library project, I assumed full ownership and accountability throughout its lifecycle. Responsibilities encompassed every aspect, from conceptualization and design to implementation and refinement. This project epitomizes my capacity to initiate, execute, and deliver complex technical initiatives independently.

- **Challenges Faced**  
  1. ***Integrating x25519 and ed25519 algorithms***  
     <b>Challenge: </b> Integrating the x25519 algorithm for shared secret generation with the ed25519 algorithm for signature generation and verification posed challenges due to their different purposes and implementations.  
     <b>Solution: </b> Implemented an initial stealth address generation mechanism using the shared secret methodology of x25519, ensuring that the process of creating secure and private addresses was initiated correctly. Instead of relying on standard libraries for ed25519, developed a custom core implementation based on RFC8032 specifications. This approach allowed for seamless integration and ensured that the unique requirements of the project were met, maintaining high security standards.

  2. ***Ensuring compatibility between cryptographic algorithms***  
     <b>Challenge: </b> Ensuring that the x25519 and ed25519 algorithms worked together seamlessly, despite their differing cryptographic purposes and underlying mathematical principles, was complex.  
     <b>Solution: </b> Utilized advanced mathematical and cryptographic principles to design a robust mechanism for generating stealth addresses. This involved a deep understanding of both algorithms and their interaction to ensure compatibility and security. Conducted iterative testing and validation to verify that the integrated algorithms worked together as intended. This process helped identify and resolve any compatibility issues, ensuring the reliability of the stealth address generation process.

  3. ***Developing a custom implementation of ed25519***  
     <b>Challenge: </b> Creating a custom implementation of the ed25519 algorithm required a comprehensive understanding of its specifications and intricate details, as well as ensuring it adhered to security standards.  
     <b>Solution: </b> Followed the RFC8032 specifications meticulously to develop a custom core implementation of ed25519. This ensured that the algorithm was implemented correctly and securely, avoiding potential pitfalls associated with standard libraries.


---

<!-- 
php
nodejs
dynamodb
mysql



data mining
a priori
pattern finding
rest api
authorization
-->

### Products Pair
- **Description**  
  Products Pair is a system designed to predict the probability of items being sold together. The Apriori algorithm is utilized to calculate these probabilities based on transactional data.

- **Role and Responsibilities**  
  As a senior software engineer for the Products Pair project, my responsibilities included designing and implementing the predictive algorithm and optimizing system performance.

- **Challenges Faced**  
  1. ***High latency in retrieving probabilities from transactional database***  
     <b>Challenge: </b> Implementing the Apriori algorithm was successful, but retrieving probabilities of product pairs from the transactional database (MySQL) each time resulted in high latency. This negatively impacted system performance and user experience.  
     <b>Solution: </b> Implemented a denormalized data store that periodically updates data from the transactional database. This data store contains pre-calculated probabilities of product pairs, allowing for faster retrieval. Scheduled batch processes to update the denormalized data store at regular intervals, ensuring that the data remains current while minimizing the impact on the transactional database.

  2. ***Ensuring data consistency between transactional and denormalized databases***  
     <b>Challenge: </b> Maintaining consistency between the transactional database and the denormalized data store was crucial to ensure accurate probability calculations and system reliability.  
     <b>Solution: </b> Developed a robust synchronization mechanism to ensure that updates in the transactional database are reflected in the denormalized data store without significant delays. Implemented conflict resolution strategies to handle discrepancies between the two data stores, ensuring data integrity and consistency.

  3. ***Optimizing the Apriori algorithm for large datasets***  
     <b>Challenge: </b> The Apriori algorithm can be computationally intensive, especially when dealing with large transactional datasets, leading to performance issues.  
     <b>Solution: </b> Optimized the Apriori algorithm by implementing efficient data structures and pruning strategies to reduce the search space and computational overhead. Utilized parallel processing techniques to distribute the computation across multiple cores or nodes, significantly reducing the time required to calculate product pair probabilities.

  4. ***Handling real-time updates and maintaining low latency***  
     <b>Challenge: </b> Ensuring that the system can handle real-time updates and maintain low latency for probability queries was essential for providing timely and accurate predictions.  
     <b>Solution: </b> Implemented incremental update mechanisms that allow the system to update probabilities of product pairs in real-time based on new transactional data without requiring a complete recalculation. Utilized caching strategies to store frequently accessed probabilities in memory, reducing the need for repetitive database queries and further lowering latency.


---

### Reports management system

<!-- 
php
nodejs
mysql
new relic
memecache



data mining
data cubes
data dimensions
data warehouse
stored procedures
multi-tenant
-->

- **Description**  
  The Reporting System is designed to generate multitenant reports using data cubes and slices. It provides insights into various dimensions such as time, product, category, branch, and brand, catering to the diverse reporting needs of hundreds of clients. Reports can be saved and they're continuesly updated.

- **Role and Responsibilities**  
  As a senior software engineer for the Reporting System project, my responsibilities included designing and implementing the reporting functionalities, ensuring scalability and efficiency.

- **Challenges Faced**  
  1. ***Making reports generic for hundreds of clients***  
     <b>Challenge: </b> Ensuring that the reporting system can generate and handle reports for hundreds of clients with diverse requirements and data structures posed a significant challenge.  
     <b>Solution: </b> Designed a multitenant architecture that isolates data and configurations for each client, allowing the system to generate tailored reports while maintaining efficiency. Implemented a flexible configuration management system that allows customization of report dimensions and filters based on client-specific requirements.

  2. ***Calculating dimensions from transactional data for each client***  
     <b>Challenge: </b> Calculating dimensions such as time, product, category, branch, and brand from transactional data for each client required significant computational resources and time.  
     <b>Solution: </b> Developed a mechanism to pre-calculate dimensions for data cubes from transactional data. These dimensions are then stored in a cache (e.g., Memcached) for efficient retrieval during report generation. Utilized batch processing to periodically update and pre-calculate dimensions, ensuring that the data remains current and reduces the load during real-time report generation.

  3. ***Continuous updating and saving of reports***  
     <b>Challenge: </b> Reports needed to be continuously updated with the latest data and saved for future retrieval, which required efficient mechanisms to manage data consistency and report storage.  
     <b>Solution: </b> Implemented incremental update mechanisms that allow the system to update reports with new data in real-time, ensuring that reports are always up-to-date without requiring full recalculations. Utilized efficient storage solutions to save reports, including leveraging database partitioning and archiving strategies to manage large volumes of report data.

  4. ***Handling complex data cubes and slices***  
     <b>Challenge: </b> Managing complex data cubes and slices for generating detailed and multidimensional reports added to the complexity of the system.  
     <b>Solution: </b> Developed dynamic data cubes that can be configured and adjusted based on client requirements, allowing for flexible and detailed report generation. Implemented efficient data slicing techniques to handle various dimensions and filters, enabling the system to generate reports quickly and accurately based on user-defined criteria.

  5. ***Ensuring data security and privacy***  
     <b>Challenge: </b> Given the multitenant nature of the system, ensuring data security and privacy for each client's data was paramount.  
     <b>Solution: </b> Implemented robust access control mechanisms to ensure that only authorized users can access and generate reports for their respective clients.


---

### KidSafe

<!-- 
nodejs
typescript
postgresql
mongodb
youtube apis



-->

- **Description**  
  KidSafe is an application designed to provide a safe environment for children to watch YouTube videos. It utilizes the YouTube API to curate a selection of kid-friendly content.

- **Role and Responsibilities**  
  As a senior software engineer for the KidSafe project, my responsibilities included implementing features, integrating APIs, and ensuring child safety and usability.

- **Challenges Faced**  
  1. ***Manual video selection by parents***  
     <b>Challenge: </b> Initially, the app was designed to allow parents to manually select videos for their children. This approach was cumbersome and time-consuming for parents, reducing the usability and efficiency of the app.  
     <b>Solution: </b> Shifted from manual selection to an automated process by integrating functionality to include all videos from a specified YouTube channel. This significantly streamlined the user experience, making it easier for parents to provide a curated list of kid-friendly content.

  2. ***Fetching videos by YouTube channel name***  
     <b>Challenge: </b> Integrating functionality to automatically include all videos from a YouTube channel posed a challenge, as the YouTube API does not provide direct access to fetch videos by channel name.  
     <b>Solution: </b> Developed a Python service using Beautiful Soup to scrape the web and fetch the YouTube channel ID using the channel name. This involved parsing the HTML of the YouTube channel page to extract the channel ID. Once the channel ID was obtained, implemented recursive calls to the YouTube API to fetch all videos associated with the channel. This ensured that the app could automatically and efficiently gather all relevant videos for inclusion in the KidSafe app.

  3. ***Ensuring child safety and content appropriateness***  
     <b>Challenge: </b> Ensuring that all videos included in the app were appropriate and safe for children was critical.  
     <b>Solution: </b> Implemented additional content filtering mechanisms to verify the suitability of videos. This included checking video metadata, descriptions, and comments for any inappropriate content. Added parental control features allowing parents to review and approve the automatically fetched videos before making them accessible to children, providing an additional layer of safety.

  4. ***Handling API rate limits and data fetching efficiency***  
     <b>Challenge: </b> Efficiently fetching large numbers of videos while respecting YouTube API rate limits was a technical challenge.  
     <b>Solution: </b> Implemented rate limit management techniques, such as batching requests and using exponential backoff strategies, to ensure compliance with YouTube API limits. Optimized the data fetching process by implementing pagination and caching strategies, reducing the number of API calls and improving the performance and responsiveness of the app.

  5. ***Maintaining a user-friendly interface***  
     <b>Challenge: </b> Ensuring that the app's interface remained user-friendly and intuitive despite the added complexity of automated content fetching.  
     <b>Solution: </b> Focused on designing a clean and intuitive user interface that simplifies navigation and content discovery for both parents and children. Ensured seamless integration of the new automated features into the existing interface, providing clear instructions and feedback to users throughout the process.


 ---

### Notifications Service

<!-- 
nodejs
typescript
postgresql
mongodb
dynamodb
firebase
fcm


event loop
asynch programming
offloading
clustering
-->

- **Description**  
  The Notifications Service is designed to deliver up to 1,000 notifications per minute efficiently. It utilizes Firebase Cloud Messaging (FCM) for message delivery, Cassandra for data storage, and supports features such as retry mechanisms and recurring/one-time notifications.

- **Role and Responsibilities**  
  As a senior software engineer for the Notifications Service project, my responsibilities included architecting the system, optimizing performance, and ensuring reliable delivery of notifications.

- **Challenges Faced**  
  1. ***Inefficient query performance due to data model design***  
     <b>Challenge: </b> The initial data model had the partition key set as the job_id and the sort key as the next notification trigger time. This design caused slower query performance because queries for the next jobs to be executed needed to scan across all partitions, especially when multiple partitions had the same next notification trigger time.  
     <b>Solution: </b> Redesigned the data model by setting the next notification timestamp as the partition key and the job_id as the sort key. This change ensured that all notifications scheduled for the same time were stored within the same partition. This redesign improved query efficiency by localizing the data related to the same trigger time within a single partition, thus reducing the need to scan multiple partitions and significantly enhancing performance and reducing latency.

  2. ***Handling high throughput of notifications***  
     <b>Challenge: </b> Delivering up to 1,000 notifications per minute required a system capable of handling high throughput without performance degradation.  
     <b>Solution: </b> Architected the system to utilize parallel processing and asynchronous operations, ensuring that notification delivery could scale horizontally as the load increased.

  3. ***Ensuring reliable delivery of notifications***  
     <b>Challenge: </b> Reliable delivery of notifications, including retry mechanisms for failed deliveries, was critical for the service's success.  
     <b>Solution: </b> Developed robust retry mechanisms to handle transient failures in notification delivery. Implemented exponential backoff strategies to manage retries, ensuring that the system did not become overwhelmed by repeated immediate retries.

  4. ***Supporting recurring and one-time notifications***  
     <b>Challenge: </b> The system needed to support both recurring and one-time notifications, adding complexity to the scheduling and delivery logic.  
     <b>Solution: </b> Designed a flexible scheduling system capable of managing both recurring and one-time notifications. Implemented mechanisms to track and manage recurring schedules, ensuring accurate and timely delivery of notifications. Optimized data storage and retrieval to handle the different requirements of recurring and one-time notifications, ensuring efficient processing regardless of the notification type.

  5. ***Scalability and data consistency***  
     <b>Challenge: </b> Ensuring that the system could scale to handle increasing load while maintaining data consistency was a critical challenge.  
     <b>Solution: </b> Built the system on a scalable infrastructure, leveraging Cassandra's distributed nature to handle large volumes of data and high throughput. Implemented strategies for ensuring data consistency across distributed nodes, such as using lightweight transactions and carefully designed consistency levels in Cassandra.

  6. ***Latency and timely notification delivery***  
     <b>Challenge: </b> Minimizing latency and ensuring timely delivery of notifications were essential for the service's effectiveness.  
     <b>Solution: </b> Optimized data access patterns to reduce latency in retrieving and processing notifications. The redesigned data model played a crucial role in achieving this by localizing relevant data. Implemented real-time processing techniques to ensure that notifications were delivered at the correct times, leveraging efficient scheduling and immediate processing upon trigger events.

  
---

### Google Map Scraper

<!-- 
Description:The Google Map Scraper is a tool designed to extract information about stores from Google
Maps based on location and store type. It is built using Python, with Beautiful Soup and Selenium utilized
for web scraping.

Role and Responsibilities:As the sole creator and developer of the Google Map Scraper, I orchestrated
all facets of the project, from conceptualization to implementation. My responsibilities encompassed
designing the scraping process, integrating essential web scraping libraries, and fine-tuning data
extraction mechanisms. This project underscores my adeptness in independently driving and delivering
complex technical solutions.
-->

<!-- 
python
cron jobs
beautiful soap
selenium
mongodb


web scraping
-->

- **Description**  
  The Google Map Scraper is a tool designed to extract information about stores from Google Maps based on location and store type. It is built using Python, with Beautiful Soup and Selenium utilized for web scraping.

- **Role and Responsibilities**  
  As the sole creator and developer of the Google Map Scraper, I orchestrated all facets of the project, from conceptualization to implementation. My responsibilities encompassed designing the scraping process, integrating essential web scraping libraries, and fine-tuning data extraction mechanisms. This project underscores my adeptness in independently driving and delivering complex technical solutions.

- **Challenges Faced**  
  1. ***Dynamic Rendering of Google Maps***    
  <b>Challenge: </b> Google Maps uses dynamic rendering techniques that load content asynchronously, making
it difficult for traditional web scraping tools like Beautiful Soup to access the dynamically loaded data.    
  <b>Solution: </b> Employed Selenium to automate a web browser to interact with the Google Maps
webpage. Selenium is capable of handling JavaScript and waiting for the page to fully render before
accessing the content. This approach allowed for capturing all dynamically loaded data. Implemented mechanisms in Selenium to wait for specific elements to load
completely, ensuring that all relevant data was available before starting the extraction process.

  2. ***Extracting Detailed Metadata***  
  <b>Challenge: </b> Extracting detailed information such as store addresses, star ratings, phone numbers, and
photos from the rendered Google Maps page required a methodical approach to handle the complex
HTML structure.  
  <b>Solution: </b> Used Selenium to navigate through the Google Maps interface and
extract metadata related to each store. This included using XPath or CSS selectors to locate and retrieve
the necessary data. After obtaining the metadata, utilized Beautiful Soup to
parse the HTML and extract detailed information about each store, including addresses, ratings, phone
numbers, and photos.

  3. ***Managing Data Extraction Efficiency***  
  <b>Challenge: </b> Efficiently managing the data extraction process to handle multiple stores and pages while
maintaining performance and avoiding timeouts or errors was critical.  
  <b>Solution: </b> Implemented pagination handling in Selenium to navigate through multiple pages of
search results. This ensured that the scraper could extract data from all relevant pages. Used concurrency techniques to speed up the extraction process while
implementing throttling to avoid overwhelming the Google Maps servers and to adhere to ethical scraping
practices.
  
  4. ***Data Accuracy and Consistency***  
  <b>Challenge: </b> Ensuring the accuracy and consistency of the extracted data was crucial, as discrepancies
in store information could impact the reliability of the scraper.  
  <b>Solution: </b> Incorporated data validation checks to verify the accuracy of the extracted information.
This included cross-referencing data with multiple sources or validating against known patterns. Implemented robust error handling and logging mechanisms to capture and
address issues during the scraping process, allowing for accurate data extraction and easier debugging.

