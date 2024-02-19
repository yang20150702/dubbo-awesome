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
# Warmup Iteration   1: 5.206 ops/ms
# Warmup Iteration   2: 12.238 ops/ms
# Warmup Iteration   3: 12.479 ops/ms
Iteration   1: 12.738 ops/ms
Iteration   2: 12.741 ops/ms
Iteration   3: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.755 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (12.738, 12.755, 12.785), stdev = 0.026
  CI (99.9%): [12.279, 13.231] (assumes normal distribution)


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
# Warmup Iteration   1: 7.740 ops/ms
# Warmup Iteration   2: 12.796 ops/ms
# Warmup Iteration   3: 12.824 ops/ms
Iteration   1: 12.962 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 12.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.929 ±(99.9%) 0.514 ops/ms [Average]
  (min, avg, max) = (12.912, 12.929, 12.962), stdev = 0.028
  CI (99.9%): [12.415, 13.443] (assumes normal distribution)


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
# Warmup Iteration   1: 7.979 ops/ms
# Warmup Iteration   2: 12.732 ops/ms
# Warmup Iteration   3: 12.765 ops/ms
Iteration   1: 12.850 ops/ms
Iteration   2: 12.644 ops/ms
Iteration   3: 12.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.768 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (12.644, 12.768, 12.850), stdev = 0.109
  CI (99.9%): [10.777, 14.758] (assumes normal distribution)


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
# Warmup Iteration   1: 6.709 ops/ms
# Warmup Iteration   2: 10.434 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.769 ±(99.9%) 0.337 ops/ms [Average]
  (min, avg, max) = (10.752, 10.769, 10.789), stdev = 0.018
  CI (99.9%): [10.432, 11.106] (assumes normal distribution)


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.003 ms/op
Iteration   3: 2.476 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.482 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.476, 2.482, 2.488), stdev = 0.006
  CI (99.9%): [2.371, 2.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.425 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.004 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.419 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.407, 2.419, 2.431), stdev = 0.012
  CI (99.9%): [2.201, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.484, 2.490, 2.494), stdev = 0.005
  CI (99.9%): [2.391, 2.589] (assumes normal distribution)


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
# Warmup Iteration   1: 4.651 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 2.966 ±(99.9%) 0.005 ms/op
Iteration   2: 2.994 ±(99.9%) 0.004 ms/op
Iteration   3: 3.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (2.966, 2.995, 3.025), stdev = 0.030
  CI (99.9%): [2.455, 3.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  7.069 ms/op
                 createUser·p0.9999: 16.110 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  9.419 ms/op
                 createUser·p0.9999: 12.416 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  8.645 ms/op
                 createUser·p0.9999: 10.994 ms/op
                 createUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387858
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 188939 
    [ 2.500,  3.750) = 195381 
    [ 3.750,  5.000) = 2706 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.669 ms/op
     p(99.9900) =     13.242 ms/op
     p(99.9990) =     16.982 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  5.235 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   2: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.398 ms/op
                 existUser·p0.999:  6.223 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.700 ms/op
                 existUser·p0.9999: 11.589 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398013
  mean =      2.410 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 200651 
    [ 2.500,  3.750) = 194393 
    [ 3.750,  5.000) = 2272 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =     12.983 ms/op
     p(99.9990) =     14.898 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  7.509 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.143 ms/op
                 getUser·p0.9999: 15.299 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.817 ms/op
                 getUser·p0.9999: 11.372 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391912
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 199949 
    [ 2.500,  3.750) = 186726 
    [ 3.750,  5.000) = 4149 
    [ 5.000,  6.250) = 563 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     13.543 ms/op
     p(99.9990) =     16.008 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.932 ms/op
                 listUser·p0.9999: 10.746 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 13.156 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.300 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 10.555 ms/op
                 listUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323486
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 99858 
    [ 2.500,  3.750) = 187367 
    [ 3.750,  5.000) = 29979 
    [ 5.000,  6.250) = 4977 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     13.292 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.755 ± 0.476  ops/ms
ClientPb.existUser                       thrpt       3  12.929 ± 0.514  ops/ms
ClientPb.getUser                         thrpt       3  12.768 ± 1.990  ops/ms
ClientPb.listUser                        thrpt       3  10.769 ± 0.337  ops/ms
ClientPb.createUser                       avgt       3   2.482 ± 0.110   ms/op
ClientPb.existUser                        avgt       3   2.419 ± 0.218   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.099   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.540   ms/op
ClientPb.createUser                     sample  387858   2.473 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.731           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.669           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.242           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  398013   2.410 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.062           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.983           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  391912   2.447 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.684           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.717           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.543           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.073           ms/op
ClientPb.listUser                       sample  323486   2.965 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.912           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
