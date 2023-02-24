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
# Warmup Iteration   1: 1.503 ops/ms
# Warmup Iteration   2: 3.338 ops/ms
# Warmup Iteration   3: 6.788 ops/ms
Iteration   1: 7.064 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.579 ±(99.9%) 8.213 ops/ms [Average]
  (min, avg, max) = (7.064, 7.579, 7.899), stdev = 0.450
  CI (99.9%): [≈ 0, 15.792] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.199 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 8.315 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.220 ±(99.9%) 1.510 ops/ms [Average]
  (min, avg, max) = (8.171, 8.220, 8.315), stdev = 0.083
  CI (99.9%): [6.710, 9.729] (assumes normal distribution)


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
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 7.295 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 7.811 ops/ms
Iteration   3: 7.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.830 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (7.811, 7.830, 7.853), stdev = 0.021
  CI (99.9%): [7.439, 8.221] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.261 ops/ms
# Warmup Iteration   2: 5.510 ops/ms
# Warmup Iteration   3: 6.591 ops/ms
Iteration   1: 6.518 ops/ms
Iteration   2: 6.437 ops/ms
Iteration   3: 6.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.533 ±(99.9%) 1.907 ops/ms [Average]
  (min, avg, max) = (6.437, 6.533, 6.644), stdev = 0.105
  CI (99.9%): [4.626, 8.440] (assumes normal distribution)


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
# Warmup Iteration   1: 12.580 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.927 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.012 ms/op
Iteration   1: 4.092 ±(99.9%) 0.011 ms/op
Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
Iteration   3: 4.080 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.106 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (4.080, 4.106, 4.147), stdev = 0.035
  CI (99.9%): [3.459, 4.753] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.723 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.433 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.005 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
Iteration   2: 3.838 ±(99.9%) 0.011 ms/op
Iteration   3: 3.829 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.828 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.816, 3.828, 3.838), stdev = 0.011
  CI (99.9%): [3.628, 4.027] (assumes normal distribution)


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
# Warmup Iteration   1: 13.161 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.006 ms/op
Iteration   1: 4.080 ±(99.9%) 0.015 ms/op
Iteration   2: 4.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.903 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.018 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.903, 4.018, 4.080), stdev = 0.099
  CI (99.9%): [2.208, 5.828] (assumes normal distribution)


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
# Warmup Iteration   1: 14.091 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.633 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.063 ±(99.9%) 0.013 ms/op
Iteration   1: 4.960 ±(99.9%) 0.008 ms/op
Iteration   2: 4.807 ±(99.9%) 0.016 ms/op
Iteration   3: 4.793 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.853 ±(99.9%) 1.689 ms/op [Average]
  (min, avg, max) = (4.793, 4.853, 4.960), stdev = 0.093
  CI (99.9%): [3.165, 6.542] (assumes normal distribution)


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
# Warmup Iteration   1: 13.257 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.624 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.644 ±(99.9%) 0.022 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.555 ms/op
                 createUser·p0.99:   7.299 ms/op
                 createUser·p0.999:  12.501 ms/op
                 createUser·p0.9999: 26.640 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 4.079 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  29.011 ms/op
                 createUser·p0.9999: 36.055 ms/op
                 createUser·p1.00:   36.766 ms/op

Iteration   3: 4.172 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  25.386 ms/op
                 createUser·p0.9999: 32.778 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234060
  mean =      4.100 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 295 
    [ 2.500,  5.000) = 215745 
    [ 5.000,  7.500) = 15298 
    [ 7.500, 10.000) = 1842 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     33.855 ms/op
     p(99.9990) =     36.743 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 13.663 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.727 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
Iteration   1: 4.061 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   7.938 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 26.452 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 4.128 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   8.143 ms/op
                 existUser·p0.999:  15.335 ms/op
                 existUser·p0.9999: 29.262 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 4.034 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.719 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.447 ms/op
                 existUser·p0.999:  30.987 ms/op
                 existUser·p0.9999: 43.450 ms/op
                 existUser·p1.00:   44.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235519
  mean =      4.074 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216796 
    [ 5.000, 10.000) = 17804 
    [10.000, 15.000) = 671 
    [15.000, 20.000) = 24 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 92 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     15.818 ms/op
     p(99.9900) =     42.286 ms/op
     p(99.9990) =     43.844 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.011 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.015 ms/op
Iteration   1: 4.172 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  23.931 ms/op
                 getUser·p0.9999: 27.143 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.701 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 27.923 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 4.070 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.901 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  10.149 ms/op
                 getUser·p0.9999: 32.061 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233970
  mean =      4.101 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 219428 
    [ 5.000,  7.500) = 11503 
    [ 7.500, 10.000) = 2040 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.867 ms/op
     p(99.9000) =     15.189 ms/op
     p(99.9900) =     30.560 ms/op
     p(99.9990) =     32.364 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 15.112 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 5.807 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.020 ms/op
Iteration   1: 4.953 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  28.700 ms/op
                 listUser·p0.9999: 37.558 ms/op
                 listUser·p1.00:   38.339 ms/op

Iteration   2: 5.030 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  19.654 ms/op
                 listUser·p0.9999: 23.564 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   3: 4.789 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.458 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194974
  mean =      4.922 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 141607 
    [ 5.000,  7.500) = 45522 
    [ 7.500, 10.000) = 6131 
    [10.000, 12.500) = 1010 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.980 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     20.448 ms/op
     p(99.9900) =     35.816 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.579 ± 8.213  ops/ms
ClientPb.existUser                       thrpt       3   8.220 ± 1.510  ops/ms
ClientPb.getUser                         thrpt       3   7.830 ± 0.391  ops/ms
ClientPb.listUser                        thrpt       3   6.533 ± 1.907  ops/ms
ClientPb.createUser                       avgt       3   4.106 ± 0.647   ms/op
ClientPb.existUser                        avgt       3   3.828 ± 0.199   ms/op
ClientPb.getUser                          avgt       3   4.018 ± 1.810   ms/op
ClientPb.listUser                         avgt       3   4.853 ± 1.689   ms/op
ClientPb.createUser                     sample  234060   4.100 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.720           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.347           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.855           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.766           ms/op
ClientPb.existUser                      sample  235519   4.074 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.848           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.818           ms/op
ClientPb.existUser:existUser·p0.9999    sample          42.286           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.040           ms/op
ClientPb.getUser                        sample  233970   4.101 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.475           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.867           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.189           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.292           ms/op
ClientPb.listUser                       sample  194974   4.922 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.814           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.816           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.339           ms/op
