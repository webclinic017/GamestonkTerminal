---
title: exp
description: The 'exp' page provides comprehensive details on setting expiration dates
  using the 'exp' command in Python. It includes information on usage, parameters,
  and examples to assist users in understanding and effectively managing dates.
keywords:
- exp documentation
- expiration date setting
- expiry date tool
- expiry date parameters
- exp usage
- exp examples
- exp command
- exp date selection
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/options/exp - Reference | OpenBB Terminal Docs" />

See and set expiration date

### Usage

```python
exp [-i {0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17}] [-d {2022-11-25,2022-12-02,2022-12-09,2022-12-16,2022-12-23,2022-12-30,2023-01-20,2023-02-17,2023-03-17,2023-04-21,2023-05-19,2023-06-16,2023-07-21,2023-09-15,2024-01-19,2024-03-15,2024-06-21,2025-01-17,}]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| index | Select index for expiry date. | -1 | True | range(0, 18) |
| date | Select date (YYYY-MM-DD) |  | True | 2022-11-25, 2022-12-02, 2022-12-09, 2022-12-16, 2022-12-23, 2022-12-30, 2023-01-20, 2023-02-17, 2023-03-17, 2023-04-21, 2023-05-19, 2023-06-16, 2023-07-21, 2023-09-15, 2024-01-19, 2024-03-15, 2024-06-21, 2025-01-17,  |


---

## Examples

```python
2022 Feb 16, 08:50 (🦋) /stocks/options/ $ exp

Available expiry dates:
    0.  2022-02-18
    1.  2022-02-25
    2.  2022-03-04
    3.  2022-03-11
    4.  2022-03-18
    5.  2022-03-25
    6.  2022-04-01
    7.  2022-04-14
    8.  2022-05-20
    9.  2022-06-17
   10.  2022-07-15
   11.  2022-08-19
   12.  2022-09-16
   13.  2022-10-21
   14.  2022-11-18
   15.  2022-12-16
   16.  2023-01-20
   17.  2023-03-17
   18.  2023-06-16
   19.  2023-09-15
   20.  2024-01-19

2022 Feb 16, 08:50 (🦋) /stocks/options/ $ exp 7
Expiration set to 2022-04-14
```
---
