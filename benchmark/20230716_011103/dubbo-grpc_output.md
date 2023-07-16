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
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 5.421 ops/ms
# Warmup Iteration   3: 7.028 ops/ms
Iteration   1: 7.239 ops/ms
Iteration   2: 7.261 ops/ms
Iteration   3: 7.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.466 ±(99.9%) 6.824 ops/ms [Average]
  (min, avg, max) = (7.239, 7.466, 7.898), stdev = 0.374
  CI (99.9%): [0.641, 14.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ops/ms
# Warmup Iteration   2: 7.206 ops/ms
# Warmup Iteration   3: 7.603 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 7.821 ops/ms
Iteration   3: 7.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.835 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (7.813, 7.835, 7.871), stdev = 0.031
  CI (99.9%): [7.265, 8.405] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 7.028 ops/ms
# Warmup Iteration   3: 7.030 ops/ms
Iteration   1: 7.225 ops/ms
Iteration   2: 7.443 ops/ms
Iteration   3: 7.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.340 ±(99.9%) 2.003 ops/ms [Average]
  (min, avg, max) = (7.225, 7.340, 7.443), stdev = 0.110
  CI (99.9%): [5.337, 9.343] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ops/ms
# Warmup Iteration   2: 5.161 ops/ms
# Warmup Iteration   3: 5.724 ops/ms
Iteration   1: 5.469 ops/ms
Iteration   2: 5.688 ops/ms
Iteration   3: 5.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.684 ±(99.9%) 3.867 ops/ms [Average]
  (min, avg, max) = (5.469, 5.684, 5.893), stdev = 0.212
  CI (99.9%): [1.816, 9.551] (assumes normal distribution)


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
# Warmup Iteration   1: 6.929 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.693 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.517 ±(99.9%) 0.014 ms/op
Iteration   1: 4.356 ±(99.9%) 0.005 ms/op
Iteration   2: 4.468 ±(99.9%) 0.003 ms/op
Iteration   3: 4.288 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.371 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (4.288, 4.371, 4.468), stdev = 0.091
  CI (99.9%): [2.711, 6.030] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.254 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.205 ±(99.9%) 0.003 ms/op
Iteration   1: 4.157 ±(99.9%) 0.003 ms/op
Iteration   2: 4.076 ±(99.9%) 0.006 ms/op
Iteration   3: 4.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.093 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (4.045, 4.093, 4.157), stdev = 0.058
  CI (99.9%): [3.036, 5.150] (assumes normal distribution)


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
# Warmup Iteration   1: 7.090 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.006 ms/op
Iteration   1: 4.403 ±(99.9%) 0.004 ms/op
Iteration   2: 4.235 ±(99.9%) 0.004 ms/op
Iteration   3: 4.346 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.328 ±(99.9%) 1.560 ms/op [Average]
  (min, avg, max) = (4.235, 4.328, 4.403), stdev = 0.086
  CI (99.9%): [2.768, 5.888] (assumes normal distribution)


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
# Warmup Iteration   1: 7.932 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.959 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.761 ±(99.9%) 0.016 ms/op
Iteration   1: 5.584 ±(99.9%) 0.012 ms/op
Iteration   2: 5.475 ±(99.9%) 0.031 ms/op
Iteration   3: 5.585 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.548 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (5.475, 5.548, 5.585), stdev = 0.063
  CI (99.9%): [4.390, 6.706] (assumes normal distribution)


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
# Warmup Iteration   1: 6.883 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.014 ms/op
Iteration   1: 4.413 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.918 ms/op
                 createUser·p0.999:  13.306 ms/op
                 createUser·p0.9999: 29.909 ms/op
                 createUser·p1.00:   32.768 ms/op

Iteration   2: 4.394 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  13.488 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   3: 4.323 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  11.111 ms/op
                 createUser·p0.9999: 27.519 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219216
  mean =      4.377 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5169 
    [ 2.500,  5.000) = 174359 
    [ 5.000,  7.500) = 36828 
    [ 7.500, 10.000) = 2022 
    [10.000, 12.500) = 577 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     28.937 ms/op
     p(99.9990) =     32.647 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 5.984 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.011 ms/op
Iteration   1: 4.122 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.054 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  12.901 ms/op
                 existUser·p0.9999: 17.113 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 4.231 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   4.088 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   7.864 ms/op
                 existUser·p0.999:  14.368 ms/op
                 existUser·p0.9999: 18.557 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   3: 4.128 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.406 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230648
  mean =      4.160 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8724 
    [ 2.500,  5.000) = 192320 
    [ 5.000,  7.500) = 27275 
    [ 7.500, 10.000) = 1760 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     21.623 ms/op
     p(99.9990) =     22.567 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 7.345 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.716 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.484 ±(99.9%) 0.011 ms/op
Iteration   1: 4.465 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  12.932 ms/op
                 getUser·p0.9999: 24.407 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 4.497 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  12.057 ms/op
                 getUser·p0.9999: 20.174 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 4.402 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   6.968 ms/op
                 getUser·p0.999:  11.438 ms/op
                 getUser·p0.9999: 29.485 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215434
  mean =      4.454 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3928 
    [ 2.500,  5.000) = 166897 
    [ 5.000,  7.500) = 42804 
    [ 7.500, 10.000) = 1345 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     30.651 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 8.507 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.143 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.721 ±(99.9%) 0.022 ms/op
Iteration   1: 5.778 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.563 ms/op
                 listUser·p0.999:  17.976 ms/op
                 listUser·p0.9999: 22.658 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 5.639 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   10.157 ms/op
                 listUser·p0.999:  17.409 ms/op
                 listUser·p0.9999: 22.247 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   3: 5.868 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   13.402 ms/op
                 listUser·p0.999:  22.136 ms/op
                 listUser·p0.9999: 24.318 ms/op
                 listUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166623
  mean =      5.760 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 46428 
    [ 5.000,  7.500) = 104286 
    [ 7.500, 10.000) = 12414 
    [10.000, 12.500) = 2271 
    [12.500, 15.000) = 511 
    [15.000, 17.500) = 282 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     23.102 ms/op
     p(99.9990) =     26.543 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.466 ± 6.824  ops/ms
ClientGrpc.existUser                       thrpt       3   7.835 ± 0.570  ops/ms
ClientGrpc.getUser                         thrpt       3   7.340 ± 2.003  ops/ms
ClientGrpc.listUser                        thrpt       3   5.684 ± 3.867  ops/ms
ClientGrpc.createUser                       avgt       3   4.371 ± 1.659   ms/op
ClientGrpc.existUser                        avgt       3   4.093 ± 1.057   ms/op
ClientGrpc.getUser                          avgt       3   4.328 ± 1.560   ms/op
ClientGrpc.listUser                         avgt       3   5.548 ± 1.158   ms/op
ClientGrpc.createUser                     sample  219216   4.377 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.031           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.399           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.004           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.937           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.768           ms/op
ClientGrpc.existUser                      sample  230648   4.160 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.926           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.652           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.528           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.468           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.623           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.577           ms/op
ClientGrpc.getUser                        sample  215434   4.454 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.813           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.201           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.846           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.477           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.802           ms/op
ClientGrpc.listUser                       sample  166623   5.760 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.368           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.321           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.464           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.102           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
