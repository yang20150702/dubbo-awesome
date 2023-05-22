# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 5.933 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.455 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (9.340, 9.455, 9.544), stdev = 0.105
  CI (99.9%): [7.546, 11.364] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.282 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.426 ops/ms
Iteration   1: 9.432 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.762 ±(99.9%) 5.582 ops/ms [Average]
  (min, avg, max) = (9.432, 9.762, 10.036), stdev = 0.306
  CI (99.9%): [4.180, 15.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 8.487 ops/ms
# Warmup Iteration   3: 9.094 ops/ms
Iteration   1: 9.107 ops/ms
Iteration   2: 9.458 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.337 ±(99.9%) 3.630 ops/ms [Average]
  (min, avg, max) = (9.107, 9.337, 9.458), stdev = 0.199
  CI (99.9%): [5.707, 12.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.936 ops/ms
# Warmup Iteration   2: 7.350 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 8.028 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.177 ±(99.9%) 5.726 ops/ms [Average]
  (min, avg, max) = (7.966, 8.177, 8.538), stdev = 0.314
  CI (99.9%): [2.452, 13.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.978 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.003 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
Iteration   3: 3.378 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.410 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.378, 3.410, 3.464), stdev = 0.047
  CI (99.9%): [2.547, 4.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.003 ms/op
Iteration   1: 3.253 ±(99.9%) 0.010 ms/op
Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
Iteration   3: 3.148 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.181 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (3.140, 3.181, 3.253), stdev = 0.063
  CI (99.9%): [2.031, 4.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.736 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.004 ms/op
Iteration   1: 3.494 ±(99.9%) 0.004 ms/op
Iteration   2: 3.361 ±(99.9%) 0.007 ms/op
Iteration   3: 3.261 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.372 ±(99.9%) 2.128 ms/op [Average]
  (min, avg, max) = (3.261, 3.372, 3.494), stdev = 0.117
  CI (99.9%): [1.244, 5.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.280 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.006 ms/op
Iteration   1: 3.907 ±(99.9%) 0.011 ms/op
Iteration   2: 3.893 ±(99.9%) 0.009 ms/op
Iteration   3: 3.813 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.871 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.813, 3.871, 3.907), stdev = 0.051
  CI (99.9%): [2.948, 4.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.527 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.013 ms/op
Iteration   1: 3.321 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  20.796 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   36.176 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  21.362 ms/op
                 createUser·p0.9999: 24.234 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.362 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.507 ms/op
                 createUser·p0.9999: 33.191 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285806
  mean =      3.356 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20695 
    [ 2.500,  5.000) = 259188 
    [ 5.000,  7.500) = 4978 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.689 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.025 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 22.248 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.307 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.879 ms/op
                 existUser·p0.9999: 24.357 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  12.259 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294702
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18531 
    [ 2.500,  5.000) = 271832 
    [ 5.000,  7.500) = 3442 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     11.528 ms/op
     p(99.9900) =     23.938 ms/op
     p(99.9990) =     24.709 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.258 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.608 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  15.880 ms/op
                 getUser·p0.9999: 23.961 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  21.150 ms/op
                 getUser·p0.9999: 27.552 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 26.764 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277006
  mean =      3.467 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10502 
    [ 2.500,  5.000) = 256914 
    [ 5.000,  7.500) = 8306 
    [ 7.500, 10.000) = 773 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.023 ms/op
     p(99.9900) =     26.781 ms/op
     p(99.9990) =     28.291 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.939 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.012 ms/op
Iteration   1: 3.943 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 25.746 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 3.796 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.330 ms/op
                 listUser·p0.999:  14.156 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.846 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248504
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 241852 
    [ 5.000,  7.500) = 4731 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     15.851 ms/op
     p(99.9900) =     23.257 ms/op
     p(99.9990) =     27.118 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.455 ± 1.909  ops/ms
ClientPb.existUser                       thrpt       3   9.762 ± 5.582  ops/ms
ClientPb.getUser                         thrpt       3   9.337 ± 3.630  ops/ms
ClientPb.listUser                        thrpt       3   8.177 ± 5.726  ops/ms
ClientPb.createUser                       avgt       3   3.410 ± 0.863   ms/op
ClientPb.existUser                        avgt       3   3.181 ± 1.150   ms/op
ClientPb.getUser                          avgt       3   3.372 ± 2.128   ms/op
ClientPb.listUser                         avgt       3   3.871 ± 0.923   ms/op
ClientPb.createUser                     sample  285806   3.356 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.176           ms/op
ClientPb.existUser                      sample  294702   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.452           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.528           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  277006   3.467 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.989           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.023           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.781           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.574           ms/op
ClientPb.listUser                       sample  248504   3.861 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.851           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
