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
# Warmup Iteration   1: 4.581 ops/ms
# Warmup Iteration   2: 9.224 ops/ms
# Warmup Iteration   3: 10.321 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.771 ops/ms
Iteration   3: 10.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.788 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (10.755, 10.788, 10.838), stdev = 0.044
  CI (99.9%): [9.986, 11.591] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.552 ops/ms
# Warmup Iteration   2: 10.912 ops/ms
# Warmup Iteration   3: 11.337 ops/ms
Iteration   1: 11.471 ops/ms
Iteration   2: 11.266 ops/ms
Iteration   3: 11.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.341 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (11.266, 11.341, 11.471), stdev = 0.113
  CI (99.9%): [9.284, 13.399] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.396 ops/ms
# Warmup Iteration   2: 10.607 ops/ms
# Warmup Iteration   3: 10.896 ops/ms
Iteration   1: 10.867 ops/ms
Iteration   2: 11.087 ops/ms
Iteration   3: 10.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.884 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (10.699, 10.884, 11.087), stdev = 0.195
  CI (99.9%): [7.330, 14.439] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.830 ops/ms
# Warmup Iteration   2: 8.281 ops/ms
# Warmup Iteration   3: 8.617 ops/ms
Iteration   1: 8.639 ops/ms
Iteration   2: 8.562 ops/ms
Iteration   3: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.577 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (8.531, 8.577, 8.639), stdev = 0.056
  CI (99.9%): [7.562, 9.593] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.002 ms/op
Iteration   1: 3.006 ±(99.9%) 0.009 ms/op
Iteration   2: 2.943 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.982 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (2.943, 2.982, 3.006), stdev = 0.034
  CI (99.9%): [2.370, 3.593] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.856 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.832 ±(99.9%) 0.021 ms/op
Iteration   1: 2.829 ±(99.9%) 0.002 ms/op
Iteration   2: 2.801 ±(99.9%) 0.003 ms/op
Iteration   3: 2.704 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.778 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (2.704, 2.778, 2.829), stdev = 0.066
  CI (99.9%): [1.581, 3.976] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 2.897 ±(99.9%) 0.005 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.921 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (2.897, 2.921, 2.947), stdev = 0.025
  CI (99.9%): [2.465, 3.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.036 ms/op
Iteration   1: 3.877 ±(99.9%) 0.013 ms/op
Iteration   2: 3.778 ±(99.9%) 0.015 ms/op
Iteration   3: 3.735 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.796 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.735, 3.796, 3.877), stdev = 0.073
  CI (99.9%): [2.469, 5.123] (assumes normal distribution)


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  6.046 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 19.806 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.505 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.752 ms/op
                 createUser·p0.9999: 16.399 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322693
  mean =      2.975 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25075 
    [ 2.500,  5.000) = 296565 
    [ 5.000,  7.500) = 735 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.460 ms/op
     p(99.9900) =     19.849 ms/op
     p(99.9990) =     20.400 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
Iteration   1: 2.791 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  5.761 ms/op
                 existUser·p0.9999: 11.108 ms/op
                 existUser·p1.00:   11.305 ms/op

Iteration   2: 2.796 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.815 ms/op
                 existUser·p0.9999: 14.181 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  5.775 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342468
  mean =      2.804 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5374 
    [ 1.250,  2.500) = 59279 
    [ 2.500,  3.750) = 266274 
    [ 3.750,  5.000) = 10580 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.714 ms/op
     p(99.9900) =     14.328 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 2.962 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.515 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.365 ms/op
                 getUser·p0.9999: 11.777 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   2: 2.913 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  5.989 ms/op
                 getUser·p0.9999: 12.583 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.338 ms/op
                 getUser·p0.9999: 15.928 ms/op
                 getUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326187
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1897 
    [ 1.250,  2.500) = 32334 
    [ 2.500,  3.750) = 276866 
    [ 3.750,  5.000) = 13945 
    [ 5.000,  6.250) = 658 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.854 ms/op
     p(99.9900) =     14.654 ms/op
     p(99.9990) =     16.154 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


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
# Warmup Iteration   1: 4.064 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.011 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.232 ms/op
                 listUser·p0.9999: 17.992 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 3.812 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.366 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 3.773 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 18.798 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253386
  mean =      3.788 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6646 
    [ 2.500,  5.000) = 226610 
    [ 5.000,  7.500) = 19040 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.788 ± 0.802  ops/ms
ClientGrpc.existUser                       thrpt       3  11.341 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3  10.884 ± 3.555  ops/ms
ClientGrpc.listUser                        thrpt       3   8.577 ± 1.015  ops/ms
ClientGrpc.createUser                       avgt       3   2.982 ± 0.612   ms/op
ClientGrpc.existUser                        avgt       3   2.778 ± 1.197   ms/op
ClientGrpc.getUser                          avgt       3   2.921 ± 0.456   ms/op
ClientGrpc.listUser                         avgt       3   3.796 ± 1.327   ms/op
ClientGrpc.createUser                     sample  322693   2.975 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.560           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.460           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.849           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.546           ms/op
ClientGrpc.existUser                      sample  342468   2.804 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.498           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.814           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.714           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.328           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  326187   2.943 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.597           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.929           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.854           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.654           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.548           ms/op
ClientGrpc.listUser                       sample  253386   3.788 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.366           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.641           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.630           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
