# Fuzzy-tsukamoto-washing-machine
Case Analysis

A washing machine factory is developing an automatic fuzzy-based washing machine that can adjust the spinning speed based on the amount of laundry and the level of dirtiness. The washing machine is equipped with sensors that can detect the amount of laundry and its dirtiness level. The specifications are as follows:

The spinning speed during washing ranges from a minimum of 600 rpm (slow) to a maximum of 1300 rpm (fast).
The amount of laundry is represented by a value from 0 to 100, where a value ≤ 50 is considered "few" and ≥ 90 is considered "many."
The level of dirtiness is represented by a value from 0 to 100, where 0-50 is "low," 60 is "medium," and 90-100 is "high."
Based on various tests conducted on the machine prototype, the following rules were established:

[R1] If the laundry amount is few and dirtiness is low, then the spinning speed is slow.
[R2] If the laundry amount is few and dirtiness is medium, then the spinning speed is slow.
[R3] If the laundry amount is few and dirtiness is high, then the spinning speed is fast.
[R4] If the laundry amount is many and dirtiness is low, then the spinning speed is slow.
[R5] If the laundry amount is many and dirtiness is medium, then the spinning speed is fast.
[R6] If the laundry amount is many and dirtiness is high, then the spinning speed is fast.









