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
# Warmup Iteration   1: 4.534 ops/ms
# Warmup Iteration   2: 9.711 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.915 ops/ms
Iteration   3: 10.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.747 ±(99.9%) 2.790 ops/ms [Average]
  (min, avg, max) = (10.616, 10.747, 10.915), stdev = 0.153
  CI (99.9%): [7.957, 13.537] (assumes normal distribution)


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
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 10.618 ops/ms
# Warmup Iteration   3: 11.172 ops/ms
Iteration   1: 11.143 ops/ms
Iteration   2: 11.066 ops/ms
Iteration   3: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.062 ±(99.9%) 1.525 ops/ms [Average]
  (min, avg, max) = (10.976, 11.062, 11.143), stdev = 0.084
  CI (99.9%): [9.537, 12.586] (assumes normal distribution)


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
# Warmup Iteration   1: 8.122 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.801 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.722 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (10.674, 10.722, 10.801), stdev = 0.069
  CI (99.9%): [9.462, 11.983] (assumes normal distribution)


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
# Warmup Iteration   1: 5.834 ops/ms
# Warmup Iteration   2: 7.866 ops/ms
# Warmup Iteration   3: 8.196 ops/ms
Iteration   1: 8.139 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.146 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (8.108, 8.146, 8.192), stdev = 0.042
  CI (99.9%): [7.376, 8.916] (assumes normal distribution)


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.039 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (2.995, 3.028, 3.049), stdev = 0.028
  CI (99.9%): [2.511, 3.544] (assumes normal distribution)


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.004 ms/op
Iteration   1: 2.887 ±(99.9%) 0.004 ms/op
Iteration   2: 2.917 ±(99.9%) 0.003 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (2.877, 2.894, 2.917), stdev = 0.021
  CI (99.9%): [2.514, 3.274] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 2.990 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.990, 2.996, 3.001), stdev = 0.006
  CI (99.9%): [2.894, 3.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.007 ms/op
Iteration   1: 3.876 ±(99.9%) 0.005 ms/op
Iteration   2: 3.950 ±(99.9%) 0.022 ms/op
Iteration   3: 3.947 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (3.876, 3.924, 3.950), stdev = 0.042
  CI (99.9%): [3.164, 4.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  6.605 ms/op
                 createUser·p0.9999: 12.184 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   2: 2.907 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.348 ms/op
                 createUser·p0.9999: 16.335 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.383 ms/op
                 createUser·p0.9999: 27.034 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324012
  mean =      2.962 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34203 
    [ 2.500,  5.000) = 288514 
    [ 5.000,  7.500) = 994 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     23.058 ms/op
     p(99.9990) =     27.157 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.262 ms/op
                 existUser·p0.9999: 15.075 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   2: 2.780 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 15.024 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.934 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333507
  mean =      2.876 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41309 
    [ 2.500,  5.000) = 291000 
    [ 5.000,  7.500) = 846 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.680 ms/op
     p(99.9900) =     15.335 ms/op
     p(99.9990) =     26.892 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.540 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.832 ms/op
                 getUser·p0.9999: 11.531 ms/op
                 getUser·p1.00:   12.026 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 12.992 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 3.019 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.682 ms/op
                 getUser·p0.9999: 14.377 ms/op
                 getUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318621
  mean =      3.012 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 902 
    [ 1.250,  2.500) = 14152 
    [ 2.500,  3.750) = 292453 
    [ 3.750,  5.000) = 9863 
    [ 5.000,  6.250) = 799 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     12.962 ms/op
     p(99.9990) =     14.720 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.740 ms/op
                 listUser·p0.999:  13.185 ms/op
                 listUser·p0.9999: 20.233 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.850 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.001 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  18.960 ms/op
                 listUser·p0.9999: 22.044 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.911 ms/op
                 listUser·p0.9999: 25.975 ms/op
                 listUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248805
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4390 
    [ 2.500,  5.000) = 225256 
    [ 5.000,  7.500) = 18059 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     15.060 ms/op
     p(99.9900) =     23.597 ms/op
     p(99.9990) =     26.329 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.747 ± 2.790  ops/ms
ClientGrpc.existUser                       thrpt       3  11.062 ± 1.525  ops/ms
ClientGrpc.getUser                         thrpt       3  10.722 ± 1.261  ops/ms
ClientGrpc.listUser                        thrpt       3   8.146 ± 0.770  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.517   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.380   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.101   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 0.760   ms/op
ClientGrpc.createUser                     sample  324012   2.962 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.078           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.058           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  333507   2.876 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.680           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.335           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  318621   3.012 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.679           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          12.962           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.828           ms/op
ClientGrpc.listUser                       sample  248805   3.861 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.810           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.723           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.060           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.597           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
