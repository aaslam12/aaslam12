## Hi there 👋

My name is Altamash and I am a **C++** systems developer interested in **low-latency infrastructure, and performance engineering**. I build performance-critical systems from scratch and focus on writing deterministic, measurable, and efficient code.


🔭 Currently building:
- **Low-Latency Market Data + Matching Engine Simulation** \
  A multi-threaded (with thread pinning) trading system simulation designed to model real exchange infrastructure featuring:
  - Network ingestion with Kernel Bypass (`DPDK / AF_XDP`)
  - Bitset scanning with `__builtin_ctzll`
  - Lock free communication with SPSC Ring Buffers
  - Limit order book + matching engine
  - Nanosecond level latency measurement via `TSC`
  - Throughput and tail-latency benchmarking
  - Profiling with `perf` and flamegraphs
  - Integrating my low level low latency memory allocator `Palloc`
  - Asynchronous zero copy logging


📫 How to reach me:
- Email: altamashaslam12@gmail.com
