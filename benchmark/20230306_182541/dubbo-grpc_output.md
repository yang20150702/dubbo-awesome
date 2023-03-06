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
# Warmup Iteration   1: 4.683 ops/ms
# Warmup Iteration   2: 9.930 ops/ms
# Warmup Iteration   3: 10.531 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.208 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.469 ±(99.9%) 4.165 ops/ms [Average]
  (min, avg, max) = (10.208, 10.469, 10.634), stdev = 0.228
  CI (99.9%): [6.304, 14.634] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 10.618 ops/ms
# Warmup Iteration   3: 11.414 ops/ms
Iteration   1: 10.604 ops/ms
Iteration   2: 11.052 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.777 ±(99.9%) 4.389 ops/ms [Average]
  (min, avg, max) = (10.604, 10.777, 11.052), stdev = 0.241
  CI (99.9%): [6.388, 15.166] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 10.555 ops/ms
Iteration   1: 10.878 ops/ms
Iteration   2: 10.419 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.587 ±(99.9%) 4.618 ops/ms [Average]
  (min, avg, max) = (10.419, 10.587, 10.878), stdev = 0.253
  CI (99.9%): [5.969, 15.204] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 7.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.826 ±(99.9%) 2.895 ops/ms [Average]
  (min, avg, max) = (7.668, 7.826, 7.985), stdev = 0.159
  CI (99.9%): [4.931, 10.721] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.002 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.023, 3.053, 3.107), stdev = 0.047
  CI (99.9%): [2.196, 3.910] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.562 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.845 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.001 ms/op
Iteration   2: 2.943 ±(99.9%) 0.002 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.934 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (2.892, 2.934, 2.966), stdev = 0.038
  CI (99.9%): [2.239, 3.628] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.002 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.036 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.009, 3.036, 3.065), stdev = 0.028
  CI (99.9%): [2.529, 3.544] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.016 ms/op
Iteration   1: 4.237 ±(99.9%) 0.034 ms/op
Iteration   2: 4.080 ±(99.9%) 0.045 ms/op
Iteration   3: 4.123 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.147 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (4.080, 4.147, 4.237), stdev = 0.081
  CI (99.9%): [2.669, 5.625] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.016 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.289 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.823 ms/op
                 createUser·p0.9999: 24.032 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  12.905 ms/op
                 createUser·p0.9999: 16.007 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.281 ms/op
                 createUser·p0.9999: 24.805 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307896
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27765 
    [ 2.500,  5.000) = 278591 
    [ 5.000,  7.500) = 1106 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.289 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.790 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.015 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.856 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.007 ms/op
Iteration   1: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  5.630 ms/op
                 existUser·p0.9999: 11.503 ms/op
                 existUser·p1.00:   11.911 ms/op

Iteration   2: 2.906 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.409 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   3: 2.887 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330763
  mean =      2.903 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53650 
    [ 2.500,  5.000) = 276259 
    [ 5.000,  7.500) = 509 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     22.313 ms/op
     p(99.9990) =     23.409 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.224 ms/op
                 getUser·p0.999:  6.383 ms/op
                 getUser·p0.9999: 17.549 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.379 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  8.390 ms/op
                 getUser·p0.9999: 12.875 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.967 ms/op
                 getUser·p0.9999: 17.814 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311808
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1183 
    [ 1.250,  2.500) = 22712 
    [ 2.500,  3.750) = 263078 
    [ 3.750,  5.000) = 23897 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.587 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.577 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.316 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.011 ms/op
Iteration   1: 4.220 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  12.012 ms/op
                 listUser·p0.9999: 17.276 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 4.208 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.475 ms/op
                 listUser·p0.999:  14.665 ms/op
                 listUser·p0.9999: 25.192 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.098 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  21.121 ms/op
                 listUser·p0.9999: 25.407 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230043
  mean =      4.175 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4546 
    [ 2.500,  5.000) = 184779 
    [ 5.000,  7.500) = 38688 
    [ 7.500, 10.000) = 1555 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.875 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.296 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.469 ± 4.165  ops/ms
ClientGrpc.existUser                       thrpt       3  10.777 ± 4.389  ops/ms
ClientGrpc.getUser                         thrpt       3  10.587 ± 4.618  ops/ms
ClientGrpc.listUser                        thrpt       3   7.826 ± 2.895  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.857   ms/op
ClientGrpc.existUser                        avgt       3   2.934 ± 0.695   ms/op
ClientGrpc.getUser                          avgt       3   3.036 ± 0.508   ms/op
ClientGrpc.listUser                         avgt       3   4.147 ± 1.478   ms/op
ClientGrpc.createUser                     sample  307896   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.289           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.790           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.444           ms/op
ClientGrpc.existUser                      sample  330763   2.903 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.594           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.313           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.495           ms/op
ClientGrpc.getUser                        sample  311808   3.079 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.379           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.587           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.367           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  230043   4.175 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.017           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.875           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
