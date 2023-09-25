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
# Warmup Iteration   1: 2.823 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 7.925 ops/ms
Iteration   1: 8.494 ops/ms
Iteration   2: 8.473 ops/ms
Iteration   3: 8.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.486 ±(99.9%) 0.205 ops/ms [Average]
  (min, avg, max) = (8.473, 8.486, 8.494), stdev = 0.011
  CI (99.9%): [8.281, 8.691] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.407 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 9.009 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.642 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.387 ±(99.9%) 4.169 ops/ms [Average]
  (min, avg, max) = (9.201, 9.387, 9.642), stdev = 0.229
  CI (99.9%): [5.218, 13.556] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.388 ops/ms
# Warmup Iteration   2: 7.854 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.555 ops/ms
Iteration   2: 8.408 ops/ms
Iteration   3: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.591 ±(99.9%) 3.713 ops/ms [Average]
  (min, avg, max) = (8.408, 8.591, 8.810), stdev = 0.204
  CI (99.9%): [4.878, 12.304] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.500 ops/ms
# Warmup Iteration   2: 6.148 ops/ms
# Warmup Iteration   3: 6.573 ops/ms
Iteration   1: 6.740 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.735 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (6.688, 6.735, 6.777), stdev = 0.044
  CI (99.9%): [5.924, 7.547] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.278 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.012 ms/op
Iteration   1: 3.755 ±(99.9%) 0.004 ms/op
Iteration   2: 3.653 ±(99.9%) 0.003 ms/op
Iteration   3: 3.726 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.711 ±(99.9%) 0.956 ms/op [Average]
  (min, avg, max) = (3.653, 3.711, 3.755), stdev = 0.052
  CI (99.9%): [2.755, 4.668] (assumes normal distribution)


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
# Warmup Iteration   1: 5.247 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.005 ms/op
Iteration   1: 3.640 ±(99.9%) 0.006 ms/op
Iteration   2: 3.566 ±(99.9%) 0.006 ms/op
Iteration   3: 3.423 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.543 ±(99.9%) 2.013 ms/op [Average]
  (min, avg, max) = (3.423, 3.543, 3.640), stdev = 0.110
  CI (99.9%): [1.530, 5.557] (assumes normal distribution)


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.004 ms/op
Iteration   1: 3.757 ±(99.9%) 0.003 ms/op
Iteration   2: 3.725 ±(99.9%) 0.005 ms/op
Iteration   3: 3.663 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.715 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (3.663, 3.715, 3.757), stdev = 0.048
  CI (99.9%): [2.837, 4.593] (assumes normal distribution)


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
# Warmup Iteration   1: 6.561 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.018 ms/op
Iteration   1: 4.738 ±(99.9%) 0.012 ms/op
Iteration   2: 4.720 ±(99.9%) 0.016 ms/op
Iteration   3: 4.756 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.738 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (4.720, 4.738, 4.756), stdev = 0.018
  CI (99.9%): [4.411, 5.065] (assumes normal distribution)


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
# Warmup Iteration   1: 5.304 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.702 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 28.257 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.855 ms/op
                 createUser·p0.9999: 23.973 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.759 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.425 ms/op
                 createUser·p0.999:  18.872 ms/op
                 createUser·p0.9999: 23.265 ms/op
                 createUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256291
  mean =      3.746 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9290 
    [ 2.500,  5.000) = 236009 
    [ 5.000,  7.500) = 9198 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.709 ms/op
     p(99.9900) =     24.043 ms/op
     p(99.9990) =     28.424 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 5.415 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.012 ms/op
Iteration   1: 3.546 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.445 ms/op
                 existUser·p0.999:  17.221 ms/op
                 existUser·p0.9999: 24.017 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   2: 3.600 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.216 ms/op
                 existUser·p0.999:  12.179 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.548 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  12.974 ms/op
                 existUser·p0.9999: 28.278 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269170
  mean =      3.564 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13029 
    [ 2.500,  5.000) = 247899 
    [ 5.000,  7.500) = 6776 
    [ 7.500, 10.000) = 965 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     12.777 ms/op
     p(99.9900) =     26.676 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.907 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.390 ms/op
                 getUser·p0.999:  12.908 ms/op
                 getUser·p0.9999: 22.799 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.729 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  10.965 ms/op
                 getUser·p0.9999: 21.870 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.773 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.341 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255836
  mean =      3.751 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11617 
    [ 2.500,  5.000) = 230630 
    [ 5.000,  7.500) = 11416 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     13.975 ms/op
     p(99.9900) =     25.108 ms/op
     p(99.9990) =     26.047 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 7.135 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.984 ±(99.9%) 0.020 ms/op
Iteration   1: 4.853 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  16.613 ms/op
                 listUser·p0.9999: 19.359 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 4.892 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   10.124 ms/op
                 listUser·p0.999:  22.672 ms/op
                 listUser·p0.9999: 26.180 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   3: 4.766 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   6.267 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  20.801 ms/op
                 listUser·p0.9999: 27.806 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198542
  mean =      4.836 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 817 
    [ 2.500,  5.000) = 141273 
    [ 5.000,  7.500) = 47955 
    [ 7.500, 10.000) = 6776 
    [10.000, 12.500) = 1030 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.423 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     26.743 ms/op
     p(99.9990) =     28.181 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.486 ± 0.205  ops/ms
ClientGrpc.existUser                       thrpt       3   9.387 ± 4.169  ops/ms
ClientGrpc.getUser                         thrpt       3   8.591 ± 3.713  ops/ms
ClientGrpc.listUser                        thrpt       3   6.735 ± 0.811  ops/ms
ClientGrpc.createUser                       avgt       3   3.711 ± 0.956   ms/op
ClientGrpc.existUser                        avgt       3   3.543 ± 2.013   ms/op
ClientGrpc.getUser                          avgt       3   3.715 ± 0.878   ms/op
ClientGrpc.listUser                         avgt       3   4.738 ± 0.327   ms/op
ClientGrpc.createUser                     sample  256291   3.746 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.729           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.701           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.043           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  269170   3.564 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.398           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.373           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.777           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.676           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.738           ms/op
ClientGrpc.getUser                        sample  255836   3.751 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.842           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.119           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.975           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.108           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.182           ms/op
ClientGrpc.listUser                       sample  198542   4.836 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.147           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.547           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.423           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.340           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.617           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.005           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.743           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
