# Data-Lake
API Playground builds data lake infrastructure to index blockchain structure, semi-structured and unstructured data as the Web3 backbone

A data lake is a method of storing data in a natural format in a system or repository that helps to configure data in a various schema and structured forms, usually as object blocks or files. The main idea of a data lake is the unified storage of all data in the protocol, transforming it from raw data to target data for various tasks such as visualization, analytics, and reporting. 

Data in a data lake includes structured data (relational database data), semi-structured data (CSV, XML, JSON, etc.), unstructured data (emails, documents, PDFs), and binary data (images, audio, video), resulting in a centralized data store that holds all forms of data.

In essence, a data lake is an enterprise data architecture approach, and the physical implementation is a data storage platform to manage the storage of massive, multi-chain, multi-discipline data in an enterprise and support rapid processing and analysis of the data. 

In terms of implementation, Hadoop is currently the most commonly used technology for deploying data lakes, but it does not mean that a data lake means a Hadoop cluster. In order to cope with the characteristics of different business needs, MPP database + Hadoop cluster + traditional data warehouse this "hybrid" architecture of the data lake is also more and more appear in the enterprise information construction planning.

A data lake needs to provide sufficient data storage capacity, a storage that holds all the data in an enterprise/organization. 
A data lake can store large amounts of any type of data, including structured, semi-structured and unstructured data. 

The data in the data lake is the original data, a complete copy of the business data. The data in the data lake maintains their original appearance in the business system. The data lake needs to have complete data management capability (complete metadata), which can manage all kinds of data-related elements, including data sources, data formats, connection information, data schema, permission management, etc. 

The data lake needs to have diverse analysis capabilities, including but not limited to batch processing, streaming computing, interactive analysis, and machine learning; at the same time, it also needs to provide certain task scheduling and management capabilities.

The data lake needs to have a complete data lifecycle management capability. Not only does it need to store the original data, but also needs to be able to save the intermediate results of all kinds of analysis and processing, and to record the complete analysis and processing process of the data, so that it can help users trace the generation process of any piece of data in complete detail. 

The data lake needs to have perfect data acquisition and data distribution capabilities. The data lake needs to be able to support a variety of data sources and obtain full/incremental data from relevant data sources; then standardize the storage. The data lake can push the results of data analysis and processing to the appropriate storage engine to meet different application access requirements. 

For multichain data support, the data lake needs to recognize the current consensus state of chains as well as the weights of any forks, in order to ensure that information is not provided until sufficiently finalized.
