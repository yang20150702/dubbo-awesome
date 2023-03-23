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
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.607 ops/ms
# Warmup Iteration   3: 8.256 ops/ms
Iteration   1: 9.295 ops/ms
Iteration   2: 9.039 ops/ms
Iteration   3: 9.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.144 ±(99.9%) 2.442 ops/ms [Average]
  (min, avg, max) = (9.039, 9.144, 9.295), stdev = 0.134
  CI (99.9%): [6.703, 11.586] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.601 ops/ms
# Warmup Iteration   2: 8.125 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 9.709 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 8.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.424 ±(99.9%) 7.241 ops/ms [Average]
  (min, avg, max) = (8.971, 9.424, 9.709), stdev = 0.397
  CI (99.9%): [2.183, 16.666] (assumes normal distribution)


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
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 7.398 ops/ms
# Warmup Iteration   3: 9.070 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.474 ops/ms
Iteration   3: 9.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.512 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (9.474, 9.512, 9.533), stdev = 0.033
  CI (99.9%): [8.914, 10.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.609 ops/ms
# Warmup Iteration   2: 7.115 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.088 ops/ms
Iteration   3: 7.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.015 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (7.885, 8.015, 8.088), stdev = 0.113
  CI (99.9%): [5.950, 10.080] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.147 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.005 ms/op
Iteration   1: 3.550 ±(99.9%) 0.005 ms/op
Iteration   2: 3.364 ±(99.9%) 0.008 ms/op
Iteration   3: 3.436 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 1.710 ms/op [Average]
  (min, avg, max) = (3.364, 3.450, 3.550), stdev = 0.094
  CI (99.9%): [1.740, 5.160] (assumes normal distribution)


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
# Warmup Iteration   1: 9.492 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.005 ms/op
Iteration   1: 3.296 ±(99.9%) 0.012 ms/op
Iteration   2: 3.394 ±(99.9%) 0.006 ms/op
Iteration   3: 3.265 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.318 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (3.265, 3.318, 3.394), stdev = 0.067
  CI (99.9%): [2.088, 4.549] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.004 ms/op
Iteration   1: 3.514 ±(99.9%) 0.005 ms/op
Iteration   2: 3.594 ±(99.9%) 0.003 ms/op
Iteration   3: 3.528 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.545 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (3.514, 3.545, 3.594), stdev = 0.043
  CI (99.9%): [2.761, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 12.218 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.006 ms/op
Iteration   1: 4.040 ±(99.9%) 0.007 ms/op
Iteration   2: 3.951 ±(99.9%) 0.017 ms/op
Iteration   3: 3.994 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.995 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.951, 3.995, 4.040), stdev = 0.044
  CI (99.9%): [3.187, 4.803] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.660 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
Iteration   1: 3.536 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  22.135 ms/op
                 createUser·p0.9999: 30.473 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 3.715 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   6.832 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  23.680 ms/op
                 createUser·p0.9999: 26.358 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 32.106 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268664
  mean =      3.572 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6501 
    [ 2.500,  5.000) = 247432 
    [ 5.000,  7.500) = 11353 
    [ 7.500, 10.000) = 2410 
    [10.000, 12.500) = 486 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     17.323 ms/op
     p(99.9900) =     30.717 ms/op
     p(99.9990) =     32.250 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 9.462 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.010 ms/op
Iteration   1: 3.433 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.485 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  19.956 ms/op
                 existUser·p0.9999: 24.358 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   2: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  11.169 ms/op
                 existUser·p0.9999: 29.594 ms/op
                 existUser·p1.00:   30.573 ms/op

Iteration   3: 3.279 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  19.579 ms/op
                 existUser·p0.9999: 29.737 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288070
  mean =      3.332 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7927 
    [ 2.500,  5.000) = 274096 
    [ 5.000,  7.500) = 4901 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     19.626 ms/op
     p(99.9900) =     29.301 ms/op
     p(99.9990) =     30.580 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 10.107 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.010 ms/op
Iteration   1: 3.585 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  19.690 ms/op
                 getUser·p0.9999: 22.452 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.973 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 24.141 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.024 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  17.720 ms/op
                 getUser·p0.9999: 28.314 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271261
  mean =      3.536 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8136 
    [ 2.500,  5.000) = 252061 
    [ 5.000,  7.500) = 9397 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     19.447 ms/op
     p(99.9900) =     25.248 ms/op
     p(99.9990) =     29.463 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 10.958 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.764 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.013 ms/op
Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 4.090 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  16.365 ms/op
                 listUser·p0.9999: 23.474 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 4.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  17.149 ms/op
                 listUser·p0.9999: 25.526 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235065
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 226173 
    [ 5.000,  7.500) = 6653 
    [ 7.500, 10.000) = 1343 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.144 ± 2.442  ops/ms
ClientPb.existUser                       thrpt       3   9.424 ± 7.241  ops/ms
ClientPb.getUser                         thrpt       3   9.512 ± 0.597  ops/ms
ClientPb.listUser                        thrpt       3   8.015 ± 2.065  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 1.710   ms/op
ClientPb.existUser                        avgt       3   3.318 ± 1.231   ms/op
ClientPb.getUser                          avgt       3   3.545 ± 0.784   ms/op
ClientPb.listUser                         avgt       3   3.995 ± 0.808   ms/op
ClientPb.createUser                     sample  268664   3.572 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.323           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.717           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  288070   3.332 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.626           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.301           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  271261   3.536 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.248           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.622           ms/op
ClientPb.listUser                       sample  235065   4.083 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.516           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.907           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
