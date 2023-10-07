# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.403 ops/ms
# Warmup Iteration   2: 5.778 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.204 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (8.072, 8.204, 8.319), stdev = 0.124
  CI (99.9%): [5.937, 10.472] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.732 ops/ms
# Warmup Iteration   2: 7.878 ops/ms
# Warmup Iteration   3: 8.567 ops/ms
Iteration   1: 8.941 ops/ms
Iteration   2: 9.063 ops/ms
Iteration   3: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.005 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (8.941, 9.005, 9.063), stdev = 0.061
  CI (99.9%): [7.890, 10.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.819 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 8.062 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 8.392 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.203 ±(99.9%) 3.524 ops/ms [Average]
  (min, avg, max) = (8.006, 8.203, 8.392), stdev = 0.193
  CI (99.9%): [4.679, 11.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ops/ms
# Warmup Iteration   2: 5.911 ops/ms
# Warmup Iteration   3: 6.418 ops/ms
Iteration   1: 6.489 ops/ms
Iteration   2: 6.414 ops/ms
Iteration   3: 6.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.402 ±(99.9%) 1.704 ops/ms [Average]
  (min, avg, max) = (6.303, 6.402, 6.489), stdev = 0.093
  CI (99.9%): [4.698, 8.106] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.361 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.008 ms/op
Iteration   1: 3.920 ±(99.9%) 0.004 ms/op
Iteration   2: 3.810 ±(99.9%) 0.003 ms/op
Iteration   3: 3.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.858 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.810, 3.858, 3.920), stdev = 0.056
  CI (99.9%): [2.827, 4.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.979 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.660 ±(99.9%) 0.004 ms/op
Iteration   1: 3.549 ±(99.9%) 0.005 ms/op
Iteration   2: 3.481 ±(99.9%) 0.006 ms/op
Iteration   3: 3.615 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.549 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.481, 3.549, 3.615), stdev = 0.067
  CI (99.9%): [2.325, 4.772] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.016 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.838 ±(99.9%) 0.003 ms/op
Iteration   1: 3.897 ±(99.9%) 0.005 ms/op
Iteration   2: 3.791 ±(99.9%) 0.005 ms/op
Iteration   3: 3.790 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.826 ±(99.9%) 1.118 ms/op [Average]
  (min, avg, max) = (3.790, 3.826, 3.897), stdev = 0.061
  CI (99.9%): [2.708, 4.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.222 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.481 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.023 ±(99.9%) 0.009 ms/op
Iteration   1: 4.956 ±(99.9%) 0.023 ms/op
Iteration   2: 4.994 ±(99.9%) 0.034 ms/op
Iteration   3: 4.963 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.971 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (4.956, 4.971, 4.994), stdev = 0.020
  CI (99.9%): [4.606, 5.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.383 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  11.902 ms/op
                 createUser·p0.9999: 23.128 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.832 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  15.517 ms/op
                 createUser·p0.9999: 28.148 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 3.749 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  14.050 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250845
  mean =      3.827 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4980 
    [ 2.500,  5.000) = 230971 
    [ 5.000,  7.500) = 13287 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.721 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     29.097 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.318 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.010 ms/op
Iteration   1: 3.533 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  13.457 ms/op
                 existUser·p0.9999: 17.957 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 3.583 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  12.659 ms/op
                 existUser·p0.9999: 17.135 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   3: 3.664 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  9.760 ms/op
                 existUser·p0.9999: 19.342 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267275
  mean =      3.593 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11999 
    [ 2.500,  5.000) = 245874 
    [ 5.000,  7.500) = 7944 
    [ 7.500, 10.000) = 1009 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.482 ms/op
     p(99.9000) =     12.005 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.835 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.281 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  13.530 ms/op
                 getUser·p0.9999: 18.838 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  14.582 ms/op
                 getUser·p0.9999: 20.349 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  11.989 ms/op
                 getUser·p0.9999: 22.632 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247564
  mean =      3.875 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9829 
    [ 2.500,  5.000) = 218164 
    [ 5.000,  7.500) = 17661 
    [ 7.500, 10.000) = 1266 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.966 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     21.897 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.488 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.591 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.139 ±(99.9%) 0.018 ms/op
Iteration   1: 4.911 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  15.791 ms/op
                 listUser·p0.9999: 18.398 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 5.014 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.479 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 22.057 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   3: 5.121 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.570 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  23.023 ms/op
                 listUser·p0.9999: 35.161 ms/op
                 listUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191336
  mean =      5.014 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 118413 
    [ 5.000, 10.000) = 71247 
    [10.000, 15.000) = 1279 
    [15.000, 20.000) = 272 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =      9.808 ms/op
     p(99.9000) =     18.044 ms/op
     p(99.9900) =     29.323 ms/op
     p(99.9990) =     41.573 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.204 ± 2.268  ops/ms
ClientGrpc.existUser                       thrpt       3   9.005 ± 1.116  ops/ms
ClientGrpc.getUser                         thrpt       3   8.203 ± 3.524  ops/ms
ClientGrpc.listUser                        thrpt       3   6.402 ± 1.704  ops/ms
ClientGrpc.createUser                       avgt       3   3.858 ± 1.030   ms/op
ClientGrpc.existUser                        avgt       3   3.549 ± 1.224   ms/op
ClientGrpc.getUser                          avgt       3   3.826 ± 1.118   ms/op
ClientGrpc.listUser                         avgt       3   4.971 ± 0.365   ms/op
ClientGrpc.createUser                     sample  250845   3.827 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.862           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.104           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.562           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.721           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.262           ms/op
ClientGrpc.existUser                      sample  267275   3.593 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.783           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.482           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.005           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.957           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  247564   3.875 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.855           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.858           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.966           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.517           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.897           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  191336   5.014 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.219           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.479           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.044           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.323           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          41.812           ms/op
