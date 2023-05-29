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
# Warmup Iteration   1: 3.240 ops/ms
# Warmup Iteration   2: 6.987 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 8.869 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.887 ±(99.9%) 0.814 ops/ms [Average]
  (min, avg, max) = (8.853, 8.887, 8.937), stdev = 0.045
  CI (99.9%): [8.072, 9.701] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.958 ops/ms
# Warmup Iteration   2: 8.919 ops/ms
# Warmup Iteration   3: 9.423 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.311 ops/ms
Iteration   3: 9.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.413 ±(99.9%) 1.785 ops/ms [Average]
  (min, avg, max) = (9.311, 9.413, 9.506), stdev = 0.098
  CI (99.9%): [7.628, 11.198] (assumes normal distribution)


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
# Warmup Iteration   1: 5.516 ops/ms
# Warmup Iteration   2: 8.389 ops/ms
# Warmup Iteration   3: 8.814 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 8.800 ops/ms
Iteration   3: 8.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.868 ±(99.9%) 1.154 ops/ms [Average]
  (min, avg, max) = (8.800, 8.868, 8.925), stdev = 0.063
  CI (99.9%): [7.715, 10.022] (assumes normal distribution)


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
# Warmup Iteration   1: 4.894 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 6.724 ops/ms
Iteration   1: 6.920 ops/ms
Iteration   2: 6.752 ops/ms
Iteration   3: 6.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.804 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (6.741, 6.804, 6.920), stdev = 0.100
  CI (99.9%): [4.977, 8.632] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.004 ms/op
Iteration   1: 3.596 ±(99.9%) 0.002 ms/op
Iteration   2: 3.541 ±(99.9%) 0.005 ms/op
Iteration   3: 3.540 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.559 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (3.540, 3.559, 3.596), stdev = 0.032
  CI (99.9%): [2.974, 4.144] (assumes normal distribution)


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
# Warmup Iteration   1: 4.882 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.003 ms/op
Iteration   1: 3.399 ±(99.9%) 0.003 ms/op
Iteration   2: 3.336 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.379 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.336, 3.379, 3.404), stdev = 0.038
  CI (99.9%): [2.689, 4.070] (assumes normal distribution)


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
# Warmup Iteration   1: 5.352 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.004 ms/op
Iteration   1: 3.514 ±(99.9%) 0.004 ms/op
Iteration   2: 3.572 ±(99.9%) 0.003 ms/op
Iteration   3: 3.577 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.554 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.514, 3.554, 3.577), stdev = 0.035
  CI (99.9%): [2.918, 4.191] (assumes normal distribution)


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
# Warmup Iteration   1: 6.095 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.820 ±(99.9%) 0.015 ms/op
Iteration   1: 4.735 ±(99.9%) 0.016 ms/op
Iteration   2: 4.616 ±(99.9%) 0.008 ms/op
Iteration   3: 4.725 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.692 ±(99.9%) 1.203 ms/op [Average]
  (min, avg, max) = (4.616, 4.692, 4.735), stdev = 0.066
  CI (99.9%): [3.489, 5.895] (assumes normal distribution)


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.007 ms/op
Iteration   1: 3.579 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  9.934 ms/op
                 createUser·p0.9999: 24.904 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.614 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  10.126 ms/op
                 createUser·p0.9999: 19.895 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   3: 3.593 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  9.417 ms/op
                 createUser·p0.9999: 24.650 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266961
  mean =      3.595 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4959 
    [ 2.500,  5.000) = 255860 
    [ 5.000,  7.500) = 5274 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      9.929 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.007 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 16.008 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   2: 3.378 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 17.408 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   3: 3.472 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.110 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.331 ms/op
                 existUser·p0.9999: 22.669 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281544
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12664 
    [ 2.500,  5.000) = 264280 
    [ 5.000,  7.500) = 3781 
    [ 7.500, 10.000) = 531 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     10.237 ms/op
     p(99.9900) =     21.327 ms/op
     p(99.9990) =     22.878 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 4.989 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.008 ms/op
Iteration   1: 3.615 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  9.675 ms/op
                 getUser·p0.9999: 14.933 ms/op
                 getUser·p1.00:   15.450 ms/op

Iteration   2: 3.546 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  10.612 ms/op
                 getUser·p0.9999: 15.679 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   3: 3.577 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  8.413 ms/op
                 getUser·p0.9999: 19.993 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268319
  mean =      3.579 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7666 
    [ 2.500,  5.000) = 255260 
    [ 5.000,  7.500) = 4719 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.350 ms/op
     p(99.9900) =     19.175 ms/op
     p(99.9990) =     20.402 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.724 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.132 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.759 ±(99.9%) 0.014 ms/op
Iteration   1: 4.732 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  15.341 ms/op
                 listUser·p0.9999: 17.488 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 4.803 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.013 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  15.624 ms/op
                 listUser·p0.9999: 24.423 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   3: 4.740 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 26.067 ms/op
                 listUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201878
  mean =      4.758 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 153637 
    [ 5.000,  7.500) = 43365 
    [ 7.500, 10.000) = 3974 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.685 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     24.191 ms/op
     p(99.9990) =     26.767 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.887 ± 0.814  ops/ms
ClientGrpc.existUser                       thrpt       3   9.413 ± 1.785  ops/ms
ClientGrpc.getUser                         thrpt       3   8.868 ± 1.154  ops/ms
ClientGrpc.listUser                        thrpt       3   6.804 ± 1.828  ops/ms
ClientGrpc.createUser                       avgt       3   3.559 ± 0.585   ms/op
ClientGrpc.existUser                        avgt       3   3.379 ± 0.691   ms/op
ClientGrpc.getUser                          avgt       3   3.554 ± 0.636   ms/op
ClientGrpc.listUser                         avgt       3   4.692 ± 1.203   ms/op
ClientGrpc.createUser                     sample  266961   3.595 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.856           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.609           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.395           ms/op
ClientGrpc.existUser                      sample  281544   3.407 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.689           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.998           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.431           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.237           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.327           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.003           ms/op
ClientGrpc.getUser                        sample  268319   3.579 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.826           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.350           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.175           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  201878   4.758 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.264           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.958           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.191           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.771           ms/op
