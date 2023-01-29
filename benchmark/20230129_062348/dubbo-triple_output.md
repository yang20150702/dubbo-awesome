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
# Warmup Iteration   1: 2.454 ops/ms
# Warmup Iteration   2: 6.199 ops/ms
# Warmup Iteration   3: 9.269 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 10.043 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.938 ±(99.9%) 5.667 ops/ms [Average]
  (min, avg, max) = (9.588, 9.938, 10.182), stdev = 0.311
  CI (99.9%): [4.271, 15.604] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ops/ms
# Warmup Iteration   2: 9.752 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.667 ±(99.9%) 0.334 ops/ms [Average]
  (min, avg, max) = (10.654, 10.667, 10.688), stdev = 0.018
  CI (99.9%): [10.333, 11.000] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ops/ms
# Warmup Iteration   2: 9.075 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.449 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.330 ±(99.9%) 5.103 ops/ms [Average]
  (min, avg, max) = (10.010, 10.330, 10.530), stdev = 0.280
  CI (99.9%): [5.227, 15.432] (assumes normal distribution)


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
# Warmup Iteration   1: 3.487 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.445 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.586 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (8.445, 8.586, 8.709), stdev = 0.133
  CI (99.9%): [6.167, 11.004] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.513 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.004 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.123 ±(99.9%) 0.007 ms/op
Iteration   3: 3.326 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.218 ±(99.9%) 1.859 ms/op [Average]
  (min, avg, max) = (3.123, 3.218, 3.326), stdev = 0.102
  CI (99.9%): [1.359, 5.076] (assumes normal distribution)


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
# Warmup Iteration   1: 7.157 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
Iteration   3: 3.139 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.037 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (2.970, 3.037, 3.139), stdev = 0.090
  CI (99.9%): [1.399, 4.674] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.802 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.002 ms/op
Iteration   1: 3.187 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
Iteration   3: 3.201 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.181 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.154, 3.181, 3.201), stdev = 0.024
  CI (99.9%): [2.743, 3.619] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.800 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.006 ms/op
Iteration   1: 3.705 ±(99.9%) 0.004 ms/op
Iteration   2: 3.816 ±(99.9%) 0.003 ms/op
Iteration   3: 3.684 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.735 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.684, 3.735, 3.816), stdev = 0.071
  CI (99.9%): [2.439, 5.031] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.165 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 25.263 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  10.064 ms/op
                 createUser·p0.9999: 21.625 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  16.040 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301481
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14009 
    [ 2.500,  5.000) = 283780 
    [ 5.000,  7.500) = 3003 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.624 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 7.381 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
Iteration   1: 3.174 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.020 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 22.933 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 21.328 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  8.844 ms/op
                 existUser·p0.9999: 24.084 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300307
  mean =      3.196 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26168 
    [ 2.500,  5.000) = 267664 
    [ 5.000,  7.500) = 5730 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     10.651 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.641 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 8.289 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.010 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   6.033 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  11.705 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.081 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  13.337 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299312
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21638 
    [ 2.500,  5.000) = 270076 
    [ 5.000,  7.500) = 6652 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.856 ms/op
     p(99.9000) =     13.856 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 9.515 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.011 ms/op
Iteration   1: 3.765 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.037 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  16.690 ms/op
                 listUser·p0.9999: 20.463 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.652 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.133 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 14.172 ms/op
                 listUser·p1.00:   15.647 ms/op

Iteration   3: 3.846 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 15.964 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256025
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 248142 
    [ 5.000,  7.500) = 6155 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.188 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     20.935 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.938 ± 5.667  ops/ms
ClientPb.existUser                       thrpt       3  10.667 ± 0.334  ops/ms
ClientPb.getUser                         thrpt       3  10.330 ± 5.103  ops/ms
ClientPb.listUser                        thrpt       3   8.586 ± 2.419  ops/ms
ClientPb.createUser                       avgt       3   3.218 ± 1.859   ms/op
ClientPb.existUser                        avgt       3   3.037 ± 1.637   ms/op
ClientPb.getUser                          avgt       3   3.181 ± 0.438   ms/op
ClientPb.listUser                         avgt       3   3.735 ± 1.296   ms/op
ClientPb.createUser                     sample  301481   3.184 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.887           ms/op
ClientPb.existUser                      sample  300307   3.196 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.020           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.651           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.298           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.788           ms/op
ClientPb.getUser                        sample  299312   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.856           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.856           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  256025   3.753 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.188           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.070           ms/op
