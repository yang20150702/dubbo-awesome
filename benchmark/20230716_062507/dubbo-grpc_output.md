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
# Warmup Iteration   1: 2.127 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 6.701 ops/ms
Iteration   1: 6.743 ops/ms
Iteration   2: 7.230 ops/ms
Iteration   3: 7.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.119 ±(99.9%) 6.100 ops/ms [Average]
  (min, avg, max) = (6.743, 7.119, 7.384), stdev = 0.334
  CI (99.9%): [1.019, 13.219] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 7.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.809 ±(99.9%) 3.551 ops/ms [Average]
  (min, avg, max) = (7.589, 7.809, 7.961), stdev = 0.195
  CI (99.9%): [4.258, 11.360] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ops/ms
# Warmup Iteration   2: 6.415 ops/ms
# Warmup Iteration   3: 6.856 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.540 ops/ms
Iteration   3: 7.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.663 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (7.540, 7.663, 7.725), stdev = 0.106
  CI (99.9%): [5.727, 9.599] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.593 ops/ms
# Warmup Iteration   2: 5.743 ops/ms
# Warmup Iteration   3: 5.649 ops/ms
Iteration   1: 5.839 ops/ms
Iteration   2: 6.152 ops/ms
Iteration   3: 5.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.966 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (5.839, 5.966, 6.152), stdev = 0.165
  CI (99.9%): [2.962, 8.970] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.520 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.545 ±(99.9%) 0.006 ms/op
Iteration   1: 4.568 ±(99.9%) 0.004 ms/op
Iteration   2: 4.471 ±(99.9%) 0.004 ms/op
Iteration   3: 4.311 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.450 ±(99.9%) 2.365 ms/op [Average]
  (min, avg, max) = (4.311, 4.450, 4.568), stdev = 0.130
  CI (99.9%): [2.085, 6.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.297 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.004 ms/op
Iteration   1: 4.148 ±(99.9%) 0.003 ms/op
Iteration   2: 4.008 ±(99.9%) 0.003 ms/op
Iteration   3: 4.097 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.084 ±(99.9%) 1.297 ms/op [Average]
  (min, avg, max) = (4.008, 4.084, 4.148), stdev = 0.071
  CI (99.9%): [2.787, 5.382] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.658 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.004 ms/op
Iteration   1: 4.334 ±(99.9%) 0.004 ms/op
Iteration   2: 4.274 ±(99.9%) 0.003 ms/op
Iteration   3: 4.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.353 ±(99.9%) 1.635 ms/op [Average]
  (min, avg, max) = (4.274, 4.353, 4.450), stdev = 0.090
  CI (99.9%): [2.718, 5.988] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 6.328 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.020 ms/op
Iteration   1: 6.011 ±(99.9%) 0.016 ms/op
Iteration   2: 5.933 ±(99.9%) 0.016 ms/op
Iteration   3: 5.929 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.958 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (5.929, 5.958, 6.011), stdev = 0.046
  CI (99.9%): [5.111, 6.805] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.978 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 5.065 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.021 ms/op
Iteration   1: 4.666 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   6.167 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  15.227 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   2: 4.650 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   10.390 ms/op
                 createUser·p0.999:  16.237 ms/op
                 createUser·p0.9999: 29.569 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   3: 4.718 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   4.407 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   7.627 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  16.857 ms/op
                 createUser·p0.9999: 23.141 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205158
  mean =      4.678 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5564 
    [ 2.500,  5.000) = 140532 
    [ 5.000,  7.500) = 49217 
    [ 7.500, 10.000) = 7345 
    [10.000, 12.500) = 1704 
    [12.500, 15.000) = 510 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.430 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     16.005 ms/op
     p(99.9900) =     27.016 ms/op
     p(99.9990) =     30.010 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.917 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.774 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.603 ±(99.9%) 0.020 ms/op
Iteration   1: 4.692 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.715 ms/op
                 existUser·p0.999:  16.899 ms/op
                 existUser·p0.9999: 29.804 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   2: 4.606 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   10.551 ms/op
                 existUser·p0.999:  16.295 ms/op
                 existUser·p0.9999: 39.977 ms/op
                 existUser·p1.00:   40.042 ms/op

Iteration   3: 4.258 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   4.084 ms/op
                 existUser·p0.90:   5.374 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   8.143 ms/op
                 existUser·p0.999:  14.187 ms/op
                 existUser·p0.9999: 24.516 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 212700
  mean =      4.511 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 164850 
    [ 5.000, 10.000) = 45608 
    [10.000, 15.000) = 1918 
    [15.000, 20.000) = 195 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      4.170 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     33.912 ms/op
     p(99.9990) =     39.977 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.473 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.649 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.014 ms/op
Iteration   1: 4.280 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  11.038 ms/op
                 getUser·p0.9999: 25.185 ms/op
                 getUser·p1.00:   25.756 ms/op

Iteration   2: 4.354 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  11.729 ms/op
                 getUser·p0.9999: 28.375 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 4.412 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  16.960 ms/op
                 getUser·p0.9999: 38.863 ms/op
                 getUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 220803
  mean =      4.348 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5801 
    [ 2.500,  5.000) = 172385 
    [ 5.000,  7.500) = 39949 
    [ 7.500, 10.000) = 2091 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     12.308 ms/op
     p(99.9900) =     36.891 ms/op
     p(99.9990) =     39.084 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.258 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 6.326 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.593 ±(99.9%) 0.021 ms/op
Iteration   1: 5.363 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   5.112 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.469 ms/op
                 listUser·p0.999:  16.250 ms/op
                 listUser·p0.9999: 22.090 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 5.519 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   10.889 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 22.604 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 5.540 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 25.398 ms/op
                 listUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 175326
  mean =      5.473 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 242 
    [ 2.500,  5.000) = 73633 
    [ 5.000,  7.500) = 86197 
    [ 7.500, 10.000) = 12576 
    [10.000, 12.500) = 1902 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     19.355 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     28.487 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.119 ± 6.100  ops/ms
ClientGrpc.existUser                       thrpt       3   7.809 ± 3.551  ops/ms
ClientGrpc.getUser                         thrpt       3   7.663 ± 1.936  ops/ms
ClientGrpc.listUser                        thrpt       3   5.966 ± 3.004  ops/ms
ClientGrpc.createUser                       avgt       3   4.450 ± 2.365   ms/op
ClientGrpc.existUser                        avgt       3   4.084 ± 1.297   ms/op
ClientGrpc.getUser                          avgt       3   4.353 ± 1.635   ms/op
ClientGrpc.listUser                         avgt       3   5.958 ± 0.847   ms/op
ClientGrpc.createUser                     sample  205158   4.678 ± 0.011   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.957           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.234           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.404           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          16.005           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.016           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.114           ms/op
ClientGrpc.existUser                      sample  212700   4.511 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.922           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.095           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.381           ms/op
ClientGrpc.existUser:existUser·p0.99      sample          10.093           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          16.269           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.912           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          40.042           ms/op
ClientGrpc.getUser                        sample  220803   4.348 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.909           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.448           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.308           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          36.891           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          39.125           ms/op
ClientGrpc.listUser                       sample  175326   5.473 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.290           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.699           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.355           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.069           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.622           ms/op
