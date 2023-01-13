# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.657 ops/ms
Iteration   3: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.620 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (8.562, 8.620, 8.657), stdev = 0.051
  CI (99.9%): [7.687, 9.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.670 ops/ms
# Warmup Iteration   2: 8.298 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 8.878 ops/ms
Iteration   2: 8.891 ops/ms
Iteration   3: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.850 ±(99.9%) 1.101 ops/ms [Average]
  (min, avg, max) = (8.781, 8.850, 8.891), stdev = 0.060
  CI (99.9%): [7.749, 9.951] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.969 ops/ms
# Warmup Iteration   2: 8.126 ops/ms
# Warmup Iteration   3: 8.051 ops/ms
Iteration   1: 8.624 ops/ms
Iteration   2: 8.488 ops/ms
Iteration   3: 8.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.599 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (8.488, 8.599, 8.686), stdev = 0.102
  CI (99.9%): [6.747, 10.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 6.139 ops/ms
# Warmup Iteration   3: 6.578 ops/ms
Iteration   1: 6.672 ops/ms
Iteration   2: 7.001 ops/ms
Iteration   3: 7.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.901 ±(99.9%) 3.629 ops/ms [Average]
  (min, avg, max) = (6.672, 6.901, 7.031), stdev = 0.199
  CI (99.9%): [3.272, 10.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.004 ms/op
Iteration   1: 3.718 ±(99.9%) 0.003 ms/op
Iteration   2: 3.852 ±(99.9%) 0.002 ms/op
Iteration   3: 3.659 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.743 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (3.659, 3.743, 3.852), stdev = 0.099
  CI (99.9%): [1.937, 5.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.148 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.004 ms/op
Iteration   1: 3.754 ±(99.9%) 0.004 ms/op
Iteration   2: 3.653 ±(99.9%) 0.003 ms/op
Iteration   3: 3.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.659 ±(99.9%) 1.685 ms/op [Average]
  (min, avg, max) = (3.570, 3.659, 3.754), stdev = 0.092
  CI (99.9%): [1.974, 5.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.415 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.015 ms/op
Iteration   1: 3.732 ±(99.9%) 0.004 ms/op
Iteration   2: 3.670 ±(99.9%) 0.003 ms/op
Iteration   3: 3.557 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.653 ±(99.9%) 1.621 ms/op [Average]
  (min, avg, max) = (3.557, 3.653, 3.732), stdev = 0.089
  CI (99.9%): [2.031, 5.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.938 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.011 ms/op
Iteration   1: 4.584 ±(99.9%) 0.020 ms/op
Iteration   2: 4.638 ±(99.9%) 0.014 ms/op
Iteration   3: 4.660 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.627 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (4.584, 4.627, 4.660), stdev = 0.039
  CI (99.9%): [3.913, 5.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.630 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.011 ms/op
Iteration   1: 3.759 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  10.129 ms/op
                 createUser·p0.9999: 14.826 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  10.096 ms/op
                 createUser·p0.9999: 14.727 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   3: 3.695 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  14.063 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255969
  mean =      3.749 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8396 
    [ 2.500,  5.000) = 239435 
    [ 5.000,  7.500) = 7393 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     21.670 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.009 ms/op
Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 23.312 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.561 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   3.527 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  8.049 ms/op
                 existUser·p0.9999: 20.842 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 3.603 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 18.600 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266384
  mean =      3.601 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8290 
    [ 2.500,  5.000) = 253419 
    [ 5.000,  7.500) = 3746 
    [ 7.500, 10.000) = 408 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     13.052 ms/op
     p(99.9900) =     22.470 ms/op
     p(99.9990) =     23.681 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.330 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.669 ms/op
                 getUser·p0.999:  12.069 ms/op
                 getUser·p0.9999: 25.941 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 3.851 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  9.825 ms/op
                 getUser·p0.9999: 24.752 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.729 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.372 ms/op
                 getUser·p0.9999: 30.062 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250599
  mean =      3.830 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6882 
    [ 2.500,  5.000) = 230922 
    [ 5.000,  7.500) = 11648 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     10.951 ms/op
     p(99.9900) =     28.275 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.341 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.051 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.013 ms/op
Iteration   1: 4.760 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.873 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.658 ms/op
                 listUser·p0.9999: 25.594 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 4.753 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 25.601 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   3: 5.126 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  20.147 ms/op
                 listUser·p0.9999: 22.299 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197013
  mean =      4.873 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 138650 
    [ 5.000,  7.500) = 51303 
    [ 7.500, 10.000) = 5928 
    [10.000, 12.500) = 534 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     17.432 ms/op
     p(99.9900) =     25.438 ms/op
     p(99.9990) =     26.346 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.620 ± 0.933  ops/ms
ClientGrpc.existUser                       thrpt       3   8.850 ± 1.101  ops/ms
ClientGrpc.getUser                         thrpt       3   8.599 ± 1.852  ops/ms
ClientGrpc.listUser                        thrpt       3   6.901 ± 3.629  ops/ms
ClientGrpc.createUser                       avgt       3   3.743 ± 1.806   ms/op
ClientGrpc.existUser                        avgt       3   3.659 ± 1.685   ms/op
ClientGrpc.getUser                          avgt       3   3.653 ± 1.621   ms/op
ClientGrpc.listUser                         avgt       3   4.627 ± 0.714   ms/op
ClientGrpc.createUser                     sample  255969   3.749 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.817           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.764           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.972           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  266384   3.601 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.612           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.052           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.470           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.822           ms/op
ClientGrpc.getUser                        sample  250599   3.830 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.773           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.316           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.951           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.275           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.474           ms/op
ClientGrpc.listUser                       sample  197013   4.873 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.316           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.798           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.432           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.438           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
