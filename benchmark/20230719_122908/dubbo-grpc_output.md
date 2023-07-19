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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 5.236 ops/ms
# Warmup Iteration   3: 6.523 ops/ms
Iteration   1: 6.974 ops/ms
Iteration   2: 7.076 ops/ms
Iteration   3: 7.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.033 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (6.974, 7.033, 7.076), stdev = 0.053
  CI (99.9%): [6.069, 7.997] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ops/ms
# Warmup Iteration   2: 6.764 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 7.911 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 7.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.878 ±(99.9%) 0.522 ops/ms [Average]
  (min, avg, max) = (7.861, 7.878, 7.911), stdev = 0.029
  CI (99.9%): [7.357, 8.400] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ops/ms
# Warmup Iteration   2: 6.319 ops/ms
# Warmup Iteration   3: 6.880 ops/ms
Iteration   1: 7.171 ops/ms
Iteration   2: 7.296 ops/ms
Iteration   3: 7.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.240 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (7.171, 7.240, 7.296), stdev = 0.064
  CI (99.9%): [6.074, 8.405] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ops/ms
# Warmup Iteration   2: 5.202 ops/ms
# Warmup Iteration   3: 5.472 ops/ms
Iteration   1: 5.581 ops/ms
Iteration   2: 5.687 ops/ms
Iteration   3: 5.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.609 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (5.560, 5.609, 5.687), stdev = 0.068
  CI (99.9%): [4.375, 6.843] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 4.556 ±(99.9%) 0.007 ms/op
Iteration   1: 4.471 ±(99.9%) 0.003 ms/op
Iteration   2: 4.401 ±(99.9%) 0.003 ms/op
Iteration   3: 4.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.420 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (4.389, 4.420, 4.471), stdev = 0.044
  CI (99.9%): [3.613, 5.227] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.006 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.004 ms/op
Iteration   1: 4.282 ±(99.9%) 0.004 ms/op
Iteration   2: 4.294 ±(99.9%) 0.003 ms/op
Iteration   3: 4.122 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.233 ±(99.9%) 1.757 ms/op [Average]
  (min, avg, max) = (4.122, 4.233, 4.294), stdev = 0.096
  CI (99.9%): [2.475, 5.990] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.595 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.005 ms/op
Iteration   1: 4.353 ±(99.9%) 0.006 ms/op
Iteration   2: 4.409 ±(99.9%) 0.005 ms/op
Iteration   3: 4.363 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.375 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (4.353, 4.375, 4.409), stdev = 0.030
  CI (99.9%): [3.831, 4.920] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.520 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.145 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.657 ±(99.9%) 0.015 ms/op
Iteration   1: 5.645 ±(99.9%) 0.024 ms/op
Iteration   2: 6.006 ±(99.9%) 0.033 ms/op
Iteration   3: 5.986 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.879 ±(99.9%) 3.704 ms/op [Average]
  (min, avg, max) = (5.645, 5.879, 6.006), stdev = 0.203
  CI (99.9%): [2.175, 9.583] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.287 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.491 ±(99.9%) 0.016 ms/op
Iteration   1: 4.389 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.193 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  12.404 ms/op
                 createUser·p0.9999: 16.237 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   2: 4.357 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.800 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  11.429 ms/op
                 createUser·p0.9999: 18.634 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 4.314 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.718 ms/op
                 createUser·p0.99:   7.534 ms/op
                 createUser·p0.999:  22.310 ms/op
                 createUser·p0.9999: 34.838 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220578
  mean =      4.353 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7392 
    [ 2.500,  5.000) = 174322 
    [ 5.000,  7.500) = 36150 
    [ 7.500, 10.000) = 2012 
    [10.000, 12.500) = 480 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.850 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     34.071 ms/op
     p(99.9990) =     35.310 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.253 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.013 ms/op
Iteration   1: 4.200 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  13.429 ms/op
                 existUser·p0.9999: 17.098 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 4.204 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.759 ms/op
                 existUser·p0.99:   7.569 ms/op
                 existUser·p0.999:  13.681 ms/op
                 existUser·p0.9999: 18.179 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   3: 4.245 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.825 ms/op
                 existUser·p0.99:   8.110 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 21.198 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227714
  mean =      4.216 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7420 
    [ 2.500,  5.000) = 189146 
    [ 5.000,  7.500) = 28549 
    [ 7.500, 10.000) = 2037 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     20.316 ms/op
     p(99.9990) =     21.487 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.481 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.581 ±(99.9%) 0.016 ms/op
Iteration   1: 4.483 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   6.013 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  13.069 ms/op
                 getUser·p0.9999: 19.368 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 4.320 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  10.059 ms/op
                 getUser·p0.9999: 25.153 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 4.497 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  15.522 ms/op
                 getUser·p0.9999: 28.111 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216454
  mean =      4.431 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4854 
    [ 2.500,  5.000) = 170607 
    [ 5.000,  7.500) = 38000 
    [ 7.500, 10.000) = 2506 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      8.118 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     27.396 ms/op
     p(99.9990) =     28.394 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.646 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.386 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.884 ±(99.9%) 0.021 ms/op
Iteration   1: 5.904 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.776 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.856 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.818 ms/op
                 listUser·p0.999:  23.522 ms/op
                 listUser·p0.9999: 26.801 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   2: 5.900 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   11.928 ms/op
                 listUser·p0.999:  21.095 ms/op
                 listUser·p0.9999: 33.827 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   3: 5.841 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.765 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  22.009 ms/op
                 listUser·p0.9999: 25.892 ms/op
                 listUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163127
  mean =      5.882 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 168 
    [ 2.500,  5.000) = 44151 
    [ 5.000,  7.500) = 98871 
    [ 7.500, 10.000) = 16048 
    [10.000, 12.500) = 2751 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     31.973 ms/op
     p(99.9990) =     35.879 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.033 ± 0.964  ops/ms
ClientGrpc.existUser                       thrpt       3   7.878 ± 0.522  ops/ms
ClientGrpc.getUser                         thrpt       3   7.240 ± 1.165  ops/ms
ClientGrpc.listUser                        thrpt       3   5.609 ± 1.234  ops/ms
ClientGrpc.createUser                       avgt       3   4.420 ± 0.807   ms/op
ClientGrpc.existUser                        avgt       3   4.233 ± 1.757   ms/op
ClientGrpc.getUser                          avgt       3   4.375 ± 0.544   ms/op
ClientGrpc.listUser                         avgt       3   5.879 ± 3.704   ms/op
ClientGrpc.createUser                     sample  220578   4.353 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.979           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.923           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.850           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.517           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.324           ms/op
ClientGrpc.existUser                      sample  227714   4.216 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.810           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.733           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.304           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.316           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  216454   4.431 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.147           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.118           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.763           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.396           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.541           ms/op
ClientGrpc.listUser                       sample  163127   5.882 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.444           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.823           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.633           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.675           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.973           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.045           ms/op
