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
# Warmup Iteration   1: 4.801 ops/ms
# Warmup Iteration   2: 9.547 ops/ms
# Warmup Iteration   3: 10.377 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.859 ops/ms
Iteration   3: 10.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.384 ±(99.9%) 7.497 ops/ms [Average]
  (min, avg, max) = (10.138, 10.384, 10.859), stdev = 0.411
  CI (99.9%): [2.887, 17.881] (assumes normal distribution)


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
# Warmup Iteration   1: 8.010 ops/ms
# Warmup Iteration   2: 10.818 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.768 ops/ms
Iteration   2: 10.886 ops/ms
Iteration   3: 11.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.901 ±(99.9%) 2.581 ops/ms [Average]
  (min, avg, max) = (10.768, 10.901, 11.049), stdev = 0.142
  CI (99.9%): [8.319, 13.482] (assumes normal distribution)


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
# Warmup Iteration   1: 7.651 ops/ms
# Warmup Iteration   2: 10.410 ops/ms
# Warmup Iteration   3: 10.451 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.479 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (10.343, 10.479, 10.561), stdev = 0.118
  CI (99.9%): [8.319, 12.638] (assumes normal distribution)


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
# Warmup Iteration   1: 7.193 ops/ms
# Warmup Iteration   2: 8.433 ops/ms
# Warmup Iteration   3: 8.207 ops/ms
Iteration   1: 7.832 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.977 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (7.832, 7.977, 8.059), stdev = 0.126
  CI (99.9%): [5.674, 10.281] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.004 ms/op
Iteration   2: 3.200 ±(99.9%) 0.002 ms/op
Iteration   3: 3.117 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.150 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.117, 3.150, 3.200), stdev = 0.044
  CI (99.9%): [2.351, 3.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.003 ms/op
Iteration   1: 2.998 ±(99.9%) 0.001 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.866 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.938 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (2.866, 2.938, 2.998), stdev = 0.067
  CI (99.9%): [1.722, 4.155] (assumes normal distribution)


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.099 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (2.973, 3.057, 3.099), stdev = 0.073
  CI (99.9%): [1.730, 4.383] (assumes normal distribution)


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.014 ms/op
Iteration   2: 4.055 ±(99.9%) 0.013 ms/op
Iteration   3: 3.925 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.923, 3.968, 4.055), stdev = 0.076
  CI (99.9%): [2.586, 5.349] (assumes normal distribution)


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.202 ms/op
                 createUser·p0.9999: 14.702 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.281 ms/op
                 createUser·p0.9999: 12.235 ms/op
                 createUser·p1.00:   12.616 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.773 ms/op
                 createUser·p0.9999: 15.606 ms/op
                 createUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307760
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 860 
    [ 1.250,  2.500) = 26615 
    [ 2.500,  3.750) = 246955 
    [ 3.750,  5.000) = 32302 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     10.035 ms/op
     p(99.9900) =     15.421 ms/op
     p(99.9990) =     15.822 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.944 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  7.560 ms/op
                 existUser·p0.9999: 12.108 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.216 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 14.235 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  9.912 ms/op
                 existUser·p0.9999: 18.592 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325893
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2868 
    [ 1.250,  2.500) = 51476 
    [ 2.500,  3.750) = 251660 
    [ 3.750,  5.000) = 19087 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.216 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     16.655 ms/op
     p(99.9990) =     19.071 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.356 ms/op
                 getUser·p0.9999: 18.252 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.521 ms/op
                 getUser·p0.9999: 12.764 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313170
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1502 
    [ 1.250,  2.500) = 23151 
    [ 2.500,  3.750) = 266961 
    [ 3.750,  5.000) = 20587 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.789 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     18.542 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.399 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 14.247 ms/op
                 listUser·p1.00:   15.466 ms/op

Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.365 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.250 ms/op
                 listUser·p0.9999: 16.142 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.289 ms/op
                 listUser·p0.9999: 28.211 ms/op
                 listUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241715
  mean =      3.970 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3839 
    [ 2.500,  5.000) = 211619 
    [ 5.000,  7.500) = 25169 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     24.821 ms/op
     p(99.9990) =     28.677 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.384 ± 7.497  ops/ms
ClientGrpc.existUser                       thrpt       3  10.901 ± 2.581  ops/ms
ClientGrpc.getUser                         thrpt       3  10.479 ± 2.159  ops/ms
ClientGrpc.listUser                        thrpt       3   7.977 ± 2.303  ops/ms
ClientGrpc.createUser                       avgt       3   3.150 ± 0.800   ms/op
ClientGrpc.existUser                        avgt       3   2.938 ± 1.216   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 1.327   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 1.382   ms/op
ClientGrpc.createUser                     sample  307760   3.122 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.035           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.421           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.974           ms/op
ClientGrpc.existUser                      sample  325893   2.945 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.216           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.340           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.655           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  313170   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.518           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.789           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  241715   3.970 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.365           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.821           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.836           ms/op
