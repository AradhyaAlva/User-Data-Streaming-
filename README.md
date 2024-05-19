**User Data Streaming**

The goal os this project is to act as a detailed and comprehensive guide for constructing a robust end-to-end data engineering pipeline. It encompasses the entire lifecycle of data, starting from the ingestion phase, followed by processing, and concluding with storage. The chosen tech stack includes a set of powerful tools such as Apache Airflow for workflow management, Python for scripting and programming, Apache Kafka for real-time data streaming, Apache Zookeeper for centralized service configuration, Apache Spark for large-scale data processing, and Cassandra for distributed database management. To ensure ease of deployment and scalability, all components are containerized using Docker, allowing for efficient management and orchestration of the entire pipeline.



The project is designed with the following components:

- **Data Source**: `randomuser.me` API is used to generate random user data for pipeline.
- **Apache Airflow**: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.
- **Apache Kafka and Zookeeper**: Used for streaming data from PostgreSQL to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.
- **Cassandra**: Where the processed data will be stored.

**Technologies: **
- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker


For more detailed instructions, please check out the video tutorial linked below.

## Watch the Video Tutorial

For a complete walkthrough and practical demonstration, check out our [YouTube Video Tutorial](https://www.youtube.com/watch?v=GqAcTrqKcrY).
