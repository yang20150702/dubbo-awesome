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
# Warmup Iteration   1: 3.797 ops/ms
# Warmup Iteration   2: 8.455 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 9.892 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.035 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (9.892, 10.035, 10.144), stdev = 0.130
  CI (99.9%): [7.672, 12.399] (assumes normal distribution)


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
# Warmup Iteration   1: 7.366 ops/ms
# Warmup Iteration   2: 10.414 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.818 ops/ms
Iteration   2: 10.522 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.707 ±(99.9%) 2.949 ops/ms [Average]
  (min, avg, max) = (10.522, 10.707, 10.818), stdev = 0.162
  CI (99.9%): [7.758, 13.656] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.506 ops/ms
# Warmup Iteration   2: 9.730 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.236 ±(99.9%) 0.251 ops/ms [Average]
  (min, avg, max) = (10.227, 10.236, 10.252), stdev = 0.014
  CI (99.9%): [9.985, 10.486] (assumes normal distribution)


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
# Warmup Iteration   1: 5.101 ops/ms
# Warmup Iteration   2: 7.725 ops/ms
# Warmup Iteration   3: 8.016 ops/ms
Iteration   1: 8.155 ops/ms
Iteration   2: 8.279 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.165 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (8.060, 8.165, 8.279), stdev = 0.110
  CI (99.9%): [6.159, 10.170] (assumes normal distribution)


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
# Warmup Iteration   1: 3.949 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.001 ms/op
Iteration   1: 3.176 ±(99.9%) 0.001 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.127 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.121 ±(99.9%) 1.055 ms/op [Average]
  (min, avg, max) = (3.061, 3.121, 3.176), stdev = 0.058
  CI (99.9%): [2.067, 4.176] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.946, 2.950, 2.958), stdev = 0.007
  CI (99.9%): [2.816, 3.084] (assumes normal distribution)


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.002 ms/op
Iteration   3: 3.111 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.122 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.111, 3.122, 3.130), stdev = 0.010
  CI (99.9%): [2.942, 3.301] (assumes normal distribution)


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
# Warmup Iteration   1: 5.473 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.021 ms/op
Iteration   1: 3.987 ±(99.9%) 0.026 ms/op
Iteration   2: 4.027 ±(99.9%) 0.039 ms/op
Iteration   3: 3.891 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.891, 3.968, 4.027), stdev = 0.070
  CI (99.9%): [2.694, 5.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.045 ms/op
                 createUser·p0.9999: 13.759 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.154 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.140 ms/op
                 createUser·p0.9999: 15.310 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   3: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.299 ms/op
                 createUser·p0.999:  9.173 ms/op
                 createUser·p0.9999: 27.402 ms/op
                 createUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307022
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12433 
    [ 2.500,  5.000) = 293122 
    [ 5.000,  7.500) = 1108 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.790 ms/op
     p(99.9900) =     24.487 ms/op
     p(99.9990) =     27.944 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.278 ms/op
                 existUser·p0.9999: 17.776 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.189 ms/op
                 existUser·p0.9999: 19.073 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  7.215 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321207
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30550 
    [ 2.500,  5.000) = 289607 
    [ 5.000,  7.500) = 807 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      7.060 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     20.783 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 4.552 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 13.801 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 3.167 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.365 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.336 ms/op
                 getUser·p0.9999: 18.579 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305543
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9486 
    [ 2.500,  5.000) = 293993 
    [ 5.000,  7.500) = 1723 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     18.922 ms/op
     p(99.9990) =     20.007 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.091 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.009 ms/op
Iteration   1: 3.927 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.043 ms/op
                 listUser·p0.9999: 16.407 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   2: 3.983 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.132 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.614 ms/op
                 listUser·p0.9999: 19.631 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240841
  mean =      3.986 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1760 
    [ 2.500,  3.750) = 88372 
    [ 3.750,  5.000) = 134505 
    [ 5.000,  6.250) = 9646 
    [ 6.250,  7.500) = 5167 
    [ 7.500,  8.750) = 601 
    [ 8.750, 10.000) = 217 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 82 
    [15.000, 16.250) = 110 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     19.298 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.035 ± 2.363  ops/ms
ClientGrpc.existUser                       thrpt       3  10.707 ± 2.949  ops/ms
ClientGrpc.getUser                         thrpt       3  10.236 ± 0.251  ops/ms
ClientGrpc.listUser                        thrpt       3   8.165 ± 2.006  ops/ms
ClientGrpc.createUser                       avgt       3   3.121 ± 1.055   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.134   ms/op
ClientGrpc.getUser                          avgt       3   3.122 ± 0.180   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 1.274   ms/op
ClientGrpc.createUser                     sample  307022   3.128 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.790           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.487           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.377           ms/op
ClientGrpc.existUser                      sample  321207   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.734           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.060           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.266           ms/op
ClientGrpc.getUser                        sample  305543   3.141 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.795           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.922           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  240841   3.986 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.298           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.890           ms/op
