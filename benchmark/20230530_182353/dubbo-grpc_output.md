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
# Warmup Iteration   1: 4.577 ops/ms
# Warmup Iteration   2: 9.039 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.417 ±(99.9%) 6.555 ops/ms [Average]
  (min, avg, max) = (10.007, 10.417, 10.680), stdev = 0.359
  CI (99.9%): [3.862, 16.972] (assumes normal distribution)


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
# Warmup Iteration   1: 7.639 ops/ms
# Warmup Iteration   2: 10.370 ops/ms
# Warmup Iteration   3: 11.085 ops/ms
Iteration   1: 10.917 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 11.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.012 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (10.917, 11.012, 11.075), stdev = 0.083
  CI (99.9%): [9.493, 12.531] (assumes normal distribution)


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
# Warmup Iteration   1: 7.418 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.577 ±(99.9%) 1.318 ops/ms [Average]
  (min, avg, max) = (10.505, 10.577, 10.649), stdev = 0.072
  CI (99.9%): [9.259, 11.896] (assumes normal distribution)


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
# Warmup Iteration   1: 5.784 ops/ms
# Warmup Iteration   2: 7.948 ops/ms
# Warmup Iteration   3: 7.992 ops/ms
Iteration   1: 8.111 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.118 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (8.076, 8.118, 8.167), stdev = 0.046
  CI (99.9%): [7.281, 8.955] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.003 ms/op
Iteration   1: 3.064 ±(99.9%) 0.002 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (3.014, 3.043, 3.064), stdev = 0.026
  CI (99.9%): [2.573, 3.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.922 ±(99.9%) 0.004 ms/op
Iteration   2: 2.904 ±(99.9%) 0.004 ms/op
Iteration   3: 2.893 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.893, 2.907, 2.922), stdev = 0.015
  CI (99.9%): [2.639, 3.174] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.082 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
Iteration   3: 3.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.019, 3.066, 3.097), stdev = 0.041
  CI (99.9%): [2.313, 3.819] (assumes normal distribution)


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.013 ms/op
Iteration   1: 3.933 ±(99.9%) 0.021 ms/op
Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
Iteration   3: 3.920 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (3.920, 3.938, 3.962), stdev = 0.022
  CI (99.9%): [3.544, 4.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  7.169 ms/op
                 createUser·p0.9999: 11.088 ms/op
                 createUser·p1.00:   11.272 ms/op

Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.982 ms/op
                 createUser·p0.9999: 16.739 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.711 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 15.950 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320846
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1798 
    [ 1.250,  2.500) = 30550 
    [ 2.500,  3.750) = 271834 
    [ 3.750,  5.000) = 14658 
    [ 5.000,  6.250) = 1271 
    [ 6.250,  7.500) = 334 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      9.587 ms/op
     p(99.9900) =     16.249 ms/op
     p(99.9990) =     16.993 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.102 ms/op
                 existUser·p0.9999: 12.802 ms/op
                 existUser·p1.00:   12.993 ms/op

Iteration   2: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 12.110 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.915 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  7.470 ms/op
                 existUser·p0.9999: 26.543 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326937
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41866 
    [ 2.500,  5.000) = 283729 
    [ 5.000,  7.500) = 1118 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      6.832 ms/op
     p(99.9900) =     18.746 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 18.051 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.252 ms/op
                 getUser·p0.9999: 21.004 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.771 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316638
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22048 
    [ 2.500,  5.000) = 293175 
    [ 5.000,  7.500) = 998 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     21.998 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.141 ms/op
                 listUser·p0.9999: 13.963 ms/op
                 listUser·p1.00:   14.582 ms/op

Iteration   2: 3.920 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.620 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.326 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245652
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6478 
    [ 2.500,  5.000) = 214488 
    [ 5.000,  7.500) = 23467 
    [ 7.500, 10.000) = 699 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     20.658 ms/op
     p(99.9990) =     23.181 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.417 ± 6.555  ops/ms
ClientGrpc.existUser                       thrpt       3  11.012 ± 1.519  ops/ms
ClientGrpc.getUser                         thrpt       3  10.577 ± 1.318  ops/ms
ClientGrpc.listUser                        thrpt       3   8.118 ± 0.837  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.469   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.268   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.753   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 0.394   ms/op
ClientGrpc.createUser                     sample  320846   2.994 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.587           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.249           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.105           ms/op
ClientGrpc.existUser                      sample  326937   2.933 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.431           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.746           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.640           ms/op
ClientGrpc.getUser                        sample  316638   3.030 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.700           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.998           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  245652   3.908 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.833           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.658           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
