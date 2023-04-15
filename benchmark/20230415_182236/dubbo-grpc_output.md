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
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 10.459 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.667 ±(99.9%) 2.876 ops/ms [Average]
  (min, avg, max) = (10.486, 10.667, 10.771), stdev = 0.158
  CI (99.9%): [7.791, 13.543] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 10.916 ops/ms
# Warmup Iteration   3: 11.470 ops/ms
Iteration   1: 11.253 ops/ms
Iteration   2: 11.406 ops/ms
Iteration   3: 10.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.205 ±(99.9%) 4.172 ops/ms [Average]
  (min, avg, max) = (10.956, 11.205, 11.406), stdev = 0.229
  CI (99.9%): [7.033, 15.377] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.097 ops/ms
# Warmup Iteration   2: 10.503 ops/ms
# Warmup Iteration   3: 10.549 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.635 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (10.547, 10.635, 10.731), stdev = 0.092
  CI (99.9%): [8.948, 12.322] (assumes normal distribution)


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
# Warmup Iteration   1: 5.474 ops/ms
# Warmup Iteration   2: 8.006 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.116 ops/ms
Iteration   2: 8.070 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.078 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (8.048, 8.078, 8.116), stdev = 0.035
  CI (99.9%): [7.441, 8.716] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 2.976 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.976, 3.005, 3.027), stdev = 0.026
  CI (99.9%): [2.529, 3.480] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.904 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.003 ms/op
Iteration   1: 2.873 ±(99.9%) 0.004 ms/op
Iteration   2: 2.908 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.889 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.873, 2.889, 2.908), stdev = 0.018
  CI (99.9%): [2.560, 3.218] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.033 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (2.974, 3.005, 3.025), stdev = 0.027
  CI (99.9%): [2.512, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.021 ms/op
Iteration   1: 3.939 ±(99.9%) 0.030 ms/op
Iteration   2: 3.892 ±(99.9%) 0.011 ms/op
Iteration   3: 3.947 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.926 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.892, 3.926, 3.947), stdev = 0.030
  CI (99.9%): [3.385, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.340 ms/op
                 createUser·p0.9999: 11.092 ms/op
                 createUser·p1.00:   11.567 ms/op

Iteration   2: 2.943 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.860 ms/op
                 createUser·p0.9999: 12.833 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.036 ms/op
                 createUser·p0.9999: 16.118 ms/op
                 createUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324623
  mean =      2.956 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1867 
    [ 1.250,  2.500) = 32357 
    [ 2.500,  3.750) = 275309 
    [ 3.750,  5.000) = 13685 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.657 ms/op
     p(99.9900) =     14.206 ms/op
     p(99.9990) =     16.519 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  5.829 ms/op
                 existUser·p0.9999: 11.304 ms/op
                 existUser·p1.00:   11.583 ms/op

Iteration   2: 2.844 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.390 ms/op
                 existUser·p0.9999: 16.704 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 2.878 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.518 ms/op
                 existUser·p0.9999: 22.512 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333981
  mean =      2.873 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54444 
    [ 2.500,  5.000) = 278367 
    [ 5.000,  7.500) = 795 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     22.686 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.726 ms/op
                 getUser·p0.9999: 19.874 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 15.275 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  6.578 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320344
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23193 
    [ 2.500,  5.000) = 296133 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.616 ms/op
     p(99.9900) =     27.883 ms/op
     p(99.9990) =     28.625 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
Iteration   1: 3.916 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.437 ms/op
                 listUser·p0.9999: 18.606 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  16.180 ms/op
                 listUser·p0.9999: 23.505 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 3.779 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.705 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 22.678 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248143
  mean =      3.868 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6263 
    [ 2.500,  5.000) = 220144 
    [ 5.000,  7.500) = 20701 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     16.145 ms/op
     p(99.9900) =     23.140 ms/op
     p(99.9990) =     24.070 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.667 ± 2.876  ops/ms
ClientGrpc.existUser                       thrpt       3  11.205 ± 4.172  ops/ms
ClientGrpc.getUser                         thrpt       3  10.635 ± 1.687  ops/ms
ClientGrpc.listUser                        thrpt       3   8.078 ± 0.638  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   2.889 ± 0.329   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   3.926 ± 0.541   ms/op
ClientGrpc.createUser                     sample  324623   2.956 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.583           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.657           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.206           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.663           ms/op
ClientGrpc.existUser                      sample  333981   2.873 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.807           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.793           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.741           ms/op
ClientGrpc.getUser                        sample  320344   2.995 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.608           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.616           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.883           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.836           ms/op
ClientGrpc.listUser                       sample  248143   3.868 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.705           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.145           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.140           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
