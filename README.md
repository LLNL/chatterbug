Communication Proxies
===========
Set of communication-only codes that mimic commonly found communication patterns
in HPC codes. These codes can be used as synthetic codes for benchmarking, or
for trace generation using OTF2.

List of benchmarks:
===========
  * PingPing: multi-pairs message exchange (user specified pairs)
  * Pairs: all pairs multi-pairs message exchange
  * Spread: k-neighbor communication within rankspace neighborhood
  * Stencil3D: structured 3D near neighbor pattern like that of jacobi/halo
  * Stencil4D: structured 4D near neighbor pattern like that of jacobi/halo
  * Unstr-mesh: unstructured mesh communication pattern
  * Subcom-a2a: FFT-style subcommunicator-based all to all communication

OTF2 Tracing
===========
For OTF2 tracing, see notes here: https://github.com/LLNL/tracer/blob/master/README.OTF


