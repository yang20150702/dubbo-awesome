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
# Warmup Iteration   1: 3.328 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 8.487 ops/ms
Iteration   1: 8.695 ops/ms
Iteration   2: 8.707 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.837 ±(99.9%) 4.307 ops/ms [Average]
  (min, avg, max) = (8.695, 8.837, 9.109), stdev = 0.236
  CI (99.9%): [4.530, 13.144] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.312 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.252 ops/ms
Iteration   1: 9.136 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.327 ±(99.9%) 3.319 ops/ms [Average]
  (min, avg, max) = (9.136, 9.327, 9.498), stdev = 0.182
  CI (99.9%): [6.008, 12.646] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.857 ops/ms
# Warmup Iteration   2: 8.784 ops/ms
# Warmup Iteration   3: 8.836 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 8.658 ops/ms
Iteration   3: 8.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.753 ±(99.9%) 4.346 ops/ms [Average]
  (min, avg, max) = (8.577, 8.753, 9.024), stdev = 0.238
  CI (99.9%): [4.407, 13.099] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.187 ops/ms
# Warmup Iteration   2: 6.444 ops/ms
# Warmup Iteration   3: 6.735 ops/ms
Iteration   1: 6.810 ops/ms
Iteration   2: 6.949 ops/ms
Iteration   3: 6.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.821 ±(99.9%) 2.247 ops/ms [Average]
  (min, avg, max) = (6.703, 6.821, 6.949), stdev = 0.123
  CI (99.9%): [4.574, 9.068] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.982 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.004 ms/op
Iteration   1: 3.673 ±(99.9%) 0.002 ms/op
Iteration   2: 3.611 ±(99.9%) 0.002 ms/op
Iteration   3: 3.634 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.639 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.611, 3.639, 3.673), stdev = 0.031
  CI (99.9%): [3.070, 4.209] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.737 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.002 ms/op
Iteration   1: 3.401 ±(99.9%) 0.002 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.489 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.453 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.401, 3.453, 3.489), stdev = 0.046
  CI (99.9%): [2.609, 4.297] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.003 ms/op
Iteration   1: 3.713 ±(99.9%) 0.003 ms/op
Iteration   2: 3.930 ±(99.9%) 0.002 ms/op
Iteration   3: 3.805 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.816 ±(99.9%) 1.987 ms/op [Average]
  (min, avg, max) = (3.713, 3.816, 3.930), stdev = 0.109
  CI (99.9%): [1.829, 5.803] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.177 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.017 ms/op
Iteration   1: 4.668 ±(99.9%) 0.005 ms/op
Iteration   2: 4.613 ±(99.9%) 0.008 ms/op
Iteration   3: 4.732 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.671 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (4.613, 4.671, 4.732), stdev = 0.060
  CI (99.9%): [3.584, 5.759] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.138 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.009 ms/op
Iteration   1: 3.798 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  13.332 ms/op
                 createUser·p0.9999: 15.998 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   2: 3.622 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 16.031 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   3: 3.680 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  8.657 ms/op
                 createUser·p0.9999: 22.499 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259596
  mean =      3.699 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9765 
    [ 2.500,  5.000) = 240092 
    [ 5.000,  7.500) = 8960 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     11.646 ms/op
     p(99.9900) =     22.021 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.009 ms/op
Iteration   1: 3.621 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  11.033 ms/op
                 existUser·p0.9999: 15.521 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   2: 3.645 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  7.721 ms/op
                 existUser·p0.9999: 16.072 ms/op
                 existUser·p1.00:   16.253 ms/op

Iteration   3: 3.705 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  9.168 ms/op
                 existUser·p0.9999: 18.820 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262566
  mean =      3.657 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 6853 
    [ 2.500,  3.750) = 151214 
    [ 3.750,  5.000) = 97492 
    [ 5.000,  6.250) = 5225 
    [ 6.250,  7.500) = 834 
    [ 7.500,  8.750) = 364 
    [ 8.750, 10.000) = 169 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     18.374 ms/op
     p(99.9990) =     19.771 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.555 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.009 ms/op
Iteration   1: 3.775 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  12.752 ms/op
                 getUser·p0.9999: 15.368 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 3.764 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  9.618 ms/op
                 getUser·p0.9999: 17.285 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.482 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 19.638 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253191
  mean =      3.791 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7847 
    [ 2.500,  5.000) = 234262 
    [ 5.000,  7.500) = 10111 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      5.948 ms/op
     p(99.9000) =     10.024 ms/op
     p(99.9900) =     17.608 ms/op
     p(99.9990) =     20.019 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 6.452 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.010 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.016 ms/op
Iteration   1: 4.786 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   6.898 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  14.288 ms/op
                 listUser·p0.9999: 18.836 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.718 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  16.765 ms/op
                 listUser·p0.9999: 26.564 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   3: 4.720 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.668 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 22.952 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202478
  mean =      4.741 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 335 
    [ 2.500,  5.000) = 150780 
    [ 5.000,  7.500) = 46357 
    [ 7.500, 10.000) = 4277 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     15.524 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     28.796 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.837 ± 4.307  ops/ms
ClientGrpc.existUser                       thrpt       3   9.327 ± 3.319  ops/ms
ClientGrpc.getUser                         thrpt       3   8.753 ± 4.346  ops/ms
ClientGrpc.listUser                        thrpt       3   6.821 ± 2.247  ops/ms
ClientGrpc.createUser                       avgt       3   3.639 ± 0.569   ms/op
ClientGrpc.existUser                        avgt       3   3.453 ± 0.844   ms/op
ClientGrpc.getUser                          avgt       3   3.816 ± 1.987   ms/op
ClientGrpc.listUser                         avgt       3   4.671 ± 1.088   ms/op
ClientGrpc.createUser                     sample  259596   3.699 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.865           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.646           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.021           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.905           ms/op
ClientGrpc.existUser                      sample  262566   3.657 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.782           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.535           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.374           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  253191   3.791 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.482           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.948           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.948           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.024           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.608           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  202478   4.741 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.323           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.524           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
