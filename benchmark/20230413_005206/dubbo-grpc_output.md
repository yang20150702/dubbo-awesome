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
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 9.373 ops/ms
# Warmup Iteration   3: 10.493 ops/ms
Iteration   1: 10.675 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.779 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (10.675, 10.779, 10.861), stdev = 0.095
  CI (99.9%): [9.047, 12.510] (assumes normal distribution)


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
# Warmup Iteration   1: 7.928 ops/ms
# Warmup Iteration   2: 11.016 ops/ms
# Warmup Iteration   3: 11.199 ops/ms
Iteration   1: 11.192 ops/ms
Iteration   2: 11.353 ops/ms
Iteration   3: 11.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.248 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (11.192, 11.248, 11.353), stdev = 0.091
  CI (99.9%): [9.592, 12.904] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.609 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.998 ops/ms
Iteration   3: 10.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.900 ±(99.9%) 1.789 ops/ms [Average]
  (min, avg, max) = (10.802, 10.900, 10.998), stdev = 0.098
  CI (99.9%): [9.111, 12.689] (assumes normal distribution)


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
# Warmup Iteration   1: 6.738 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.515 ops/ms
Iteration   1: 8.439 ops/ms
Iteration   2: 8.462 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.472 ±(99.9%) 0.700 ops/ms [Average]
  (min, avg, max) = (8.439, 8.472, 8.514), stdev = 0.038
  CI (99.9%): [7.772, 9.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.979 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.960, 2.979, 2.995), stdev = 0.018
  CI (99.9%): [2.651, 3.306] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.682 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.848 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.003 ms/op
Iteration   1: 2.815 ±(99.9%) 0.005 ms/op
Iteration   2: 2.870 ±(99.9%) 0.004 ms/op
Iteration   3: 2.817 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.834 ±(99.9%) 0.567 ms/op [Average]
  (min, avg, max) = (2.815, 2.834, 2.870), stdev = 0.031
  CI (99.9%): [2.267, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.908 ±(99.9%) 0.002 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.935 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (2.908, 2.935, 2.960), stdev = 0.026
  CI (99.9%): [2.452, 3.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.016 ms/op
Iteration   1: 3.796 ±(99.9%) 0.007 ms/op
Iteration   2: 3.778 ±(99.9%) 0.014 ms/op
Iteration   3: 3.802 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.792 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (3.778, 3.792, 3.802), stdev = 0.013
  CI (99.9%): [3.561, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.351 ms/op
                 createUser·p0.9999: 12.090 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  9.568 ms/op
                 createUser·p0.9999: 14.212 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.203 ms/op
                 createUser·p0.999:  7.912 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323032
  mean =      2.972 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1469 
    [ 1.250,  2.500) = 28607 
    [ 2.500,  3.750) = 278928 
    [ 3.750,  5.000) = 12731 
    [ 5.000,  6.250) = 639 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     15.325 ms/op
     p(99.9990) =     17.057 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.005 ms/op
Iteration   1: 2.799 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.481 ms/op
                 existUser·p0.9999: 11.825 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.833 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.101 ms/op
                 existUser·p0.9999: 12.311 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   3: 2.816 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  5.635 ms/op
                 existUser·p0.9999: 15.520 ms/op
                 existUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340890
  mean =      2.816 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3951 
    [ 1.250,  2.500) = 53800 
    [ 2.500,  3.750) = 274163 
    [ 3.750,  5.000) = 8006 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     12.546 ms/op
     p(99.9990) =     15.715 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  10.844 ms/op
                 getUser·p0.9999: 14.798 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   2: 2.921 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.488 ms/op
                 getUser·p0.9999: 14.043 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.065 ms/op
                 getUser·p0.9999: 15.148 ms/op
                 getUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325021
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2526 
    [ 1.250,  2.500) = 30514 
    [ 2.500,  3.750) = 276911 
    [ 3.750,  5.000) = 13965 
    [ 5.000,  6.250) = 577 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.027 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     16.650 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
Iteration   1: 3.807 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  11.680 ms/op
                 listUser·p0.9999: 14.080 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   2: 3.833 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   16.318 ms/op

Iteration   3: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.053 ms/op
                 listUser·p0.9999: 18.405 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251058
  mean =      3.825 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 5701 
    [ 2.500,  3.750) = 134241 
    [ 3.750,  5.000) = 91608 
    [ 5.000,  6.250) = 15411 
    [ 6.250,  7.500) = 3061 
    [ 7.500,  8.750) = 422 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 145 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.418 ms/op
     p(99.9900) =     17.619 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.779 ± 1.732  ops/ms
ClientGrpc.existUser                       thrpt       3  11.248 ± 1.656  ops/ms
ClientGrpc.getUser                         thrpt       3  10.900 ± 1.789  ops/ms
ClientGrpc.listUser                        thrpt       3   8.472 ± 0.700  ops/ms
ClientGrpc.createUser                       avgt       3   2.979 ± 0.327   ms/op
ClientGrpc.existUser                        avgt       3   2.834 ± 0.567   ms/op
ClientGrpc.getUser                          avgt       3   2.935 ± 0.483   ms/op
ClientGrpc.listUser                         avgt       3   3.792 ± 0.231   ms/op
ClientGrpc.createUser                     sample  323032   2.972 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.621           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.325           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.203           ms/op
ClientGrpc.existUser                      sample  340890   2.816 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.581           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.814           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.546           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.778           ms/op
ClientGrpc.getUser                        sample  325021   2.954 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.027           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.844           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.974           ms/op
ClientGrpc.listUser                       sample  251058   3.825 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.418           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.619           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.776           ms/op
