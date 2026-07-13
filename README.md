# Mixed-Criticality Scheduling in Real-Time Systems

This seminar paper presents an overview of Mixed-Criticality Scheduling (MCS) in real-time and safety-critical systems.

Modern embedded systems often execute tasks with different levels of importance on the same computing platform. Traditional scheduling methods normally use a single Worst-Case Execution Time (WCET) estimate for each task. Mixed-criticality scheduling introduces different criticality levels and multiple WCET estimates to provide stronger timing guarantees for safety-critical tasks.

The paper focuses on the Mixed-Criticality Model introduced by Steve Vestal and explains execution-time assurance, scheduling behaviour, processor utilization, and LO-to-HI mode switching.

A case study based on Vestal's RTSS 2007 paper is also discussed. The industrial avionics workloads demonstrate how mixed-criticality analysis can improve schedulability compared with traditional scheduling approaches.

## Topics Covered

- Real-Time Systems
- Mixed-Criticality Systems
- LO and HI Criticality Levels
- Worst-Case Execution Time (WCET)
- Multiple WCET Estimates
- Vestal's Mixed-Criticality Model
- Processor Utilization
- LO and HI Mode Switching
- Limitations and Trade-offs
- Industrial Avionics Case Study
- Critical Scaling Factor (Δ*)

## Case Study

The paper discusses three industrial avionics workloads evaluated in Vestal's original RTSS 2007 research.

The reported schedulability improvements were:

- Workload 1: 11%
- Workload 2: 42%
- Workload 3: 59%

The Critical Scaling Factor (Δ*) is used to evaluate how much additional execution demand a task set can tolerate while remaining schedulable.

## Tools

- Overleaf
- LaTeX
- IEEE Paper Format
- Graphviz
- Python / Google Colab

## Author

Sayed Galib Hossen Rizvi  
B.Eng. Electronics Engineering  
Hamm-Lippstadt University of Applied Sciences

## Course

Real-Time Systems Seminar

## Main Reference

Steve Vestal, "Preemptive Scheduling of Multi-Criticality Systems with Varying Degrees of Execution Time Assurance," IEEE Real-Time Systems Symposium (RTSS), 2007.
