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
# Warmup Iteration   1: 5.130 ops/ms
# Warmup Iteration   2: 12.398 ops/ms
# Warmup Iteration   3: 12.573 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.942 ops/ms
Iteration   3: 12.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.915 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (12.831, 12.915, 12.973), stdev = 0.074
  CI (99.9%): [11.559, 14.271] (assumes normal distribution)


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
# Warmup Iteration   1: 8.510 ops/ms
# Warmup Iteration   2: 13.344 ops/ms
# Warmup Iteration   3: 13.053 ops/ms
Iteration   1: 13.218 ops/ms
Iteration   2: 13.273 ops/ms
Iteration   3: 13.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.252 ±(99.9%) 0.536 ops/ms [Average]
  (min, avg, max) = (13.218, 13.252, 13.273), stdev = 0.029
  CI (99.9%): [12.716, 13.787] (assumes normal distribution)


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
# Warmup Iteration   1: 8.276 ops/ms
# Warmup Iteration   2: 12.848 ops/ms
# Warmup Iteration   3: 13.019 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 13.082 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.045 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (13.021, 13.045, 13.082), stdev = 0.032
  CI (99.9%): [12.456, 13.635] (assumes normal distribution)


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
# Warmup Iteration   1: 6.757 ops/ms
# Warmup Iteration   2: 10.624 ops/ms
# Warmup Iteration   3: 10.664 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.711 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.705 ±(99.9%) 0.226 ops/ms [Average]
  (min, avg, max) = (10.691, 10.705, 10.713), stdev = 0.012
  CI (99.9%): [10.479, 10.931] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.482 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.471, 2.482, 2.495), stdev = 0.012
  CI (99.9%): [2.262, 2.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.478 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.407 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.407 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.389, 2.407, 2.424), stdev = 0.017
  CI (99.9%): [2.092, 2.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.474, 2.486, 2.494), stdev = 0.010
  CI (99.9%): [2.298, 2.673] (assumes normal distribution)


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.986, 2.992, 2.998), stdev = 0.006
  CI (99.9%): [2.884, 3.099] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  6.920 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.844 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  7.753 ms/op
                 createUser·p0.9999: 13.108 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.267 ms/op
                 createUser·p0.9999: 9.978 ms/op
                 createUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389150
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 190064 
    [ 2.500,  3.750) = 195302 
    [ 3.750,  5.000) = 2838 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 137 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.246 ms/op
     p(99.9900) =     13.195 ms/op
     p(99.9990) =     13.857 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.378 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
Iteration   1: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.322 ms/op
                 existUser·p0.999:  5.915 ms/op
                 existUser·p0.9999: 13.451 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  7.211 ms/op
                 existUser·p0.9999: 14.137 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.363 ms/op
                 existUser·p0.999:  7.823 ms/op
                 existUser·p0.9999: 13.215 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396799
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 198837 
    [ 2.500,  3.750) = 195621 
    [ 3.750,  5.000) = 1654 
    [ 5.000,  6.250) = 213 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =      6.676 ms/op
     p(99.9900) =     13.451 ms/op
     p(99.9990) =     14.468 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.664 ms/op
                 getUser·p0.999:  7.277 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.733 ms/op
                 getUser·p0.9999: 11.987 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 10.894 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389190
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 195440 
    [ 2.500,  3.750) = 189323 
    [ 3.750,  5.000) = 3123 
    [ 5.000,  6.250) = 733 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      7.763 ms/op
     p(99.9900) =     12.863 ms/op
     p(99.9990) =     13.901 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.149 ms/op
                 listUser·p0.9999: 10.597 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   2: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.928 ms/op
                 listUser·p0.9999: 10.984 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322660
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 99622 
    [ 2.500,  3.750) = 185198 
    [ 3.750,  5.000) = 30999 
    [ 5.000,  6.250) = 5467 
    [ 6.250,  7.500) = 518 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 314 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     12.115 ms/op
     p(99.9999) =     13.091 ms/op
    p(100.0000) =     13.091 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.915 ± 1.356  ops/ms
ClientPb.existUser                       thrpt       3  13.252 ± 0.536  ops/ms
ClientPb.getUser                         thrpt       3  13.045 ± 0.589  ops/ms
ClientPb.listUser                        thrpt       3  10.705 ± 0.226  ops/ms
ClientPb.createUser                       avgt       3   2.482 ± 0.220   ms/op
ClientPb.existUser                        avgt       3   2.407 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.187   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.108   ms/op
ClientPb.createUser                     sample  389150   2.464 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.246           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.195           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.057           ms/op
ClientPb.existUser                      sample  396799   2.417 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.878           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.676           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.451           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  389190   2.465 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.763           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.863           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.615           ms/op
ClientPb.listUser                       sample  322660   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.907           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.091           ms/op
