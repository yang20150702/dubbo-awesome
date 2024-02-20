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
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 11.711 ops/ms
# Warmup Iteration   3: 12.206 ops/ms
Iteration   1: 12.497 ops/ms
Iteration   2: 12.583 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.540 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (12.497, 12.540, 12.583), stdev = 0.043
  CI (99.9%): [11.755, 13.325] (assumes normal distribution)


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
# Warmup Iteration   1: 7.943 ops/ms
# Warmup Iteration   2: 12.803 ops/ms
# Warmup Iteration   3: 12.794 ops/ms
Iteration   1: 12.803 ops/ms
Iteration   2: 12.918 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.879 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (12.803, 12.879, 12.918), stdev = 0.065
  CI (99.9%): [11.685, 14.073] (assumes normal distribution)


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
# Warmup Iteration   1: 7.901 ops/ms
# Warmup Iteration   2: 12.594 ops/ms
# Warmup Iteration   3: 12.913 ops/ms
Iteration   1: 13.049 ops/ms
Iteration   2: 12.893 ops/ms
Iteration   3: 12.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.921 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (12.821, 12.921, 13.049), stdev = 0.116
  CI (99.9%): [10.798, 15.043] (assumes normal distribution)


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
# Warmup Iteration   1: 6.418 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.459 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (10.407, 10.459, 10.517), stdev = 0.055
  CI (99.9%): [9.461, 11.458] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.562, 2.566, 2.569), stdev = 0.003
  CI (99.9%): [2.506, 2.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.472, 2.478, 2.489), stdev = 0.009
  CI (99.9%): [2.314, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.476, 2.480, 2.487), stdev = 0.006
  CI (99.9%): [2.367, 2.593] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
Iteration   1: 3.003 ±(99.9%) 0.007 ms/op
Iteration   2: 2.996 ±(99.9%) 0.009 ms/op
Iteration   3: 3.071 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (2.996, 3.023, 3.071), stdev = 0.041
  CI (99.9%): [2.273, 3.773] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 16.922 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 11.579 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 10.961 ms/op
                 createUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377058
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 180684 
    [ 2.500,  3.750) = 192335 
    [ 3.750,  5.000) = 3077 
    [ 5.000,  6.250) = 432 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      9.402 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.082 ms/op
                 existUser·p0.9999: 15.171 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  6.095 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.768 ms/op
                 existUser·p0.999:  8.988 ms/op
                 existUser·p0.9999: 12.337 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389779
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 192807 
    [ 2.500,  3.750) = 193259 
    [ 3.750,  5.000) = 2903 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      7.329 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     16.256 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  12.464 ms/op
                 getUser·p0.9999: 14.334 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 12.980 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380521
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 186500 
    [ 2.500,  3.750) = 188586 
    [ 3.750,  5.000) = 4337 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      8.855 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.009 ms/op
Iteration   1: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.622 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 10.376 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.369 ms/op
                 listUser·p0.9999: 12.052 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 12.206 ms/op
                 listUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313150
  mean =      3.063 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 83143 
    [ 2.500,  3.750) = 187369 
    [ 3.750,  5.000) = 34237 
    [ 5.000,  6.250) = 6757 
    [ 6.250,  7.500) = 879 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.960 ms/op
     p(99.9990) =     13.656 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.540 ± 0.785  ops/ms
ClientPb.existUser                       thrpt       3  12.879 ± 1.194  ops/ms
ClientPb.getUser                         thrpt       3  12.921 ± 2.122  ops/ms
ClientPb.listUser                        thrpt       3  10.459 ± 0.999  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.059   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.164   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.113   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.750   ms/op
ClientPb.createUser                     sample  377058   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.402           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.596           ms/op
ClientPb.existUser                      sample  389779   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.801           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.329           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.368           ms/op
ClientPb.getUser                        sample  380521   2.520 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.855           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.959           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  313150   3.063 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.795           ms/op
