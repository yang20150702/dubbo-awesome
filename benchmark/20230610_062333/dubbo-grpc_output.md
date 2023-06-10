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
# Warmup Iteration   1: 3.034 ops/ms
# Warmup Iteration   2: 6.801 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.585 ops/ms
Iteration   2: 8.642 ops/ms
Iteration   3: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.643 ±(99.9%) 1.085 ops/ms [Average]
  (min, avg, max) = (8.585, 8.643, 8.704), stdev = 0.059
  CI (99.9%): [7.558, 9.728] (assumes normal distribution)


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
# Warmup Iteration   1: 6.116 ops/ms
# Warmup Iteration   2: 8.159 ops/ms
# Warmup Iteration   3: 8.721 ops/ms
Iteration   1: 8.746 ops/ms
Iteration   2: 9.070 ops/ms
Iteration   3: 9.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.986 ±(99.9%) 3.849 ops/ms [Average]
  (min, avg, max) = (8.746, 8.986, 9.142), stdev = 0.211
  CI (99.9%): [5.137, 12.836] (assumes normal distribution)


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
# Warmup Iteration   1: 5.289 ops/ms
# Warmup Iteration   2: 8.153 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.736 ops/ms
Iteration   2: 8.913 ops/ms
Iteration   3: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.747 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (8.593, 8.747, 8.913), stdev = 0.160
  CI (99.9%): [5.821, 11.674] (assumes normal distribution)


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
# Warmup Iteration   1: 4.667 ops/ms
# Warmup Iteration   2: 6.221 ops/ms
# Warmup Iteration   3: 6.731 ops/ms
Iteration   1: 6.976 ops/ms
Iteration   2: 6.714 ops/ms
Iteration   3: 6.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.821 ±(99.9%) 2.505 ops/ms [Average]
  (min, avg, max) = (6.714, 6.821, 6.976), stdev = 0.137
  CI (99.9%): [4.316, 9.326] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.025 ms/op
Iteration   1: 3.691 ±(99.9%) 0.003 ms/op
Iteration   2: 3.693 ±(99.9%) 0.003 ms/op
Iteration   3: 3.647 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.677 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.647, 3.677, 3.693), stdev = 0.026
  CI (99.9%): [3.199, 4.155] (assumes normal distribution)


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
# Warmup Iteration   1: 5.102 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.503 ±(99.9%) 0.003 ms/op
Iteration   2: 3.591 ±(99.9%) 0.002 ms/op
Iteration   3: 3.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.537 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.503, 3.537, 3.591), stdev = 0.047
  CI (99.9%): [2.671, 4.402] (assumes normal distribution)


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.005 ms/op
Iteration   1: 3.703 ±(99.9%) 0.004 ms/op
Iteration   2: 3.700 ±(99.9%) 0.003 ms/op
Iteration   3: 3.688 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.697 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.688, 3.697, 3.703), stdev = 0.008
  CI (99.9%): [3.547, 3.847] (assumes normal distribution)


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
# Warmup Iteration   1: 6.840 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.017 ms/op
Iteration   1: 4.738 ±(99.9%) 0.007 ms/op
Iteration   2: 4.777 ±(99.9%) 0.020 ms/op
Iteration   3: 4.754 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.756 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (4.738, 4.756, 4.777), stdev = 0.020
  CI (99.9%): [4.396, 5.117] (assumes normal distribution)


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.008 ms/op
Iteration   1: 3.744 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 17.808 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.701 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  11.749 ms/op
                 createUser·p0.9999: 20.492 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   3: 3.655 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.858 ms/op
                 createUser·p0.999:  12.493 ms/op
                 createUser·p0.9999: 34.685 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259353
  mean =      3.700 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4233 
    [ 2.500,  5.000) = 246953 
    [ 5.000,  7.500) = 7211 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     11.714 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     34.892 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.008 ms/op
Iteration   1: 3.551 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 20.905 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 3.545 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  11.984 ms/op
                 existUser·p0.9999: 16.972 ms/op
                 existUser·p1.00:   17.662 ms/op

Iteration   3: 3.541 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.537 ms/op
                 existUser·p0.999:  8.777 ms/op
                 existUser·p0.9999: 19.201 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270770
  mean =      3.546 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6311 
    [ 2.500,  5.000) = 257648 
    [ 5.000,  7.500) = 5842 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     10.539 ms/op
     p(99.9900) =     20.321 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.008 ms/op
Iteration   1: 3.716 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  7.781 ms/op
                 getUser·p0.9999: 14.158 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 3.759 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  10.060 ms/op
                 getUser·p0.9999: 16.728 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.705 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  9.531 ms/op
                 getUser·p0.9999: 17.805 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257500
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 7703 
    [ 2.500,  3.750) = 141471 
    [ 3.750,  5.000) = 97639 
    [ 5.000,  6.250) = 8087 
    [ 6.250,  7.500) = 1754 
    [ 7.500,  8.750) = 423 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 55 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =      9.101 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     19.721 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 6.798 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.256 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.747 ±(99.9%) 0.015 ms/op
Iteration   1: 4.695 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  16.543 ms/op
                 listUser·p0.9999: 23.543 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.780 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.234 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 26.497 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   3: 4.826 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  19.999 ms/op
                 listUser·p0.9999: 31.854 ms/op
                 listUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201396
  mean =      4.766 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 641 
    [ 2.500,  5.000) = 149917 
    [ 5.000,  7.500) = 44278 
    [ 7.500, 10.000) = 5553 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.086 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     17.747 ms/op
     p(99.9900) =     30.054 ms/op
     p(99.9990) =     32.373 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.643 ± 1.085  ops/ms
ClientGrpc.existUser                       thrpt       3   8.986 ± 3.849  ops/ms
ClientGrpc.getUser                         thrpt       3   8.747 ± 2.927  ops/ms
ClientGrpc.listUser                        thrpt       3   6.821 ± 2.505  ops/ms
ClientGrpc.createUser                       avgt       3   3.677 ± 0.478   ms/op
ClientGrpc.existUser                        avgt       3   3.537 ± 0.866   ms/op
ClientGrpc.getUser                          avgt       3   3.697 ± 0.150   ms/op
ClientGrpc.listUser                         avgt       3   4.756 ± 0.361   ms/op
ClientGrpc.createUser                     sample  259353   3.700 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.739           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.714           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.275           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.996           ms/op
ClientGrpc.existUser                      sample  270770   3.546 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.850           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.923           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.321           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  257500   3.727 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.218           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.101           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.629           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  201396   4.766 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.864           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.747           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.054           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.473           ms/op
