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
# Warmup Iteration   1: 3.958 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.958 ops/ms
Iteration   1: 10.182 ops/ms
Iteration   2: 10.322 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.328 ±(99.9%) 2.727 ops/ms [Average]
  (min, avg, max) = (10.182, 10.328, 10.480), stdev = 0.149
  CI (99.9%): [7.601, 13.055] (assumes normal distribution)


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
# Warmup Iteration   1: 7.404 ops/ms
# Warmup Iteration   2: 10.401 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 11.215 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 11.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.123 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (11.075, 11.123, 11.215), stdev = 0.080
  CI (99.9%): [9.670, 12.576] (assumes normal distribution)


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
# Warmup Iteration   2: 10.033 ops/ms
# Warmup Iteration   3: 10.738 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.564 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (10.498, 10.564, 10.609), stdev = 0.058
  CI (99.9%): [9.498, 11.630] (assumes normal distribution)


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
# Warmup Iteration   1: 5.749 ops/ms
# Warmup Iteration   2: 7.765 ops/ms
# Warmup Iteration   3: 8.068 ops/ms
Iteration   1: 8.325 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.229 ±(99.9%) 1.595 ops/ms [Average]
  (min, avg, max) = (8.154, 8.229, 8.325), stdev = 0.087
  CI (99.9%): [6.633, 9.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.396 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.026 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.017, 3.026, 3.033), stdev = 0.008
  CI (99.9%): [2.879, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.002 ms/op
Iteration   1: 2.917 ±(99.9%) 0.003 ms/op
Iteration   2: 2.874 ±(99.9%) 0.003 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.874, 2.898, 2.917), stdev = 0.022
  CI (99.9%): [2.499, 3.296] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.005 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.004 ms/op
Iteration   3: 3.027 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.025 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.010, 3.025, 3.039), stdev = 0.015
  CI (99.9%): [2.759, 3.292] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.771 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.009 ms/op
Iteration   1: 4.000 ±(99.9%) 0.017 ms/op
Iteration   2: 3.927 ±(99.9%) 0.035 ms/op
Iteration   3: 3.877 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 1.130 ms/op [Average]
  (min, avg, max) = (3.877, 3.935, 4.000), stdev = 0.062
  CI (99.9%): [2.805, 5.065] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.875 ms/op
                 createUser·p0.9999: 15.938 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.510 ms/op
                 createUser·p0.9999: 14.201 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  10.522 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318027
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24832 
    [ 2.500,  5.000) = 291641 
    [ 5.000,  7.500) = 1096 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.682 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     24.636 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  6.350 ms/op
                 existUser·p0.9999: 17.597 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.699 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   3: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 16.237 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331178
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 477 
    [ 1.250,  2.500) = 35318 
    [ 2.500,  3.750) = 288517 
    [ 3.750,  5.000) = 6057 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 312 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      6.742 ms/op
     p(99.9900) =     16.104 ms/op
     p(99.9990) =     17.959 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.602 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.663 ms/op
                 getUser·p0.9999: 15.184 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.849 ms/op
                 getUser·p0.9999: 17.888 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316230
  mean =      3.033 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 590 
    [ 1.250,  2.500) = 19956 
    [ 2.500,  3.750) = 278841 
    [ 3.750,  5.000) = 15248 
    [ 5.000,  6.250) = 880 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.106 ms/op
     p(99.9900) =     16.253 ms/op
     p(99.9990) =     18.143 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.540 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.306 ms/op
                 listUser·p0.9999: 19.589 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.806 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.913 ms/op
                 listUser·p0.999:  16.367 ms/op
                 listUser·p0.9999: 28.921 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.263 ms/op
                 listUser·p0.9999: 25.063 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247202
  mean =      3.880 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4073 
    [ 2.500,  5.000) = 222591 
    [ 5.000,  7.500) = 19191 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.856 ms/op
     p(99.9900) =     26.682 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.328 ± 2.727  ops/ms
ClientGrpc.existUser                       thrpt       3  11.123 ± 1.453  ops/ms
ClientGrpc.getUser                         thrpt       3  10.564 ± 1.066  ops/ms
ClientGrpc.listUser                        thrpt       3   8.229 ± 1.595  ops/ms
ClientGrpc.createUser                       avgt       3   3.026 ± 0.147   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.398   ms/op
ClientGrpc.getUser                          avgt       3   3.025 ± 0.266   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 1.130   ms/op
ClientGrpc.createUser                     sample  318027   3.019 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.682           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.593           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  331178   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  316230   3.033 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.106           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.253           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  247202   3.880 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.540           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.856           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.682           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.360           ms/op
