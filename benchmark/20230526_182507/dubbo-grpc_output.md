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
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.140 ops/ms
Iteration   2: 10.145 ops/ms
Iteration   3: 10.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.195 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (10.140, 10.195, 10.299), stdev = 0.091
  CI (99.9%): [8.542, 11.848] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.105 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.991 ops/ms
Iteration   1: 11.136 ops/ms
Iteration   2: 11.201 ops/ms
Iteration   3: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.104 ±(99.9%) 2.112 ops/ms [Average]
  (min, avg, max) = (10.976, 11.104, 11.201), stdev = 0.116
  CI (99.9%): [8.992, 13.216] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.609 ops/ms
# Warmup Iteration   2: 10.172 ops/ms
# Warmup Iteration   3: 10.507 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.553 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (10.522, 10.553, 10.598), stdev = 0.040
  CI (99.9%): [9.816, 11.290] (assumes normal distribution)


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
# Warmup Iteration   1: 5.227 ops/ms
# Warmup Iteration   2: 7.535 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.949 ±(99.9%) 1.677 ops/ms [Average]
  (min, avg, max) = (7.843, 7.949, 8.006), stdev = 0.092
  CI (99.9%): [6.271, 9.626] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.608 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.080 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (3.050, 3.080, 3.102), stdev = 0.027
  CI (99.9%): [2.594, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.004 ms/op
Iteration   1: 2.925 ±(99.9%) 0.002 ms/op
Iteration   2: 2.883 ±(99.9%) 0.002 ms/op
Iteration   3: 2.873 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.873, 2.894, 2.925), stdev = 0.028
  CI (99.9%): [2.392, 3.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.028, 3.062, 3.107), stdev = 0.041
  CI (99.9%): [2.320, 3.804] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.185 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.007 ms/op
Iteration   1: 4.020 ±(99.9%) 0.009 ms/op
Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
Iteration   3: 3.953 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.991 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.953, 3.991, 4.020), stdev = 0.034
  CI (99.9%): [3.371, 4.611] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.787 ms/op
                 createUser·p0.9999: 27.739 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  6.717 ms/op
                 createUser·p0.9999: 18.448 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 20.402 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313616
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24443 
    [ 2.500,  5.000) = 287276 
    [ 5.000,  7.500) = 1440 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     10.144 ms/op
     p(99.9900) =     26.691 ms/op
     p(99.9990) =     27.975 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
Iteration   1: 2.945 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.105 ms/op
                 existUser·p0.999:  6.385 ms/op
                 existUser·p0.9999: 12.428 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  9.485 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   3: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  6.717 ms/op
                 existUser·p0.9999: 16.290 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327787
  mean =      2.929 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 715 
    [ 1.250,  2.500) = 34029 
    [ 2.500,  3.750) = 284684 
    [ 3.750,  5.000) = 7577 
    [ 5.000,  6.250) = 351 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =     15.892 ms/op
     p(99.9990) =     16.616 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.575 ms/op
                 getUser·p0.9999: 19.351 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.858 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 18.922 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316013
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18135 
    [ 2.500,  5.000) = 296395 
    [ 5.000,  7.500) = 1185 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     18.625 ms/op
     p(99.9990) =     19.880 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.011 ms/op
Iteration   1: 4.052 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.403 ms/op
                 listUser·p0.9999: 16.271 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 17.277 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  17.632 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235571
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2781 
    [ 2.500,  5.000) = 202098 
    [ 5.000,  7.500) = 29201 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     19.362 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.195 ± 1.653  ops/ms
ClientGrpc.existUser                       thrpt       3  11.104 ± 2.112  ops/ms
ClientGrpc.getUser                         thrpt       3  10.553 ± 0.737  ops/ms
ClientGrpc.listUser                        thrpt       3   7.949 ± 1.677  ops/ms
ClientGrpc.createUser                       avgt       3   3.080 ± 0.486   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.502   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.742   ms/op
ClientGrpc.listUser                         avgt       3   3.991 ± 0.620   ms/op
ClientGrpc.createUser                     sample  313616   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.144           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.691           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.049           ms/op
ClientGrpc.existUser                      sample  327787   2.929 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.783           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.892           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.728           ms/op
ClientGrpc.getUser                        sample  316013   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.152           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.625           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  235571   4.075 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.852           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.865           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.808           ms/op
