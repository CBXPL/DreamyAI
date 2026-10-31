# Benchmark

| Model | Context |
|---|---:|
| DreamyAI-Micro-Flash2610 | 16384 |

Columns: Syntax · Consistency · Requirements · Efficiency · Overall (mean of the four).

## C++

| Task | Syntax | Consistency | Requirements | Efficiency | Overall |
|---|---:|---:|---:|---:|---:|
| 01_string_split | 0 | 15 | 10 | 5 | 7.5 |
| 02_ring_buffer | 55 | 10 | 10 | 5 | 20.0 |
| 03_blocking_queue | 0 | 10 | 5 | 5 | 5.0 |
| 04_csv_stats | 100 | 85 | 55 | 70 | 77.5 |
| **Section** | | | | | **27.5%** |

## C#

| Task | Syntax | Consistency | Requirements | Efficiency | Overall |
|---|---:|---:|---:|---:|---:|
| 01_retry_async | 0 | 10 | 5 | 5 | 5.0 |
| 02_linq_report | 0 | 30 | 30 | 20 | 20.0 |
| 03_dispose_pattern | 0 | 25 | 10 | 15 | 12.5 |
| 04_json_filter | 0 | 60 | 55 | 75 | 47.5 |
| **Section** | | | | | **21.3%** |

## HTML

| Task | Syntax | Consistency | Requirements | Efficiency | Overall |
|---|---:|---:|---:|---:|---:|
| 01_responsive_cards | 100 | 25 | 15 | 10 | 37.5 |
| 02_form_validation | 85 | 20 | 10 | 5 | 30.0 |
| 03_modal_dialog | 95 | 20 | 5 | 5 | 31.3 |
| 04_semantic_layout | 100 | 55 | 45 | 55 | 63.8 |
| **Section** | | | | | **40.6%** |

## Overall

| Section | Score |
|---|---:|
| C++ | 27.5% |
| C# | 21.3% |
| HTML | 40.6% |
| **Overall** | **29.8%** |
