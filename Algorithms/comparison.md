# 🧾 Sorting Algorithms — Cheat Table ( to Memorize)

| Algorithm   | Remember This                         |
|------------|---------------------------------------|
| Bubble      | O(n²), Stable                         |
| Selection   | O(n²), Not stable                      |
| Insertion   | O(n²), Stable                         |
| Merge       | O(n log n), Stable, O(n) space        |
| Quick       | O(n²), In Place, Fast average                    |
| Heap        | O(n log n), In-place                   |
| Counting    | O(n + k), Stable, Range-based                  |
| Radix       | O(nk), Stable, Digit-based                     |
---
</br>
</br>

# 📊 Sorting Algorithms — Complete Comparison Table (Speed Ascending)

| Algorithm       | Best Time | Avg Time   | Worst Time | Stable      | In-Place | Space Complexity | Speed Rank           | Special Usage / Notes                          |
|-----------------|-----------|-----------|------------|------------|----------|-----------------|--------------------|-----------------------------------------------|
| Bubble Sort      | O(n)      | O(n²)     | O(n²)      | ✅ Yes      | ✅ Yes   | O(1)            | 🐢 Very Slow       | Educational only, detects already sorted array |
| Selection Sort   | O(n²)     | O(n²)     | O(n²)      | ❌ No       | ✅ Yes   | O(1)            | 🐢 Very Slow       | Minimum swaps, useful when swap cost is high  |
| Insertion Sort   | O(n)      | O(n²)     | O(n²)      | ✅ Yes      | ✅ Yes   | O(1)            | 🐢 Slow            | Best for small or nearly sorted data          |
| Shell Sort       | O(n log n)| O(n^1.5) | O(n²)      | ❌ No       | ✅ Yes   | O(1)            | ⚠️ Medium          | Optimized insertion sort, rarely used now    |
| Merge Sort       | O(n log n)| O(n log n)| O(n log n) | ✅ Yes      | ❌ No    | O(n)            | 🏃 Fast            | Guaranteed performance, external sorting, linked lists |
| Quick Sort       | O(n log n)| O(n log n)| O(n²)      | ❌ No       | ✅ Yes   | O(log n)        | 🔥 Very Fast       | Fastest in practice, used in C++ STL         |
| Heap Sort        | O(n log n)| O(n log n)| O(n log n) | ❌ No       | ✅ Yes   | O(1)            | 🏃 Fast            | Guaranteed time, memory efficient            |
| Counting Sort    | O(n + k)  | O(n + k)  | O(n + k)   | ✅ Yes      | ❌ No    | O(k)            | 🚀 Very Fast       | Integers with small range, non-comparison sort |
| Radix Sort       | O(nk)     | O(nk)     | O(nk)      | ✅ Yes      | ❌ No    | O(n + k)        | 🚀 Very Fast       | Large integers / strings, digit-based        |
| Bucket Sort      | O(n + k)  | O(n + k)  | O(n²)      | ⚠️ Depends  | ❌ No    | O(n + k)        | 🚀 Fastest (Ideal) | Uniformly distributed data, floats           |
