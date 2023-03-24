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
# Warmup Iteration   1: 4.965 ops/ms
# Warmup Iteration   2: 9.714 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.916 ops/ms
Iteration   3: 10.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.874 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (10.735, 10.874, 10.971), stdev = 0.123
  CI (99.9%): [8.623, 13.125] (assumes normal distribution)


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
# Warmup Iteration   1: 8.394 ops/ms
# Warmup Iteration   2: 11.001 ops/ms
# Warmup Iteration   3: 11.328 ops/ms
Iteration   1: 11.423 ops/ms
Iteration   2: 11.108 ops/ms
Iteration   3: 11.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.298 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (11.108, 11.298, 11.423), stdev = 0.167
  CI (99.9%): [8.251, 14.345] (assumes normal distribution)


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
# Warmup Iteration   1: 8.033 ops/ms
# Warmup Iteration   2: 10.401 ops/ms
# Warmup Iteration   3: 10.885 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.820 ±(99.9%) 3.117 ops/ms [Average]
  (min, avg, max) = (10.654, 10.820, 10.995), stdev = 0.171
  CI (99.9%): [7.703, 13.936] (assumes normal distribution)


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
# Warmup Iteration   1: 5.923 ops/ms
# Warmup Iteration   2: 8.071 ops/ms
# Warmup Iteration   3: 8.254 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.440 ±(99.9%) 1.673 ops/ms [Average]
  (min, avg, max) = (8.361, 8.440, 8.540), stdev = 0.092
  CI (99.9%): [6.766, 10.113] (assumes normal distribution)


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.004 ms/op
Iteration   1: 2.925 ±(99.9%) 0.004 ms/op
Iteration   2: 2.938 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.948 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (2.925, 2.948, 2.982), stdev = 0.030
  CI (99.9%): [2.403, 3.493] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.002 ms/op
Iteration   1: 2.833 ±(99.9%) 0.003 ms/op
Iteration   2: 2.843 ±(99.9%) 0.003 ms/op
Iteration   3: 2.857 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.844 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.833, 2.844, 2.857), stdev = 0.012
  CI (99.9%): [2.623, 3.065] (assumes normal distribution)


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.004 ms/op
Iteration   1: 2.934 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.950 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.949 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (2.934, 2.949, 2.963), stdev = 0.014
  CI (99.9%): [2.686, 3.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.014 ms/op
Iteration   1: 3.802 ±(99.9%) 0.027 ms/op
Iteration   2: 3.820 ±(99.9%) 0.013 ms/op
Iteration   3: 3.814 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.812 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (3.802, 3.812, 3.820), stdev = 0.009
  CI (99.9%): [3.645, 3.979] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.162 ms/op
                 createUser·p0.9999: 11.310 ms/op
                 createUser·p1.00:   11.715 ms/op

Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.579 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 2.962 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.230 ms/op
                 createUser·p0.9999: 25.205 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326509
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39012 
    [ 2.500,  5.000) = 286286 
    [ 5.000,  7.500) = 863 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     20.301 ms/op
     p(99.9990) =     25.476 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.902 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
Iteration   1: 2.772 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.789 ms/op
                 existUser·p0.9999: 11.205 ms/op
                 existUser·p1.00:   11.600 ms/op

Iteration   2: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.174 ms/op
                 existUser·p0.9999: 12.693 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.837 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.215 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.840 ms/op
                 existUser·p0.9999: 15.853 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339336
  mean =      2.827 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5074 
    [ 1.250,  2.500) = 49669 
    [ 2.500,  3.750) = 275091 
    [ 3.750,  5.000) = 8785 
    [ 5.000,  6.250) = 356 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.382 ms/op
     p(99.9900) =     14.846 ms/op
     p(99.9990) =     19.363 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.245 ms/op
                 getUser·p0.9999: 11.345 ms/op
                 getUser·p1.00:   11.862 ms/op

Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.888 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.861 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 2.959 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 22.944 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327113
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38507 
    [ 2.500,  5.000) = 287170 
    [ 5.000,  7.500) = 1079 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.847 ms/op
     p(99.9900) =     20.692 ms/op
     p(99.9990) =     23.158 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.011 ms/op
Iteration   1: 3.845 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.382 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.810 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  14.511 ms/op
                 listUser·p0.9999: 17.637 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 16.772 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250081
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 5710 
    [ 2.500,  3.750) = 133291 
    [ 3.750,  5.000) = 88745 
    [ 5.000,  6.250) = 18034 
    [ 6.250,  7.500) = 3245 
    [ 7.500,  8.750) = 450 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 115 
    [15.000, 16.250) = 73 
    [16.250, 17.500) = 67 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     18.235 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.874 ± 2.251  ops/ms
ClientGrpc.existUser                       thrpt       3  11.298 ± 3.047  ops/ms
ClientGrpc.getUser                         thrpt       3  10.820 ± 3.117  ops/ms
ClientGrpc.listUser                        thrpt       3   8.440 ± 1.673  ops/ms
ClientGrpc.createUser                       avgt       3   2.948 ± 0.545   ms/op
ClientGrpc.existUser                        avgt       3   2.844 ± 0.221   ms/op
ClientGrpc.getUser                          avgt       3   2.949 ± 0.264   ms/op
ClientGrpc.listUser                         avgt       3   3.812 ± 0.167   ms/op
ClientGrpc.createUser                     sample  326509   2.940 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.375           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.301           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  339336   2.827 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.382           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.846           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  327113   2.933 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.908           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.692           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.298           ms/op
ClientGrpc.listUser                       sample  250081   3.837 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.382           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.894           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.236           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.645           ms/op
