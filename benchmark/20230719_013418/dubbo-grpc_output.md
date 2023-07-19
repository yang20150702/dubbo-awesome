# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.163 ops/ms
# Warmup Iteration   2: 6.545 ops/ms
# Warmup Iteration   3: 7.887 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.314 ±(99.9%) 2.976 ops/ms [Average]
  (min, avg, max) = (8.171, 8.314, 8.491), stdev = 0.163
  CI (99.9%): [5.338, 11.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.794 ops/ms
# Warmup Iteration   2: 8.384 ops/ms
# Warmup Iteration   3: 8.856 ops/ms
Iteration   1: 8.982 ops/ms
Iteration   2: 8.687 ops/ms
Iteration   3: 9.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.904 ±(99.9%) 3.468 ops/ms [Average]
  (min, avg, max) = (8.687, 8.904, 9.043), stdev = 0.190
  CI (99.9%): [5.436, 12.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 8.154 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.274 ops/ms
Iteration   3: 8.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.403 ±(99.9%) 2.694 ops/ms [Average]
  (min, avg, max) = (8.274, 8.403, 8.564), stdev = 0.148
  CI (99.9%): [5.709, 11.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ops/ms
# Warmup Iteration   2: 5.739 ops/ms
# Warmup Iteration   3: 6.355 ops/ms
Iteration   1: 6.643 ops/ms
Iteration   2: 6.695 ops/ms
Iteration   3: 6.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.645 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (6.597, 6.645, 6.695), stdev = 0.049
  CI (99.9%): [5.748, 7.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.015 ms/op
Iteration   1: 3.857 ±(99.9%) 0.003 ms/op
Iteration   2: 3.721 ±(99.9%) 0.004 ms/op
Iteration   3: 3.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.821 ±(99.9%) 1.616 ms/op [Average]
  (min, avg, max) = (3.721, 3.821, 3.886), stdev = 0.089
  CI (99.9%): [2.205, 5.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.058 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.004 ms/op
Iteration   1: 3.653 ±(99.9%) 0.004 ms/op
Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
Iteration   3: 3.618 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.622 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.597, 3.622, 3.653), stdev = 0.028
  CI (99.9%): [3.104, 4.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.344 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.005 ms/op
Iteration   1: 3.767 ±(99.9%) 0.003 ms/op
Iteration   2: 3.678 ±(99.9%) 0.004 ms/op
Iteration   3: 3.683 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.709 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.678, 3.709, 3.767), stdev = 0.050
  CI (99.9%): [2.798, 4.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.167 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.014 ms/op
Iteration   1: 4.781 ±(99.9%) 0.015 ms/op
Iteration   2: 4.834 ±(99.9%) 0.018 ms/op
Iteration   3: 4.729 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.781 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (4.729, 4.781, 4.834), stdev = 0.053
  CI (99.9%): [3.818, 5.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.010 ms/op
Iteration   1: 3.807 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  14.779 ms/op
                 createUser·p0.9999: 19.438 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  12.780 ms/op
                 createUser·p0.9999: 22.653 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   3: 3.890 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  11.985 ms/op
                 createUser·p0.9999: 28.115 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251921
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9127 
    [ 2.500,  5.000) = 228872 
    [ 5.000,  7.500) = 12157 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     26.228 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.161 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.644 ±(99.9%) 0.009 ms/op
Iteration   1: 3.587 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  9.191 ms/op
                 existUser·p0.9999: 14.733 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.680 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  11.093 ms/op
                 existUser·p0.9999: 16.941 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   3: 3.492 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  10.385 ms/op
                 existUser·p0.9999: 17.395 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267663
  mean =      3.585 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 278 
    [ 1.250,  2.500) = 11991 
    [ 2.500,  3.750) = 177068 
    [ 3.750,  5.000) = 69267 
    [ 5.000,  6.250) = 6348 
    [ 6.250,  7.500) = 1525 
    [ 7.500,  8.750) = 630 
    [ 8.750, 10.000) = 199 
    [10.000, 11.250) = 192 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     10.535 ms/op
     p(99.9900) =     17.014 ms/op
     p(99.9990) =     19.155 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.235 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.010 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  10.797 ms/op
                 getUser·p0.9999: 18.913 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.743 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  12.978 ms/op
                 getUser·p0.9999: 21.442 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.714 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  9.092 ms/op
                 getUser·p0.9999: 23.927 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255641
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7498 
    [ 2.500,  5.000) = 237692 
    [ 5.000,  7.500) = 9243 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     10.803 ms/op
     p(99.9900) =     21.885 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.936 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.297 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.059 ±(99.9%) 0.017 ms/op
Iteration   1: 4.782 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  15.354 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 4.847 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  17.107 ms/op
                 listUser·p0.9999: 19.805 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.876 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   10.258 ms/op
                 listUser·p0.999:  20.238 ms/op
                 listUser·p0.9999: 24.516 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198527
  mean =      4.835 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 562 
    [ 2.500,  5.000) = 141560 
    [ 5.000,  7.500) = 49628 
    [ 7.500, 10.000) = 5509 
    [10.000, 12.500) = 727 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     17.546 ms/op
     p(99.9900) =     22.844 ms/op
     p(99.9990) =     25.069 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.314 ± 2.976  ops/ms
ClientGrpc.existUser                       thrpt       3   8.904 ± 3.468  ops/ms
ClientGrpc.getUser                         thrpt       3   8.403 ± 2.694  ops/ms
ClientGrpc.listUser                        thrpt       3   6.645 ± 0.897  ops/ms
ClientGrpc.createUser                       avgt       3   3.821 ± 1.616   ms/op
ClientGrpc.existUser                        avgt       3   3.622 ± 0.519   ms/op
ClientGrpc.getUser                          avgt       3   3.709 ± 0.911   ms/op
ClientGrpc.listUser                         avgt       3   4.781 ± 0.963   ms/op
ClientGrpc.createUser                     sample  251921   3.811 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.761           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.840           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.451           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.228           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.148           ms/op
ClientGrpc.existUser                      sample  267663   3.585 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.818           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.535           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.014           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  255641   3.753 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.914           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.803           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.885           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  198527   4.835 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.083           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.093           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.546           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.844           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.166           ms/op
