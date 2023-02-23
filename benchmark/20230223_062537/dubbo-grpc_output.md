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
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 6.697 ops/ms
# Warmup Iteration   3: 7.551 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.911 ±(99.9%) 4.088 ops/ms [Average]
  (min, avg, max) = (7.715, 7.911, 8.156), stdev = 0.224
  CI (99.9%): [3.823, 11.999] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.804 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 8.455 ops/ms
Iteration   2: 8.899 ops/ms
Iteration   3: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.669 ±(99.9%) 4.056 ops/ms [Average]
  (min, avg, max) = (8.455, 8.669, 8.899), stdev = 0.222
  CI (99.9%): [4.613, 12.725] (assumes normal distribution)


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
# Warmup Iteration   1: 5.453 ops/ms
# Warmup Iteration   2: 7.922 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.014 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (7.931, 8.014, 8.160), stdev = 0.127
  CI (99.9%): [5.696, 10.332] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 6.138 ops/ms
# Warmup Iteration   3: 6.499 ops/ms
Iteration   1: 6.569 ops/ms
Iteration   2: 6.234 ops/ms
Iteration   3: 6.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.323 ±(99.9%) 3.927 ops/ms [Average]
  (min, avg, max) = (6.167, 6.323, 6.569), stdev = 0.215
  CI (99.9%): [2.396, 10.250] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.675 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.004 ms/op
Iteration   1: 3.767 ±(99.9%) 0.006 ms/op
Iteration   2: 3.822 ±(99.9%) 0.005 ms/op
Iteration   3: 3.808 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.799 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.767, 3.799, 3.822), stdev = 0.029
  CI (99.9%): [3.278, 4.320] (assumes normal distribution)


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.004 ms/op
Iteration   1: 3.791 ±(99.9%) 0.003 ms/op
Iteration   2: 3.729 ±(99.9%) 0.002 ms/op
Iteration   3: 3.771 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.764 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (3.729, 3.764, 3.791), stdev = 0.032
  CI (99.9%): [3.184, 4.343] (assumes normal distribution)


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
# Warmup Iteration   1: 5.634 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.003 ms/op
Iteration   1: 4.018 ±(99.9%) 0.004 ms/op
Iteration   2: 3.934 ±(99.9%) 0.003 ms/op
Iteration   3: 3.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.974 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.934, 3.974, 4.018), stdev = 0.042
  CI (99.9%): [3.209, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.889 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.976 ±(99.9%) 0.023 ms/op
Iteration   1: 4.777 ±(99.9%) 0.020 ms/op
Iteration   2: 4.901 ±(99.9%) 0.012 ms/op
Iteration   3: 4.907 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.862 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (4.777, 4.862, 4.907), stdev = 0.073
  CI (99.9%): [3.527, 6.196] (assumes normal distribution)


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
# Warmup Iteration   1: 5.448 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   5.014 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  12.523 ms/op
                 createUser·p0.9999: 21.857 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.897 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  9.745 ms/op
                 createUser·p0.9999: 22.898 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  23.170 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239748
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5242 
    [ 2.500,  5.000) = 211198 
    [ 5.000,  7.500) = 21909 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.406 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     26.582 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.011 ms/op
Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 16.109 ms/op
                 existUser·p1.00:   16.679 ms/op

Iteration   2: 3.689 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.624 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 16.853 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 3.650 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.917 ms/op
                 existUser·p0.9999: 17.954 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 257343
  mean =      3.729 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9961 
    [ 2.500,  5.000) = 233967 
    [ 5.000,  7.500) = 12316 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.239 ms/op
     p(99.9000) =     10.207 ms/op
     p(99.9900) =     17.540 ms/op
     p(99.9990) =     19.210 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.017 ms/op
Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  13.061 ms/op
                 getUser·p0.9999: 18.746 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  9.350 ms/op
                 getUser·p0.9999: 20.776 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 4.079 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  12.671 ms/op
                 getUser·p0.9999: 23.167 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 237644
  mean =      4.037 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6521 
    [ 2.500,  5.000) = 205009 
    [ 5.000,  7.500) = 24540 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.886 ms/op
     p(99.9000) =     11.956 ms/op
     p(99.9900) =     21.642 ms/op
     p(99.9990) =     23.458 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.855 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.553 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.943 ±(99.9%) 0.017 ms/op
Iteration   1: 4.926 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  16.061 ms/op
                 listUser·p0.9999: 17.286 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 4.889 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  18.006 ms/op
                 listUser·p0.9999: 29.273 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   3: 5.056 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.470 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.758 ms/op
                 listUser·p0.95:   7.635 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  21.556 ms/op
                 listUser·p0.9999: 30.191 ms/op
                 listUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 193567
  mean =      4.956 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 487 
    [ 2.500,  5.000) = 127181 
    [ 5.000,  7.500) = 56988 
    [ 7.500, 10.000) = 7661 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     17.316 ms/op
     p(99.9900) =     29.292 ms/op
     p(99.9990) =     30.496 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.911 ± 4.088  ops/ms
ClientGrpc.existUser                       thrpt       3   8.669 ± 4.056  ops/ms
ClientGrpc.getUser                         thrpt       3   8.014 ± 2.318  ops/ms
ClientGrpc.listUser                        thrpt       3   6.323 ± 3.927  ops/ms
ClientGrpc.createUser                       avgt       3   3.799 ± 0.521   ms/op
ClientGrpc.existUser                        avgt       3   3.764 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.974 ± 0.765   ms/op
ClientGrpc.listUser                         avgt       3   4.862 ± 1.335   ms/op
ClientGrpc.createUser                     sample  239748   4.004 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.834           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.660           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.821           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  257343   3.729 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.805           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.239           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.207           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.540           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  237644   4.037 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.886           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.956           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.642           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.527           ms/op
ClientGrpc.listUser                       sample  193567   4.956 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.149           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.406           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.355           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.316           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.292           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.293           ms/op
