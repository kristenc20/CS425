# Results for Assignment 02

## Improvement Iterations

Here's a table showing the improvements I did to make the application go faster.  The **Time** column in the table represents the _wall-clock time_ for a program run. Note: time based on running with Test data to get speedup, final is time based on Final data

| Version | Time | Speedup | Final | Changes |
| ------- | ---- | ------- | ----- | ------- |
| [02](lychrel.cpp) | 1m49.64s | &mdash; | &mdash; | Initial version - no changes |
| [02](lychrel2.cpp) | &mdash; | &mdash; | &mdash; | Threaded the Lychrel loop, too long |
| [02](lychrel3.cpp) | 0m0.72s | 152.28x | 1m35.29s | Threaded loop so each thread runs a chunk of data |
| [02](lychrel4.cpp) | 0m0.54s | 203.04x | 1m40.44s | Changed loop to get next data |
