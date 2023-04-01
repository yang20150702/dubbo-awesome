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
# Warmup Iteration   1: 3.898 ops/ms
# Warmup Iteration   2: 8.844 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.770 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.659 ±(99.9%) 2.461 ops/ms [Average]
  (min, avg, max) = (10.509, 10.659, 10.770), stdev = 0.135
  CI (99.9%): [8.198, 13.120] (assumes normal distribution)


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
# Warmup Iteration   1: 7.467 ops/ms
# Warmup Iteration   2: 10.566 ops/ms
# Warmup Iteration   3: 11.026 ops/ms
Iteration   1: 11.057 ops/ms
Iteration   2: 10.893 ops/ms
Iteration   3: 11.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.019 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (10.893, 11.019, 11.109), stdev = 0.113
  CI (99.9%): [8.959, 13.080] (assumes normal distribution)


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
# Warmup Iteration   1: 6.792 ops/ms
# Warmup Iteration   2: 10.148 ops/ms
# Warmup Iteration   3: 10.601 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.633 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.631 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (10.596, 10.631, 10.664), stdev = 0.034
  CI (99.9%): [10.009, 11.253] (assumes normal distribution)


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
# Warmup Iteration   1: 5.297 ops/ms
# Warmup Iteration   2: 7.807 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 8.052 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.074 ±(99.9%) 0.385 ops/ms [Average]
  (min, avg, max) = (8.052, 8.074, 8.094), stdev = 0.021
  CI (99.9%): [7.689, 8.459] (assumes normal distribution)


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
# Warmup Iteration   1: 4.235 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.007 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (2.970, 3.006, 3.026), stdev = 0.031
  CI (99.9%): [2.441, 3.571] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.818 ±(99.9%) 0.003 ms/op
Iteration   1: 2.887 ±(99.9%) 0.002 ms/op
Iteration   2: 2.866 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.888 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (2.866, 2.888, 2.913), stdev = 0.023
  CI (99.9%): [2.461, 3.316] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.008 ±(99.9%) 0.003 ms/op
Iteration   2: 2.994 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.990 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.969, 2.990, 3.008), stdev = 0.020
  CI (99.9%): [2.624, 3.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.016 ms/op
Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
Iteration   2: 3.996 ±(99.9%) 0.015 ms/op
Iteration   3: 4.025 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.996, 4.016, 4.026), stdev = 0.017
  CI (99.9%): [3.707, 4.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.081 ms/op
                 createUser·p0.9999: 15.864 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.851 ms/op
                 createUser·p0.9999: 17.980 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.234 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319259
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27816 
    [ 2.500,  5.000) = 289965 
    [ 5.000,  7.500) = 1138 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.797 ms/op
     p(99.9900) =     23.726 ms/op
     p(99.9990) =     24.334 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.044 ms/op
                 existUser·p0.9999: 18.936 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 14.910 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.000 ms/op
                 existUser·p0.9999: 23.213 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330842
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39831 
    [ 2.500,  5.000) = 289643 
    [ 5.000,  7.500) = 1120 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     19.557 ms/op
     p(99.9990) =     23.648 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.428 ms/op
                 getUser·p0.9999: 12.949 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.229 ms/op
                 getUser·p0.9999: 16.284 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.816 ms/op
                 getUser·p0.9999: 20.759 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317362
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23064 
    [ 2.500,  5.000) = 292596 
    [ 5.000,  7.500) = 1425 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =     19.016 ms/op
     p(99.9990) =     21.130 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 5.244 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.252 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.012 ms/op
Iteration   1: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.714 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.926 ms/op
                 listUser·p0.9999: 22.127 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.039 ms/op
                 listUser·p0.999:  15.709 ms/op
                 listUser·p0.9999: 20.501 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 26.486 ms/op
                 listUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239610
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2511 
    [ 2.500,  5.000) = 211822 
    [ 5.000,  7.500) = 23941 
    [ 7.500, 10.000) = 855 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.757 ms/op
     p(99.9900) =     25.594 ms/op
     p(99.9990) =     27.159 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.659 ± 2.461  ops/ms
ClientGrpc.existUser                       thrpt       3  11.019 ± 2.061  ops/ms
ClientGrpc.getUser                         thrpt       3  10.631 ± 0.622  ops/ms
ClientGrpc.listUser                        thrpt       3   8.074 ± 0.385  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.565   ms/op
ClientGrpc.existUser                        avgt       3   2.888 ± 0.427   ms/op
ClientGrpc.getUser                          avgt       3   2.990 ± 0.366   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.309   ms/op
ClientGrpc.createUser                     sample  319259   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.596           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.797           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.445           ms/op
ClientGrpc.existUser                      sample  330842   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.614           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.865           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.557           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.822           ms/op
ClientGrpc.getUser                        sample  317362   3.023 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.738           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.016           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.398           ms/op
ClientGrpc.listUser                       sample  239610   4.006 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.180           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.757           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.594           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
