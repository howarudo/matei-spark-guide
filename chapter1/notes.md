# Chapter 1 What is Apache Spark?

## Philosophy
A unified computing engine, and libraries for big data

### Unified
- **Unified Platform** for big data applications (Streaming, analytics, ML)
- Combination of general APIs and high-performance execution

### Computing Engine
- Limits scope to **computing engine** -> Only loads and perform computation, not permanent storage itself
- Data is stored in a combination of storages, so better to foucs on computation performance
- Hadoop strives to be both, but there was S3, and other cloud, so better Spark

### Libraries
- Provide unified API for common data analysis tasks

## The big data problem and History of Spark
- After 2005, due to heat dissipation problems, developers started adding more parallel CPU for speed, allowing parallelism based program like Apache Spark to strive
- Camera resolution, data collection becomes faster -> more data is collected but is expensive
- More complex data processing applications are needed
- Cluster computing engines like MapReduce proved to be powerful in 2009 but took time to pass data between clusters. Spark team designed **API based on functinal programming that express multistep applications**. This API is implemented over an engine that could perform **efficient, in-memory data sharing** across computation steps
