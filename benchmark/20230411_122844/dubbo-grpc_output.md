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
# Warmup Iteration   1: 2.701 ops/ms
# Warmup Iteration   2: 6.191 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.756 ops/ms
Iteration   3: 7.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.629 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (7.409, 7.629, 7.756), stdev = 0.192
  CI (99.9%): [4.131, 11.128] (assumes normal distribution)


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
# Warmup Iteration   1: 4.944 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 8.238 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.211 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.253 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (8.149, 8.253, 8.398), stdev = 0.130
  CI (99.9%): [5.887, 10.618] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.231 ops/ms
# Warmup Iteration   2: 7.104 ops/ms
# Warmup Iteration   3: 7.710 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 8.008 ops/ms
Iteration   3: 7.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.996 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (7.867, 7.996, 8.114), stdev = 0.124
  CI (99.9%): [5.737, 10.255] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ops/ms
# Warmup Iteration   2: 5.459 ops/ms
# Warmup Iteration   3: 5.806 ops/ms
Iteration   1: 5.786 ops/ms
Iteration   2: 5.888 ops/ms
Iteration   3: 5.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.825 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (5.786, 5.825, 5.888), stdev = 0.055
  CI (99.9%): [4.813, 6.836] (assumes normal distribution)


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
# Warmup Iteration   1: 5.924 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.002 ms/op
Iteration   1: 3.765 ±(99.9%) 0.003 ms/op
Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
Iteration   3: 3.826 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.774 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.730, 3.774, 3.826), stdev = 0.049
  CI (99.9%): [2.887, 4.661] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.002 ms/op
Iteration   1: 4.056 ±(99.9%) 0.002 ms/op
Iteration   2: 3.936 ±(99.9%) 0.003 ms/op
Iteration   3: 3.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.991 ±(99.9%) 1.110 ms/op [Average]
  (min, avg, max) = (3.936, 3.991, 4.056), stdev = 0.061
  CI (99.9%): [2.881, 5.101] (assumes normal distribution)


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
# Warmup Iteration   1: 5.858 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.873 ±(99.9%) 0.004 ms/op
Iteration   2: 3.879 ±(99.9%) 0.002 ms/op
Iteration   3: 3.755 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.836 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.755, 3.836, 3.879), stdev = 0.070
  CI (99.9%): [2.556, 5.115] (assumes normal distribution)


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
# Warmup Iteration   1: 7.317 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.838 ±(99.9%) 0.021 ms/op
Iteration   1: 4.641 ±(99.9%) 0.024 ms/op
Iteration   2: 4.710 ±(99.9%) 0.017 ms/op
Iteration   3: 4.737 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.696 ±(99.9%) 0.903 ms/op [Average]
  (min, avg, max) = (4.641, 4.696, 4.737), stdev = 0.049
  CI (99.9%): [3.794, 5.599] (assumes normal distribution)


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
# Warmup Iteration   1: 5.649 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.010 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  11.142 ms/op
                 createUser·p0.9999: 16.214 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.823 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.367 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 23.548 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.724 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  10.882 ms/op
                 createUser·p0.9999: 17.643 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253552
  mean =      3.785 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7277 
    [ 2.500,  5.000) = 231426 
    [ 5.000,  7.500) = 13893 
    [ 7.500, 10.000) = 598 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     23.045 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
Iteration   1: 3.453 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  11.274 ms/op
                 existUser·p0.9999: 16.039 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   2: 3.545 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.098 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.496 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  10.204 ms/op
                 existUser·p0.9999: 19.262 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274487
  mean =      3.498 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11221 
    [ 2.500,  5.000) = 256740 
    [ 5.000,  7.500) = 5933 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     19.417 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 5.689 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
Iteration   1: 3.757 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.528 ms/op
                 getUser·p0.999:  10.041 ms/op
                 getUser·p0.9999: 24.068 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  9.924 ms/op
                 getUser·p0.9999: 18.982 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.689 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  11.595 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259045
  mean =      3.704 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9067 
    [ 2.500,  5.000) = 237448 
    [ 5.000,  7.500) = 11345 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     10.649 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     33.352 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 6.676 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.403 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.035 ±(99.9%) 0.016 ms/op
Iteration   1: 4.794 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.111 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 17.902 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 4.848 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  18.798 ms/op
                 listUser·p0.9999: 23.186 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 4.943 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  19.180 ms/op
                 listUser·p0.9999: 22.190 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197572
  mean =      4.861 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 477 
    [ 2.500,  5.000) = 131187 
    [ 5.000,  7.500) = 59524 
    [ 7.500, 10.000) = 5320 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      6.988 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     17.283 ms/op
     p(99.9900) =     22.683 ms/op
     p(99.9990) =     26.150 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.629 ± 3.499  ops/ms
ClientGrpc.existUser                       thrpt       3   8.253 ± 2.365  ops/ms
ClientGrpc.getUser                         thrpt       3   7.996 ± 2.259  ops/ms
ClientGrpc.listUser                        thrpt       3   5.825 ± 1.011  ops/ms
ClientGrpc.createUser                       avgt       3   3.774 ± 0.887   ms/op
ClientGrpc.existUser                        avgt       3   3.991 ± 1.110   ms/op
ClientGrpc.getUser                          avgt       3   3.836 ± 1.280   ms/op
ClientGrpc.listUser                         avgt       3   4.696 ± 0.903   ms/op
ClientGrpc.createUser                     sample  253552   3.785 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.854           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.087           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.185           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.190           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.045           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  274487   3.498 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.333           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.830           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.183           ms/op
ClientGrpc.getUser                        sample  259045   3.704 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.756           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.242           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.649           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.015           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.423           ms/op
ClientGrpc.listUser                       sample  197572   4.861 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.354           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.160           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.995           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.283           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.683           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
