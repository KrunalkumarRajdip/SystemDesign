# Scalability

Scalability is the ability of a system to handle growing amounts of work in a graceful manner. In the context of system design, scalability refers to designing systems that can accommodate increased loads and user bases without sacrificing performance or reliability.

## Topics Covered

1. **Horizontal Scaling**: 
   - Horizontal scaling, also known as scaling out, involves adding more machines or instances to distribute the load across multiple servers. It helps in accommodating increased traffic by adding more resources.

2. **Vertical Scaling**: 
   - Vertical scaling, also known as scaling up, involves upgrading the existing hardware (e.g., CPU, memory) to handle increased loads. While vertical scaling can improve performance, it has limitations in terms of scalability compared to horizontal scaling.

3. **Sharding**: 
   - Sharding is a technique used to horizontally partition data across multiple databases or servers. It helps in distributing the data and workload evenly, thereby improving scalability and performance.

4. **Load Balancing**: 
   - Load balancing involves distributing incoming network traffic across multiple servers or resources to ensure optimal resource utilization and prevent overloading of any single server. Various load balancing algorithms can be used based on factors like server health, response time, and server capacity.

## Further Reading

- [Scaling Up vs. Scaling Out](https://stackoverflow.com/questions/11707879/scaling-up-vs-scaling-out)
- [Introduction to Database Sharding](https://medium.com/@adrianm/what-is-database-sharding-804e5a74e007)
- [Introduction to Load Balancing](https://www.nginx.com/resources/glossary/load-balancing/)
- [build-scalable-notification-service](https://blog.quastor.org/p/build-scalable-notification-service)
- [AWS autoscaling](https://aws.amazon.com/autoscaling/)
- [a-brief-history-of-scaling-netflix](https://blog.bytebytego.com/p/a-brief-history-of-scaling-netflix)
- [sharding](https://hazelcast.com/glossary/sharding/)
- [types-of-load-balancing-algorithms](https://www.cloudflare.com/en-gb/learning/performance/types-of-load-balancing-algorithms/)
- [elasticloadbalancing](https://aws.amazon.com/elasticloadbalancing/)
