# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.366 ops/ms
# Warmup Iteration   2: 5.736 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.915 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.728 ±(99.9%) 4.898 ops/ms [Average]
  (min, avg, max) = (9.421, 9.728, 9.915), stdev = 0.268
  CI (99.9%): [4.831, 14.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ops/ms
# Warmup Iteration   2: 9.351 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.132 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 10.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.069 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (9.969, 10.069, 10.132), stdev = 0.087
  CI (99.9%): [8.476, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.276 ops/ms
# Warmup Iteration   2: 9.214 ops/ms
# Warmup Iteration   3: 9.439 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.943 ±(99.9%) 2.211 ops/ms [Average]
  (min, avg, max) = (9.805, 9.943, 10.031), stdev = 0.121
  CI (99.9%): [7.732, 12.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.948 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 8.401 ops/ms
Iteration   1: 8.315 ops/ms
Iteration   2: 8.249 ops/ms
Iteration   3: 8.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.313 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (8.249, 8.313, 8.375), stdev = 0.063
  CI (99.9%): [7.161, 9.465] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.183 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.002 ms/op
Iteration   1: 3.313 ±(99.9%) 0.002 ms/op
Iteration   2: 3.350 ±(99.9%) 0.004 ms/op
Iteration   3: 3.343 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.336 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.313, 3.336, 3.350), stdev = 0.020
  CI (99.9%): [2.971, 3.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.181 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.093 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.070, 3.113, 3.177), stdev = 0.056
  CI (99.9%): [2.088, 4.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.506 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.003 ms/op
Iteration   1: 3.300 ±(99.9%) 0.002 ms/op
Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
Iteration   3: 3.289 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.260 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (3.190, 3.260, 3.300), stdev = 0.060
  CI (99.9%): [2.158, 4.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.129 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.005 ms/op
Iteration   1: 3.875 ±(99.9%) 0.005 ms/op
Iteration   2: 3.809 ±(99.9%) 0.004 ms/op
Iteration   3: 3.836 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.840 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.809, 3.840, 3.875), stdev = 0.033
  CI (99.9%): [3.229, 4.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.787 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  17.793 ms/op
                 createUser·p0.9999: 20.419 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  19.277 ms/op
                 createUser·p0.9999: 22.580 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  15.788 ms/op
                 createUser·p0.9999: 36.700 ms/op
                 createUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296011
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10800 
    [ 2.500,  5.000) = 281564 
    [ 5.000,  7.500) = 2829 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     36.836 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.991 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  17.182 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.206 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  14.815 ms/op
                 existUser·p0.9999: 20.808 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300624
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14462 
    [ 2.500,  5.000) = 278834 
    [ 5.000,  7.500) = 6353 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     22.376 ms/op
     p(99.9990) =     23.393 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.487 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  18.291 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  15.271 ms/op
                 getUser·p0.9999: 24.841 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  11.927 ms/op
                 getUser·p0.9999: 22.061 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294395
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8136 
    [ 2.500,  5.000) = 280486 
    [ 5.000,  7.500) = 4819 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.487 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     15.087 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     27.811 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.265 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
Iteration   1: 3.840 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.155 ms/op
                 listUser·p0.9999: 19.879 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.237 ms/op
                 listUser·p0.999:  13.068 ms/op
                 listUser·p0.9999: 22.639 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 3.803 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.136 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 18.178 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248511
  mean =      3.859 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 242477 
    [ 5.000,  7.500) = 4433 
    [ 7.500, 10.000) = 810 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.771 ms/op
     p(99.9900) =     19.605 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.728 ± 4.898  ops/ms
ClientPb.existUser                       thrpt       3  10.069 ± 1.592  ops/ms
ClientPb.getUser                         thrpt       3   9.943 ± 2.211  ops/ms
ClientPb.listUser                        thrpt       3   8.313 ± 1.152  ops/ms
ClientPb.createUser                       avgt       3   3.336 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 1.025   ms/op
ClientPb.getUser                          avgt       3   3.260 ± 1.102   ms/op
ClientPb.listUser                         avgt       3   3.840 ± 0.611   ms/op
ClientPb.createUser                     sample  296011   3.241 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.727           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.474           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.962           ms/op
ClientPb.existUser                      sample  300624   3.194 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.795           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.376           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  294395   3.257 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.487           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.759           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.087           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.822           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  248511   3.859 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.771           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.605           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.774           ms/op
