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
# Warmup Iteration   1: 4.098 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 10.100 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.468 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.584 ±(99.9%) 1.853 ops/ms [Average]
  (min, avg, max) = (10.468, 10.584, 10.654), stdev = 0.102
  CI (99.9%): [8.732, 12.437] (assumes normal distribution)


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
# Warmup Iteration   1: 7.340 ops/ms
# Warmup Iteration   2: 10.634 ops/ms
# Warmup Iteration   3: 11.256 ops/ms
Iteration   1: 11.221 ops/ms
Iteration   2: 11.122 ops/ms
Iteration   3: 11.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.165 ±(99.9%) 0.935 ops/ms [Average]
  (min, avg, max) = (11.122, 11.165, 11.221), stdev = 0.051
  CI (99.9%): [10.230, 12.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.595 ops/ms
# Warmup Iteration   2: 10.019 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.605 ±(99.9%) 0.799 ops/ms [Average]
  (min, avg, max) = (10.570, 10.605, 10.654), stdev = 0.044
  CI (99.9%): [9.805, 11.404] (assumes normal distribution)


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
# Warmup Iteration   1: 6.445 ops/ms
# Warmup Iteration   2: 7.709 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.098 ops/ms
Iteration   2: 8.016 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.035 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (7.991, 8.035, 8.098), stdev = 0.056
  CI (99.9%): [7.015, 9.055] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.004 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.761 ms/op [Average]
  (min, avg, max) = (2.991, 3.038, 3.070), stdev = 0.042
  CI (99.9%): [2.278, 3.799] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.003 ms/op
Iteration   1: 2.871 ±(99.9%) 0.003 ms/op
Iteration   2: 2.876 ±(99.9%) 0.002 ms/op
Iteration   3: 2.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.871, 2.879, 2.891), stdev = 0.010
  CI (99.9%): [2.694, 3.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.000 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.999 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.986, 2.999, 3.011), stdev = 0.013
  CI (99.9%): [2.765, 3.233] (assumes normal distribution)


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
# Warmup Iteration   1: 5.157 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.017 ms/op
Iteration   1: 4.019 ±(99.9%) 0.037 ms/op
Iteration   2: 3.907 ±(99.9%) 0.014 ms/op
Iteration   3: 3.847 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.847, 3.924, 4.019), stdev = 0.087
  CI (99.9%): [2.331, 5.518] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.107 ms/op
                 createUser·p0.9999: 12.312 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.881 ms/op
                 createUser·p0.9999: 14.613 ms/op
                 createUser·p1.00:   15.073 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.649 ms/op
                 createUser·p0.9999: 16.351 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317134
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 535 
    [ 1.250,  2.500) = 23363 
    [ 2.500,  3.750) = 277238 
    [ 3.750,  5.000) = 14801 
    [ 5.000,  6.250) = 655 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     16.171 ms/op
     p(99.9990) =     16.545 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
Iteration   1: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.203 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 14.156 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 15.352 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329952
  mean =      2.908 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1208 
    [ 1.250,  2.500) = 42871 
    [ 2.500,  3.750) = 276774 
    [ 3.750,  5.000) = 8262 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     15.517 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 17.211 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.355 ms/op
                 getUser·p0.999:  7.944 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.297 ms/op
                 getUser·p0.95:   3.383 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.852 ms/op
                 getUser·p0.9999: 30.293 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318287
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16026 
    [ 2.500,  5.000) = 301280 
    [ 5.000,  7.500) = 704 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.191 ms/op
     p(99.9000) =      7.108 ms/op
     p(99.9900) =     28.874 ms/op
     p(99.9990) =     30.632 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 5.435 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 4.102 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 15.208 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.673 ms/op
                 listUser·p0.9999: 19.182 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.366 ms/op
                 listUser·p0.9999: 22.678 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235326
  mean =      4.079 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2038 
    [ 2.500,  5.000) = 207551 
    [ 5.000,  7.500) = 24279 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.076 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     19.938 ms/op
     p(99.9990) =     22.860 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.584 ± 1.853  ops/ms
ClientGrpc.existUser                       thrpt       3  11.165 ± 0.935  ops/ms
ClientGrpc.getUser                         thrpt       3  10.605 ± 0.799  ops/ms
ClientGrpc.listUser                        thrpt       3   8.035 ± 1.020  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.761   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.185   ms/op
ClientGrpc.getUser                          avgt       3   2.999 ± 0.234   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 1.593   ms/op
ClientGrpc.createUser                     sample  317134   3.027 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.171           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.679           ms/op
ClientGrpc.existUser                      sample  329952   2.908 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.653           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.369           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.679           ms/op
ClientGrpc.getUser                        sample  318287   3.014 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.765           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.191           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.108           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.874           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.704           ms/op
ClientGrpc.listUser                       sample  235326   4.079 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.881           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.938           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.036           ms/op
