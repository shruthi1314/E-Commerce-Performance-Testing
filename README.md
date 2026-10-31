# E-Commerce Website Performance Testing Using Apache JMeter
## Tools Used
- Apache JMeter
- Docker
- ## Test Scenarios
The following load test scenarios were executed using Apache JMeter:
| Test Scenario | Number of Users |
|---|---:|
| Test 1 | 50 |
| Test 2 | 100 |
| Test 3 | 200 |
| Test 4 | 400 |
E-Commerce-Performance-Testing/
│
├── 50-Users-Test-Plan.jmx
├── 100-Users-Test-Plan.jmx
├── 200-Users-Test-Plan.jmx
├── 400-Users-Test-Plan.jmx
└── README.md
The performance test aims to analyze the following metrics:
- Response Time
- Throughput
- Error Rate
- Average Response Time
- Number of Successful Requests
- Number of Failed Requests
- ## How to Run the Project
1. Install Apache JMeter.
2. Start the application using Docker.
3. Open Apache JMeter.
4. Load the JMeter test plan (.jmx) file.
5. Configure the number of users and ramp-up period.
6. Execute the test.
7. Analyze the results using JMeter listeners.
8. ## Conclusion
This project helps to understand the basics of performance testing using Apache JMeter and Docker.
It focuses on evaluating application performance under different user loads and understanding key performance metrics such as response time, throughput, and error rate.
  

