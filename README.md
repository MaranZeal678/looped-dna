# looped-dna

**Adaptive-depth transformers for genomic sequence modeling.**

Most sequence models spend the same amount of compute on every position. Genomes do not work that way: long stretches carry little information, while a small fraction of positions carry most of the biological signal.

This project explores architectures that decide, per position, how much computation to apply. The aim is to allocate depth where the sequence demands it and to measure whether that allocation aligns with known biology and improves accuracy per unit of compute.

The work is in progress and not yet public. Code, results, and a full write-up will be released later.

## Environment

```bash
pip install -r requirements.txt
```

Requires Python 3.10 or newer.

## Contact

Questions, ideas, or collaboration: eelangov@uci.edu

## License

MIT
