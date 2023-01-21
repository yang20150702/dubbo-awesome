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
# Warmup Iteration   1: 4.014 ops/ms
# Warmup Iteration   2: 9.165 ops/ms
# Warmup Iteration   3: 9.932 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.298 ±(99.9%) 3.580 ops/ms [Average]
  (min, avg, max) = (10.088, 10.298, 10.477), stdev = 0.196
  CI (99.9%): [6.718, 13.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.575 ops/ms
# Warmup Iteration   2: 10.424 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.444 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.524 ±(99.9%) 1.433 ops/ms [Average]
  (min, avg, max) = (10.444, 10.524, 10.601), stdev = 0.079
  CI (99.9%): [9.091, 11.956] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.850 ops/ms
# Warmup Iteration   2: 9.831 ops/ms
# Warmup Iteration   3: 10.435 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.209 ops/ms
Iteration   3: 10.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.241 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (10.184, 10.241, 10.329), stdev = 0.078
  CI (99.9%): [8.826, 11.655] (assumes normal distribution)


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
# Warmup Iteration   1: 5.460 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 8.123 ops/ms
Iteration   2: 7.951 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.054 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (7.951, 8.054, 8.123), stdev = 0.091
  CI (99.9%): [6.398, 9.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.141 ±(99.9%) 0.001 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.140 ±(99.9%) 0.649 ms/op [Average]
  (min, avg, max) = (3.103, 3.140, 3.174), stdev = 0.036
  CI (99.9%): [2.490, 3.789] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.021 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (2.973, 3.021, 3.070), stdev = 0.048
  CI (99.9%): [2.141, 3.900] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.002 ms/op
Iteration   1: 3.186 ±(99.9%) 0.002 ms/op
Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.181 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (3.175, 3.181, 3.186), stdev = 0.005
  CI (99.9%): [3.083, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 5.779 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.010 ms/op
Iteration   1: 4.023 ±(99.9%) 0.062 ms/op
Iteration   2: 3.892 ±(99.9%) 0.003 ms/op
Iteration   3: 4.019 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.978 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.892, 3.978, 4.023), stdev = 0.075
  CI (99.9%): [2.615, 5.340] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.191 ms/op
                 createUser·p0.9999: 13.005 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  10.455 ms/op
                 createUser·p0.9999: 27.357 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.251 ms/op
                 createUser·p0.999:  10.011 ms/op
                 createUser·p0.9999: 17.223 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311837
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27321 
    [ 2.500,  5.000) = 282950 
    [ 5.000,  7.500) = 1194 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.555 ms/op
     p(99.9900) =     25.535 ms/op
     p(99.9990) =     27.972 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 3.595 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.605 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  5.377 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  10.162 ms/op
                 existUser·p0.9999: 15.137 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320735
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43885 
    [ 2.500,  5.000) = 275927 
    [ 5.000,  7.500) = 612 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.187 ms/op
     p(99.9900) =     19.254 ms/op
     p(99.9990) =     20.604 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.443 ms/op
                 getUser·p0.9999: 23.193 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.466 ms/op
                 getUser·p0.9999: 18.501 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304126
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19944 
    [ 2.500,  5.000) = 283113 
    [ 5.000,  7.500) = 645 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.379 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     23.425 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.010 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.830 ms/op
                 listUser·p0.999:  13.449 ms/op
                 listUser·p0.9999: 16.423 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   2: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 20.469 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 19.630 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241916
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2373 
    [ 2.500,  5.000) = 214815 
    [ 5.000,  7.500) = 23531 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.337 ms/op
     p(99.9900) =     19.550 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.298 ± 3.580  ops/ms
ClientGrpc.existUser                       thrpt       3  10.524 ± 1.433  ops/ms
ClientGrpc.getUser                         thrpt       3  10.241 ± 1.415  ops/ms
ClientGrpc.listUser                        thrpt       3   8.054 ± 1.656  ops/ms
ClientGrpc.createUser                       avgt       3   3.140 ± 0.649   ms/op
ClientGrpc.existUser                        avgt       3   3.021 ± 0.880   ms/op
ClientGrpc.getUser                          avgt       3   3.181 ± 0.097   ms/op
ClientGrpc.listUser                         avgt       3   3.978 ± 1.362   ms/op
ClientGrpc.createUser                     sample  311837   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.555           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.115           ms/op
ClientGrpc.existUser                      sample  320735   2.992 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.679           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.187           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.254           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  304126   3.156 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.002           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.379           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.544           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.560           ms/op
ClientGrpc.listUser                       sample  241916   3.967 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.997           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.337           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.550           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.398           ms/op
