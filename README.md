# Optimizing Uplink Communication of IoT clients in Distributed Ledger Technologies

## Abstract

Distributed Ledger Technology (DLT) or blockchain is recognized as the most assuring distributed and decentralized architecture to assist interaction among a large number of Internet of Things (IoT). The blockchain network consists of set of blockchain nodes (BNs). Resourceconstrained IoT devices act as lightweight clients that can only store the subset of blockchain data and rely on BNs for full information. IoT devices generate a massive amount of data, i.e., uplink traffic and transmit it to BNs as transactions. BNs capacity to handle the requests from light clients will downgrade due to increased load, and consequently BNs will limit the amount of requests processed for each light client or serve the requests slowly. In some cases, BN can completely stop serving the IoT device or just drop the connection. It is challenging
for the BNs to handle large burst of transactions without affecting the underlying connection. Therefore, the main objective of this thesis is to optimize and reduce the uplink traffic sent from the light clients to BNs.

In this thesis, we propose an aggregation scheme, which aggregates the transactions to reduce the uplink communication traffic of IoT devices. Data and signature aggregation are performed based on the position of the aggregation point. We conduct experiments to demonstrate the effectiveness of aggregation scheme. We consider four possible scenarios depending on location of the aggregation point: no aggregation, on-device aggregation, aggregation at a neighboring node and aggregation at the base station. We measure the performance of the proposed aggregation system using various metrics: communication cost and latency.

The results show the gain and drawbacks of using the aggregation schemes. The evaluation shows the 60-99 % reduction in the amount of information transmitted from IoT light clients to the BN based on used aggregation methods. The comparative study of four possible scenarios summarizes that the latency varies depending on the location of the aggregation point, and the location of aggregation can be selected based on the latency tolerated by the blockchain-IoT use case.

## Blockchain-enabled IoT Ecosystem

<img height="350" width="600" src="https://github.com/ManjiriBirajdar/MasterThesis-Blockchain/blob/main/Blockchain-enabled%20IoT%20ecosystem.png"/>

## Contribution

The contributions of the thesis are as follows:

- Propose aggregation approaches to optimize and reduce the uplink traffic sent from light clients to the BNs.

- Implement the proposed aggregation approach

- Evaluate the performance of the aggregation scheme using various metrics such as communication cost and latency. Conduct experiments to demonstrate the communication
overhead of sending signed transactions to the BN.Then,evaluate the effects of sending signed transactions to BN with aggregation and without aggregation and determine
the aggregation cost.

- Conduct comparative study of four scenarios depending on location of the aggregation point where light clients are sending signed transactions to BN with no-aggregation, on-device aggregation, aggregation at a neighboring node and aggregation at the base station.

- Study performance of signature schemes on the IoT device.

## Thesis Outline

This thesis is structured as follows:

- Chapter 2 gives an overview of the background knowledge required to understand this thesis.
- Chapter 3 describes the details of existing schemes to reduce the communication cost of connected IoT devices. Approaches used for optimizing the communication traffic are also discussed.
- Chapter 4 describes about the considered system model in this thesis and introduces the main components of the blockchain system. We describe the components of the
blockchain-tailored for IoT system with respect to Ethereum [38].
- Chapter 5 explains the proposed solution to minimize the uplink communication of the lightweight IoT client with BN. We also discuss the four aggregation scenarios and its aspects based on the aggregation point.
- Chapter 6 describes the implementation of the proposed solution with technical details.
- Chapter 7 provides the outline designed experimental setup to test the proposed implementation.
- Chapter 8 illustrate the performance evaluation of the proposed solution based on defined performance metrics. This section shows the conducted experiments and its
results in graphs.
- Chapter 9 presents the application and use case for given solution.
- Chapter 10 gives remark on the the thesis by providing the findings and its limitations.

