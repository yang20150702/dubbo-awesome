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
# Warmup Iteration   1: 4.677 ops/ms
# Warmup Iteration   2: 12.452 ops/ms
# Warmup Iteration   3: 12.693 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.878 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.865 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (12.793, 12.865, 12.925), stdev = 0.067
  CI (99.9%): [11.649, 14.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ops/ms
# Warmup Iteration   2: 13.163 ops/ms
# Warmup Iteration   3: 13.240 ops/ms
Iteration   1: 13.095 ops/ms
Iteration   2: 13.168 ops/ms
Iteration   3: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.167 ±(99.9%) 1.325 ops/ms [Average]
  (min, avg, max) = (13.095, 13.167, 13.240), stdev = 0.073
  CI (99.9%): [11.842, 14.492] (assumes normal distribution)


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
# Warmup Iteration   1: 7.593 ops/ms
# Warmup Iteration   2: 12.591 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 12.753 ops/ms
Iteration   2: 12.898 ops/ms
Iteration   3: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.794 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (12.732, 12.794, 12.898), stdev = 0.091
  CI (99.9%): [11.142, 14.447] (assumes normal distribution)


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
# Warmup Iteration   1: 6.800 ops/ms
# Warmup Iteration   2: 10.666 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 10.787 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.816 ±(99.9%) 0.579 ops/ms [Average]
  (min, avg, max) = (10.787, 10.816, 10.850), stdev = 0.032
  CI (99.9%): [10.237, 11.395] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.476 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.469, 2.476, 2.482), stdev = 0.006
  CI (99.9%): [2.358, 2.593] (assumes normal distribution)


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.398 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.367 ±(99.9%) 0.003 ms/op
Iteration   1: 2.375 ±(99.9%) 0.004 ms/op
Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
Iteration   3: 2.371 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.391 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (2.371, 2.391, 2.427), stdev = 0.031
  CI (99.9%): [1.817, 2.965] (assumes normal distribution)


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.424 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.414 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.410, 2.414, 2.422), stdev = 0.007
  CI (99.9%): [2.295, 2.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
Iteration   3: 2.960 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.943, 2.963, 2.985), stdev = 0.021
  CI (99.9%): [2.576, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 13.877 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.502 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 11.928 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.263 ms/op
                 createUser·p0.9999: 10.306 ms/op
                 createUser·p1.00:   10.879 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382362
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 185757 
    [ 2.500,  3.750) = 193049 
    [ 3.750,  5.000) = 2808 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.708 ms/op
     p(99.9000) =      8.254 ms/op
     p(99.9900) =     13.296 ms/op
     p(99.9990) =     14.175 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.005 ms/op
Iteration   1: 2.386 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  10.388 ms/op
                 existUser·p0.9999: 14.320 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 12.063 ms/op
                 existUser·p1.00:   12.632 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.454 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  8.791 ms/op
                 existUser·p0.9999: 11.551 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399221
  mean =      2.402 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 204018 
    [ 2.500,  3.750) = 192129 
    [ 3.750,  5.000) = 2325 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      8.238 ms/op
     p(99.9900) =     13.599 ms/op
     p(99.9990) =     14.467 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.849 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.006 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.953 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.650 ms/op
                 getUser·p0.999:  6.157 ms/op
                 getUser·p0.9999: 14.103 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  6.707 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.394 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.959 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  6.027 ms/op
                 getUser·p0.9999: 10.482 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 396210
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 206126 
    [ 2.500,  3.750) = 185498 
    [ 3.750,  5.000) = 3645 
    [ 5.000,  6.250) = 419 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      6.320 ms/op
     p(99.9900) =     13.081 ms/op
     p(99.9990) =     14.289 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.438 ms/op
                 listUser·p0.9999: 9.953 ms/op
                 listUser·p1.00:   10.142 ms/op

Iteration   2: 2.940 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.706 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.439 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   3: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.374 ms/op
                 listUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324127
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 100600 
    [ 2.500,  3.750) = 186893 
    [ 3.750,  5.000) = 29792 
    [ 5.000,  6.250) = 5493 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 294 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.495 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     10.338 ms/op
     p(99.9990) =     11.474 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.865 ± 1.216  ops/ms
ClientPb.existUser                       thrpt       3  13.167 ± 1.325  ops/ms
ClientPb.getUser                         thrpt       3  12.794 ± 1.652  ops/ms
ClientPb.listUser                        thrpt       3  10.816 ± 0.579  ops/ms
ClientPb.createUser                       avgt       3   2.476 ± 0.117   ms/op
ClientPb.existUser                        avgt       3   2.391 ± 0.574   ms/op
ClientPb.getUser                          avgt       3   2.414 ± 0.120   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 0.386   ms/op
ClientPb.createUser                     sample  382362   2.509 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.708           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.296           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  399221   2.402 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.599           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.615           ms/op
ClientPb.getUser                        sample  396210   2.421 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.394           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.320           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.081           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.909           ms/op
ClientPb.listUser                       sample  324127   2.959 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.495           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.782           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.338           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.993           ms/op
