# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.371 ops/ms
# Warmup Iteration   2: 12.472 ops/ms
# Warmup Iteration   3: 12.894 ops/ms
Iteration   1: 13.062 ops/ms
Iteration   2: 13.019 ops/ms
Iteration   3: 12.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.020 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (12.977, 13.020, 13.062), stdev = 0.042
  CI (99.9%): [12.249, 13.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.570 ops/ms
# Warmup Iteration   2: 13.357 ops/ms
# Warmup Iteration   3: 13.315 ops/ms
Iteration   1: 13.360 ops/ms
Iteration   2: 13.441 ops/ms
Iteration   3: 13.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.374 ±(99.9%) 1.119 ops/ms [Average]
  (min, avg, max) = (13.321, 13.374, 13.441), stdev = 0.061
  CI (99.9%): [12.255, 14.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.380 ops/ms
# Warmup Iteration   2: 12.915 ops/ms
# Warmup Iteration   3: 13.112 ops/ms
Iteration   1: 13.083 ops/ms
Iteration   2: 13.057 ops/ms
Iteration   3: 12.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.031 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (12.952, 13.031, 13.083), stdev = 0.069
  CI (99.9%): [11.767, 14.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.829 ops/ms
# Warmup Iteration   2: 10.631 ops/ms
# Warmup Iteration   3: 10.970 ops/ms
Iteration   1: 10.844 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.833 ±(99.9%) 1.162 ops/ms [Average]
  (min, avg, max) = (10.764, 10.833, 10.890), stdev = 0.064
  CI (99.9%): [9.670, 11.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.003 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.472 ±(99.9%) 0.307 ms/op [Average]
  (min, avg, max) = (2.453, 2.472, 2.484), stdev = 0.017
  CI (99.9%): [2.165, 2.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
Iteration   1: 2.410 ±(99.9%) 0.003 ms/op
Iteration   2: 2.388 ±(99.9%) 0.004 ms/op
Iteration   3: 2.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.400 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (2.388, 2.400, 2.410), stdev = 0.011
  CI (99.9%): [2.197, 2.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.475 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.458, 2.475, 2.487), stdev = 0.015
  CI (99.9%): [2.203, 2.746] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
Iteration   3: 2.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.951, 2.965, 2.983), stdev = 0.016
  CI (99.9%): [2.668, 3.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.689 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  5.832 ms/op
                 createUser·p0.9999: 13.501 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.621 ms/op
                 createUser·p0.999:  8.861 ms/op
                 createUser·p0.9999: 11.188 ms/op
                 createUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387241
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 190319 
    [ 2.500,  3.750) = 193554 
    [ 3.750,  5.000) = 2633 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      8.715 ms/op
     p(99.9900) =     14.160 ms/op
     p(99.9990) =     14.963 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.397 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.383 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  6.505 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.387 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.601 ms/op
                 existUser·p0.999:  8.505 ms/op
                 existUser·p0.9999: 10.863 ms/op
                 existUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400209
  mean =      2.396 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 205006 
    [ 2.500,  3.750) = 191855 
    [ 3.750,  5.000) = 2361 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.362 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.472 ms/op
                 getUser·p0.999:  7.822 ms/op
                 getUser·p0.9999: 12.973 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  6.968 ms/op
                 getUser·p0.9999: 12.320 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  5.432 ms/op
                 getUser·p0.9999: 12.716 ms/op
                 getUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393826
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 199499 
    [ 2.500,  3.750) = 190634 
    [ 3.750,  5.000) = 2790 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 168 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      7.702 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     13.158 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.009 ms/op
Iteration   1: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.457 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.691 ms/op
                 listUser·p0.9999: 11.017 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.355 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323345
  mean =      2.967 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 99592 
    [ 2.500,  3.750) = 186413 
    [ 3.750,  5.000) = 30409 
    [ 5.000,  6.250) = 5352 
    [ 6.250,  7.500) = 720 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.775 ms/op
     p(99.9990) =     12.938 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.020 ± 0.771  ops/ms
ClientPb.existUser                       thrpt       3  13.374 ± 1.119  ops/ms
ClientPb.getUser                         thrpt       3  13.031 ± 1.264  ops/ms
ClientPb.listUser                        thrpt       3  10.833 ± 1.162  ops/ms
ClientPb.createUser                       avgt       3   2.472 ± 0.307   ms/op
ClientPb.existUser                        avgt       3   2.400 ± 0.203   ms/op
ClientPb.getUser                          avgt       3   2.475 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.297   ms/op
ClientPb.createUser                     sample  387241   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.715           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.160           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.237           ms/op
ClientPb.existUser                      sample  400209   2.396 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.912           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.362           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  393826   2.435 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.966           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.702           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.845           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.484           ms/op
ClientPb.listUser                       sample  323345   2.967 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.775           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
