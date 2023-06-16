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
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 7.402 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 9.196 ops/ms
Iteration   2: 9.122 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.179 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (9.122, 9.179, 9.218), stdev = 0.050
  CI (99.9%): [8.265, 10.092] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.138 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 9.437 ops/ms
Iteration   1: 9.396 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.500 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (9.396, 9.500, 9.602), stdev = 0.103
  CI (99.9%): [7.622, 11.378] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.680 ops/ms
# Warmup Iteration   2: 8.628 ops/ms
# Warmup Iteration   3: 9.001 ops/ms
Iteration   1: 9.199 ops/ms
Iteration   2: 9.151 ops/ms
Iteration   3: 9.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.203 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (9.151, 9.203, 9.259), stdev = 0.054
  CI (99.9%): [8.216, 10.189] (assumes normal distribution)


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
# Warmup Iteration   1: 5.123 ops/ms
# Warmup Iteration   2: 6.453 ops/ms
# Warmup Iteration   3: 6.839 ops/ms
Iteration   1: 6.888 ops/ms
Iteration   2: 7.254 ops/ms
Iteration   3: 7.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.063 ±(99.9%) 3.356 ops/ms [Average]
  (min, avg, max) = (6.888, 7.063, 7.254), stdev = 0.184
  CI (99.9%): [3.707, 10.419] (assumes normal distribution)


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
# Warmup Iteration   1: 5.155 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.023 ms/op
Iteration   1: 3.537 ±(99.9%) 0.006 ms/op
Iteration   2: 3.483 ±(99.9%) 0.004 ms/op
Iteration   3: 3.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.518 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.483, 3.518, 3.537), stdev = 0.030
  CI (99.9%): [2.967, 4.069] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.003 ms/op
Iteration   1: 3.328 ±(99.9%) 0.003 ms/op
Iteration   2: 3.377 ±(99.9%) 0.003 ms/op
Iteration   3: 3.279 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.328 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (3.279, 3.328, 3.377), stdev = 0.049
  CI (99.9%): [2.434, 4.223] (assumes normal distribution)


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
# Warmup Iteration   1: 5.379 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.004 ms/op
Iteration   1: 3.505 ±(99.9%) 0.004 ms/op
Iteration   2: 3.501 ±(99.9%) 0.005 ms/op
Iteration   3: 3.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.511 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.501, 3.511, 3.529), stdev = 0.015
  CI (99.9%): [3.238, 3.785] (assumes normal distribution)


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
# Warmup Iteration   1: 6.567 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.029 ms/op
Iteration   1: 4.604 ±(99.9%) 0.011 ms/op
Iteration   2: 4.503 ±(99.9%) 0.016 ms/op
Iteration   3: 4.559 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.555 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (4.503, 4.555, 4.604), stdev = 0.050
  CI (99.9%): [3.634, 5.477] (assumes normal distribution)


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
# Warmup Iteration   1: 5.271 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.567 ±(99.9%) 0.008 ms/op
Iteration   1: 3.537 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  8.749 ms/op
                 createUser·p0.9999: 15.202 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   2: 3.554 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.925 ms/op
                 createUser·p0.9999: 15.942 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   3: 3.516 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  10.056 ms/op
                 createUser·p0.9999: 28.606 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271727
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8550 
    [ 2.500,  5.000) = 257426 
    [ 5.000,  7.500) = 5133 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.720 ms/op
     p(99.9900) =     28.279 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.007 ms/op
Iteration   1: 3.370 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.319 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 14.287 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 3.395 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  8.012 ms/op
                 existUser·p0.9999: 18.917 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 3.391 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  7.757 ms/op
                 existUser·p0.9999: 17.259 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283482
  mean =      3.385 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9301 
    [ 2.500,  5.000) = 270369 
    [ 5.000,  7.500) = 3451 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.009 ms/op
Iteration   1: 3.502 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  9.847 ms/op
                 getUser·p0.9999: 18.645 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.523 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  11.408 ms/op
                 getUser·p0.9999: 20.899 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   3: 3.566 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 23.582 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 271628
  mean =      3.530 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7850 
    [ 2.500,  5.000) = 259042 
    [ 5.000,  7.500) = 4091 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =      9.181 ms/op
     p(99.9900) =     22.998 ms/op
     p(99.9990) =     25.699 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 6.503 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.014 ms/op
Iteration   1: 4.621 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.035 ms/op
                 listUser·p0.999:  16.561 ms/op
                 listUser·p0.9999: 20.974 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 4.579 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  16.401 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   3: 4.557 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.636 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 25.559 ms/op
                 listUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209370
  mean =      4.585 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 476 
    [ 2.500,  5.000) = 171591 
    [ 5.000,  7.500) = 33603 
    [ 7.500, 10.000) = 3115 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     25.563 ms/op
     p(99.9990) =     27.218 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.179 ± 0.913  ops/ms
ClientGrpc.existUser                       thrpt       3   9.500 ± 1.878  ops/ms
ClientGrpc.getUser                         thrpt       3   9.203 ± 0.987  ops/ms
ClientGrpc.listUser                        thrpt       3   7.063 ± 3.356  ops/ms
ClientGrpc.createUser                       avgt       3   3.518 ± 0.551   ms/op
ClientGrpc.existUser                        avgt       3   3.328 ± 0.895   ms/op
ClientGrpc.getUser                          avgt       3   3.511 ± 0.273   ms/op
ClientGrpc.listUser                         avgt       3   4.555 ± 0.921   ms/op
ClientGrpc.createUser                     sample  271727   3.536 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.638           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.186           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.720           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.279           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.967           ms/op
ClientGrpc.existUser                      sample  283482   3.385 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.267           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.832           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.496           ms/op
ClientGrpc.getUser                        sample  271628   3.530 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.900           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.181           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.998           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  209370   4.585 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.128           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.036           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.563           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.492           ms/op
