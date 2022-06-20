# theory-distributed-computing
Learning Notes

## Motives of Using Distributed Systems

1. Consensus

The need for a solution where we need to reach a consensus among parties that are dispersed geographically (e.g. online banking, blockchain, bidding platform, etc.)

2. Resource Sharing

* Distributed Databases
* Distributed File Systems
* E.g. BitTorrent

3. Other Reasons

* Data replication
* Horizontal Scalability
* Availability, etc...

MIT Lectures:
* Parallelism
* Fault tolerance (one machine works, one machine fails)
* Physical distributed
* Security / isolated

Challenges:
* Concurrency
* Partial failure
* Performance

## Types of Distributed Systems

Coupling & Scale

* Cluster Computing
  * Homogeneous
  * Management is centralized
  * Used for high-performance minimum downtime
* Grid Computing
  * Heterogeneous and geographically dispersed
  * Management is decentralized
  * Used for large data repositories and high computing power requirements

Architectural Model

* Layered Model 
* Object-based Model
* Data-centered Model
* Event-based Model

## Advantages of Distributed Systems

* Reliability
* **Scalability**
* Fault Tolerance
* Increased Performance

## Disadvantages of Distributed Systems

* Hard to detect failure
* Redundancy
* Inconsistency
* Performance bottlenecks

## Implementation Tools

### RPC

### Threads

* I/O concurrency
* Parallelism, multi-core machines
* Convenience, periodic check 

1. Process is a single address space.
2. Inside a process, there might be multiple Threads.
3. Processes are separated from each other, threads share memory.

**Atomic**: "one at a time"

For example, when accessing or mutating a property is atomic, it means that only one read or write operation can be performed at a time.

## Concurrency Control


