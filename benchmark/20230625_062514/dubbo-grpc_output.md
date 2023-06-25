# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 9.463 ops/ms
# Warmup Iteration   3: 10.412 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 10.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.786 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (10.723, 10.786, 10.861), stdev = 0.070
  CI (99.9%): [9.507, 12.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.482 ops/ms
# Warmup Iteration   2: 10.906 ops/ms
# Warmup Iteration   3: 11.181 ops/ms
Iteration   1: 11.254 ops/ms
Iteration   2: 11.144 ops/ms
Iteration   3: 11.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.212 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (11.144, 11.212, 11.254), stdev = 0.060
  CI (99.9%): [10.121, 12.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.498 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 10.706 ops/ms
Iteration   1: 10.861 ops/ms
Iteration   2: 10.922 ops/ms
Iteration   3: 10.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.907 ±(99.9%) 0.754 ops/ms [Average]
  (min, avg, max) = (10.861, 10.907, 10.940), stdev = 0.041
  CI (99.9%): [10.154, 11.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.125 ops/ms
# Warmup Iteration   2: 7.958 ops/ms
# Warmup Iteration   3: 8.116 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.234 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (8.149, 8.234, 8.361), stdev = 0.112
  CI (99.9%): [6.186, 10.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.003 ms/op
Iteration   1: 2.885 ±(99.9%) 0.004 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.931 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (2.885, 2.931, 2.962), stdev = 0.041
  CI (99.9%): [2.190, 3.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.004 ms/op
Iteration   1: 2.933 ±(99.9%) 0.003 ms/op
Iteration   2: 2.803 ±(99.9%) 0.003 ms/op
Iteration   3: 2.856 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 1.191 ms/op [Average]
  (min, avg, max) = (2.803, 2.864, 2.933), stdev = 0.065
  CI (99.9%): [1.673, 4.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.428 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.984 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.963, 2.984, 2.995), stdev = 0.018
  CI (99.9%): [2.655, 3.312] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.995 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.023 ms/op
Iteration   1: 4.026 ±(99.9%) 0.024 ms/op
Iteration   2: 3.928 ±(99.9%) 0.020 ms/op
Iteration   3: 3.925 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.960 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.925, 3.960, 4.026), stdev = 0.058
  CI (99.9%): [2.907, 5.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.390 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.488 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.036 ms/op
                 createUser·p0.9999: 15.221 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.022 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321177
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1537 
    [ 1.250,  2.500) = 23150 
    [ 2.500,  3.750) = 281067 
    [ 3.750,  5.000) = 13860 
    [ 5.000,  6.250) = 828 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.959 ms/op
     p(99.9900) =     18.716 ms/op
     p(99.9990) =     19.883 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.374 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.848 ±(99.9%) 0.006 ms/op
Iteration   1: 2.808 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.800 ms/op
                 existUser·p0.9999: 16.187 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.228 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.083 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.665 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335088
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3595 
    [ 1.250,  2.500) = 45848 
    [ 2.500,  3.750) = 274691 
    [ 3.750,  5.000) = 9990 
    [ 5.000,  6.250) = 484 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 72 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.228 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.822 ms/op
     p(99.9900) =     17.545 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.031 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.418 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.297 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.136 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.046 ms/op
                 getUser·p0.9999: 24.674 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323598
  mean =      2.964 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25631 
    [ 2.500,  5.000) = 297151 
    [ 5.000,  7.500) = 537 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.473 ms/op
     p(99.9900) =     21.709 ms/op
     p(99.9990) =     25.212 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.410 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.010 ms/op
Iteration   1: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  11.738 ms/op
                 listUser·p0.9999: 15.073 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 16.859 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.285 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.680 ms/op
                 listUser·p0.999:  14.445 ms/op
                 listUser·p0.9999: 26.782 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250059
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5073 
    [ 2.500,  5.000) = 224439 
    [ 5.000,  7.500) = 19577 
    [ 7.500, 10.000) = 485 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.171 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.786 ± 1.278  ops/ms
ClientGrpc.existUser                       thrpt       3  11.212 ± 1.092  ops/ms
ClientGrpc.getUser                         thrpt       3  10.907 ± 0.754  ops/ms
ClientGrpc.listUser                        thrpt       3   8.234 ± 2.048  ops/ms
ClientGrpc.createUser                       avgt       3   2.931 ± 0.741   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 1.191   ms/op
ClientGrpc.getUser                          avgt       3   2.984 ± 0.328   ms/op
ClientGrpc.listUser                         avgt       3   3.960 ± 1.053   ms/op
ClientGrpc.createUser                     sample  321177   2.987 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.390           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.959           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.716           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  335088   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.228           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.822           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.545           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  323598   2.964 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.297           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.473           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.709           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  250059   3.840 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.285           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.171           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
