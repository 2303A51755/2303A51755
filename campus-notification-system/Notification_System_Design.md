# Stage 1

## Priority Logic

Placement > Result > Event

Weights:

Placement = 3
Result = 2
Event = 1

## Recency

Latest notifications are given higher priority.

## Efficient Top 10

A Min Heap of size 10 can be maintained.

Whenever a new notification arrives:

1. Compare with smallest element
2. Replace if higher priority
3. Keep heap size fixed at 10

Complexity:

O(log 10)

Effectively O(1)git 