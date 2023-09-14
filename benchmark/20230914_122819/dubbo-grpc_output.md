# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ops/ms
# Warmup Iteration   2: 6.617 ops/ms
# Warmup Iteration   3: 7.774 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.358 ±(99.9%) 4.708 ops/ms [Average]
  (min, avg, max) = (8.060, 8.358, 8.522), stdev = 0.258
  CI (99.9%): [3.649, 13.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.403 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.094 ops/ms
Iteration   2: 9.003 ops/ms
Iteration   3: 8.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.007 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (8.925, 9.007, 9.094), stdev = 0.085
  CI (99.9%): [7.457, 10.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.602 ops/ms
# Warmup Iteration   2: 8.083 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 8.502 ops/ms
Iteration   2: 8.676 ops/ms
Iteration   3: 8.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.588 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (8.502, 8.588, 8.676), stdev = 0.087
  CI (99.9%): [6.997, 10.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.273 ops/ms
# Warmup Iteration   2: 5.826 ops/ms
# Warmup Iteration   3: 6.184 ops/ms
Iteration   1: 6.392 ops/ms
Iteration   2: 6.545 ops/ms
Iteration   3: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.520 ±(99.9%) 2.138 ops/ms [Average]
  (min, avg, max) = (6.392, 6.520, 6.622), stdev = 0.117
  CI (99.9%): [4.381, 8.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.516 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.006 ms/op
Iteration   1: 3.883 ±(99.9%) 0.003 ms/op
Iteration   2: 3.841 ±(99.9%) 0.003 ms/op
Iteration   3: 3.849 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.858 ±(99.9%) 0.403 ms/op [Average]
  (min, avg, max) = (3.841, 3.858, 3.883), stdev = 0.022
  CI (99.9%): [3.455, 4.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.240 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.004 ms/op
Iteration   1: 3.801 ±(99.9%) 0.003 ms/op
Iteration   2: 3.613 ±(99.9%) 0.004 ms/op
Iteration   3: 3.749 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.721 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (3.613, 3.721, 3.801), stdev = 0.097
  CI (99.9%): [1.950, 5.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.320 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.004 ms/op
Iteration   1: 3.793 ±(99.9%) 0.004 ms/op
Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
Iteration   3: 4.023 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.915 ±(99.9%) 2.108 ms/op [Average]
  (min, avg, max) = (3.793, 3.915, 4.023), stdev = 0.116
  CI (99.9%): [1.807, 6.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.166 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.412 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.096 ±(99.9%) 0.013 ms/op
Iteration   1: 5.154 ±(99.9%) 0.014 ms/op
Iteration   2: 4.931 ±(99.9%) 0.006 ms/op
Iteration   3: 5.091 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.059 ±(99.9%) 2.095 ms/op [Average]
  (min, avg, max) = (4.931, 5.059, 5.154), stdev = 0.115
  CI (99.9%): [2.964, 7.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.186 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
Iteration   1: 3.751 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  12.988 ms/op
                 createUser·p0.9999: 16.179 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   2: 3.878 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  10.128 ms/op
                 createUser·p0.9999: 21.783 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.886 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.587 ms/op
                 createUser·p0.999:  18.383 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250061
  mean =      3.837 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8391 
    [ 2.500,  5.000) = 226614 
    [ 5.000,  7.500) = 13081 
    [ 7.500, 10.000) = 1459 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.008 ms/op
Iteration   1: 3.544 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  13.091 ms/op
                 existUser·p0.9999: 25.002 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.572 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.412 ms/op
                 existUser·p0.999:  11.621 ms/op
                 existUser·p0.9999: 20.058 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 3.487 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  15.833 ms/op
                 existUser·p0.9999: 24.019 ms/op
                 existUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271926
  mean =      3.534 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8123 
    [ 2.500,  5.000) = 258001 
    [ 5.000,  7.500) = 4478 
    [ 7.500, 10.000) = 815 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     11.994 ms/op
     p(99.9900) =     24.045 ms/op
     p(99.9990) =     25.104 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.445 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.009 ms/op
Iteration   1: 3.663 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.634 ms/op
                 getUser·p0.999:  10.885 ms/op
                 getUser·p0.9999: 14.591 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 3.556 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  10.517 ms/op
                 getUser·p0.9999: 15.696 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   3: 3.635 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  8.217 ms/op
                 getUser·p0.9999: 19.438 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265330
  mean =      3.618 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6563 
    [ 2.500,  5.000) = 252659 
    [ 5.000,  7.500) = 5274 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     17.496 ms/op
     p(99.9990) =     20.295 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.986 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.351 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.759 ±(99.9%) 0.016 ms/op
Iteration   1: 4.818 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  16.460 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 4.999 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.335 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  18.057 ms/op
                 listUser·p0.9999: 21.129 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.974 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  23.673 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194604
  mean =      4.929 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 132725 
    [ 5.000,  7.500) = 53115 
    [ 7.500, 10.000) = 6931 
    [10.000, 12.500) = 1059 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     18.016 ms/op
     p(99.9900) =     30.384 ms/op
     p(99.9990) =     32.377 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.358 ± 4.708  ops/ms
ClientGrpc.existUser                       thrpt       3   9.007 ± 1.551  ops/ms
ClientGrpc.getUser                         thrpt       3   8.588 ± 1.591  ops/ms
ClientGrpc.listUser                        thrpt       3   6.520 ± 2.138  ops/ms
ClientGrpc.createUser                       avgt       3   3.858 ± 0.403   ms/op
ClientGrpc.existUser                        avgt       3   3.721 ± 1.771   ms/op
ClientGrpc.getUser                          avgt       3   3.915 ± 2.108   ms/op
ClientGrpc.listUser                         avgt       3   5.059 ± 2.095   ms/op
ClientGrpc.createUser                     sample  250061   3.837 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.128           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.045           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.592           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.524           ms/op
ClientGrpc.existUser                      sample  271926   3.534 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.994           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.045           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  265330   3.618 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.699           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.273           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.496           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  194604   4.929 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.634           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.016           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.384           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.408           ms/op
