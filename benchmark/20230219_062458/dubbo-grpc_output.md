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
# Warmup Iteration   1: 4.600 ops/ms
# Warmup Iteration   2: 9.335 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 10.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.298 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (10.251, 10.298, 10.380), stdev = 0.071
  CI (99.9%): [9.000, 11.595] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 10.260 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.840 ops/ms
Iteration   3: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.834 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (10.680, 10.834, 10.981), stdev = 0.151
  CI (99.9%): [8.083, 13.584] (assumes normal distribution)


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
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 10.175 ops/ms
# Warmup Iteration   3: 10.917 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.583 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (10.336, 10.583, 10.723), stdev = 0.215
  CI (99.9%): [6.661, 14.505] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 7.961 ops/ms
Iteration   1: 7.943 ops/ms
Iteration   2: 7.958 ops/ms
Iteration   3: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.999 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (7.943, 7.999, 8.095), stdev = 0.084
  CI (99.9%): [6.466, 9.532] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.100 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.037, 3.100, 3.189), stdev = 0.079
  CI (99.9%): [1.659, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 2.923 ±(99.9%) 0.003 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.933 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.923, 2.929, 2.933), stdev = 0.005
  CI (99.9%): [2.837, 3.021] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.004 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.049, 3.066, 3.094), stdev = 0.025
  CI (99.9%): [2.619, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.013 ms/op
Iteration   1: 3.994 ±(99.9%) 0.025 ms/op
Iteration   2: 3.897 ±(99.9%) 0.035 ms/op
Iteration   3: 3.903 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.897, 3.931, 3.994), stdev = 0.054
  CI (99.9%): [2.944, 4.918] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.231 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.553 ms/op
                 createUser·p0.9999: 17.465 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.850 ms/op
                 createUser·p0.9999: 17.325 ms/op
                 createUser·p1.00:   17.826 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.219 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 19.513 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310907
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 854 
    [ 1.250,  2.500) = 24902 
    [ 2.500,  3.750) = 257987 
    [ 3.750,  5.000) = 26027 
    [ 5.000,  6.250) = 557 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.219 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.579 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     19.785 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.006 ms/op
Iteration   1: 2.900 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 11.092 ms/op
                 existUser·p1.00:   11.387 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.663 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  5.225 ms/op
                 existUser·p0.9999: 14.083 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.720 ms/op
                 existUser·p0.9999: 24.421 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326099
  mean =      2.942 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50198 
    [ 2.500,  5.000) = 275252 
    [ 5.000,  7.500) = 401 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      6.848 ms/op
     p(99.9900) =     18.379 ms/op
     p(99.9990) =     24.723 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.242 ms/op
                 getUser·p0.9999: 16.941 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.217 ms/op
                 getUser·p0.9999: 15.873 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.044 ms/op
                 getUser·p0.9999: 18.012 ms/op
                 getUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311147
  mean =      3.082 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1202 
    [ 1.250,  2.500) = 24745 
    [ 2.500,  3.750) = 257752 
    [ 3.750,  5.000) = 26629 
    [ 5.000,  6.250) = 378 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     18.310 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.749 ms/op
                 listUser·p0.999:  11.983 ms/op
                 listUser·p0.9999: 13.581 ms/op
                 listUser·p1.00:   13.959 ms/op

Iteration   2: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.162 ms/op
                 listUser·p0.9999: 17.216 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.660 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.955 ms/op
                 listUser·p0.9999: 19.830 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238184
  mean =      4.028 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3598 
    [ 2.500,  5.000) = 203567 
    [ 5.000,  7.500) = 29746 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     16.724 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.298 ± 1.298  ops/ms
ClientGrpc.existUser                       thrpt       3  10.834 ± 2.750  ops/ms
ClientGrpc.getUser                         thrpt       3  10.583 ± 3.922  ops/ms
ClientGrpc.listUser                        thrpt       3   7.999 ± 1.533  ops/ms
ClientGrpc.createUser                       avgt       3   3.100 ± 1.442   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.092   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.447   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.987   ms/op
ClientGrpc.createUser                     sample  310907   3.086 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.219           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.579           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.923           ms/op
ClientGrpc.existUser                      sample  326099   2.942 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.848           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.379           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.838           ms/op
ClientGrpc.getUser                        sample  311147   3.082 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.941           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.481           ms/op
ClientGrpc.listUser                       sample  238184   4.028 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.660           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.724           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.775           ms/op
