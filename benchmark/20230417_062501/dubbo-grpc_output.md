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
# Warmup Iteration   1: 2.603 ops/ms
# Warmup Iteration   2: 6.078 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 8.028 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.889 ±(99.9%) 2.784 ops/ms [Average]
  (min, avg, max) = (7.725, 7.889, 8.028), stdev = 0.153
  CI (99.9%): [5.105, 10.672] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 8.098 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.761 ops/ms
Iteration   2: 9.006 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.858 ±(99.9%) 2.375 ops/ms [Average]
  (min, avg, max) = (8.761, 8.858, 9.006), stdev = 0.130
  CI (99.9%): [6.483, 11.234] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.810 ops/ms
# Warmup Iteration   2: 7.699 ops/ms
# Warmup Iteration   3: 8.142 ops/ms
Iteration   1: 8.103 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 8.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.071 ±(99.9%) 3.304 ops/ms [Average]
  (min, avg, max) = (7.875, 8.071, 8.233), stdev = 0.181
  CI (99.9%): [4.766, 11.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ops/ms
# Warmup Iteration   2: 5.555 ops/ms
# Warmup Iteration   3: 6.181 ops/ms
Iteration   1: 6.059 ops/ms
Iteration   2: 6.049 ops/ms
Iteration   3: 6.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.072 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (6.049, 6.072, 6.109), stdev = 0.032
  CI (99.9%): [5.481, 6.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.756 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.003 ms/op
Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
Iteration   3: 3.896 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.880 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.839, 3.880, 3.906), stdev = 0.036
  CI (99.9%): [3.226, 4.535] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.345 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.006 ms/op
Iteration   1: 3.580 ±(99.9%) 0.004 ms/op
Iteration   2: 3.690 ±(99.9%) 0.003 ms/op
Iteration   3: 3.703 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.657 ±(99.9%) 1.234 ms/op [Average]
  (min, avg, max) = (3.580, 3.657, 3.703), stdev = 0.068
  CI (99.9%): [2.423, 4.891] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.953 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.004 ms/op
Iteration   1: 3.933 ±(99.9%) 0.002 ms/op
Iteration   2: 3.877 ±(99.9%) 0.003 ms/op
Iteration   3: 3.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.900 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.877, 3.900, 3.933), stdev = 0.029
  CI (99.9%): [3.367, 4.434] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.376 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.252 ±(99.9%) 0.022 ms/op
Iteration   1: 5.010 ±(99.9%) 0.015 ms/op
Iteration   2: 5.119 ±(99.9%) 0.013 ms/op
Iteration   3: 5.180 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.103 ±(99.9%) 1.574 ms/op [Average]
  (min, avg, max) = (5.010, 5.103, 5.180), stdev = 0.086
  CI (99.9%): [3.529, 6.677] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.012 ms/op
Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  12.066 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   30.343 ms/op

Iteration   2: 3.858 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   5.824 ms/op
                 createUser·p0.999:  7.834 ms/op
                 createUser·p0.9999: 21.118 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.887 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  22.577 ms/op
                 createUser·p0.9999: 25.962 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246808
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3865 
    [ 2.500,  5.000) = 225292 
    [ 5.000,  7.500) = 16829 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     10.443 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.674 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.541 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.008 ms/op
Iteration   1: 3.568 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  12.833 ms/op
                 existUser·p0.9999: 17.728 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.509 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 15.655 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   3: 3.595 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  9.981 ms/op
                 existUser·p0.9999: 20.254 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269957
  mean =      3.557 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10364 
    [ 2.500,  5.000) = 250837 
    [ 5.000,  7.500) = 7958 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     11.323 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     20.696 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.924 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.011 ms/op
Iteration   1: 3.999 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.923 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.286 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 18.842 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   2: 3.955 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  10.974 ms/op
                 getUser·p0.9999: 17.364 ms/op
                 getUser·p1.00:   17.727 ms/op

Iteration   3: 3.964 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 31.815 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241536
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5492 
    [ 2.500,  5.000) = 215221 
    [ 5.000,  7.500) = 19735 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     31.419 ms/op
     p(99.9990) =     31.954 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 7.475 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.738 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.258 ±(99.9%) 0.022 ms/op
Iteration   1: 5.157 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   4.866 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.725 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  16.205 ms/op
                 listUser·p0.9999: 25.138 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 5.215 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   29.000 ms/op

Iteration   3: 5.412 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.864 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  19.726 ms/op
                 listUser·p0.9999: 29.849 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 182523
  mean =      5.259 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 90964 
    [ 5.000,  7.500) = 80022 
    [ 7.500, 10.000) = 9692 
    [10.000, 12.500) = 1105 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     18.956 ms/op
     p(99.9900) =     28.008 ms/op
     p(99.9990) =     30.591 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.889 ± 2.784  ops/ms
ClientGrpc.existUser                       thrpt       3   8.858 ± 2.375  ops/ms
ClientGrpc.getUser                         thrpt       3   8.071 ± 3.304  ops/ms
ClientGrpc.listUser                        thrpt       3   6.072 ± 0.591  ops/ms
ClientGrpc.createUser                       avgt       3   3.880 ± 0.654   ms/op
ClientGrpc.existUser                        avgt       3   3.657 ± 1.234   ms/op
ClientGrpc.getUser                          avgt       3   3.900 ± 0.533   ms/op
ClientGrpc.listUser                         avgt       3   5.103 ± 1.574   ms/op
ClientGrpc.createUser                     sample  246808   3.892 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.915           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.193           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.443           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.640           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.343           ms/op
ClientGrpc.existUser                      sample  269957   3.557 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.887           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.734           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.323           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.547           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  241536   3.972 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.292           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.419           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.014           ms/op
ClientGrpc.listUser                       sample  182523   5.259 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.389           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.830           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.956           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.008           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.835           ms/op
