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
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 8.909 ops/ms
Iteration   2: 9.045 ops/ms
Iteration   3: 8.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.982 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (8.909, 8.982, 9.045), stdev = 0.068
  CI (99.9%): [7.733, 10.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.053 ops/ms
# Warmup Iteration   2: 9.088 ops/ms
# Warmup Iteration   3: 9.320 ops/ms
Iteration   1: 9.042 ops/ms
Iteration   2: 9.189 ops/ms
Iteration   3: 8.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.070 ±(99.9%) 1.969 ops/ms [Average]
  (min, avg, max) = (8.979, 9.070, 9.189), stdev = 0.108
  CI (99.9%): [7.100, 11.039] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 8.810 ops/ms
Iteration   1: 8.651 ops/ms
Iteration   2: 8.954 ops/ms
Iteration   3: 9.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.939 ±(99.9%) 5.137 ops/ms [Average]
  (min, avg, max) = (8.651, 8.939, 9.214), stdev = 0.282
  CI (99.9%): [3.803, 14.076] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.129 ops/ms
# Warmup Iteration   2: 6.183 ops/ms
# Warmup Iteration   3: 6.781 ops/ms
Iteration   1: 7.014 ops/ms
Iteration   2: 6.744 ops/ms
Iteration   3: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.946 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (6.744, 6.946, 7.079), stdev = 0.178
  CI (99.9%): [3.704, 10.187] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.403 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.005 ms/op
Iteration   1: 3.488 ±(99.9%) 0.004 ms/op
Iteration   2: 3.519 ±(99.9%) 0.003 ms/op
Iteration   3: 3.454 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.487 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.454, 3.487, 3.519), stdev = 0.033
  CI (99.9%): [2.888, 4.085] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.003 ms/op
Iteration   1: 3.338 ±(99.9%) 0.003 ms/op
Iteration   2: 3.303 ±(99.9%) 0.004 ms/op
Iteration   3: 3.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.366 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.303, 3.366, 3.457), stdev = 0.081
  CI (99.9%): [1.892, 4.840] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.002 ms/op
Iteration   1: 3.578 ±(99.9%) 0.004 ms/op
Iteration   2: 3.474 ±(99.9%) 0.004 ms/op
Iteration   3: 3.725 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.592 ±(99.9%) 2.294 ms/op [Average]
  (min, avg, max) = (3.474, 3.592, 3.725), stdev = 0.126
  CI (99.9%): [1.298, 5.887] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.485 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.838 ±(99.9%) 0.014 ms/op
Iteration   1: 4.877 ±(99.9%) 0.009 ms/op
Iteration   2: 4.917 ±(99.9%) 0.011 ms/op
Iteration   3: 4.702 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.832 ±(99.9%) 2.082 ms/op [Average]
  (min, avg, max) = (4.702, 4.832, 4.917), stdev = 0.114
  CI (99.9%): [2.749, 6.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.008 ms/op
Iteration   1: 3.725 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  9.212 ms/op
                 createUser·p0.9999: 14.602 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.655 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  12.795 ms/op
                 createUser·p0.9999: 16.605 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.672 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  12.936 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260617
  mean =      3.684 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 6357 
    [ 2.500,  3.750) = 148400 
    [ 3.750,  5.000) = 98844 
    [ 5.000,  6.250) = 5367 
    [ 6.250,  7.500) = 800 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.137 ms/op
     p(99.9900) =     18.870 ms/op
     p(99.9990) =     19.608 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.007 ms/op
Iteration   1: 3.504 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.401 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  12.320 ms/op
                 existUser·p0.9999: 23.718 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 3.548 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.533 ms/op
                 existUser·p0.999:  8.316 ms/op
                 existUser·p0.9999: 15.417 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 18.018 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271852
  mean =      3.531 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8717 
    [ 2.500,  5.000) = 256766 
    [ 5.000,  7.500) = 5534 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.401 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.079 ms/op
     p(99.9900) =     18.895 ms/op
     p(99.9990) =     26.266 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.207 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.008 ms/op
Iteration   1: 3.729 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 18.364 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 3.636 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  10.879 ms/op
                 getUser·p0.9999: 16.001 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.626 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  12.463 ms/op
                 getUser·p0.9999: 20.715 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262060
  mean =      3.663 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7072 
    [ 2.500,  5.000) = 247572 
    [ 5.000,  7.500) = 6619 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     10.927 ms/op
     p(99.9900) =     19.060 ms/op
     p(99.9990) =     21.115 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 6.278 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.015 ms/op
Iteration   1: 4.730 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  17.035 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 4.722 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.949 ms/op
                 listUser·p0.9999: 21.165 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 4.643 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 23.371 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204398
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 317 
    [ 2.500,  5.000) = 155751 
    [ 5.000,  7.500) = 43260 
    [ 7.500, 10.000) = 4352 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     22.563 ms/op
     p(99.9990) =     23.688 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.982 ± 1.249  ops/ms
ClientGrpc.existUser                       thrpt       3   9.070 ± 1.969  ops/ms
ClientGrpc.getUser                         thrpt       3   8.939 ± 5.137  ops/ms
ClientGrpc.listUser                        thrpt       3   6.946 ± 3.242  ops/ms
ClientGrpc.createUser                       avgt       3   3.487 ± 0.599   ms/op
ClientGrpc.existUser                        avgt       3   3.366 ± 1.474   ms/op
ClientGrpc.getUser                          avgt       3   3.592 ± 2.294   ms/op
ClientGrpc.listUser                         avgt       3   4.832 ± 2.082   ms/op
ClientGrpc.createUser                     sample  260617   3.684 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.137           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.870           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  271852   3.531 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.401           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.767           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.079           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.895           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.345           ms/op
ClientGrpc.getUser                        sample  262060   3.663 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.507           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.060           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  204398   4.698 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.249           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.323           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.547           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.563           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
