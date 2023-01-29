# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 6.725 ops/ms
# Warmup Iteration   3: 9.259 ops/ms
Iteration   1: 9.525 ops/ms
Iteration   2: 9.934 ops/ms
Iteration   3: 9.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.783 ±(99.9%) 4.106 ops/ms [Average]
  (min, avg, max) = (9.525, 9.783, 9.934), stdev = 0.225
  CI (99.9%): [5.678, 13.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.148 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.401 ±(99.9%) 4.854 ops/ms [Average]
  (min, avg, max) = (10.148, 10.401, 10.679), stdev = 0.266
  CI (99.9%): [5.547, 15.255] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ops/ms
# Warmup Iteration   2: 8.814 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.681 ops/ms
Iteration   2: 9.584 ops/ms
Iteration   3: 9.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.685 ±(99.9%) 1.882 ops/ms [Average]
  (min, avg, max) = (9.584, 9.685, 9.790), stdev = 0.103
  CI (99.9%): [7.803, 11.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 7.575 ops/ms
# Warmup Iteration   3: 8.259 ops/ms
Iteration   1: 8.517 ops/ms
Iteration   2: 8.574 ops/ms
Iteration   3: 8.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.560 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (8.517, 8.560, 8.588), stdev = 0.038
  CI (99.9%): [7.875, 9.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.000 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.005 ms/op
Iteration   1: 3.144 ±(99.9%) 0.004 ms/op
Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
Iteration   3: 3.178 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.169 ±(99.9%) 0.405 ms/op [Average]
  (min, avg, max) = (3.144, 3.169, 3.186), stdev = 0.022
  CI (99.9%): [2.765, 3.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.165 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.004 ms/op
Iteration   1: 3.084 ±(99.9%) 0.004 ms/op
Iteration   2: 3.159 ±(99.9%) 0.004 ms/op
Iteration   3: 3.180 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.141 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.084, 3.141, 3.180), stdev = 0.050
  CI (99.9%): [2.225, 4.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.003 ms/op
Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
Iteration   2: 3.128 ±(99.9%) 0.001 ms/op
Iteration   3: 3.121 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.149 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (3.121, 3.149, 3.198), stdev = 0.043
  CI (99.9%): [2.372, 3.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.326 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.005 ms/op
Iteration   1: 3.765 ±(99.9%) 0.006 ms/op
Iteration   2: 3.767 ±(99.9%) 0.006 ms/op
Iteration   3: 3.803 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.765, 3.778, 3.803), stdev = 0.021
  CI (99.9%): [3.394, 4.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.011 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.010 ms/op
Iteration   1: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.473 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  16.913 ms/op
                 createUser·p0.9999: 19.547 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  14.014 ms/op
                 createUser·p0.9999: 22.191 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.087 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  14.425 ms/op
                 createUser·p0.9999: 18.708 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307741
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14816 
    [ 2.500,  5.000) = 288658 
    [ 5.000,  7.500) = 3406 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.500 ms/op
     p(99.9900) =     21.602 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.267 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  9.915 ms/op
                 existUser·p0.9999: 20.290 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   2: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.470 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.111 ms/op
                 existUser·p0.999:  11.860 ms/op
                 existUser·p0.9999: 21.627 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.187 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 31.818 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302358
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21957 
    [ 2.500,  5.000) = 274571 
    [ 5.000,  7.500) = 5066 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     14.280 ms/op
     p(99.9900) =     29.803 ms/op
     p(99.9990) =     32.599 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.011 ms/op
Iteration   1: 3.242 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  17.378 ms/op
                 getUser·p0.9999: 20.419 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  17.883 ms/op
                 getUser·p0.9999: 22.376 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  9.230 ms/op
                 getUser·p0.9999: 22.313 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300531
  mean =      3.196 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17667 
    [ 2.500,  5.000) = 275040 
    [ 5.000,  7.500) = 7143 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.781 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     22.018 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.733 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.013 ms/op
Iteration   1: 3.849 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  14.908 ms/op
                 listUser·p0.9999: 17.775 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   2: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  15.994 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.885 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252583
  mean =      3.801 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 82 
    [ 2.500,  3.750) = 159944 
    [ 3.750,  5.000) = 84137 
    [ 5.000,  6.250) = 2684 
    [ 6.250,  7.500) = 3520 
    [ 7.500,  8.750) = 1230 
    [ 8.750, 10.000) = 326 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 83 
    [16.250, 17.500) = 82 
    [17.500, 18.750) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     18.923 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.783 ± 4.106  ops/ms
ClientPb.existUser                       thrpt       3  10.401 ± 4.854  ops/ms
ClientPb.getUser                         thrpt       3   9.685 ± 1.882  ops/ms
ClientPb.listUser                        thrpt       3   8.560 ± 0.685  ops/ms
ClientPb.createUser                       avgt       3   3.169 ± 0.405   ms/op
ClientPb.existUser                        avgt       3   3.141 ± 0.916   ms/op
ClientPb.getUser                          avgt       3   3.149 ± 0.777   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 0.385   ms/op
ClientPb.createUser                     sample  307741   3.119 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.500           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.602           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.134           ms/op
ClientPb.existUser                      sample  302358   3.174 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.280           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.803           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  300531   3.196 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.781           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.429           ms/op
ClientPb.listUser                       sample  252583   3.801 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.416           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.268           ms/op
