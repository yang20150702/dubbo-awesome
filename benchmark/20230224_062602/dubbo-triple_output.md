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
# Warmup Iteration   1: 1.895 ops/ms
# Warmup Iteration   2: 5.629 ops/ms
# Warmup Iteration   3: 8.284 ops/ms
Iteration   1: 9.207 ops/ms
Iteration   2: 9.479 ops/ms
Iteration   3: 8.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.166 ±(99.9%) 6.096 ops/ms [Average]
  (min, avg, max) = (8.814, 9.166, 9.479), stdev = 0.334
  CI (99.9%): [3.070, 15.262] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 8.707 ops/ms
# Warmup Iteration   3: 9.669 ops/ms
Iteration   1: 9.708 ops/ms
Iteration   2: 9.742 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.682 ±(99.9%) 1.417 ops/ms [Average]
  (min, avg, max) = (9.594, 9.682, 9.742), stdev = 0.078
  CI (99.9%): [8.265, 11.098] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 8.223 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 9.052 ops/ms
Iteration   3: 8.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.152 ±(99.9%) 5.342 ops/ms [Average]
  (min, avg, max) = (8.923, 9.152, 9.482), stdev = 0.293
  CI (99.9%): [3.811, 14.494] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.722 ops/ms
# Warmup Iteration   2: 7.031 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 7.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.837 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (7.625, 7.837, 7.974), stdev = 0.187
  CI (99.9%): [4.433, 11.240] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.463 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.007 ms/op
Iteration   1: 3.623 ±(99.9%) 0.005 ms/op
Iteration   2: 3.430 ±(99.9%) 0.006 ms/op
Iteration   3: 3.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.491 ±(99.9%) 2.080 ms/op [Average]
  (min, avg, max) = (3.421, 3.491, 3.623), stdev = 0.114
  CI (99.9%): [1.411, 5.571] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.006 ms/op
Iteration   1: 3.275 ±(99.9%) 0.007 ms/op
Iteration   2: 3.323 ±(99.9%) 0.005 ms/op
Iteration   3: 3.277 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.275, 3.292, 3.323), stdev = 0.028
  CI (99.9%): [2.789, 3.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.464 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.005 ms/op
Iteration   1: 3.515 ±(99.9%) 0.007 ms/op
Iteration   2: 3.435 ±(99.9%) 0.009 ms/op
Iteration   3: 3.508 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.486 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.435, 3.486, 3.515), stdev = 0.044
  CI (99.9%): [2.676, 4.296] (assumes normal distribution)


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
# Warmup Iteration   1: 11.279 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.010 ms/op
Iteration   1: 3.993 ±(99.9%) 0.014 ms/op
Iteration   2: 4.030 ±(99.9%) 0.012 ms/op
Iteration   3: 3.927 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.983 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.927, 3.983, 4.030), stdev = 0.052
  CI (99.9%): [3.033, 4.934] (assumes normal distribution)


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
# Warmup Iteration   1: 10.560 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.013 ms/op
Iteration   1: 3.471 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  22.787 ms/op
                 createUser·p0.9999: 25.388 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  24.050 ms/op
                 createUser·p0.9999: 28.467 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.540 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.351 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  21.107 ms/op
                 createUser·p0.9999: 30.573 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275196
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17123 
    [ 2.500,  5.000) = 251554 
    [ 5.000,  7.500) = 5500 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     22.073 ms/op
     p(99.9900) =     28.753 ms/op
     p(99.9990) =     32.978 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 9.062 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.008 ms/op
Iteration   1: 3.378 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  21.103 ms/op
                 existUser·p0.9999: 24.203 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.309 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  18.910 ms/op
                 existUser·p0.9999: 37.751 ms/op
                 existUser·p1.00:   40.632 ms/op

Iteration   3: 3.372 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  20.906 ms/op
                 existUser·p0.9999: 34.047 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285996
  mean =      3.353 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 281099 
    [ 5.000, 10.000) = 4377 
    [10.000, 15.000) = 231 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 144 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 52 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     36.766 ms/op
     p(99.9990) =     39.101 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


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
# Warmup Iteration   1: 10.088 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.012 ms/op
Iteration   1: 3.586 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  23.389 ms/op
                 getUser·p0.9999: 28.286 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  23.790 ms/op
                 getUser·p0.9999: 27.336 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.690 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271492
  mean =      3.533 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1154 
    [ 2.500,  5.000) = 260496 
    [ 5.000,  7.500) = 8673 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     21.562 ms/op
     p(99.9900) =     28.274 ms/op
     p(99.9990) =     29.903 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 12.578 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.016 ms/op
Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  21.347 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 4.021 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.985 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.556 ms/op
                 listUser·p0.9999: 22.972 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.039 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  15.659 ms/op
                 listUser·p0.9999: 19.732 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234490
  mean =      4.090 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 224694 
    [ 5.000,  7.500) = 7248 
    [ 7.500, 10.000) = 1652 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.985 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     24.794 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.166 ± 6.096  ops/ms
ClientPb.existUser                       thrpt       3   9.682 ± 1.417  ops/ms
ClientPb.getUser                         thrpt       3   9.152 ± 5.342  ops/ms
ClientPb.listUser                        thrpt       3   7.837 ± 3.404  ops/ms
ClientPb.createUser                       avgt       3   3.491 ± 2.080   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 0.502   ms/op
ClientPb.getUser                          avgt       3   3.486 ± 0.810   ms/op
ClientPb.listUser                         avgt       3   3.983 ± 0.951   ms/op
ClientPb.createUser                     sample  275196   3.488 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.351           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.073           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.753           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.013           ms/op
ClientPb.existUser                      sample  285996   3.353 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.906           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.766           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.632           ms/op
ClientPb.getUser                        sample  271492   3.533 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.562           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.274           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  234490   4.090 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.985           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
