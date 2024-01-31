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
# Warmup Iteration   1: 4.598 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.440 ops/ms
Iteration   1: 12.561 ops/ms
Iteration   2: 12.628 ops/ms
Iteration   3: 12.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.562 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (12.496, 12.562, 12.628), stdev = 0.066
  CI (99.9%): [11.359, 13.764] (assumes normal distribution)


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
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 13.029 ops/ms
# Warmup Iteration   3: 13.167 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 12.991 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.963 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (12.906, 12.963, 12.991), stdev = 0.049
  CI (99.9%): [12.070, 13.856] (assumes normal distribution)


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
# Warmup Iteration   1: 7.751 ops/ms
# Warmup Iteration   2: 12.353 ops/ms
# Warmup Iteration   3: 12.902 ops/ms
Iteration   1: 12.715 ops/ms
Iteration   2: 12.736 ops/ms
Iteration   3: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.705 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (12.665, 12.705, 12.736), stdev = 0.037
  CI (99.9%): [12.038, 13.372] (assumes normal distribution)


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
# Warmup Iteration   1: 6.427 ops/ms
# Warmup Iteration   2: 10.534 ops/ms
# Warmup Iteration   3: 10.619 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.640 ±(99.9%) 1.187 ops/ms [Average]
  (min, avg, max) = (10.565, 10.640, 10.682), stdev = 0.065
  CI (99.9%): [9.453, 11.827] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
Iteration   3: 2.512 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.475, 2.504, 2.526), stdev = 0.026
  CI (99.9%): [2.022, 2.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (2.451, 2.469, 2.484), stdev = 0.017
  CI (99.9%): [2.162, 2.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (2.479, 2.489, 2.498), stdev = 0.010
  CI (99.9%): [2.315, 2.662] (assumes normal distribution)


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
Iteration   2: 3.013 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.960, 2.982, 3.013), stdev = 0.028
  CI (99.9%): [2.478, 3.485] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.654 ms/op
                 createUser·p0.999:  11.242 ms/op
                 createUser·p0.9999: 13.884 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.913 ms/op
                 createUser·p0.9999: 12.206 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 11.649 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384821
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 187749 
    [ 2.500,  3.750) = 193942 
    [ 3.750,  5.000) = 2399 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =     13.443 ms/op
     p(99.9990) =     14.262 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  4.989 ms/op
                 existUser·p0.9999: 13.893 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.755 ms/op
                 existUser·p0.9999: 12.312 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  9.242 ms/op
                 existUser·p0.9999: 12.298 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388201
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 191011 
    [ 2.500,  3.750) = 193767 
    [ 3.750,  5.000) = 2715 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =      6.788 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     14.391 ms/op
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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  6.128 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   4.092 ms/op
                 getUser·p0.999:  8.429 ms/op
                 getUser·p0.9999: 12.636 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  5.800 ms/op
                 getUser·p0.9999: 11.125 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387837
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 193709 
    [ 2.500,  3.750) = 189440 
    [ 3.750,  5.000) = 3511 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.134 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      6.743 ms/op
     p(99.9900) =     13.209 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.009 ms/op
Iteration   1: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.894 ms/op
                 listUser·p0.9999: 13.164 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   2: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.186 ms/op
                 listUser·p0.9999: 12.310 ms/op
                 listUser·p1.00:   14.156 ms/op

Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.463 ms/op
                 listUser·p0.9999: 10.999 ms/op
                 listUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323321
  mean =      2.966 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 99078 
    [ 2.500,  3.750) = 187344 
    [ 3.750,  5.000) = 29862 
    [ 5.000,  6.250) = 5594 
    [ 6.250,  7.500) = 566 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     14.078 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.562 ± 1.203  ops/ms
ClientPb.existUser                       thrpt       3  12.963 ± 0.893  ops/ms
ClientPb.getUser                         thrpt       3  12.705 ± 0.667  ops/ms
ClientPb.listUser                        thrpt       3  10.640 ± 1.187  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.483   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.308   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.173   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.504   ms/op
ClientPb.createUser                     sample  384821   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.768           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.897           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.443           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.269           ms/op
ClientPb.existUser                      sample  388201   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.788           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  387837   2.473 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.134           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.828           ms/op
ClientPb.listUser                       sample  323321   2.966 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.829           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.156           ms/op
