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
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 5.466 ops/ms
# Warmup Iteration   3: 8.740 ops/ms
Iteration   1: 9.235 ops/ms
Iteration   2: 9.330 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (9.235, 9.299, 9.331), stdev = 0.055
  CI (99.9%): [8.287, 10.310] (assumes normal distribution)


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
# Warmup Iteration   1: 3.512 ops/ms
# Warmup Iteration   2: 8.438 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 9.628 ops/ms
Iteration   3: 9.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.654 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (9.628, 9.654, 9.671), stdev = 0.023
  CI (99.9%): [9.239, 10.070] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.070 ops/ms
# Warmup Iteration   2: 8.211 ops/ms
# Warmup Iteration   3: 8.955 ops/ms
Iteration   1: 9.307 ops/ms
Iteration   2: 9.089 ops/ms
Iteration   3: 9.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.210 ±(99.9%) 2.023 ops/ms [Average]
  (min, avg, max) = (9.089, 9.210, 9.307), stdev = 0.111
  CI (99.9%): [7.186, 11.233] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.038 ops/ms
# Warmup Iteration   2: 7.148 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 7.854 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.024 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (7.854, 8.024, 8.221), stdev = 0.185
  CI (99.9%): [4.645, 11.403] (assumes normal distribution)


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
# Warmup Iteration   1: 8.808 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.009 ms/op
Iteration   1: 3.393 ±(99.9%) 0.013 ms/op
Iteration   2: 3.356 ±(99.9%) 0.015 ms/op
Iteration   3: 3.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.374 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.356, 3.374, 3.393), stdev = 0.019
  CI (99.9%): [3.036, 3.712] (assumes normal distribution)


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
# Warmup Iteration   1: 9.580 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.007 ms/op
Iteration   1: 3.286 ±(99.9%) 0.005 ms/op
Iteration   2: 3.250 ±(99.9%) 0.003 ms/op
Iteration   3: 3.249 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.262 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.249, 3.262, 3.286), stdev = 0.021
  CI (99.9%): [2.873, 3.650] (assumes normal distribution)


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
# Warmup Iteration   1: 9.328 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.004 ms/op
Iteration   1: 3.622 ±(99.9%) 0.003 ms/op
Iteration   2: 3.384 ±(99.9%) 0.005 ms/op
Iteration   3: 3.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 2.243 ms/op [Average]
  (min, avg, max) = (3.384, 3.485, 3.622), stdev = 0.123
  CI (99.9%): [1.242, 5.728] (assumes normal distribution)


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
# Warmup Iteration   1: 9.522 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.920 ±(99.9%) 0.007 ms/op
Iteration   2: 3.861 ±(99.9%) 0.014 ms/op
Iteration   3: 3.932 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.904 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.861, 3.904, 3.932), stdev = 0.038
  CI (99.9%): [3.211, 4.598] (assumes normal distribution)


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
# Warmup Iteration   1: 10.252 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.013 ms/op
Iteration   1: 3.598 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.448 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 28.446 ms/op
                 createUser·p1.00:   30.802 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 32.026 ms/op
                 createUser·p1.00:   32.932 ms/op

Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 27.943 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278506
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7401 
    [ 2.500,  5.000) = 261299 
    [ 5.000,  7.500) = 8528 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     21.741 ms/op
     p(99.9900) =     29.567 ms/op
     p(99.9990) =     32.653 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 8.623 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.293 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  11.948 ms/op
                 existUser·p0.9999: 30.114 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  16.538 ms/op
                 existUser·p0.9999: 28.685 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292697
  mean =      3.280 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14764 
    [ 2.500,  5.000) = 273387 
    [ 5.000,  7.500) = 3205 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     29.301 ms/op
     p(99.9990) =     30.776 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 9.307 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.013 ms/op
Iteration   1: 3.410 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  20.878 ms/op
                 getUser·p0.9999: 31.961 ms/op
                 getUser·p1.00:   32.309 ms/op

Iteration   2: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  22.057 ms/op
                 getUser·p0.9999: 26.705 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 27.149 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278337
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9525 
    [ 2.500,  5.000) = 259600 
    [ 5.000,  7.500) = 8200 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     30.938 ms/op
     p(99.9990) =     32.218 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 10.567 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.014 ms/op
Iteration   1: 4.057 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  20.120 ms/op
                 listUser·p0.9999: 26.396 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   2: 4.054 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 3.978 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.996 ms/op
                 listUser·p0.9999: 21.298 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238153
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 228184 
    [ 5.000,  7.500) = 7350 
    [ 7.500, 10.000) = 1674 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     24.916 ms/op
     p(99.9990) =     26.937 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 1.011  ops/ms
ClientPb.existUser                       thrpt       3   9.654 ± 0.415  ops/ms
ClientPb.getUser                         thrpt       3   9.210 ± 2.023  ops/ms
ClientPb.listUser                        thrpt       3   8.024 ± 3.379  ops/ms
ClientPb.createUser                       avgt       3   3.374 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   3.262 ± 0.389   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 2.243   ms/op
ClientPb.listUser                         avgt       3   3.904 ± 0.694   ms/op
ClientPb.createUser                     sample  278506   3.445 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.567           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  292697   3.280 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.587           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.827           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.301           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.130           ms/op
ClientPb.getUser                        sample  278337   3.448 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.938           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.309           ms/op
ClientPb.listUser                       sample  238153   4.029 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.546           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.916           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.460           ms/op
