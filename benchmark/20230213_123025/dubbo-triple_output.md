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
# Warmup Iteration   1: 2.592 ops/ms
# Warmup Iteration   2: 6.580 ops/ms
# Warmup Iteration   3: 9.028 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 9.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.714 ±(99.9%) 5.695 ops/ms [Average]
  (min, avg, max) = (9.456, 9.714, 10.061), stdev = 0.312
  CI (99.9%): [4.019, 15.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.082 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.693 ops/ms
Iteration   3: 10.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.474 ±(99.9%) 3.796 ops/ms [Average]
  (min, avg, max) = (10.280, 10.474, 10.693), stdev = 0.208
  CI (99.9%): [6.678, 14.269] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 9.198 ops/ms
# Warmup Iteration   3: 9.649 ops/ms
Iteration   1: 9.830 ops/ms
Iteration   2: 9.937 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.963 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (9.830, 9.963, 10.120), stdev = 0.147
  CI (99.9%): [7.289, 12.636] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 8.666 ops/ms
Iteration   1: 8.649 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.627 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (8.546, 8.627, 8.685), stdev = 0.072
  CI (99.9%): [7.306, 9.948] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.882 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.007 ms/op
Iteration   1: 3.199 ±(99.9%) 0.004 ms/op
Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
Iteration   3: 3.310 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 2.201 ms/op [Average]
  (min, avg, max) = (3.069, 3.193, 3.310), stdev = 0.121
  CI (99.9%): [0.992, 5.394] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.005 ms/op
Iteration   1: 3.023 ±(99.9%) 0.004 ms/op
Iteration   2: 2.977 ±(99.9%) 0.004 ms/op
Iteration   3: 2.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.984 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (2.953, 2.984, 3.023), stdev = 0.036
  CI (99.9%): [2.331, 3.637] (assumes normal distribution)


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
# Warmup Iteration   1: 8.671 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.002 ms/op
Iteration   1: 3.099 ±(99.9%) 0.004 ms/op
Iteration   2: 3.111 ±(99.9%) 0.001 ms/op
Iteration   3: 3.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.101 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (3.092, 3.101, 3.111), stdev = 0.010
  CI (99.9%): [2.925, 3.277] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.008 ms/op
Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
Iteration   2: 3.683 ±(99.9%) 0.008 ms/op
Iteration   3: 3.707 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.703 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.683, 3.703, 3.720), stdev = 0.019
  CI (99.9%): [3.360, 4.047] (assumes normal distribution)


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
# Warmup Iteration   1: 7.800 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 19.559 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 22.711 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  15.378 ms/op
                 createUser·p0.9999: 21.889 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300388
  mean =      3.192 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11243 
    [ 2.500,  5.000) = 282673 
    [ 5.000,  7.500) = 5719 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     23.690 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.704 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.213 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  14.828 ms/op
                 existUser·p0.9999: 21.628 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302175
  mean =      3.177 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30435 
    [ 2.500,  5.000) = 267121 
    [ 5.000,  7.500) = 4024 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.757 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     13.279 ms/op
     p(99.9900) =     22.982 ms/op
     p(99.9990) =     24.574 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 7.318 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.011 ms/op
Iteration   1: 3.108 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  16.548 ms/op
                 getUser·p0.9999: 19.130 ms/op
                 getUser·p1.00:   20.218 ms/op

Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  9.001 ms/op
                 getUser·p0.9999: 21.543 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.231 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  11.732 ms/op
                 getUser·p0.9999: 26.254 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303800
  mean =      3.157 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15140 
    [ 2.500,  5.000) = 281811 
    [ 5.000,  7.500) = 5975 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     16.030 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     27.030 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.872 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.013 ms/op
Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.735 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.083 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 22.409 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.609 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.080 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.260 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.057 ms/op

Iteration   3: 3.681 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  12.671 ms/op
                 listUser·p0.9999: 18.425 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261103
  mean =      3.674 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 253220 
    [ 5.000,  7.500) = 5922 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.735 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     22.896 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.714 ± 5.695  ops/ms
ClientPb.existUser                       thrpt       3  10.474 ± 3.796  ops/ms
ClientPb.getUser                         thrpt       3   9.963 ± 2.674  ops/ms
ClientPb.listUser                        thrpt       3   8.627 ± 1.321  ops/ms
ClientPb.createUser                       avgt       3   3.193 ± 2.201   ms/op
ClientPb.existUser                        avgt       3   2.984 ± 0.653   ms/op
ClientPb.getUser                          avgt       3   3.101 ± 0.176   ms/op
ClientPb.listUser                         avgt       3   3.703 ± 0.343   ms/op
ClientPb.createUser                     sample  300388   3.192 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.317           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.204           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.889           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  302175   3.177 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.730           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.757           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.279           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.982           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  303800   3.157 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.067           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.482           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.030           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.740           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  261103   3.674 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.735           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.564           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.562           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
