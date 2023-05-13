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
# Warmup Iteration   1: 3.856 ops/ms
# Warmup Iteration   2: 8.889 ops/ms
# Warmup Iteration   3: 9.971 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.519 ±(99.9%) 0.799 ops/ms [Average]
  (min, avg, max) = (10.478, 10.519, 10.565), stdev = 0.044
  CI (99.9%): [9.720, 11.318] (assumes normal distribution)


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
# Warmup Iteration   1: 7.350 ops/ms
# Warmup Iteration   2: 10.717 ops/ms
# Warmup Iteration   3: 10.807 ops/ms
Iteration   1: 11.048 ops/ms
Iteration   2: 11.431 ops/ms
Iteration   3: 11.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.184 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (11.048, 11.184, 11.431), stdev = 0.214
  CI (99.9%): [7.277, 15.091] (assumes normal distribution)


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
# Warmup Iteration   1: 7.349 ops/ms
# Warmup Iteration   2: 10.047 ops/ms
# Warmup Iteration   3: 10.562 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.574 ±(99.9%) 2.550 ops/ms [Average]
  (min, avg, max) = (10.434, 10.574, 10.714), stdev = 0.140
  CI (99.9%): [8.024, 13.124] (assumes normal distribution)


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
# Warmup Iteration   1: 5.521 ops/ms
# Warmup Iteration   2: 7.877 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.108 ops/ms
Iteration   3: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.194 ±(99.9%) 1.913 ops/ms [Average]
  (min, avg, max) = (8.108, 8.194, 8.311), stdev = 0.105
  CI (99.9%): [6.282, 10.107] (assumes normal distribution)


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.003 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.945, 3.003, 3.046), stdev = 0.052
  CI (99.9%): [2.053, 3.953] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.003 ms/op
Iteration   1: 2.833 ±(99.9%) 0.002 ms/op
Iteration   2: 2.889 ±(99.9%) 0.002 ms/op
Iteration   3: 2.860 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.861 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.833, 2.861, 2.889), stdev = 0.028
  CI (99.9%): [2.349, 3.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
Iteration   3: 3.028 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 0.645 ms/op [Average]
  (min, avg, max) = (2.983, 3.021, 3.052), stdev = 0.035
  CI (99.9%): [2.376, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.416 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.016 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
Iteration   2: 3.915 ±(99.9%) 0.016 ms/op
Iteration   3: 3.947 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.908, 3.923, 3.947), stdev = 0.020
  CI (99.9%): [3.553, 4.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.939 ms/op
                 createUser·p0.9999: 12.539 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.028 ms/op
                 createUser·p0.9999: 13.596 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.610 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  11.155 ms/op
                 createUser·p0.9999: 27.708 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316595
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23537 
    [ 2.500,  5.000) = 291431 
    [ 5.000,  7.500) = 1192 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.968 ms/op
     p(99.9900) =     26.707 ms/op
     p(99.9990) =     27.951 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
Iteration   1: 2.852 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.727 ms/op
                 existUser·p0.9999: 12.396 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.152 ms/op
                 existUser·p0.9999: 16.676 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  11.027 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333366
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48288 
    [ 2.500,  5.000) = 284054 
    [ 5.000,  7.500) = 674 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.632 ms/op
     p(99.9900) =     17.312 ms/op
     p(99.9990) =     19.781 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.071 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.782 ms/op
                 getUser·p0.9999: 14.116 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.866 ms/op
                 getUser·p0.9999: 13.964 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  6.743 ms/op
                 getUser·p0.9999: 25.572 ms/op
                 getUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317218
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25127 
    [ 2.500,  5.000) = 290973 
    [ 5.000,  7.500) = 790 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.574 ms/op
     p(99.9900) =     23.274 ms/op
     p(99.9990) =     25.974 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.431 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.011 ms/op
Iteration   1: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.390 ms/op
                 listUser·p0.9999: 16.386 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.913 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.242 ms/op
                 listUser·p0.9999: 26.394 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  18.956 ms/op
                 listUser·p0.9999: 24.374 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244996
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2264 
    [ 2.500,  5.000) = 222659 
    [ 5.000,  7.500) = 18839 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.125 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.519 ± 0.799  ops/ms
ClientGrpc.existUser                       thrpt       3  11.184 ± 3.907  ops/ms
ClientGrpc.getUser                         thrpt       3  10.574 ± 2.550  ops/ms
ClientGrpc.listUser                        thrpt       3   8.194 ± 1.913  ops/ms
ClientGrpc.createUser                       avgt       3   3.003 ± 0.950   ms/op
ClientGrpc.existUser                        avgt       3   2.861 ± 0.512   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 0.645   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 0.371   ms/op
ClientGrpc.createUser                     sample  316595   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.610           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.968           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.707           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.017           ms/op
ClientGrpc.existUser                      sample  333366   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.613           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.632           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.312           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  317218   3.025 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.730           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.574           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.274           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.083           ms/op
ClientGrpc.listUser                       sample  244996   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.592           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.754           ms/op
