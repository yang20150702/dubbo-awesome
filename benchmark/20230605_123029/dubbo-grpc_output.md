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
# Warmup Iteration   1: 4.305 ops/ms
# Warmup Iteration   2: 8.959 ops/ms
# Warmup Iteration   3: 10.203 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.674 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (10.608, 10.674, 10.768), stdev = 0.083
  CI (99.9%): [9.154, 12.194] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.150 ops/ms
# Warmup Iteration   2: 10.579 ops/ms
# Warmup Iteration   3: 11.044 ops/ms
Iteration   1: 10.979 ops/ms
Iteration   2: 11.334 ops/ms
Iteration   3: 11.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.178 ±(99.9%) 3.304 ops/ms [Average]
  (min, avg, max) = (10.979, 11.178, 11.334), stdev = 0.181
  CI (99.9%): [7.873, 14.482] (assumes normal distribution)


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
# Warmup Iteration   1: 6.751 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.717 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.742 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (10.715, 10.742, 10.794), stdev = 0.045
  CI (99.9%): [9.922, 11.562] (assumes normal distribution)


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
# Warmup Iteration   1: 5.764 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 8.052 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.185 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (8.157, 8.185, 8.223), stdev = 0.034
  CI (99.9%): [7.563, 8.807] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.004 ms/op
Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.999 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (2.995, 2.999, 3.004), stdev = 0.005
  CI (99.9%): [2.910, 3.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.002 ms/op
Iteration   1: 2.855 ±(99.9%) 0.002 ms/op
Iteration   2: 2.880 ±(99.9%) 0.003 ms/op
Iteration   3: 2.876 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.855, 2.870, 2.880), stdev = 0.013
  CI (99.9%): [2.631, 3.110] (assumes normal distribution)


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.004 ms/op
Iteration   3: 3.003 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.003, 3.035, 3.052), stdev = 0.028
  CI (99.9%): [2.528, 3.541] (assumes normal distribution)


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
# Warmup Iteration   1: 5.438 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.007 ms/op
Iteration   1: 4.008 ±(99.9%) 0.011 ms/op
Iteration   2: 3.882 ±(99.9%) 0.011 ms/op
Iteration   3: 3.955 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.949 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (3.882, 3.949, 4.008), stdev = 0.063
  CI (99.9%): [2.795, 5.102] (assumes normal distribution)


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.309 ms/op
                 createUser·p0.9999: 12.932 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.962 ms/op
                 createUser·p0.9999: 15.349 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 17.038 ms/op
                 createUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319699
  mean =      3.001 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 739 
    [ 1.250,  2.500) = 30456 
    [ 2.500,  3.750) = 274354 
    [ 3.750,  5.000) = 12628 
    [ 5.000,  6.250) = 860 
    [ 6.250,  7.500) = 281 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.990 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.005 ms/op
Iteration   1: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 12.527 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.844 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.411 ms/op
                 existUser·p0.9999: 12.985 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 16.837 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335090
  mean =      2.863 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1294 
    [ 1.250,  2.500) = 46930 
    [ 2.500,  3.750) = 278134 
    [ 3.750,  5.000) = 7537 
    [ 5.000,  6.250) = 660 
    [ 6.250,  7.500) = 218 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.192 ms/op
     p(99.9900) =     16.015 ms/op
     p(99.9990) =     17.061 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.626 ms/op
                 getUser·p0.9999: 13.558 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.676 ms/op
                 getUser·p0.9999: 25.765 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.062 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319108
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26469 
    [ 2.500,  5.000) = 291372 
    [ 5.000,  7.500) = 1017 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.151 ms/op
     p(99.9900) =     25.175 ms/op
     p(99.9990) =     25.919 ms/op
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
# Warmup Iteration   1: 5.510 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
Iteration   1: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  13.189 ms/op
                 listUser·p0.9999: 14.549 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   2: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  16.194 ms/op
                 listUser·p0.9999: 27.547 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 3.832 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.932 ms/op
                 listUser·p0.9999: 24.824 ms/op
                 listUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247236
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3158 
    [ 2.500,  5.000) = 225537 
    [ 5.000,  7.500) = 17514 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     14.922 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     27.673 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.674 ± 1.520  ops/ms
ClientGrpc.existUser                       thrpt       3  11.178 ± 3.304  ops/ms
ClientGrpc.getUser                         thrpt       3  10.742 ± 0.820  ops/ms
ClientGrpc.listUser                        thrpt       3   8.185 ± 0.622  ops/ms
ClientGrpc.createUser                       avgt       3   2.999 ± 0.088   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 0.239   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   3.949 ± 1.154   ms/op
ClientGrpc.createUser                     sample  319699   3.001 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.990           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.465           ms/op
ClientGrpc.existUser                      sample  335090   2.863 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.775           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.281           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.192           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.015           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.105           ms/op
ClientGrpc.getUser                        sample  319108   3.006 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.758           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.151           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.175           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.083           ms/op
ClientGrpc.listUser                       sample  247236   3.885 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.922           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
