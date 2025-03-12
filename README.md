# 📊 JMeter Performance Testing  

##  Project Overview  
This repository contains **JMeter test plans** and a **performance report** used to evaluate system performance under different load conditions. The tests assess response times, error rates, and overall system reliability to ensure optimal performance.  

## 📂 Project Structure  
JMeter-Performance-Testing \
├── 📄 JMeter_Assignment.jmx # Main JMeter test plan \
├── 📄 First_Load.jmx # Initial load test script \
├── 📄 Second_Load.jmx # Secondary load test script \
└── 📄 Aggregate Report.pdf # Summary of test results and analysis

## 📈 Performance Results  
The performance evaluation was conducted with specific **Service Level Agreements (SLAs)**:  

- ✅ **Total Error Percentage**: **0.13%** (Passed, must be ≤ 10%)  
- ✅ **90% of Requests**: **≤ 484 ms** (Passed, must be ≤ 3 seconds)  
- ✅ **99% of Requests**: **≤ 830 ms** (Passed, must be ≤ 5 seconds)  

All SLAs were successfully met, confirming that the system performs efficiently under the tested load conditions.  

## How to Use  
1. **Clone the repository**  
   ```sh
   git clone https://github.com/GehadAshry/Performance-JMeter.git
2. **Open Apache JMeter**  and load any of the .jmx files.
3. **Configure** test parameters as needed.
4. **Run** the tests and analyze results in JMeter’s Aggregate Report.
5. **Review** the Aggregate Report.pdf for a summary of the performance analysis.
