# zephyr-planner
The planner service behind Project Zephyr.

Language: Rust (minimum supported Rust version 1.82)
Licence: Apache-2.0
Build: cargo build --release
The planner reads robot positions from NATS and writes assignments back every 30 seconds.
