# Performance

## Performance Metrics

- **Response Time:** Time between a client sending a request and receiving a response. It includes:
  - **Processing Time:** Time spent in the code, databases, or other parts of the system actively working on processing the request.
  - **Waiting Time:** Time that the request or response spends inactively in the system, often in transit or in queues.
- **Throughput:** Amount of work or data processed by the system per unit of time. It can be measured as tasks accomplished per second or in data units (e.g., megabytes) per second.

## Considerations for Measuring and Analyzing Performance

1. **Correct Measurement of Response Time:**
   - Ensure that both processing time and waiting time are accounted for.
   - Avoid measuring only the processing time and mistaking it for the full response time.
2. **Response Time Distribution:**
   - Analyze response times using percentile distribution rather than just averages or medians.
   - Focus on tail latency, which represents the response times that are longer than the majority.
   - Set performance goals in terms of percentiles and tail latency (e.g., 95th percentile should be less than 30 milliseconds).
3. **Performance Degradation Point:**
   - Identify the point at which performance significantly worsens as the load increases.
   - Investigate the cause of degradation, which could be due to resource utilization (CPU, memory, network, or software queues).

## Key Takeaways

- Performance is a critical quality attribute in large scale systems, encompassing both response time and throughput.
- Accurate measurement and analysis of performance metrics are essential for setting realistic goals and ensuring user satisfaction.
- Understanding and addressing performance degradation is crucial for maintaining system efficiency and reliability.

## Terms

- **Degradation Point:** The point at which performance significantly worsens as the load increases.
