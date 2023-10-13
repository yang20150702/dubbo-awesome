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
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 6.563 ops/ms
# Warmup Iteration   3: 7.834 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.175 ±(99.9%) 7.449 ops/ms [Average]
  (min, avg, max) = (7.732, 8.175, 8.536), stdev = 0.408
  CI (99.9%): [0.726, 15.624] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.410 ops/ms
# Warmup Iteration   2: 8.327 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 9.022 ops/ms
Iteration   2: 8.543 ops/ms
Iteration   3: 9.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.866 ±(99.9%) 5.102 ops/ms [Average]
  (min, avg, max) = (8.543, 8.866, 9.032), stdev = 0.280
  CI (99.9%): [3.764, 13.967] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.028 ops/ms
# Warmup Iteration   2: 7.403 ops/ms
# Warmup Iteration   3: 7.601 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.860 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (7.791, 7.860, 7.957), stdev = 0.086
  CI (99.9%): [6.287, 9.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.323 ops/ms
# Warmup Iteration   2: 6.284 ops/ms
# Warmup Iteration   3: 6.495 ops/ms
Iteration   1: 6.770 ops/ms
Iteration   2: 6.544 ops/ms
Iteration   3: 6.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.664 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (6.544, 6.664, 6.770), stdev = 0.113
  CI (99.9%): [4.599, 8.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.514 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.003 ms/op
Iteration   1: 3.902 ±(99.9%) 0.005 ms/op
Iteration   2: 3.675 ±(99.9%) 0.004 ms/op
Iteration   3: 3.801 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.792 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (3.675, 3.792, 3.902), stdev = 0.114
  CI (99.9%): [1.720, 5.865] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.486 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.004 ms/op
Iteration   1: 3.731 ±(99.9%) 0.005 ms/op
Iteration   2: 3.786 ±(99.9%) 0.004 ms/op
Iteration   3: 3.731 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.749 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.731, 3.749, 3.786), stdev = 0.032
  CI (99.9%): [3.172, 4.326] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.945 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.003 ms/op
Iteration   1: 3.692 ±(99.9%) 0.004 ms/op
Iteration   2: 3.749 ±(99.9%) 0.005 ms/op
Iteration   3: 3.746 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.729 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (3.692, 3.729, 3.749), stdev = 0.032
  CI (99.9%): [3.140, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 7.164 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.013 ms/op
Iteration   1: 4.778 ±(99.9%) 0.022 ms/op
Iteration   2: 4.747 ±(99.9%) 0.010 ms/op
Iteration   3: 4.892 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.805 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (4.747, 4.805, 4.892), stdev = 0.076
  CI (99.9%): [3.413, 6.198] (assumes normal distribution)


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
# Warmup Iteration   1: 5.646 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.010 ms/op
Iteration   1: 4.129 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  14.905 ms/op
                 createUser·p0.9999: 27.763 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  14.221 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 3.907 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.887 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  20.184 ms/op
                 createUser·p0.9999: 32.893 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 239387
  mean =      4.009 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11469 
    [ 2.500,  5.000) = 204340 
    [ 5.000,  7.500) = 20758 
    [ 7.500, 10.000) = 2036 
    [10.000, 12.500) = 467 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     14.805 ms/op
     p(99.9900) =     31.922 ms/op
     p(99.9990) =     33.194 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 5.369 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.011 ms/op
Iteration   1: 3.452 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   3.404 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.993 ms/op
                 existUser·p0.999:  12.036 ms/op
                 existUser·p0.9999: 15.872 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  10.422 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.663 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 20.521 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274924
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16936 
    [ 2.500,  5.000) = 249513 
    [ 5.000,  7.500) = 7342 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.274 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.875 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.010 ms/op
Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  9.604 ms/op
                 getUser·p0.9999: 20.605 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.715 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  13.962 ms/op
                 getUser·p0.9999: 25.191 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.676 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 19.854 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254956
  mean =      3.764 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6357 
    [ 2.500,  5.000) = 233128 
    [ 5.000,  7.500) = 14118 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =     11.913 ms/op
     p(99.9900) =     21.742 ms/op
     p(99.9990) =     25.457 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 7.863 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.782 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.023 ms/op
Iteration   1: 5.231 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   10.576 ms/op
                 listUser·p0.999:  16.462 ms/op
                 listUser·p0.9999: 21.774 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 5.293 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.467 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   8.145 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  19.148 ms/op
                 listUser·p0.9999: 22.281 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 5.209 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.857 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.158 ms/op
                 listUser·p0.999:  21.987 ms/op
                 listUser·p0.9999: 34.135 ms/op
                 listUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183061
  mean =      5.244 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 467 
    [ 2.500,  5.000) = 95836 
    [ 5.000,  7.500) = 73981 
    [ 7.500, 10.000) = 10435 
    [10.000, 12.500) = 1632 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     33.479 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.175 ± 7.449  ops/ms
ClientGrpc.existUser                       thrpt       3   8.866 ± 5.102  ops/ms
ClientGrpc.getUser                         thrpt       3   7.860 ± 1.573  ops/ms
ClientGrpc.listUser                        thrpt       3   6.664 ± 2.065  ops/ms
ClientGrpc.createUser                       avgt       3   3.792 ± 2.073   ms/op
ClientGrpc.existUser                        avgt       3   3.749 ± 0.577   ms/op
ClientGrpc.getUser                          avgt       3   3.729 ± 0.589   ms/op
ClientGrpc.listUser                         avgt       3   4.805 ± 1.392   ms/op
ClientGrpc.createUser                     sample  239387   4.009 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.823           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.750           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.805           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.358           ms/op
ClientGrpc.existUser                      sample  274924   3.491 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.686           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.095           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.289           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  254956   3.764 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.803           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.426           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.742           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.494           ms/op
ClientGrpc.listUser                       sample  183061   5.244 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.467           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.907           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.479           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.472           ms/op
