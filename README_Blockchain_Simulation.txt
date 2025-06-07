
README: Blockchain Simulation Dataset (100,000+ entries)

This dataset contains simulated performance measurements for three blockchain interoperability protocols:
- ASTRA
- Cosmos IBC
- Polkadot XCMP

Each row in the dataset represents a simulation entry with the following fields:

1. Protocol: The blockchain protocol tested (ASTRA, Cosmos IBC, or Polkadot XCMP).
2. Throughput_TPS: Number of transactions per second achieved.
3. Latency_Seconds: Average cross-chain message confirmation latency.
4. Success_Rate_Percent: Percentage of cross-chain messages successfully validated.
5. CPU_Utilization_Percent: Average CPU usage during the simulation run.
6. Bandwidth_Utilization_Percent: Average bandwidth usage.

Units:
- Throughput in transactions per second (TPS)
- Latency in seconds
- Success rate, CPU, and bandwidth in percentages (%)

Note: The data is synthetically generated using normal distributions around observed experimental averages to facilitate statistical modeling, benchmarking, and algorithm development.

Author: Dr. Fahad Rahman
Generated with OpenAI GPT-4
