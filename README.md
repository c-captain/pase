# PASE

PASE: PostgreSQL Ultra-High Dimensional Approximate Nearest Neighbor Search Extension

**(PASE now is in the Ant Financial's open source review process, so it is currently only a directory structure, the code will be added soon after it is approved.)**


## Introduction
PASE is the index extention  of PostgreSQL. So far two types of NNS algorithms are supported: quantization-based and graph-based. The other algorithms can be easily implemented under the proposed framework. Experiments have been conducted on large data sets to illustrate the efficiency of the proposed retrieval mechanism.

## Building

1. install psql
2. make USE_PGXS=1

## How Pase works

PASE can be used directly through the simple command 'create extention pase;' in PG. For specific usage examples, please refer to "sql/pase.sql".


## Full documentation of Pase

## Authors
Wen Yang (yangwen.yw@antfin.com)

Tao Li (lyee.lit@antfin.com)

Gai Fang (fanggai.fg@antfin.com)

## Reference

## License
PASE is MIT-licensed.
