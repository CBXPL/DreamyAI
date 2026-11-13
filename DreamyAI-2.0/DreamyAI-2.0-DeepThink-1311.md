# Benchmark

## Benchmark Version: **DreamyAIBench-1.5**

| Model | Context | Token Speed | Thinking |
|---|---|---:|---|
| DreamyAI-2.0-DeepThink-1311 | 262k-320k IN, 64k Out | ~80 tk/s average | Enabled |

## Agentic coding

| Metric | Score |
|---|---:|
| **Overall** | **60.7%** |

## Tool calling

| Metric | Score |
|---|---:|
| **Overall** | **64.3%** |

## C++

| Metric | Score |
|---|---:|
| Tasks | 10 |
| Syntax | 78.7 |
| Consistency | 95.7 |
| Requirements | 48.2 |
| Efficiency | 68.9 |
| **Overall** | **72.9%** |

## C#

| Metric | Score |
|---|---:|
| Tasks | 12 |
| Syntax | 94.8 |
| Consistency | 100.0 |
| Requirements | 87.2 |
| Efficiency | 88.1 |
| **Overall** | **92.5%** |

## HTML

| Metric | Score |
|---|---:|
| Tasks | 6 |
| Syntax | 97.2 |
| Consistency | 95.5 |
| Requirements | 62.5 |
| Efficiency | 88.7 |
| Styling | 95.0 |
| **Overall** | **87.8%** |

## Overall

| Section | Score |
|---|---:|
| Agentic Coding | 60.7% |
| Tool Calling | 64.3% |
| C++ | 72.9% |
| C# | 92.5% |
| HTML | 87.8% |
| **Overall** | **75.6%** |

## Model comparison

| Section | DreamyAI-2.0-DeepThink-1311 | Gemini 4 Hydrogen | DeepSeek v4.1 Flash | Delta (DeepSeek - DreamyAI) | Delta (Hydrogen - DreamyAI) |
|---|---:|---:|---:|---:|---:|
| Agentic Coding | 60.7% | 76.1% (AutomationBench) | 77.0% | +16.3 | +15.4 |
| Tool Calling | 64.3% | 57.0% (Terminal-Bench 4.1) | 90.6% (tool execution) | +26.3 | -7.3 |
| C++ | 72.9% | 98.8% | 89.9% | +17.0 | +25.9 |
| C# | 92.5% | 99.6% | 92.6% | +0.1 | +7.1 |
| HTML | 87.8% | 99.4% | 99.7% | +11.9 | +11.6 |
| **Overall (everything/overall)** | **75.6%** | **86.2%** | **90.0%** | **+14.4** | **+10.6** |
| **Overall (code only)** | **84.4%** | **99.3%** | **94.1%** | **+9.7** | **+14.9** |

