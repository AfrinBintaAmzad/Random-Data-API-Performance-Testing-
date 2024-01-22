## Technology Used
- Jmeter

## Scenarios
Load testing was conducted using the Random Data API with an expected load of 120,000 users over a 12-hour duration. Multiple tests were executed for 60s, 300s, 600s, and 900s using JMeter. Test scenarios with varying user loads provided TPS breakdowns, and corresponding summaries were recorded in an Excel spreadsheet. Screenshots of the tests, along with an HTML report for the last 900s test involving 2500 users, have been attached.

Additionally, stress testing was performed on the Random Data API to identify the bottleneck or stress point, defined as the threshold where the system begins to exhibit a 1% error rate. Similar to load testing, tests were conducted for 60s, 300s, 600s, and 900s with user loads of 166, 833, 1666, 2500, 3500, 4000, and 3900. The TPS breakdowns for these stress tests were documented in an Excel spreadsheet, and screenshots for the last 900s test with 3900 users were provided for detailed analysis.

Both load and stress testing aimed to assess system performance, identify bottlenecks, and determine how the system behaves under various loads and stress conditions. The collected data and reports serve as valuable resources for optimizing the system for improved responsiveness and scalability.

## How to run project
- download the .jmx file in the project directory
## Prerequisite
- JDK must be installed


![Load Test Strategy](https://github.com/AfrinBintaAmzad/Ques-04-Performance-Testing-/assets/83439797/2ae4ad17-acbe-45c2-b336-c4c79a0feb72)

![stress test point](https://github.com/AfrinBintaAmzad/Ques-04-Performance-Testing-/assets/83439797/eb1eeeab-515d-4244-8142-9e5130e56851)
