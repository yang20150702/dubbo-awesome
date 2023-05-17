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
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 6.689 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.740 ops/ms
Iteration   2: 8.848 ops/ms
Iteration   3: 8.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.784 ±(99.9%) 1.034 ops/ms [Average]
  (min, avg, max) = (8.740, 8.784, 8.848), stdev = 0.057
  CI (99.9%): [7.750, 9.818] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.174 ops/ms
# Warmup Iteration   2: 8.528 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.277 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 9.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.221 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (9.193, 9.221, 9.277), stdev = 0.048
  CI (99.9%): [8.339, 10.104] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.257 ops/ms
# Warmup Iteration   2: 8.162 ops/ms
# Warmup Iteration   3: 8.496 ops/ms
Iteration   1: 8.631 ops/ms
Iteration   2: 8.726 ops/ms
Iteration   3: 8.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.679 ±(99.9%) 0.860 ops/ms [Average]
  (min, avg, max) = (8.631, 8.679, 8.726), stdev = 0.047
  CI (99.9%): [7.819, 9.539] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.458 ops/ms
# Warmup Iteration   2: 6.371 ops/ms
# Warmup Iteration   3: 6.670 ops/ms
Iteration   1: 6.908 ops/ms
Iteration   2: 6.722 ops/ms
Iteration   3: 6.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.783 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (6.718, 6.783, 6.908), stdev = 0.109
  CI (99.9%): [4.797, 8.768] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.005 ms/op
Iteration   1: 3.727 ±(99.9%) 0.004 ms/op
Iteration   2: 3.556 ±(99.9%) 0.004 ms/op
Iteration   3: 3.633 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.639 ±(99.9%) 1.563 ms/op [Average]
  (min, avg, max) = (3.556, 3.639, 3.727), stdev = 0.086
  CI (99.9%): [2.076, 5.202] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.003 ms/op
Iteration   1: 3.403 ±(99.9%) 0.003 ms/op
Iteration   2: 3.495 ±(99.9%) 0.002 ms/op
Iteration   3: 3.551 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.483 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (3.403, 3.483, 3.551), stdev = 0.075
  CI (99.9%): [2.119, 4.847] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.461 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.003 ms/op
Iteration   1: 3.715 ±(99.9%) 0.006 ms/op
Iteration   2: 3.752 ±(99.9%) 0.004 ms/op
Iteration   3: 3.629 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.699 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.629, 3.699, 3.752), stdev = 0.063
  CI (99.9%): [2.550, 4.848] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.463 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.351 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.018 ms/op
Iteration   1: 4.820 ±(99.9%) 0.013 ms/op
Iteration   2: 4.806 ±(99.9%) 0.031 ms/op
Iteration   3: 4.627 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.751 ±(99.9%) 1.963 ms/op [Average]
  (min, avg, max) = (4.627, 4.751, 4.820), stdev = 0.108
  CI (99.9%): [2.787, 6.714] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.747 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
Iteration   1: 3.696 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  14.231 ms/op
                 createUser·p0.9999: 19.082 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   2: 3.658 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  10.512 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   3: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  17.325 ms/op
                 createUser·p0.9999: 20.277 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263366
  mean =      3.645 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8120 
    [ 2.500,  5.000) = 247323 
    [ 5.000,  7.500) = 6880 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     19.715 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.943 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.008 ms/op
Iteration   1: 3.438 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   5.987 ms/op
                 existUser·p0.999:  9.436 ms/op
                 existUser·p0.9999: 17.183 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.515 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  12.550 ms/op
                 existUser·p0.9999: 16.286 ms/op
                 existUser·p1.00:   18.809 ms/op

Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 27.918 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277006
  mean =      3.463 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16460 
    [ 2.500,  5.000) = 253951 
    [ 5.000,  7.500) = 5621 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.432 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.009 ms/op
Iteration   1: 3.612 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  12.680 ms/op
                 getUser·p0.9999: 15.127 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 3.689 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  12.577 ms/op
                 getUser·p0.9999: 16.766 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.696 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  8.757 ms/op
                 getUser·p0.9999: 19.431 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261865
  mean =      3.665 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 7629 
    [ 2.500,  3.750) = 157291 
    [ 3.750,  5.000) = 88635 
    [ 5.000,  6.250) = 5729 
    [ 6.250,  7.500) = 1336 
    [ 7.500,  8.750) = 578 
    [ 8.750, 10.000) = 175 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     11.897 ms/op
     p(99.9900) =     18.803 ms/op
     p(99.9990) =     19.620 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 6.362 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.058 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.016 ms/op
Iteration   1: 4.772 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  14.989 ms/op
                 listUser·p0.9999: 17.822 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 4.729 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.078 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.668 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.496 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  20.799 ms/op
                 listUser·p0.9999: 31.266 ms/op
                 listUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203233
  mean =      4.723 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 259 
    [ 2.500,  5.000) = 158475 
    [ 5.000,  7.500) = 39367 
    [ 7.500, 10.000) = 4395 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.841 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     30.322 ms/op
     p(99.9990) =     31.650 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.784 ± 1.034  ops/ms
ClientGrpc.existUser                       thrpt       3   9.221 ± 0.883  ops/ms
ClientGrpc.getUser                         thrpt       3   8.679 ± 0.860  ops/ms
ClientGrpc.listUser                        thrpt       3   6.783 ± 1.986  ops/ms
ClientGrpc.createUser                       avgt       3   3.639 ± 1.563   ms/op
ClientGrpc.existUser                        avgt       3   3.483 ± 1.364   ms/op
ClientGrpc.getUser                          avgt       3   3.699 ± 1.149   ms/op
ClientGrpc.listUser                         avgt       3   4.751 ± 1.963   ms/op
ClientGrpc.createUser                     sample  263366   3.645 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.859           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.270           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.715           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  277006   3.463 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.722           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.011           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.657           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.213           ms/op
ClientGrpc.getUser                        sample  261865   3.665 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.838           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.897           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.803           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.694           ms/op
ClientGrpc.listUser                       sample  203233   4.723 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.141           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.351           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.322           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.818           ms/op
