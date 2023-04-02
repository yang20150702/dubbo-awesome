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
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 6.990 ops/ms
# Warmup Iteration   3: 9.262 ops/ms
Iteration   1: 9.937 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 9.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.834 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (9.734, 9.834, 9.937), stdev = 0.101
  CI (99.9%): [7.985, 11.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.671 ±(99.9%) 5.792 ops/ms [Average]
  (min, avg, max) = (10.305, 10.671, 10.860), stdev = 0.317
  CI (99.9%): [4.880, 16.463] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.541 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.982 ±(99.9%) 1.277 ops/ms [Average]
  (min, avg, max) = (9.905, 9.982, 10.041), stdev = 0.070
  CI (99.9%): [8.704, 11.259] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ops/ms
# Warmup Iteration   2: 7.737 ops/ms
# Warmup Iteration   3: 8.352 ops/ms
Iteration   1: 8.565 ops/ms
Iteration   2: 8.378 ops/ms
Iteration   3: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.468 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (8.378, 8.468, 8.565), stdev = 0.094
  CI (99.9%): [6.751, 10.185] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.360 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.003 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.083 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.037, 3.083, 3.124), stdev = 0.044
  CI (99.9%): [2.284, 3.883] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.546 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.031 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.016, 3.031, 3.040), stdev = 0.013
  CI (99.9%): [2.791, 3.270] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.003 ms/op
Iteration   1: 3.261 ±(99.9%) 0.006 ms/op
Iteration   2: 3.300 ±(99.9%) 0.006 ms/op
Iteration   3: 3.078 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 2.166 ms/op [Average]
  (min, avg, max) = (3.078, 3.213, 3.300), stdev = 0.119
  CI (99.9%): [1.046, 5.379] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.579 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.004 ms/op
Iteration   1: 3.711 ±(99.9%) 0.005 ms/op
Iteration   2: 3.595 ±(99.9%) 0.010 ms/op
Iteration   3: 3.693 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.666 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.595, 3.666, 3.711), stdev = 0.062
  CI (99.9%): [2.532, 4.801] (assumes normal distribution)


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
# Warmup Iteration   1: 7.508 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  13.876 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302581
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16376 
    [ 2.500,  5.000) = 280705 
    [ 5.000,  7.500) = 4437 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     16.156 ms/op
     p(99.9900) =     21.160 ms/op
     p(99.9990) =     22.576 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.953 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  7.749 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.391 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.960 ms/op
                 existUser·p0.9999: 26.403 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 25.651 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309746
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19467 
    [ 2.500,  5.000) = 285360 
    [ 5.000,  7.500) = 4216 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     27.451 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 8.547 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.011 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  16.876 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   19.890 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.867 ms/op
                 getUser·p0.9999: 25.731 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 21.979 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302468
  mean =      3.173 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14920 
    [ 2.500,  5.000) = 282219 
    [ 5.000,  7.500) = 4457 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     16.369 ms/op
     p(99.9900) =     24.036 ms/op
     p(99.9990) =     26.992 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 8.377 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.012 ms/op
Iteration   1: 3.683 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 26.952 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 3.682 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  13.043 ms/op
                 listUser·p0.9999: 14.139 ms/op
                 listUser·p1.00:   14.533 ms/op

Iteration   3: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258993
  mean =      3.707 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 252330 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.845 ms/op
     p(99.9900) =     18.648 ms/op
     p(99.9990) =     27.932 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.834 ± 1.849  ops/ms
ClientPb.existUser                       thrpt       3  10.671 ± 5.792  ops/ms
ClientPb.getUser                         thrpt       3   9.982 ± 1.277  ops/ms
ClientPb.listUser                        thrpt       3   8.468 ± 1.717  ops/ms
ClientPb.createUser                       avgt       3   3.083 ± 0.800   ms/op
ClientPb.existUser                        avgt       3   3.031 ± 0.240   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 2.166   ms/op
ClientPb.listUser                         avgt       3   3.666 ± 1.135   ms/op
ClientPb.createUser                     sample  302581   3.169 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.538           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.156           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.160           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  309746   3.098 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.313           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.854           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  302468   3.173 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.369           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.036           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  258993   3.707 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.219           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.845           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.648           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
