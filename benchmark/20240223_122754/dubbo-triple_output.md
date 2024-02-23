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
# Warmup Iteration   1: 4.596 ops/ms
# Warmup Iteration   2: 11.760 ops/ms
# Warmup Iteration   3: 12.149 ops/ms
Iteration   1: 12.406 ops/ms
Iteration   2: 12.426 ops/ms
Iteration   3: 12.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.427 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (12.406, 12.427, 12.448), stdev = 0.021
  CI (99.9%): [12.049, 12.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.343 ops/ms
# Warmup Iteration   2: 13.068 ops/ms
# Warmup Iteration   3: 13.100 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 13.086 ops/ms
Iteration   3: 13.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.033 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (12.980, 13.033, 13.086), stdev = 0.053
  CI (99.9%): [12.063, 14.002] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ops/ms
# Warmup Iteration   2: 12.807 ops/ms
# Warmup Iteration   3: 13.049 ops/ms
Iteration   1: 12.913 ops/ms
Iteration   2: 12.961 ops/ms
Iteration   3: 12.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.951 ±(99.9%) 0.633 ops/ms [Average]
  (min, avg, max) = (12.913, 12.951, 12.980), stdev = 0.035
  CI (99.9%): [12.318, 13.585] (assumes normal distribution)


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
# Warmup Iteration   1: 6.587 ops/ms
# Warmup Iteration   2: 10.451 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 10.729 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.704 ±(99.9%) 0.932 ops/ms [Average]
  (min, avg, max) = (10.645, 10.704, 10.738), stdev = 0.051
  CI (99.9%): [9.772, 11.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.003 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.488, 2.515, 2.528), stdev = 0.023
  CI (99.9%): [2.094, 2.935] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.464, 2.469, 2.474), stdev = 0.005
  CI (99.9%): [2.374, 2.565] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.008 ms/op [Average]
  (min, avg, max) = (2.489, 2.490, 2.490), stdev = 0.001
  CI (99.9%): [2.482, 2.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.004 ms/op
Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
Iteration   3: 3.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (3.021, 3.025, 3.031), stdev = 0.005
  CI (99.9%): [2.927, 3.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  12.447 ms/op
                 createUser·p0.9999: 15.458 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 12.664 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.266 ms/op
                 createUser·p0.9999: 10.289 ms/op
                 createUser·p1.00:   11.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376289
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 180092 
    [ 2.500,  3.750) = 192246 
    [ 3.750,  5.000) = 3131 
    [ 5.000,  6.250) = 315 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      9.056 ms/op
     p(99.9900) =     13.670 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.576 ms/op
                 existUser·p0.999:  6.494 ms/op
                 existUser·p0.9999: 14.009 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  7.223 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.740 ms/op
                 existUser·p0.9999: 11.043 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388439
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 189871 
    [ 2.500,  3.750) = 195202 
    [ 3.750,  5.000) = 2514 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      6.884 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.753 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  11.275 ms/op
                 getUser·p0.9999: 13.317 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  8.793 ms/op
                 getUser·p0.9999: 12.915 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.416 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  8.194 ms/op
                 getUser·p0.9999: 11.034 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378405
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 183680 
    [ 2.500,  3.750) = 189525 
    [ 3.750,  5.000) = 4339 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.523 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.777 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.840 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   11.190 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.272 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 11.839 ms/op
                 listUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317761
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 89216 
    [ 2.500,  3.750) = 190175 
    [ 3.750,  5.000) = 31568 
    [ 5.000,  6.250) = 5444 
    [ 6.250,  7.500) = 561 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     12.166 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.427 ± 0.378  ops/ms
ClientPb.existUser                       thrpt       3  13.033 ± 0.970  ops/ms
ClientPb.getUser                         thrpt       3  12.951 ± 0.633  ops/ms
ClientPb.listUser                        thrpt       3  10.704 ± 0.932  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.421   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.096   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.008   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.098   ms/op
ClientPb.createUser                     sample  376289   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.056           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.670           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.663           ms/op
ClientPb.existUser                      sample  388439   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.884           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  378405   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.416           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.523           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.042           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.254           ms/op
ClientPb.listUser                       sample  317761   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.845           ms/op
