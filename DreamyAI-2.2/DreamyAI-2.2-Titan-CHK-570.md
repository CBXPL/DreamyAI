# Benchmark

## Benchmark Version: **DreamyAIBench-2.0**

| Model | Context | Token Speed | Thinking |
|---|---|---:|---|
| DreamyAI-2.2-Titan-CHK-570 | 1M | ~68 tk/s average | Enabled |

## Agentic coding

| Metric | Score |
|---|---:|
| **Overall** | **89.6%** |

## Tool calling

| Metric | Score |
|---|---:|
| **Overall** | **84.6%** |

## C++

| Metric | Score |
|---|---:|
| Tasks | 8 |
| Syntax | 96.9 |
| Consistency | 98.1 |
| Requirements | 97.5 |
| Efficiency | 95.6 |
| **Overall** | **97.0%** |

## C#

| Metric | Score |
|---|---:|
| Tasks | 6 |
| Syntax | 90.0 |
| Consistency | 96.3 |
| Requirements | 95.0 |
| Efficiency | 95.0 |
| **Overall** | **94.1%** |

## HTML

| Metric | Score |
|---|---:|
| Tasks | 7 |
| Syntax | 100.0 |
| Consistency | 100.0 |
| Requirements | 100.0 |
| Efficiency | 95.0 |
| Styling | 95.0 |
| **Overall** | **98.0%** |

## Python

| Metric | Score |
|---|---:|
| Tasks | 4 |
| Syntax | 100.0 |
| Consistency | 100.0 |
| Requirements | 100.0 |
| Efficiency | 95.0 |
| **Overall** | **98.8%** |

## Overall

| Section | Score |
|---|---:|
| Agentic Coding | 89.6% |
| Tool Calling | 84.6% |
| C++ | 97.0% |
| C# | 94.1% |
| HTML | 98.0% |
| Python | 98.8% |
| **Overall (everything/overall)** | **93.7%** |
| **Overall (code only)** | **97.0%** |

## Model comparison

| Section | DreamyAI-2.2-Titan | DreamyAI-2.0-Pro 1811 *(carried over from DBK 1.5)* | DeepSeek v4.1 Flash *(carried over from DBK 1.5)* | Delta (DeepSeek - 2.2-Titan) | Delta (2.0 Pro - 2.2-Titan) |
|---|---:|---:|---:|---:|---:|
| Agentic Coding | 89.6% | 89.1% *(from DBK 1.5)* | 77.0% *(from DBK 1.5)* | -12.6 | -0.5 |
| Tool Calling | 84.6% | 75.7% *(from DBK 1.5)* | 90.6% *(from DBK 1.5)* | +6.0 | -8.9 |
| C++ | 97.0% | 86.9% *(from DBK 1.5)* | 89.9% *(from DBK 1.5)* | -7.1 | -10.1 |
| C# | 94.1% | 79.7% *(from DBK 1.5)* | 92.6% *(from DBK 1.5)* | -1.5 | -14.4 |
| HTML | 98.0% | 92.0% *(from DBK 1.5)* | 99.7% *(from DBK 1.5)* | +1.7 | -6.0 |
| Python | 98.8% | — *(not in DBK 1.5)* | — *(not in DBK 1.5)* | — | — |
| **Overall (everything/overall)** | **93.7%** | **84.7%** *(from DBK 1.5)* | **90.0%** *(from DBK 1.5)* | **-3.7** | **-9.0** |
| **Overall (code only)** | **97.0%** | **86.2%** *(from DBK 1.5)* | **94.1%** *(from DBK 1.5)* | **-2.9** | **-10.8** |
