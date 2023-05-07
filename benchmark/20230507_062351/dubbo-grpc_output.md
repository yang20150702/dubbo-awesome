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
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 6.989 ops/ms
# Warmup Iteration   3: 8.488 ops/ms
Iteration   1: 8.894 ops/ms
Iteration   2: 8.725 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.746 ±(99.9%) 2.544 ops/ms [Average]
  (min, avg, max) = (8.617, 8.746, 8.894), stdev = 0.139
  CI (99.9%): [6.202, 11.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.088 ops/ms
# Warmup Iteration   2: 8.566 ops/ms
# Warmup Iteration   3: 8.976 ops/ms
Iteration   1: 9.027 ops/ms
Iteration   2: 8.965 ops/ms
Iteration   3: 8.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.933 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (8.808, 8.933, 9.027), stdev = 0.113
  CI (99.9%): [6.874, 10.992] (assumes normal distribution)


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
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 7.795 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.455 ops/ms
Iteration   2: 8.791 ops/ms
Iteration   3: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.678 ±(99.9%) 3.524 ops/ms [Average]
  (min, avg, max) = (8.455, 8.678, 8.791), stdev = 0.193
  CI (99.9%): [5.153, 12.202] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 6.612 ops/ms
Iteration   1: 6.502 ops/ms
Iteration   2: 6.600 ops/ms
Iteration   3: 6.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.600 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (6.502, 6.600, 6.698), stdev = 0.098
  CI (99.9%): [4.813, 8.386] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.360 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.004 ms/op
Iteration   1: 3.694 ±(99.9%) 0.003 ms/op
Iteration   2: 3.650 ±(99.9%) 0.006 ms/op
Iteration   3: 3.646 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.663 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.646, 3.663, 3.694), stdev = 0.027
  CI (99.9%): [3.169, 4.158] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.930 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.004 ms/op
Iteration   1: 3.500 ±(99.9%) 0.004 ms/op
Iteration   2: 3.408 ±(99.9%) 0.003 ms/op
Iteration   3: 3.617 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.508 ±(99.9%) 1.913 ms/op [Average]
  (min, avg, max) = (3.408, 3.508, 3.617), stdev = 0.105
  CI (99.9%): [1.595, 5.421] (assumes normal distribution)


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.003 ms/op
Iteration   1: 3.779 ±(99.9%) 0.004 ms/op
Iteration   2: 3.755 ±(99.9%) 0.005 ms/op
Iteration   3: 3.820 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.785 ±(99.9%) 0.605 ms/op [Average]
  (min, avg, max) = (3.755, 3.785, 3.820), stdev = 0.033
  CI (99.9%): [3.180, 4.390] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.548 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.150 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.957 ±(99.9%) 0.017 ms/op
Iteration   1: 4.799 ±(99.9%) 0.017 ms/op
Iteration   2: 4.725 ±(99.9%) 0.010 ms/op
Iteration   3: 4.873 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.799 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (4.725, 4.799, 4.873), stdev = 0.074
  CI (99.9%): [3.448, 6.149] (assumes normal distribution)


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
# Warmup Iteration   1: 5.673 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  14.871 ms/op
                 createUser·p0.9999: 16.230 ms/op
                 createUser·p1.00:   16.384 ms/op

Iteration   2: 3.849 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  14.089 ms/op
                 createUser·p0.9999: 18.035 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.449 ms/op
                 createUser·p0.999:  11.447 ms/op
                 createUser·p0.9999: 18.512 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252438
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 7101 
    [ 2.500,  3.750) = 125143 
    [ 3.750,  5.000) = 108963 
    [ 5.000,  6.250) = 8202 
    [ 6.250,  7.500) = 1571 
    [ 7.500,  8.750) = 704 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 101 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     18.840 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.832 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.008 ms/op
Iteration   1: 3.669 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.516 ms/op
                 existUser·p0.999:  11.611 ms/op
                 existUser·p0.9999: 15.558 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 3.477 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 16.541 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 3.678 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 22.849 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266240
  mean =      3.606 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9614 
    [ 2.500,  5.000) = 248127 
    [ 5.000,  7.500) = 7126 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.313 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     19.653 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 5.272 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.009 ms/op
Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  10.904 ms/op
                 getUser·p0.9999: 14.358 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 3.795 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 16.590 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  9.840 ms/op
                 getUser·p0.9999: 21.898 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251530
  mean =      3.814 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6140 
    [ 2.500,  5.000) = 233586 
    [ 5.000,  7.500) = 10603 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     20.432 ms/op
     p(99.9990) =     22.343 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 6.171 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.273 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.015 ms/op
Iteration   1: 4.785 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  16.341 ms/op
                 listUser·p0.9999: 21.767 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 5.066 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 29.375 ms/op
                 listUser·p1.00:   30.671 ms/op

Iteration   3: 5.046 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.716 ms/op
                 listUser·p0.999:  20.685 ms/op
                 listUser·p0.9999: 23.746 ms/op
                 listUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193300
  mean =      4.963 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 333 
    [ 2.500,  5.000) = 128149 
    [ 5.000,  7.500) = 56170 
    [ 7.500, 10.000) = 7187 
    [10.000, 12.500) = 1036 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.513 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     28.227 ms/op
     p(99.9990) =     30.579 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.746 ± 2.544  ops/ms
ClientGrpc.existUser                       thrpt       3   8.933 ± 2.059  ops/ms
ClientGrpc.getUser                         thrpt       3   8.678 ± 3.524  ops/ms
ClientGrpc.listUser                        thrpt       3   6.600 ± 1.787  ops/ms
ClientGrpc.createUser                       avgt       3   3.663 ± 0.494   ms/op
ClientGrpc.existUser                        avgt       3   3.508 ± 1.913   ms/op
ClientGrpc.getUser                          avgt       3   3.785 ± 0.605   ms/op
ClientGrpc.listUser                         avgt       3   4.799 ± 1.350   ms/op
ClientGrpc.createUser                     sample  252438   3.801 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.903           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.157           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.760           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.137           ms/op
ClientGrpc.existUser                      sample  266240   3.606 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.604           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.313           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.665           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.653           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  251530   3.814 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.801           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.584           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.432           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  193300   4.963 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.365           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.568           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.038           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.227           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.671           ms/op
