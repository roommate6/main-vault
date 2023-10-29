# Definition

If **n pigeons** are assigned to **m pigeonholes**, and m < n, then at least one pigeonhole contains two or more pigeons.

**Proof**:

Consider labeling each pigeonhole with numbers from 1 to m and each pigeon with numbers from 1 to n. Now, begin with pigeonhole labeled with 1 and put inside it the pigeon that has the same label. Repeat this procces for each pigeonhole. Because we know that m < n (there are less pigeonholes than pigeons), then doing the previos step, we have one pigeon in each pigeonhole. But, we are left with **n - m** pigeons to assign in a pigeonhole. We start again from the first pigeonhole, that already has one pigeon inside, so we will have at least one pigeonhole with 2 ore more pigeons inside it.

**The extended pigeonhole principle**:

If **n pigeons** are assigned to **m pigeonholes**, then one of the pigeonholes must contain at least $[\frac{n - 1}{m}] + 1$ pigeons.

**Proof**:

If each pigeonhole contains no more than $[\frac{n-1}{m}]$ pigeons, then there are at most $m \cdot [\frac{n - 1}{m}] \le m \cdot \frac{n - 1}{m} = n - 1$ pigeons in all. This contradictis our assumption that there are n pigeons, so one of the pigeonholes must contain at least $[\frac{n - 1}{m}] + 1$ pigeons.
