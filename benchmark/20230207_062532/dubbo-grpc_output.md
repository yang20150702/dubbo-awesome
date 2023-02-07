# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ops/ms
# Warmup Iteration   2: 6.899 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.345 ops/ms
Iteration   2: 8.434 ops/ms
Iteration   3: 8.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.302 ±(99.9%) 2.881 ops/ms [Average]
  (min, avg, max) = (8.127, 8.302, 8.434), stdev = 0.158
  CI (99.9%): [5.421, 11.184] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.418 ops/ms
# Warmup Iteration   2: 8.164 ops/ms
# Warmup Iteration   3: 8.722 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 8.776 ops/ms
Iteration   3: 8.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.768 ±(99.9%) 1.434 ops/ms [Average]
  (min, avg, max) = (8.686, 8.768, 8.843), stdev = 0.079
  CI (99.9%): [7.335, 10.202] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.207 ops/ms
# Warmup Iteration   2: 8.179 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.355 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.322 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (8.222, 8.322, 8.389), stdev = 0.088
  CI (99.9%): [6.713, 9.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.945 ops/ms
# Warmup Iteration   2: 6.201 ops/ms
# Warmup Iteration   3: 6.708 ops/ms
Iteration   1: 6.669 ops/ms
Iteration   2: 6.883 ops/ms
Iteration   3: 6.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.759 ±(99.9%) 2.023 ops/ms [Average]
  (min, avg, max) = (6.669, 6.759, 6.883), stdev = 0.111
  CI (99.9%): [4.735, 8.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.005 ms/op
Iteration   1: 3.711 ±(99.9%) 0.003 ms/op
Iteration   2: 3.854 ±(99.9%) 0.002 ms/op
Iteration   3: 3.657 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.741 ±(99.9%) 1.850 ms/op [Average]
  (min, avg, max) = (3.657, 3.741, 3.854), stdev = 0.101
  CI (99.9%): [1.891, 5.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.954 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.003 ms/op
Iteration   1: 3.659 ±(99.9%) 0.003 ms/op
Iteration   2: 3.672 ±(99.9%) 0.002 ms/op
Iteration   3: 3.652 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.661 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.652, 3.661, 3.672), stdev = 0.010
  CI (99.9%): [3.478, 3.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.004 ms/op
Iteration   1: 3.854 ±(99.9%) 0.004 ms/op
Iteration   2: 3.799 ±(99.9%) 0.003 ms/op
Iteration   3: 3.766 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.807 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.766, 3.807, 3.854), stdev = 0.045
  CI (99.9%): [2.992, 4.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.619 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.994 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.011 ms/op
Iteration   1: 4.648 ±(99.9%) 0.014 ms/op
Iteration   2: 4.573 ±(99.9%) 0.005 ms/op
Iteration   3: 4.676 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.632 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (4.573, 4.632, 4.676), stdev = 0.053
  CI (99.9%): [3.662, 5.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.322 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.953 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
Iteration   1: 3.779 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  9.618 ms/op
                 createUser·p0.9999: 20.177 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.756 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  7.600 ms/op
                 createUser·p0.9999: 28.144 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.438 ms/op
                 createUser·p0.50:   3.699 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  10.364 ms/op
                 createUser·p0.9999: 33.419 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255671
  mean =      3.758 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9244 
    [ 2.500,  5.000) = 238195 
    [ 5.000,  7.500) = 7706 
    [ 7.500, 10.000) = 312 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.022 ms/op
     p(99.9900) =     32.436 ms/op
     p(99.9990) =     33.846 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.249 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.008 ms/op
Iteration   1: 3.524 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 15.920 ms/op
                 existUser·p1.00:   16.728 ms/op

Iteration   2: 3.656 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  10.355 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 3.662 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 19.645 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265777
  mean =      3.613 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12528 
    [ 2.500,  5.000) = 248288 
    [ 5.000,  7.500) = 4527 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =      9.752 ms/op
     p(99.9900) =     19.806 ms/op
     p(99.9990) =     20.229 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.398 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.010 ms/op
Iteration   1: 3.774 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   5.566 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 20.709 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 3.704 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  6.547 ms/op
                 getUser·p0.9999: 20.405 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   5.467 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255910
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8957 
    [ 2.500,  5.000) = 239031 
    [ 5.000,  7.500) = 7499 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =     21.837 ms/op
     p(99.9990) =     23.880 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.615 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.012 ms/op
Iteration   1: 4.717 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  15.436 ms/op
                 listUser·p0.9999: 20.941 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   2: 4.737 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.243 ms/op
                 listUser·p0.9999: 19.832 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.797 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  18.624 ms/op
                 listUser·p0.9999: 22.763 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202175
  mean =      4.750 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 627 
    [ 2.500,  5.000) = 151964 
    [ 5.000,  7.500) = 45045 
    [ 7.500, 10.000) = 3944 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.038 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     24.310 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.302 ± 2.881  ops/ms
ClientGrpc.existUser                       thrpt       3   8.768 ± 1.434  ops/ms
ClientGrpc.getUser                         thrpt       3   8.322 ± 1.609  ops/ms
ClientGrpc.listUser                        thrpt       3   6.759 ± 2.023  ops/ms
ClientGrpc.createUser                       avgt       3   3.741 ± 1.850   ms/op
ClientGrpc.existUser                        avgt       3   3.661 ± 0.183   ms/op
ClientGrpc.getUser                          avgt       3   3.807 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   4.632 ± 0.970   ms/op
ClientGrpc.createUser                     sample  255671   3.758 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.438           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.022           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.436           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.948           ms/op
ClientGrpc.existUser                      sample  265777   3.613 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.851           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.752           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.806           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  255910   3.752 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.910           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.348           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.953           ms/op
ClientGrpc.listUser                       sample  202175   4.750 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.348           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.445           ms/op
