# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.586 ops/ms
# Warmup Iteration   2: 3.701 ops/ms
# Warmup Iteration   3: 7.402 ops/ms
Iteration   1: 7.787 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 7.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.007 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (7.787, 8.007, 8.309), stdev = 0.271
  CI (99.9%): [3.071, 12.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 6.452 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 7.986 ops/ms
Iteration   2: 8.757 ops/ms
Iteration   3: 8.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.399 ±(99.9%) 7.083 ops/ms [Average]
  (min, avg, max) = (7.986, 8.399, 8.757), stdev = 0.388
  CI (99.9%): [1.315, 15.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 7.056 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 7.766 ops/ms
Iteration   2: 8.114 ops/ms
Iteration   3: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.982 ±(99.9%) 3.430 ops/ms [Average]
  (min, avg, max) = (7.766, 7.982, 8.114), stdev = 0.188
  CI (99.9%): [4.552, 11.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.107 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 6.643 ops/ms
Iteration   1: 6.974 ops/ms
Iteration   2: 6.740 ops/ms
Iteration   3: 6.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.790 ±(99.9%) 2.992 ops/ms [Average]
  (min, avg, max) = (6.657, 6.790, 6.974), stdev = 0.164
  CI (99.9%): [3.798, 9.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.375 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.003 ms/op
Iteration   1: 4.135 ±(99.9%) 0.008 ms/op
Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
Iteration   3: 3.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.995 ±(99.9%) 2.258 ms/op [Average]
  (min, avg, max) = (3.901, 3.995, 4.135), stdev = 0.124
  CI (99.9%): [1.737, 6.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.875 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.008 ms/op
Iteration   1: 3.805 ±(99.9%) 0.006 ms/op
Iteration   2: 3.825 ±(99.9%) 0.009 ms/op
Iteration   3: 3.794 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.808 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.794, 3.808, 3.825), stdev = 0.016
  CI (99.9%): [3.520, 4.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.773 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.004 ms/op
Iteration   1: 3.834 ±(99.9%) 0.009 ms/op
Iteration   2: 3.862 ±(99.9%) 0.015 ms/op
Iteration   3: 3.754 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.817 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.754, 3.817, 3.862), stdev = 0.056
  CI (99.9%): [2.796, 4.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.450 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.941 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.694 ±(99.9%) 0.008 ms/op
Iteration   1: 4.647 ±(99.9%) 0.011 ms/op
Iteration   2: 4.532 ±(99.9%) 0.010 ms/op
Iteration   3: 4.568 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.582 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (4.532, 4.582, 4.647), stdev = 0.059
  CI (99.9%): [3.508, 5.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.003 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.018 ms/op
Iteration   1: 3.892 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  13.105 ms/op
                 createUser·p0.9999: 26.804 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.793 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 3.824 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  27.415 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250170
  mean =      3.836 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 369 
    [ 2.500,  5.000) = 242497 
    [ 5.000,  7.500) = 5882 
    [ 7.500, 10.000) = 884 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.433 ms/op
     p(99.9000) =     22.932 ms/op
     p(99.9900) =     33.619 ms/op
     p(99.9990) =     36.471 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.213 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.011 ms/op
Iteration   1: 3.830 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.899 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.374 ms/op
                 existUser·p0.99:   7.542 ms/op
                 existUser·p0.999:  22.774 ms/op
                 existUser·p0.9999: 26.678 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.791 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.987 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  12.304 ms/op
                 existUser·p0.9999: 26.495 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250169
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 520 
    [ 2.500,  5.000) = 237466 
    [ 5.000,  7.500) = 10204 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     12.302 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.537 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.978 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.015 ms/op
Iteration   1: 3.947 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   8.139 ms/op
                 getUser·p0.999:  23.064 ms/op
                 getUser·p0.9999: 25.293 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   2: 3.963 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  20.393 ms/op
                 getUser·p0.9999: 30.046 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 3.821 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.622 ms/op
                 getUser·p0.999:  27.768 ms/op
                 getUser·p0.9999: 32.425 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245471
  mean =      3.909 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 435 
    [ 2.500,  5.000) = 232486 
    [ 5.000,  7.500) = 9933 
    [ 7.500, 10.000) = 1864 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     31.276 ms/op
     p(99.9990) =     32.801 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.672 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.408 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.663 ±(99.9%) 0.016 ms/op
Iteration   1: 4.476 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   7.859 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 27.679 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.597 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.708 ms/op
                 listUser·p0.999:  19.104 ms/op
                 listUser·p0.9999: 22.120 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 4.422 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 18.474 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 213427
  mean =      4.497 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 196495 
    [ 5.000,  7.500) = 13281 
    [ 7.500, 10.000) = 2718 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     18.467 ms/op
     p(99.9900) =     26.957 ms/op
     p(99.9990) =     27.990 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.007 ± 4.936  ops/ms
ClientPb.existUser                       thrpt       3   8.399 ± 7.083  ops/ms
ClientPb.getUser                         thrpt       3   7.982 ± 3.430  ops/ms
ClientPb.listUser                        thrpt       3   6.790 ± 2.992  ops/ms
ClientPb.createUser                       avgt       3   3.995 ± 2.258   ms/op
ClientPb.existUser                        avgt       3   3.808 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   3.817 ± 1.020   ms/op
ClientPb.listUser                         avgt       3   4.582 ± 1.074   ms/op
ClientPb.createUser                     sample  250170   3.836 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.433           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.619           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  250169   3.840 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.264           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.094           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  245471   3.909 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  213427   4.497 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.957           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
