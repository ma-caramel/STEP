# malloc_challenge

- `real_malloc` is the malloc challenge. Please read [real_malloc/README.md](./real_malloc/README.md) and [real_malloc/malloc.c](./real_malloc/malloc.c) for more information.
- `visualizer/` contains a visualizer of malloc traces.

__実行結果__

(1)First-fit
|| Challenge 1 | Challenge 2 | Challenge 3 | Challenge 4 | Challenge 5 |
|---|---|---|---|---|---|
| Time | 8 ms | 6 ms | 116 ms | 19926 ms | 17083 ms |
| Utilization | 70% | 40% | 7% | 15% | 15% |

(2)Best-fit
|| Challenge 1 | Challenge 2 | Challenge 3 | Challenge 4 | Challenge 5 |
|---|---|---|---|---|---|
| Time | 1445 ms | 530 ms | 735 ms | 9249 ms | 6317 ms |
| Utilization | 70% | 40% | 50% | 71% | 74% |

(3)Worth-fit
|| Challenge 1 | Challenge 2 | Challenge 3 | Challenge 4 | Challenge 5 |
|---|---|---|---|---|---|
| Time | 1450 ms | 563 ms | 64401 ms | 504638 ms | 438177 ms |
| Utilization | 70% | 40% | 4% | 7% | 7% |
