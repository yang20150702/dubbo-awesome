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
# Warmup Iteration   1: 3.915 ops/ms
# Warmup Iteration   2: 9.028 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.293 ops/ms
Iteration   3: 10.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.311 ±(99.9%) 0.434 ops/ms [Average]
  (min, avg, max) = (10.293, 10.311, 10.338), stdev = 0.024
  CI (99.9%): [9.878, 10.745] (assumes normal distribution)


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
# Warmup Iteration   1: 7.419 ops/ms
# Warmup Iteration   2: 10.639 ops/ms
# Warmup Iteration   3: 11.044 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.772 ±(99.9%) 1.485 ops/ms [Average]
  (min, avg, max) = (10.682, 10.772, 10.840), stdev = 0.081
  CI (99.9%): [9.286, 12.257] (assumes normal distribution)


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
# Warmup Iteration   1: 7.025 ops/ms
# Warmup Iteration   2: 10.273 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.417 ops/ms
Iteration   2: 10.539 ops/ms
Iteration   3: 10.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 1.190 ops/ms [Average]
  (min, avg, max) = (10.417, 10.491, 10.539), stdev = 0.065
  CI (99.9%): [9.301, 11.681] (assumes normal distribution)


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
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 7.493 ops/ms
# Warmup Iteration   3: 8.132 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 8.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.237 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (8.211, 8.237, 8.268), stdev = 0.029
  CI (99.9%): [7.709, 8.766] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.002 ms/op
Iteration   1: 3.123 ±(99.9%) 0.011 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.003, 3.057, 3.123), stdev = 0.061
  CI (99.9%): [1.944, 4.171] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.003 ms/op
Iteration   1: 2.932 ±(99.9%) 0.002 ms/op
Iteration   2: 2.957 ±(99.9%) 0.003 ms/op
Iteration   3: 2.901 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.901, 2.930, 2.957), stdev = 0.028
  CI (99.9%): [2.417, 3.443] (assumes normal distribution)


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
# Warmup Iteration   1: 4.417 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.044 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (3.033, 3.044, 3.050), stdev = 0.009
  CI (99.9%): [2.877, 3.211] (assumes normal distribution)


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
# Warmup Iteration   1: 5.511 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.025 ms/op
Iteration   1: 3.921 ±(99.9%) 0.022 ms/op
Iteration   2: 3.758 ±(99.9%) 0.014 ms/op
Iteration   3: 3.905 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 1.646 ms/op [Average]
  (min, avg, max) = (3.758, 3.861, 3.921), stdev = 0.090
  CI (99.9%): [2.215, 5.508] (assumes normal distribution)


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.385 ms/op
                 createUser·p0.999:  10.854 ms/op
                 createUser·p0.9999: 16.706 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  6.321 ms/op
                 createUser·p0.9999: 17.070 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.299 ms/op
                 createUser·p0.9999: 19.363 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314089
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 14253 
    [ 2.500,  3.750) = 284937 
    [ 3.750,  5.000) = 13340 
    [ 5.000,  6.250) = 475 
    [ 6.250,  7.500) = 273 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 84 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.545 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.689 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 19.568 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 2.934 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.259 ms/op
                 existUser·p0.9999: 14.471 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 16.504 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326611
  mean =      2.936 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33199 
    [ 2.500,  5.000) = 292179 
    [ 5.000,  7.500) = 878 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.038 ms/op
     p(99.9900) =     17.498 ms/op
     p(99.9990) =     19.906 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.792 ms/op
                 getUser·p0.9999: 19.584 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.493 ms/op
                 getUser·p0.9999: 22.828 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.666 ms/op
                 getUser·p0.9999: 28.262 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315214
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20996 
    [ 2.500,  5.000) = 292974 
    [ 5.000,  7.500) = 967 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.068 ms/op
     p(99.9900) =     27.377 ms/op
     p(99.9990) =     29.683 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.073 ms/op
                 listUser·p0.9999: 16.279 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.812 ms/op
                 listUser·p0.9999: 17.721 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.921 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 26.340 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244634
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2732 
    [ 2.500,  5.000) = 220190 
    [ 5.000,  7.500) = 20604 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.358 ms/op
     p(99.9900) =     25.708 ms/op
     p(99.9990) =     26.659 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.311 ± 0.434  ops/ms
ClientGrpc.existUser                       thrpt       3  10.772 ± 1.485  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 1.190  ops/ms
ClientGrpc.listUser                        thrpt       3   8.237 ± 0.529  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 1.114   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.513   ms/op
ClientGrpc.getUser                          avgt       3   3.044 ± 0.167   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 1.646   ms/op
ClientGrpc.createUser                     sample  314089   3.054 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.602           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.545           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.038           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.956           ms/op
ClientGrpc.existUser                      sample  326611   2.936 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.621           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.038           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.498           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  315214   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.821           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.068           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.377           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.721           ms/op
ClientGrpc.listUser                       sample  244634   3.925 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.087           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.358           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.708           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
