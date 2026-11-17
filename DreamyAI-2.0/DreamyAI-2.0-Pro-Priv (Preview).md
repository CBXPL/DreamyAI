# Benchmark

## Benchmark Version: **DreamyAIBench-1.5-EXP**

| Model | Context | Token Speed | Thinking |
|---|---|---:|---|
| DreamyAI-2.0-Pro-Priv | 512k-1M | ~39 tk/s average | Enabled |

## Agentic coding

| Metric | Score |
|---|---:|
| **Overall** | **86.1%** |

## Tool calling

| Metric | Score |
|---|---:|
| **Overall** | **79.5%** |

## C++

| Metric | Score |
|---|---:|
| Tasks | 7 |
| Syntax | 85.6 |
| Consistency | 87.8 |
| Requirements | 76.9 |
| Efficiency | 82.2 |
| **Overall** | **83.1%** |

## C#

| Metric | Score |
|---|---:|
| Tasks | 6 |
| Syntax | 83.1 |
| Consistency | 87.5 |
| Requirements | 82.8 |
| Efficiency | 87.8 |
| **Overall** | **85.3%** |

## HTML

| Metric | Score |
|---|---:|
| Tasks | 5 |
| Syntax | 98.1 |
| Consistency | 95.0 |
| Requirements | 88.8 |
| Efficiency | 91.6 |
| Styling | 90.9 |
| **Overall** | **92.9%** |

## Overall

| Section | Score |
|---|---:|
| Agentic Coding | 86.1% |
| Tool Calling | 79.5% |
| C++ | 83.1% |
| C# | 85.3% |
| HTML | 92.9% |
| **Overall** | **85.4%** |

## Model comparison

| Section | DreamyAI-2.0-Pro-Priv | DreamyAI-2.0-DeepThink-1311 | DeepSeek v4.1 Flash | Delta (DeepSeek - PRO) | Delta (DeepThink - PRO) |
|---|---:|---:|---:|---:|---:|
| Agentic Coding | 86.1% | 60.7% | 77.0% | -9.1 | -25.4 |
| Tool Calling | 79.5% | 64.3% | 90.6% (tool execution) | +11.1 | -15.2 |
| C++ | 83.1% | 72.9% | 89.9% | +6.8 | -10.2 |
| C# | 85.3% | 92.5% | 92.6% | +7.3 | +7.2 |
| HTML | 92.9% | 87.8% | 99.7% | +6.8 | -5.1 |
| **Overall (everything/overall)** | **85.4%** | **75.6%** | **90.0%** | **+4.6** | **-9.8** |
| **Overall (code only)** | **87.1%** | **84.4%** | **94.1%** | **+7.0** | **-2.7** |
