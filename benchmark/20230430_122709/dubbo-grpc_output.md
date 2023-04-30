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
# Warmup Iteration   1: 4.048 ops/ms
# Warmup Iteration   2: 8.732 ops/ms
# Warmup Iteration   3: 9.880 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.518 ops/ms
Iteration   3: 10.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.453 ±(99.9%) 1.061 ops/ms [Average]
  (min, avg, max) = (10.406, 10.453, 10.518), stdev = 0.058
  CI (99.9%): [9.393, 11.514] (assumes normal distribution)


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
# Warmup Iteration   1: 7.263 ops/ms
# Warmup Iteration   2: 10.672 ops/ms
# Warmup Iteration   3: 10.997 ops/ms
Iteration   1: 11.181 ops/ms
Iteration   2: 10.972 ops/ms
Iteration   3: 11.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.057 ±(99.9%) 2.005 ops/ms [Average]
  (min, avg, max) = (10.972, 11.057, 11.181), stdev = 0.110
  CI (99.9%): [9.052, 13.062] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 10.093 ops/ms
# Warmup Iteration   3: 10.318 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.495 ±(99.9%) 1.343 ops/ms [Average]
  (min, avg, max) = (10.445, 10.495, 10.579), stdev = 0.074
  CI (99.9%): [9.152, 11.838] (assumes normal distribution)


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
# Warmup Iteration   1: 5.468 ops/ms
# Warmup Iteration   2: 7.694 ops/ms
# Warmup Iteration   3: 8.076 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.046 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (7.961, 8.046, 8.156), stdev = 0.100
  CI (99.9%): [6.230, 9.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.356 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.042 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.027, 3.042, 3.060), stdev = 0.017
  CI (99.9%): [2.736, 3.348] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.002 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.888 ±(99.9%) 0.002 ms/op
Iteration   3: 2.881 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.913 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (2.881, 2.913, 2.970), stdev = 0.050
  CI (99.9%): [2.005, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.053, 3.073, 3.088), stdev = 0.018
  CI (99.9%): [2.745, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.006 ms/op
Iteration   1: 3.982 ±(99.9%) 0.008 ms/op
Iteration   2: 3.945 ±(99.9%) 0.014 ms/op
Iteration   3: 3.944 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.957 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (3.944, 3.957, 3.982), stdev = 0.022
  CI (99.9%): [3.564, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.298 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.185 ms/op
                 createUser·p0.9999: 16.471 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.347 ms/op
                 createUser·p0.9999: 18.340 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 35.476 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320190
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25282 
    [ 2.500,  5.000) = 293481 
    [ 5.000,  7.500) = 1021 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     34.202 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.006 ms/op
Iteration   1: 2.815 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.453 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.662 ms/op
                 existUser·p0.9999: 15.630 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   3: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.343 ms/op
                 existUser·p0.9999: 28.336 ms/op
                 existUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332967
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50308 
    [ 2.500,  5.000) = 281417 
    [ 5.000,  7.500) = 900 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.767 ms/op
     p(99.9900) =     16.899 ms/op
     p(99.9990) =     28.727 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.138 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.795 ms/op
                 getUser·p0.9999: 23.624 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 20.929 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313790
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20978 
    [ 2.500,  5.000) = 291231 
    [ 5.000,  7.500) = 1297 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.490 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     22.272 ms/op
     p(99.9990) =     23.851 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 5.575 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 20.452 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.369 ms/op
                 listUser·p0.99:   6.798 ms/op
                 listUser·p0.999:  14.837 ms/op
                 listUser·p0.9999: 23.778 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.567 ms/op
                 listUser·p0.9999: 24.736 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239855
  mean =      4.003 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2287 
    [ 2.500,  5.000) = 213339 
    [ 5.000,  7.500) = 22681 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     14.568 ms/op
     p(99.9900) =     23.561 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.453 ± 1.061  ops/ms
ClientGrpc.existUser                       thrpt       3  11.057 ± 2.005  ops/ms
ClientGrpc.getUser                         thrpt       3  10.495 ± 1.343  ops/ms
ClientGrpc.listUser                        thrpt       3   8.046 ± 1.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.042 ± 0.306   ms/op
ClientGrpc.existUser                        avgt       3   2.913 ± 0.908   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.328   ms/op
ClientGrpc.listUser                         avgt       3   3.957 ± 0.393   ms/op
ClientGrpc.createUser                     sample  320190   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.695           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.364           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.783           ms/op
ClientGrpc.existUser                      sample  332967   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.551           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.767           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.899           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.803           ms/op
ClientGrpc.getUser                        sample  313790   3.058 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.490           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.234           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.272           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.773           ms/op
ClientGrpc.listUser                       sample  239855   4.003 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.048           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.568           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
