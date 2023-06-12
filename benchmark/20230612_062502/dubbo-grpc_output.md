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
# Warmup Iteration   1: 4.059 ops/ms
# Warmup Iteration   2: 9.206 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.594 ±(99.9%) 3.295 ops/ms [Average]
  (min, avg, max) = (10.400, 10.594, 10.757), stdev = 0.181
  CI (99.9%): [7.299, 13.889] (assumes normal distribution)


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
# Warmup Iteration   1: 7.219 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.883 ops/ms
Iteration   1: 11.121 ops/ms
Iteration   2: 11.086 ops/ms
Iteration   3: 11.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.089 ±(99.9%) 0.568 ops/ms [Average]
  (min, avg, max) = (11.059, 11.089, 11.121), stdev = 0.031
  CI (99.9%): [10.520, 11.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.993 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.377 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.454 ±(99.9%) 0.303 ops/ms [Average]
  (min, avg, max) = (10.440, 10.454, 10.472), stdev = 0.017
  CI (99.9%): [10.151, 10.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.005 ops/ms
# Warmup Iteration   2: 7.546 ops/ms
# Warmup Iteration   3: 7.876 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.848 ±(99.9%) 0.777 ops/ms [Average]
  (min, avg, max) = (7.800, 7.848, 7.880), stdev = 0.043
  CI (99.9%): [7.071, 8.625] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.076 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.062, 3.076, 3.088), stdev = 0.013
  CI (99.9%): [2.832, 3.321] (assumes normal distribution)


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.944 ±(99.9%) 0.001 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.944, 2.955, 2.967), stdev = 0.012
  CI (99.9%): [2.737, 3.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.002 ms/op
Iteration   1: 3.082 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 3.087 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (2.990, 3.053, 3.087), stdev = 0.054
  CI (99.9%): [2.062, 4.044] (assumes normal distribution)


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
# Warmup Iteration   1: 5.876 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.016 ms/op
Iteration   1: 4.071 ±(99.9%) 0.011 ms/op
Iteration   2: 4.070 ±(99.9%) 0.022 ms/op
Iteration   3: 4.046 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.062 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (4.046, 4.062, 4.071), stdev = 0.014
  CI (99.9%): [3.800, 4.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.635 ms/op
                 createUser·p0.9999: 18.108 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   2: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.625 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.699 ms/op
                 createUser·p0.9999: 19.106 ms/op
                 createUser·p1.00:   19.628 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 20.823 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313625
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22051 
    [ 2.500,  5.000) = 290080 
    [ 5.000,  7.500) = 1189 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.376 ms/op
     p(99.9900) =     19.801 ms/op
     p(99.9990) =     21.192 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.579 ms/op
                 existUser·p0.9999: 19.271 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  6.246 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   3: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  11.168 ms/op
                 existUser·p0.9999: 16.878 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330398
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1939 
    [ 1.250,  2.500) = 32689 
    [ 2.500,  3.750) = 288841 
    [ 3.750,  5.000) = 5860 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.075 ms/op
     p(99.9900) =     18.545 ms/op
     p(99.9990) =     19.543 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  7.581 ms/op
                 getUser·p0.9999: 13.024 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.919 ms/op
                 getUser·p0.9999: 22.089 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.480 ms/op
                 getUser·p0.9999: 16.105 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312170
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18671 
    [ 2.500,  5.000) = 291451 
    [ 5.000,  7.500) = 1747 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =     21.285 ms/op
     p(99.9990) =     22.377 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 5.842 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.011 ms/op
Iteration   1: 4.073 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.868 ms/op
                 listUser·p0.9999: 20.396 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.713 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  19.973 ms/op
                 listUser·p0.9999: 28.664 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235204
  mean =      4.084 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1871 
    [ 2.500,  5.000) = 206265 
    [ 5.000,  7.500) = 25438 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     14.857 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     29.019 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.594 ± 3.295  ops/ms
ClientGrpc.existUser                       thrpt       3  11.089 ± 0.568  ops/ms
ClientGrpc.getUser                         thrpt       3  10.454 ± 0.303  ops/ms
ClientGrpc.listUser                        thrpt       3   7.848 ± 0.777  ops/ms
ClientGrpc.createUser                       avgt       3   3.076 ± 0.245   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.218   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.991   ms/op
ClientGrpc.listUser                         avgt       3   4.062 ± 0.262   ms/op
ClientGrpc.createUser                     sample  313625   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.625           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.376           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.801           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.332           ms/op
ClientGrpc.existUser                      sample  330398   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.075           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.545           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  312170   3.075 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.589           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.285           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  235204   4.084 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.284           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.857           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.164           ms/op
