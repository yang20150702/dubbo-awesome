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
# Warmup Iteration   1: 2.981 ops/ms
# Warmup Iteration   2: 6.504 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.397 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.356 ±(99.9%) 0.663 ops/ms [Average]
  (min, avg, max) = (8.331, 8.356, 8.397), stdev = 0.036
  CI (99.9%): [7.693, 9.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.657 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 8.929 ops/ms
Iteration   2: 8.677 ops/ms
Iteration   3: 9.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.023 ±(99.9%) 7.325 ops/ms [Average]
  (min, avg, max) = (8.677, 9.023, 9.464), stdev = 0.402
  CI (99.9%): [1.698, 16.349] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.488 ops/ms
# Warmup Iteration   2: 8.101 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.349 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.364 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (8.342, 8.364, 8.402), stdev = 0.032
  CI (99.9%): [7.772, 8.957] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ops/ms
# Warmup Iteration   2: 6.483 ops/ms
# Warmup Iteration   3: 6.856 ops/ms
Iteration   1: 6.648 ops/ms
Iteration   2: 6.720 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.703 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (6.648, 6.703, 6.743), stdev = 0.050
  CI (99.9%): [5.795, 7.612] (assumes normal distribution)


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
# Warmup Iteration   1: 5.359 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.019 ms/op
Iteration   1: 3.843 ±(99.9%) 0.003 ms/op
Iteration   2: 3.775 ±(99.9%) 0.006 ms/op
Iteration   3: 3.785 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.801 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.775, 3.801, 3.843), stdev = 0.037
  CI (99.9%): [3.130, 4.472] (assumes normal distribution)


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
# Warmup Iteration   1: 5.101 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.004 ms/op
Iteration   1: 3.665 ±(99.9%) 0.006 ms/op
Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
Iteration   3: 3.684 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.622 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (3.518, 3.622, 3.684), stdev = 0.091
  CI (99.9%): [1.963, 5.281] (assumes normal distribution)


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
# Warmup Iteration   1: 5.602 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.007 ms/op
Iteration   1: 3.854 ±(99.9%) 0.007 ms/op
Iteration   2: 3.863 ±(99.9%) 0.006 ms/op
Iteration   3: 3.857 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.858 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (3.854, 3.858, 3.863), stdev = 0.004
  CI (99.9%): [3.779, 3.937] (assumes normal distribution)


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
# Warmup Iteration   1: 7.274 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.806 ±(99.9%) 0.018 ms/op
Iteration   1: 4.746 ±(99.9%) 0.013 ms/op
Iteration   2: 4.683 ±(99.9%) 0.011 ms/op
Iteration   3: 4.826 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.752 ±(99.9%) 1.306 ms/op [Average]
  (min, avg, max) = (4.683, 4.752, 4.826), stdev = 0.072
  CI (99.9%): [3.446, 6.058] (assumes normal distribution)


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
# Warmup Iteration   1: 5.896 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.010 ms/op
Iteration   1: 3.736 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  14.434 ms/op
                 createUser·p0.9999: 53.075 ms/op
                 createUser·p1.00:   53.477 ms/op

Iteration   2: 3.760 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.656 ms/op
                 createUser·p0.999:  18.902 ms/op
                 createUser·p0.9999: 20.513 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.798 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.839 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  22.208 ms/op
                 createUser·p0.9999: 28.691 ms/op
                 createUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255132
  mean =      3.765 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 245365 
    [ 5.000, 10.000) = 8994 
    [10.000, 15.000) = 443 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 71 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     52.232 ms/op
     p(99.9990) =     53.412 ms/op
     p(99.9999) =     53.477 ms/op
    p(100.0000) =     53.477 ms/op


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.010 ms/op
Iteration   1: 3.578 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  12.112 ms/op
                 existUser·p0.9999: 26.903 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 3.561 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  11.781 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   3: 3.651 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.810 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  12.390 ms/op
                 existUser·p0.9999: 25.542 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 266988
  mean =      3.596 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12230 
    [ 2.500,  5.000) = 247577 
    [ 5.000,  7.500) = 6136 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     25.546 ms/op
     p(99.9990) =     27.012 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  10.560 ms/op
                 getUser·p0.9999: 17.453 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.884 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.339 ms/op
                 getUser·p0.50:   3.803 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  10.923 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.751 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 20.823 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251408
  mean =      3.818 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7026 
    [ 2.500,  5.000) = 232314 
    [ 5.000,  7.500) = 10872 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     11.282 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.987 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.512 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.050 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.912 ±(99.9%) 0.017 ms/op
Iteration   1: 4.863 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 16.494 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 4.898 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.537 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  22.567 ms/op
                 listUser·p0.9999: 28.377 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   3: 4.910 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.435 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  22.635 ms/op
                 listUser·p0.9999: 31.897 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196280
  mean =      4.890 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 608 
    [ 2.500,  5.000) = 136910 
    [ 5.000,  7.500) = 50013 
    [ 7.500, 10.000) = 7386 
    [10.000, 12.500) = 794 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     18.590 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     32.543 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.356 ± 0.663  ops/ms
ClientGrpc.existUser                       thrpt       3   9.023 ± 7.325  ops/ms
ClientGrpc.getUser                         thrpt       3   8.364 ± 0.592  ops/ms
ClientGrpc.listUser                        thrpt       3   6.703 ± 0.908  ops/ms
ClientGrpc.createUser                       avgt       3   3.801 ± 0.671   ms/op
ClientGrpc.existUser                        avgt       3   3.622 ± 1.659   ms/op
ClientGrpc.getUser                          avgt       3   3.858 ± 0.079   ms/op
ClientGrpc.listUser                         avgt       3   4.752 ± 1.306   ms/op
ClientGrpc.createUser                     sample  255132   3.765 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.782           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.334           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          52.232           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          53.477           ms/op
ClientGrpc.existUser                      sample  266988   3.596 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.810           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.141           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.546           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.034           ms/op
ClientGrpc.getUser                        sample  251408   3.818 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.339           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.282           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.349           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  196280   4.890 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.439           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.381           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.590           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.179           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.670           ms/op
