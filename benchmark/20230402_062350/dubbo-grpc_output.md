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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 9.137 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.652 ±(99.9%) 2.687 ops/ms [Average]
  (min, avg, max) = (10.488, 10.652, 10.773), stdev = 0.147
  CI (99.9%): [7.965, 13.339] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.870 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.915 ops/ms
Iteration   1: 11.032 ops/ms
Iteration   2: 10.948 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.993 ±(99.9%) 0.773 ops/ms [Average]
  (min, avg, max) = (10.948, 10.993, 11.032), stdev = 0.042
  CI (99.9%): [10.220, 11.766] (assumes normal distribution)


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
# Warmup Iteration   1: 6.794 ops/ms
# Warmup Iteration   2: 10.051 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.628 ±(99.9%) 1.565 ops/ms [Average]
  (min, avg, max) = (10.575, 10.628, 10.727), stdev = 0.086
  CI (99.9%): [9.063, 12.193] (assumes normal distribution)


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
# Warmup Iteration   1: 5.820 ops/ms
# Warmup Iteration   2: 7.409 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 0.797 ops/ms [Average]
  (min, avg, max) = (7.879, 7.926, 7.966), stdev = 0.044
  CI (99.9%): [7.129, 8.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.010 ms/op
Iteration   1: 3.044 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.001 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.031 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.007, 3.031, 3.044), stdev = 0.021
  CI (99.9%): [2.641, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.912 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.890, 2.913, 2.937), stdev = 0.024
  CI (99.9%): [2.482, 3.343] (assumes normal distribution)


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.001, 3.045, 3.070), stdev = 0.038
  CI (99.9%): [2.343, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 5.745 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.013 ms/op
Iteration   1: 4.023 ±(99.9%) 0.008 ms/op
Iteration   2: 4.142 ±(99.9%) 0.009 ms/op
Iteration   3: 3.985 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.050 ±(99.9%) 1.486 ms/op [Average]
  (min, avg, max) = (3.985, 4.050, 4.142), stdev = 0.081
  CI (99.9%): [2.564, 5.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  11.280 ms/op
                 createUser·p0.9999: 14.794 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.180 ms/op
                 createUser·p0.999:  10.830 ms/op
                 createUser·p0.9999: 18.377 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315365
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 586 
    [ 1.250,  2.500) = 21811 
    [ 2.500,  3.750) = 273843 
    [ 3.750,  5.000) = 17782 
    [ 5.000,  6.250) = 583 
    [ 6.250,  7.500) = 279 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     18.201 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  7.588 ms/op
                 existUser·p0.9999: 14.356 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.020 ms/op
                 existUser·p0.9999: 16.450 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.504 ms/op
                 existUser·p0.9999: 16.749 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327367
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1106 
    [ 1.250,  2.500) = 34134 
    [ 2.500,  3.750) = 281886 
    [ 3.750,  5.000) = 9315 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.367 ms/op
     p(99.9900) =     16.421 ms/op
     p(99.9990) =     18.615 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.080 ms/op
                 getUser·p0.9999: 13.255 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   2: 3.254 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.054 ms/op
                 getUser·p0.999:  13.544 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.542 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  10.274 ms/op
                 getUser·p0.9999: 16.699 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308027
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14358 
    [ 2.500,  5.000) = 289751 
    [ 5.000,  7.500) = 3271 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     19.477 ms/op
     p(99.9990) =     20.182 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 5.424 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.010 ms/op
Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.096 ms/op
                 listUser·p0.999:  12.902 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  14.283 ms/op
                 listUser·p0.9999: 18.516 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.940 ms/op
                 listUser·p0.999:  16.870 ms/op
                 listUser·p0.9999: 20.390 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237177
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2521 
    [ 2.500,  5.000) = 211616 
    [ 5.000,  7.500) = 21667 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.412 ms/op
     p(99.9900) =     19.286 ms/op
     p(99.9990) =     20.837 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.652 ± 2.687  ops/ms
ClientGrpc.existUser                       thrpt       3  10.993 ± 0.773  ops/ms
ClientGrpc.getUser                         thrpt       3  10.628 ± 1.565  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 0.797  ops/ms
ClientGrpc.createUser                       avgt       3   3.031 ± 0.391   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.430   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.702   ms/op
ClientGrpc.listUser                         avgt       3   4.050 ± 1.486   ms/op
ClientGrpc.createUser                     sample  315365   3.043 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.576           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.945           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.201           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.333           ms/op
ClientGrpc.existUser                      sample  327367   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.329           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.367           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  308027   3.117 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.420           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.354           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.477           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  237177   4.045 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.862           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.412           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.286           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
