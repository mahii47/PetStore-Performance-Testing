# PetStore Performance Testing

## Project Overview

This project demonstrates performance testing of a PetStore application using Apache JMeter, InfluxDB, and Grafana.

The objective was to simulate multiple users, execute different application workflows, collect performance metrics, and visualize the results.

## Tools & Technologies

- Apache JMeter
- InfluxDB
- Grafana
- Performance Testing
- Load Testing

## Test Scenarios

The following user journeys were included in the performance test:

- Login
- Fish Order
- Dogs Order
- Cat Order
- Reptiles Order
- Birds Order
- Logout

## Load Test Configuration

The test used different load levels with:

- Initial delay
- Startup time
- Hold load duration
- Shutdown time

## Performance Metrics

The following metrics were monitored:

- Response Time
- Throughput
- Error Rate
- Total Requests
- Number of Samples

## Test Results

| Metric | Result |
|---|---:|
| Total Samples | 3,119 |
| Average Response Time | 3.47 seconds |
| Throughput | 17.5 requests/sec |
| Error Rate | 0.83% |

## Monitoring

JMeter test results were integrated with InfluxDB and visualized using Grafana.

## Project Structure

```text
PetStore-Performance-Testing/
│
├── JMeter/
│   └── PetStore.jmx
│
├── Reports/
│   └── JMeter_Load_Test_Summary_Report.png
│
├── Grafana/
│   └── Grafana_Performance_Dashboard.png
│
├── InfluxDB/
│   └── InfluxDB_Response_Time_Metrics.png
│
├── Test-Configuration/
│   └── Load_Test_Thread_Schedule.png
│
└── README.md
