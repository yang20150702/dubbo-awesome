# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.073 ops/ms
# Warmup Iteration   2: 6.890 ops/ms
# Warmup Iteration   3: 8.551 ops/ms
Iteration   1: 8.768 ops/ms
Iteration   2: 9.006 ops/ms
Iteration   3: 8.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.924 ±(99.9%) 2.471 ops/ms [Average]
  (min, avg, max) = (8.768, 8.924, 9.006), stdev = 0.135
  CI (99.9%): [6.453, 11.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.089 ops/ms
# Warmup Iteration   2: 8.831 ops/ms
# Warmup Iteration   3: 9.363 ops/ms
Iteration   1: 9.557 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.495 ±(99.9%) 3.318 ops/ms [Average]
  (min, avg, max) = (9.290, 9.495, 9.638), stdev = 0.182
  CI (99.9%): [6.178, 12.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.442 ops/ms
# Warmup Iteration   2: 8.354 ops/ms
# Warmup Iteration   3: 8.714 ops/ms
Iteration   1: 8.529 ops/ms
Iteration   2: 8.705 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.489 ±(99.9%) 4.367 ops/ms [Average]
  (min, avg, max) = (8.232, 8.489, 8.705), stdev = 0.239
  CI (99.9%): [4.122, 12.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ops/ms
# Warmup Iteration   2: 6.366 ops/ms
# Warmup Iteration   3: 6.830 ops/ms
Iteration   1: 7.041 ops/ms
Iteration   2: 6.918 ops/ms
Iteration   3: 6.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.978 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (6.918, 6.978, 7.041), stdev = 0.061
  CI (99.9%): [5.856, 8.100] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.181 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.005 ms/op
Iteration   1: 3.608 ±(99.9%) 0.004 ms/op
Iteration   2: 3.539 ±(99.9%) 0.002 ms/op
Iteration   3: 3.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.560 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.533, 3.560, 3.608), stdev = 0.041
  CI (99.9%): [2.805, 4.315] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.117 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.003 ms/op
Iteration   1: 3.479 ±(99.9%) 0.003 ms/op
Iteration   2: 3.454 ±(99.9%) 0.002 ms/op
Iteration   3: 3.371 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.435 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.371, 3.435, 3.479), stdev = 0.057
  CI (99.9%): [2.402, 4.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.522 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.003 ms/op
Iteration   1: 3.556 ±(99.9%) 0.005 ms/op
Iteration   2: 3.601 ±(99.9%) 0.005 ms/op
Iteration   3: 3.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.574 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.556, 3.574, 3.601), stdev = 0.024
  CI (99.9%): [3.139, 4.009] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.480 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.915 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.017 ms/op
Iteration   1: 4.654 ±(99.9%) 0.013 ms/op
Iteration   2: 4.565 ±(99.9%) 0.016 ms/op
Iteration   3: 4.580 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.600 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (4.565, 4.600, 4.654), stdev = 0.047
  CI (99.9%): [3.734, 5.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.499 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.009 ms/op
Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 16.752 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 3.535 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  9.477 ms/op
                 createUser·p0.9999: 17.234 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 3.559 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  13.912 ms/op
                 createUser·p0.9999: 19.367 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265635
  mean =      3.616 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 3615 
    [ 2.500,  3.750) = 177625 
    [ 3.750,  5.000) = 78934 
    [ 5.000,  6.250) = 3636 
    [ 6.250,  7.500) = 674 
    [ 7.500,  8.750) = 361 
    [ 8.750, 10.000) = 173 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 90 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 94 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.136 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     19.749 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.777 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.007 ms/op
Iteration   1: 3.406 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 14.592 ms/op
                 existUser·p1.00:   15.385 ms/op

Iteration   2: 3.377 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  7.160 ms/op
                 existUser·p0.9999: 15.484 ms/op
                 existUser·p1.00:   15.925 ms/op

Iteration   3: 3.428 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   4.768 ms/op
                 existUser·p0.999:  7.288 ms/op
                 existUser·p0.9999: 18.929 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282076
  mean =      3.403 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 6871 
    [ 2.500,  3.750) = 224144 
    [ 3.750,  5.000) = 48482 
    [ 5.000,  6.250) = 1874 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      7.414 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     19.142 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.248 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.009 ms/op
Iteration   1: 3.648 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  11.407 ms/op
                 getUser·p0.9999: 16.207 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   2: 3.609 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.247 ms/op
                 getUser·p0.9999: 15.422 ms/op
                 getUser·p1.00:   15.581 ms/op

Iteration   3: 3.582 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.563 ms/op
                 getUser·p0.999:  12.906 ms/op
                 getUser·p0.9999: 19.565 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265705
  mean =      3.613 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6923 
    [ 2.500,  5.000) = 252236 
    [ 5.000,  7.500) = 5619 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     20.066 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.766 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.276 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.788 ±(99.9%) 0.014 ms/op
Iteration   1: 4.743 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.080 ms/op
                 listUser·p0.9999: 19.505 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.719 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.783 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  16.118 ms/op
                 listUser·p0.9999: 26.138 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   3: 4.725 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  20.065 ms/op
                 listUser·p0.9999: 23.344 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202973
  mean =      4.729 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 471 
    [ 2.500,  5.000) = 154127 
    [ 5.000,  7.500) = 42581 
    [ 7.500, 10.000) = 4838 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.873 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     17.237 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.408 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.924 ± 2.471  ops/ms
ClientGrpc.existUser                       thrpt       3   9.495 ± 3.318  ops/ms
ClientGrpc.getUser                         thrpt       3   8.489 ± 4.367  ops/ms
ClientGrpc.listUser                        thrpt       3   6.978 ± 1.122  ops/ms
ClientGrpc.createUser                       avgt       3   3.560 ± 0.755   ms/op
ClientGrpc.existUser                        avgt       3   3.435 ± 1.033   ms/op
ClientGrpc.getUser                          avgt       3   3.574 ± 0.435   ms/op
ClientGrpc.listUser                         avgt       3   4.600 ± 0.866   ms/op
ClientGrpc.createUser                     sample  265635   3.616 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.815           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.136           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.400           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  282076   3.403 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.971           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.414           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.317           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  265705   3.613 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.236           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  202973   4.729 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.506           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.237           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.478           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
