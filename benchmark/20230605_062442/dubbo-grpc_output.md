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
# Warmup Iteration   1: 4.081 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.408 ±(99.9%) 0.924 ops/ms [Average]
  (min, avg, max) = (10.353, 10.408, 10.454), stdev = 0.051
  CI (99.9%): [9.484, 11.332] (assumes normal distribution)


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
# Warmup Iteration   1: 6.590 ops/ms
# Warmup Iteration   2: 9.851 ops/ms
# Warmup Iteration   3: 10.673 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 11.009 ops/ms
Iteration   3: 10.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.892 ±(99.9%) 2.428 ops/ms [Average]
  (min, avg, max) = (10.747, 10.892, 11.009), stdev = 0.133
  CI (99.9%): [8.463, 13.320] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.333 ops/ms
# Warmup Iteration   2: 9.869 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.180 ops/ms
Iteration   2: 10.622 ops/ms
Iteration   3: 10.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.335 ±(99.9%) 4.537 ops/ms [Average]
  (min, avg, max) = (10.180, 10.335, 10.622), stdev = 0.249
  CI (99.9%): [5.798, 14.872] (assumes normal distribution)


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
# Warmup Iteration   1: 5.090 ops/ms
# Warmup Iteration   2: 7.551 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 7.796 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.859 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (7.791, 7.859, 7.990), stdev = 0.114
  CI (99.9%): [5.784, 9.933] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.174 ±(99.9%) 0.002 ms/op
Iteration   2: 3.182 ±(99.9%) 0.002 ms/op
Iteration   3: 3.147 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.168 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.147, 3.168, 3.182), stdev = 0.019
  CI (99.9%): [2.829, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.009 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.967 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.935, 2.967, 2.988), stdev = 0.028
  CI (99.9%): [2.455, 3.478] (assumes normal distribution)


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.002 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.122 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.116 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.068, 3.116, 3.159), stdev = 0.046
  CI (99.9%): [2.280, 3.952] (assumes normal distribution)


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
# Warmup Iteration   1: 5.433 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.017 ms/op
Iteration   1: 4.165 ±(99.9%) 0.019 ms/op
Iteration   2: 4.204 ±(99.9%) 0.016 ms/op
Iteration   3: 4.179 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.183 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (4.165, 4.183, 4.204), stdev = 0.020
  CI (99.9%): [3.821, 4.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  10.255 ms/op
                 createUser·p0.9999: 14.972 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 23.888 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.637 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  12.016 ms/op
                 createUser·p0.9999: 32.079 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302662
  mean =      3.173 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13997 
    [ 2.500,  5.000) = 286505 
    [ 5.000,  7.500) = 1576 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     11.316 ms/op
     p(99.9900) =     31.219 ms/op
     p(99.9990) =     32.402 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 4.362 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.185 ms/op
                 existUser·p0.9999: 17.551 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 14.320 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.498 ms/op
                 existUser·p0.9999: 17.784 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322278
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1143 
    [ 1.250,  2.500) = 24610 
    [ 2.500,  3.750) = 283426 
    [ 3.750,  5.000) = 11765 
    [ 5.000,  6.250) = 714 
    [ 6.250,  7.500) = 364 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.321 ms/op
     p(99.9900) =     17.556 ms/op
     p(99.9990) =     18.539 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.006 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.471 ms/op
                 getUser·p0.9999: 13.057 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.869 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.371 ms/op
                 getUser·p0.999:  8.987 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305215
  mean =      3.144 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 9150 
    [ 2.500,  3.750) = 272219 
    [ 3.750,  5.000) = 21988 
    [ 5.000,  6.250) = 953 
    [ 6.250,  7.500) = 293 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.598 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.366 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.693 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.011 ms/op
Iteration   1: 4.242 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.458 ms/op
                 listUser·p0.9999: 20.331 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 4.172 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.303 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 4.187 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.158 ms/op
                 listUser·p0.9999: 22.130 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228500
  mean =      4.200 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1423 
    [ 2.500,  5.000) = 194909 
    [ 5.000,  7.500) = 29414 
    [ 7.500, 10.000) = 2031 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     22.784 ms/op
     p(99.9990) =     23.256 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.408 ± 0.924  ops/ms
ClientGrpc.existUser                       thrpt       3  10.892 ± 2.428  ops/ms
ClientGrpc.getUser                         thrpt       3  10.335 ± 4.537  ops/ms
ClientGrpc.listUser                        thrpt       3   7.859 ± 2.074  ops/ms
ClientGrpc.createUser                       avgt       3   3.168 ± 0.338   ms/op
ClientGrpc.existUser                        avgt       3   2.967 ± 0.512   ms/op
ClientGrpc.getUser                          avgt       3   3.116 ± 0.836   ms/op
ClientGrpc.listUser                         avgt       3   4.183 ± 0.362   ms/op
ClientGrpc.createUser                     sample  302662   3.173 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.637           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.316           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.219           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.571           ms/op
ClientGrpc.existUser                      sample  322278   2.981 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.321           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.556           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  305215   3.144 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.965           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.598           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.760           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.399           ms/op
ClientGrpc.listUser                       sample  228500   4.200 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.977           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.144           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.784           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.298           ms/op
