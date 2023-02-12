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
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 7.123 ops/ms
# Warmup Iteration   3: 8.066 ops/ms
Iteration   1: 8.033 ops/ms
Iteration   2: 8.474 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.378 ±(99.9%) 5.626 ops/ms [Average]
  (min, avg, max) = (8.033, 8.378, 8.628), stdev = 0.308
  CI (99.9%): [2.752, 14.004] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 8.493 ops/ms
Iteration   1: 8.983 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 8.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.859 ±(99.9%) 3.158 ops/ms [Average]
  (min, avg, max) = (8.661, 8.859, 8.983), stdev = 0.173
  CI (99.9%): [5.701, 12.017] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.507 ops/ms
# Warmup Iteration   2: 8.082 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.360 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.422 ±(99.9%) 1.790 ops/ms [Average]
  (min, avg, max) = (8.360, 8.422, 8.536), stdev = 0.098
  CI (99.9%): [6.632, 10.213] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ops/ms
# Warmup Iteration   2: 6.476 ops/ms
# Warmup Iteration   3: 6.514 ops/ms
Iteration   1: 6.581 ops/ms
Iteration   2: 6.836 ops/ms
Iteration   3: 6.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.732 ±(99.9%) 2.441 ops/ms [Average]
  (min, avg, max) = (6.581, 6.732, 6.836), stdev = 0.134
  CI (99.9%): [4.291, 9.173] (assumes normal distribution)


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
# Warmup Iteration   1: 5.295 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.021 ms/op
Iteration   1: 3.928 ±(99.9%) 0.002 ms/op
Iteration   2: 3.909 ±(99.9%) 0.003 ms/op
Iteration   3: 3.819 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.885 ±(99.9%) 1.056 ms/op [Average]
  (min, avg, max) = (3.819, 3.885, 3.928), stdev = 0.058
  CI (99.9%): [2.830, 4.941] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.230 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.003 ms/op
Iteration   1: 3.759 ±(99.9%) 0.004 ms/op
Iteration   2: 3.737 ±(99.9%) 0.002 ms/op
Iteration   3: 3.824 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.773 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.737, 3.773, 3.824), stdev = 0.045
  CI (99.9%): [2.953, 4.594] (assumes normal distribution)


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.003 ms/op
Iteration   1: 3.752 ±(99.9%) 0.003 ms/op
Iteration   2: 3.739 ±(99.9%) 0.011 ms/op
Iteration   3: 3.736 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.742 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.736, 3.742, 3.752), stdev = 0.008
  CI (99.9%): [3.590, 3.894] (assumes normal distribution)


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
# Warmup Iteration   1: 6.272 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.015 ms/op
Iteration   1: 4.768 ±(99.9%) 0.017 ms/op
Iteration   2: 4.689 ±(99.9%) 0.020 ms/op
Iteration   3: 4.678 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.712 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (4.678, 4.712, 4.768), stdev = 0.049
  CI (99.9%): [3.815, 5.608] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.010 ms/op
Iteration   1: 3.910 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  9.402 ms/op
                 createUser·p0.9999: 16.107 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   2: 3.802 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 20.073 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   3: 3.792 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  12.679 ms/op
                 createUser·p0.9999: 24.201 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250422
  mean =      3.834 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7145 
    [ 2.500,  5.000) = 230196 
    [ 5.000,  7.500) = 12407 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     23.690 ms/op
     p(99.9990) =     24.396 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.009 ms/op
Iteration   1: 3.639 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 18.874 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.666 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  11.197 ms/op
                 existUser·p0.9999: 19.825 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 3.554 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  12.190 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265286
  mean =      3.619 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14256 
    [ 2.500,  5.000) = 242744 
    [ 5.000,  7.500) = 7529 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     11.403 ms/op
     p(99.9900) =     19.578 ms/op
     p(99.9990) =     20.077 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.983 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.009 ms/op
Iteration   1: 3.714 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  10.448 ms/op
                 getUser·p0.9999: 13.870 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.866 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  10.846 ms/op
                 getUser·p0.9999: 19.882 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 3.781 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  10.151 ms/op
                 getUser·p0.9999: 29.461 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253516
  mean =      3.786 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9364 
    [ 2.500,  5.000) = 233062 
    [ 5.000,  7.500) = 10133 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     10.477 ms/op
     p(99.9900) =     27.582 ms/op
     p(99.9990) =     29.769 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 6.589 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.027 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.627 ±(99.9%) 0.013 ms/op
Iteration   1: 4.748 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.476 ms/op
                 listUser·p0.9999: 20.915 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 4.728 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  17.042 ms/op
                 listUser·p0.9999: 25.468 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.744 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 21.300 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202467
  mean =      4.740 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 565 
    [ 2.500,  5.000) = 150179 
    [ 5.000,  7.500) = 47261 
    [ 7.500, 10.000) = 3842 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.964 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     24.552 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.378 ± 5.626  ops/ms
ClientGrpc.existUser                       thrpt       3   8.859 ± 3.158  ops/ms
ClientGrpc.getUser                         thrpt       3   8.422 ± 1.790  ops/ms
ClientGrpc.listUser                        thrpt       3   6.732 ± 2.441  ops/ms
ClientGrpc.createUser                       avgt       3   3.885 ± 1.056   ms/op
ClientGrpc.existUser                        avgt       3   3.773 ± 0.820   ms/op
ClientGrpc.getUser                          avgt       3   3.742 ± 0.152   ms/op
ClientGrpc.listUser                         avgt       3   4.712 ± 0.897   ms/op
ClientGrpc.createUser                     sample  250422   3.834 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.092           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.690           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  265286   3.619 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.403           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.578           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  253516   3.786 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.676           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.948           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.477           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.582           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.852           ms/op
ClientGrpc.listUser                       sample  202467   4.740 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.323           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.552           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
