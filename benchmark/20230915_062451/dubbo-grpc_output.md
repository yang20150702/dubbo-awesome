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
# Warmup Iteration   1: 4.175 ops/ms
# Warmup Iteration   2: 8.374 ops/ms
# Warmup Iteration   3: 9.721 ops/ms
Iteration   1: 10.084 ops/ms
Iteration   2: 10.032 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.138 ±(99.9%) 2.566 ops/ms [Average]
  (min, avg, max) = (10.032, 10.138, 10.297), stdev = 0.141
  CI (99.9%): [7.572, 12.703] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.666 ops/ms
# Warmup Iteration   2: 10.034 ops/ms
# Warmup Iteration   3: 10.344 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.556 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.556 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (10.541, 10.556, 10.572), stdev = 0.015
  CI (99.9%): [10.275, 10.837] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.180 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.008 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.078 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (10.008, 10.078, 10.182), stdev = 0.091
  CI (99.9%): [8.414, 11.743] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.371 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.174 ops/ms
Iteration   2: 8.194 ops/ms
Iteration   3: 8.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.174 ±(99.9%) 0.364 ops/ms [Average]
  (min, avg, max) = (8.155, 8.174, 8.194), stdev = 0.020
  CI (99.9%): [7.810, 8.538] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.002 ms/op
Iteration   2: 3.164 ±(99.9%) 0.002 ms/op
Iteration   3: 3.152 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.173 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (3.152, 3.173, 3.204), stdev = 0.027
  CI (99.9%): [2.677, 3.670] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.412 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.986 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (2.952, 2.986, 3.044), stdev = 0.050
  CI (99.9%): [2.066, 3.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.603 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.003 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.195 ±(99.9%) 0.002 ms/op
Iteration   3: 3.153 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.165 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.147, 3.165, 3.195), stdev = 0.027
  CI (99.9%): [2.681, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.023 ms/op
Iteration   2: 4.084 ±(99.9%) 0.020 ms/op
Iteration   3: 3.963 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (3.963, 4.038, 4.084), stdev = 0.066
  CI (99.9%): [2.839, 5.237] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.006 ms/op
Iteration   1: 3.226 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.110 ms/op
                 createUser·p0.999:  8.364 ms/op
                 createUser·p0.9999: 14.226 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.874 ms/op
                 createUser·p0.999:  11.957 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 3.224 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 16.238 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300962
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8809 
    [ 2.500,  5.000) = 289391 
    [ 5.000,  7.500) = 2218 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     17.748 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.512 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.091 ms/op

Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  12.410 ms/op
                 existUser·p0.9999: 22.955 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  7.672 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314233
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21386 
    [ 2.500,  5.000) = 290375 
    [ 5.000,  7.500) = 2034 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     21.580 ms/op
     p(99.9990) =     29.449 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.008 ms/op
Iteration   1: 3.257 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  7.756 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   2: 3.241 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.998 ms/op
                 getUser·p0.9999: 15.068 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 3.302 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  8.863 ms/op
                 getUser·p0.9999: 18.075 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293812
  mean =      3.267 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 250 
    [ 1.250,  2.500) = 5738 
    [ 2.500,  3.750) = 244677 
    [ 3.750,  5.000) = 40058 
    [ 5.000,  6.250) = 1804 
    [ 6.250,  7.500) = 784 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =      8.244 ms/op
     p(99.9900) =     16.263 ms/op
     p(99.9990) =     18.450 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 5.915 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.364 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.012 ms/op
Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.188 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 19.469 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.640 ms/op
                 listUser·p0.9999: 21.929 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 4.088 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.258 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234613
  mean =      4.090 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2537 
    [ 2.500,  5.000) = 202437 
    [ 5.000,  7.500) = 27275 
    [ 7.500, 10.000) = 1816 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     21.743 ms/op
     p(99.9990) =     23.374 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.138 ± 2.566  ops/ms
ClientGrpc.existUser                       thrpt       3  10.556 ± 0.281  ops/ms
ClientGrpc.getUser                         thrpt       3  10.078 ± 1.665  ops/ms
ClientGrpc.listUser                        thrpt       3   8.174 ± 0.364  ops/ms
ClientGrpc.createUser                       avgt       3   3.173 ± 0.496   ms/op
ClientGrpc.existUser                        avgt       3   2.986 ± 0.921   ms/op
ClientGrpc.getUser                          avgt       3   3.165 ± 0.484   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 1.199   ms/op
ClientGrpc.createUser                     sample  300962   3.191 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.602           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.748           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.201           ms/op
ClientGrpc.existUser                      sample  314233   3.054 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.763           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.580           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.590           ms/op
ClientGrpc.getUser                        sample  293812   3.267 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.871           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.203           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.244           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.263           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547           ms/op
ClientGrpc.listUser                       sample  234613   4.090 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.879           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.504           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.743           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
