# Results for Assignment 03

## Improvement Iterations

Here's a table showing the improvements I did to make the application go faster.  The **Time** column in the table represents the _wall-clock time_ for a program run. 

| Version | Time | Speedup | Changes |
| ------- | ---- | ------- | ------- |
| [01](server.cpp) | 22.71s | &mdash; | Initial version - no changes |
| [02](server.cpp) | &mdash; | &mdash; | Added threading, got core dump |
| [03](server.cpp) | 16.86s | 1.347x | Detached the thread |
