# arXiv-Streaming-Processing
A project to get acquainted with the overall workflow involved in Data Engineering.

Streaming data from arXiv, processing it in real-time using Apache Spark and Apache Kafka, and storing it in a MongoDB Atlas database for analysis is a powerful approach for handling large amounts of scientific papers data.

The process can work as follows:

- Data is streamed from arXiv in real-time and sent to Kafka.
- Spark reads data from Kafka and performs various types of analysis on the data, such as natural language processing or sentiment analysis.
- The processed data can then be stored in MongoDB Atlas, a cloud-based, globally distributed, and fully managed MongoDB database service. With MongoDB Atlas, the data can be easily queried and analyzed in real-time using various tools, such as the MongoDB Charts.

By combining the power of Spark and Kafka for real-time data processing with MongoDB Atlas for data storage and analysis, you can build a robust and efficient system for handling large amounts of scientific papers data in real-time.
