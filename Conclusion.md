# Substring Search Algorithm Efficiency Comparison

## Substring Selection
- **Existing Substring**: "algorithm"
- **Non-Existing Substring**: "nonexistentpattern123"

## Execution Time Results (in seconds)

### Article 1
| Algorithm         |   Existing Substring  | Non-Existing Substring |
|-------------------|-----------------------|------------------------|
| Boyer-Moore       | 0.007708761000003506 |   0.005296998999938296  |
| Knuth-Morris-Pratt| 0.032056341000043176 |   0.0342753579999453    |
| Rabin-Karp        | 0.04805001500005801  |   0.041868066000006365  |

### Article 2
| Algorithm         | Existing Substring   | Non-Existing Substring  |
|-------------------|----------------------|-------------------------|
| Boyer-Moore       | 0.00750925299996652  |   0.005383191999953851  |
| Knuth-Morris-Pratt| 0.032904678000022614 |   0.034647813999981736  |
| Rabin-Karp        | 0.04244607900000119  |   0.043386456000007456  |

## Conclusions

- **Article 1**:
  - The fastest algorithm for the existing substrin is Bayer-Moore
  - The fastest algorithm for the non-existing substring is Bayer-Moore

- **Article 2**:
  - The fastest algorithm for the existing substring is Bayer-Moore
  - The fastest algorithm for the non-existing substring is Bayer-Moore
