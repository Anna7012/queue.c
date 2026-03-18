# 📘 Priority Scheduling Program in C

## Description
This program implements non-preemptive priority scheduling.
The process with the highest priority is executed first.

## Input
- Process ID
- Arrival Time
- Burst Time
- Priority

## Output
- Waiting Time
- Turnaround Time
- Average Waiting Time
- Average Turnaround Time

## Working
- Select process with highest priority
- Execute it completely
- Repeat until all processes finish

## How to Run
gcc Priority.c -o priority
./priority

## Formula
TAT = CT - AT
WT = TAT - BT# queue.c
