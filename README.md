# Synch_FIFO


## Description

A FIFO is a queue-like structure used in digital circuits to temporarily store and manage data between producer and consumer modules.  
This project implements a **parameterized synchronous FIFO**, where both read and write operations are triggered by the same clock.

Key features:
- Parameterizable **data width** and **depth**.
- Generates **`full`** and **`empty`** flags.
- Provides **data_count** signal for tracking number of elements.
- Supports simultaneous read & write operations.

---

## Parameters
- `DATA_WIDTH`: Width of the data word (default: 8 bits).
- `ADDR_WIDTH`: Address width, determines FIFO depth (`DEPTH = 2^ADDR_WIDTH`).
- `DEPTH`: FIFO depth (number of elements it can hold).


