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
# Warmup Iteration   1: 3.872 ops/ms
# Warmup Iteration   2: 9.079 ops/ms
# Warmup Iteration   3: 9.914 ops/ms
Iteration   1: 10.391 ops/ms
Iteration   2: 10.340 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.349 ±(99.9%) 0.695 ops/ms [Average]
  (min, avg, max) = (10.316, 10.349, 10.391), stdev = 0.038
  CI (99.9%): [9.654, 11.044] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.107 ops/ms
# Warmup Iteration   2: 10.330 ops/ms
# Warmup Iteration   3: 10.852 ops/ms
Iteration   1: 10.965 ops/ms
Iteration   2: 10.870 ops/ms
Iteration   3: 10.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.920 ±(99.9%) 0.868 ops/ms [Average]
  (min, avg, max) = (10.870, 10.920, 10.965), stdev = 0.048
  CI (99.9%): [10.052, 11.789] (assumes normal distribution)


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
# Warmup Iteration   1: 6.442 ops/ms
# Warmup Iteration   2: 9.801 ops/ms
# Warmup Iteration   3: 10.401 ops/ms
Iteration   1: 10.400 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.398 ±(99.9%) 0.294 ops/ms [Average]
  (min, avg, max) = (10.381, 10.398, 10.412), stdev = 0.016
  CI (99.9%): [10.104, 10.691] (assumes normal distribution)


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
# Warmup Iteration   1: 6.263 ops/ms
# Warmup Iteration   2: 7.549 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.962 ±(99.9%) 3.394 ops/ms [Average]
  (min, avg, max) = (7.779, 7.962, 8.151), stdev = 0.186
  CI (99.9%): [4.568, 11.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.128 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.088, 3.128, 3.199), stdev = 0.061
  CI (99.9%): [2.012, 4.245] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 2.887 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 1.484 ms/op [Average]
  (min, avg, max) = (2.887, 2.980, 3.028), stdev = 0.081
  CI (99.9%): [1.496, 4.465] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.004 ms/op
Iteration   2: 3.123 ±(99.9%) 0.003 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.130 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.123, 3.130, 3.134), stdev = 0.006
  CI (99.9%): [3.023, 3.236] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.611 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.022 ms/op
Iteration   1: 4.066 ±(99.9%) 0.019 ms/op
Iteration   2: 4.064 ±(99.9%) 0.014 ms/op
Iteration   3: 4.060 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.064 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (4.060, 4.064, 4.066), stdev = 0.003
  CI (99.9%): [4.003, 4.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.394 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.158 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.838 ms/op
                 createUser·p0.9999: 13.119 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.298 ms/op
                 createUser·p0.9999: 17.849 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.851 ms/op
                 createUser·p0.9999: 22.949 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307403
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13760 
    [ 2.500,  5.000) = 291669 
    [ 5.000,  7.500) = 1334 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      9.532 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.007 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 12.012 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.896 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.838 ms/op
                 existUser·p0.9999: 17.136 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 18.462 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325012
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1698 
    [ 1.250,  2.500) = 30386 
    [ 2.500,  3.750) = 280748 
    [ 3.750,  5.000) = 10529 
    [ 5.000,  6.250) = 655 
    [ 6.250,  7.500) = 432 
    [ 7.500,  8.750) = 246 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     17.678 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  7.681 ms/op
                 getUser·p0.9999: 20.174 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  11.366 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310652
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16104 
    [ 2.500,  5.000) = 292338 
    [ 5.000,  7.500) = 1650 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.443 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     20.444 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 6.404 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.012 ms/op
Iteration   1: 4.117 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  14.765 ms/op
                 listUser·p0.9999: 20.356 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  18.083 ms/op
                 listUser·p0.9999: 25.740 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 20.751 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233410
  mean =      4.114 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2980 
    [ 2.500,  5.000) = 201945 
    [ 5.000,  7.500) = 26341 
    [ 7.500, 10.000) = 1593 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     16.694 ms/op
     p(99.9900) =     23.068 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.349 ± 0.695  ops/ms
ClientGrpc.existUser                       thrpt       3  10.920 ± 0.868  ops/ms
ClientGrpc.getUser                         thrpt       3  10.398 ± 0.294  ops/ms
ClientGrpc.listUser                        thrpt       3   7.962 ± 3.394  ops/ms
ClientGrpc.createUser                       avgt       3   3.128 ± 1.116   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 1.484   ms/op
ClientGrpc.getUser                          avgt       3   3.130 ± 0.107   ms/op
ClientGrpc.listUser                         avgt       3   4.064 ± 0.061   ms/op
ClientGrpc.createUser                     sample  307403   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.817           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.532           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.366           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  325012   2.954 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.700           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.776           ms/op
ClientGrpc.getUser                        sample  310652   3.089 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.761           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.443           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.792           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  233410   4.114 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.848           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.694           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.068           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
