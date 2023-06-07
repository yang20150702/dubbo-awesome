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
# Warmup Iteration   1: 4.338 ops/ms
# Warmup Iteration   2: 9.014 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.502 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (10.396, 10.502, 10.579), stdev = 0.095
  CI (99.9%): [8.766, 12.239] (assumes normal distribution)


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
# Warmup Iteration   1: 7.250 ops/ms
# Warmup Iteration   2: 10.504 ops/ms
# Warmup Iteration   3: 11.142 ops/ms
Iteration   1: 10.815 ops/ms
Iteration   2: 10.986 ops/ms
Iteration   3: 11.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.970 ±(99.9%) 2.697 ops/ms [Average]
  (min, avg, max) = (10.815, 10.970, 11.110), stdev = 0.148
  CI (99.9%): [8.273, 13.667] (assumes normal distribution)


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
# Warmup Iteration   1: 7.059 ops/ms
# Warmup Iteration   2: 10.283 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.625 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (10.524, 10.625, 10.728), stdev = 0.102
  CI (99.9%): [8.760, 12.489] (assumes normal distribution)


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
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 7.390 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.098 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (8.044, 8.098, 8.199), stdev = 0.088
  CI (99.9%): [6.491, 9.705] (assumes normal distribution)


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
# Warmup Iteration   1: 4.443 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.085 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.092 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.070, 3.092, 3.122), stdev = 0.026
  CI (99.9%): [2.613, 3.572] (assumes normal distribution)


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
# Warmup Iteration   1: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.904 ±(99.9%) 0.002 ms/op
Iteration   1: 2.877 ±(99.9%) 0.002 ms/op
Iteration   2: 2.880 ±(99.9%) 0.002 ms/op
Iteration   3: 2.860 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.860, 2.872, 2.880), stdev = 0.011
  CI (99.9%): [2.673, 3.072] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.999, 3.028, 3.049), stdev = 0.026
  CI (99.9%): [2.552, 3.504] (assumes normal distribution)


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
# Warmup Iteration   1: 5.394 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.020 ms/op
Iteration   1: 3.959 ±(99.9%) 0.015 ms/op
Iteration   2: 3.926 ±(99.9%) 0.006 ms/op
Iteration   3: 3.952 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.926, 3.946, 3.959), stdev = 0.018
  CI (99.9%): [3.622, 4.270] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.497 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.044 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.491 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  9.294 ms/op
                 createUser·p0.9999: 16.907 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.797 ms/op
                 createUser·p0.9999: 18.197 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  7.761 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315090
  mean =      3.046 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16545 
    [ 2.500,  5.000) = 297469 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     20.168 ms/op
     p(99.9990) =     21.098 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.758 ±(99.9%) 0.006 ms/op
Iteration   1: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.610 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 2.836 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  6.426 ms/op
                 existUser·p0.9999: 15.052 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   3: 2.928 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331468
  mean =      2.893 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40509 
    [ 2.500,  5.000) = 290104 
    [ 5.000,  7.500) = 485 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      8.954 ms/op
     p(99.9900) =     21.366 ms/op
     p(99.9990) =     24.361 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 20.197 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.140 ms/op
                 getUser·p0.9999: 19.291 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.705 ms/op
                 getUser·p0.9999: 19.525 ms/op
                 getUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317937
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17282 
    [ 2.500,  5.000) = 299566 
    [ 5.000,  7.500) = 873 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 5.668 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.010 ms/op
Iteration   1: 3.988 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  15.650 ms/op
                 listUser·p0.9999: 24.696 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 25.362 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  18.832 ms/op
                 listUser·p0.9999: 21.001 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240835
  mean =      3.984 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2364 
    [ 2.500,  5.000) = 215379 
    [ 5.000,  7.500) = 21527 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     25.032 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.502 ± 1.737  ops/ms
ClientGrpc.existUser                       thrpt       3  10.970 ± 2.697  ops/ms
ClientGrpc.getUser                         thrpt       3  10.625 ± 1.864  ops/ms
ClientGrpc.listUser                        thrpt       3   8.098 ± 1.607  ops/ms
ClientGrpc.createUser                       avgt       3   3.092 ± 0.480   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.199   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.476   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.324   ms/op
ClientGrpc.createUser                     sample  315090   3.046 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.491           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.168           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.398           ms/op
ClientGrpc.existUser                      sample  331468   2.893 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.080           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.954           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.068           ms/op
ClientGrpc.getUser                        sample  317937   3.018 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.865           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.399           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.070           ms/op
ClientGrpc.listUser                       sample  240835   3.984 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.767           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.678           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.032           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
