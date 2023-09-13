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
# Warmup Iteration   1: 4.277 ops/ms
# Warmup Iteration   2: 8.837 ops/ms
# Warmup Iteration   3: 10.184 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.383 ops/ms
Iteration   3: 10.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.423 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (10.338, 10.423, 10.548), stdev = 0.110
  CI (99.9%): [8.410, 12.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.356 ops/ms
# Warmup Iteration   2: 10.296 ops/ms
# Warmup Iteration   3: 10.916 ops/ms
Iteration   1: 11.266 ops/ms
Iteration   2: 11.204 ops/ms
Iteration   3: 11.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.171 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (11.041, 11.171, 11.266), stdev = 0.117
  CI (99.9%): [9.044, 13.297] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.846 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.590 ops/ms
Iteration   3: 10.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.467 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (10.359, 10.467, 10.590), stdev = 0.116
  CI (99.9%): [8.345, 12.589] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.051 ops/ms
# Warmup Iteration   2: 7.200 ops/ms
# Warmup Iteration   3: 7.749 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.846 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.807 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (7.754, 7.807, 7.846), stdev = 0.048
  CI (99.9%): [6.934, 8.681] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.028, 3.047, 3.082), stdev = 0.030
  CI (99.9%): [2.501, 3.593] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.015 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 2.951 ±(99.9%) 0.003 ms/op
Iteration   3: 2.942 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.956 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.942, 2.956, 2.976), stdev = 0.018
  CI (99.9%): [2.636, 3.277] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.004 ms/op
Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.079 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.050, 3.079, 3.103), stdev = 0.027
  CI (99.9%): [2.585, 3.574] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.231 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.026 ms/op
Iteration   1: 4.088 ±(99.9%) 0.024 ms/op
Iteration   2: 4.056 ±(99.9%) 0.015 ms/op
Iteration   3: 4.014 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (4.014, 4.053, 4.088), stdev = 0.037
  CI (99.9%): [3.374, 4.731] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.249 ms/op
                 createUser·p0.9999: 20.061 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.310 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.001 ms/op
                 createUser·p0.9999: 23.877 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.348 ms/op
                 createUser·p0.9999: 22.954 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313623
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18327 
    [ 2.500,  5.000) = 293411 
    [ 5.000,  7.500) = 1393 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.389 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.825 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.216 ms/op
                 existUser·p0.9999: 16.613 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  11.331 ms/op
                 existUser·p0.9999: 16.107 ms/op
                 existUser·p1.00:   16.613 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.315 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 17.172 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328882
  mean =      2.917 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3548 
    [ 1.250,  2.500) = 32677 
    [ 2.500,  3.750) = 282017 
    [ 3.750,  5.000) = 8799 
    [ 5.000,  6.250) = 841 
    [ 6.250,  7.500) = 431 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 77 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     16.582 ms/op
     p(99.9990) =     17.446 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  8.855 ms/op
                 getUser·p0.9999: 22.763 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  10.263 ms/op
                 getUser·p0.9999: 14.641 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.408 ms/op
                 getUser·p0.999:  8.775 ms/op
                 getUser·p0.9999: 17.883 ms/op
                 getUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307461
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13383 
    [ 2.500,  5.000) = 291597 
    [ 5.000,  7.500) = 1923 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =      9.586 ms/op
     p(99.9900) =     21.545 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 5.812 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.012 ms/op
Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.938 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 20.239 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.534 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.531 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.227 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 21.139 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237016
  mean =      4.051 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2424 
    [ 2.500,  5.000) = 208037 
    [ 5.000,  7.500) = 24683 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     19.900 ms/op
     p(99.9990) =     21.828 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.423 ± 2.013  ops/ms
ClientGrpc.existUser                       thrpt       3  11.171 ± 2.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.467 ± 2.122  ops/ms
ClientGrpc.listUser                        thrpt       3   7.807 ± 0.874  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.546   ms/op
ClientGrpc.existUser                        avgt       3   2.956 ± 0.321   ms/op
ClientGrpc.getUser                          avgt       3   3.079 ± 0.494   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.679   ms/op
ClientGrpc.createUser                     sample  313623   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.310           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.389           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.970           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.330           ms/op
ClientGrpc.existUser                      sample  328882   2.917 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.684           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.582           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.564           ms/op
ClientGrpc.getUser                        sample  307461   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.497           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.809           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.545           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.069           ms/op
ClientGrpc.listUser                       sample  237016   4.051 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.531           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.900           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
