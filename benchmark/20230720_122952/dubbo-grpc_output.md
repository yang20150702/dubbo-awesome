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
# Warmup Iteration   1: 3.141 ops/ms
# Warmup Iteration   2: 6.862 ops/ms
# Warmup Iteration   3: 8.489 ops/ms
Iteration   1: 8.848 ops/ms
Iteration   2: 8.722 ops/ms
Iteration   3: 8.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.771 ±(99.9%) 1.231 ops/ms [Average]
  (min, avg, max) = (8.722, 8.771, 8.848), stdev = 0.067
  CI (99.9%): [7.540, 10.002] (assumes normal distribution)


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
# Warmup Iteration   1: 5.931 ops/ms
# Warmup Iteration   2: 8.691 ops/ms
# Warmup Iteration   3: 9.201 ops/ms
Iteration   1: 9.416 ops/ms
Iteration   2: 9.247 ops/ms
Iteration   3: 9.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.367 ±(99.9%) 1.916 ops/ms [Average]
  (min, avg, max) = (9.247, 9.367, 9.439), stdev = 0.105
  CI (99.9%): [7.452, 11.283] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.268 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.925 ops/ms
Iteration   1: 8.955 ops/ms
Iteration   2: 8.975 ops/ms
Iteration   3: 8.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.882 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (8.716, 8.882, 8.975), stdev = 0.144
  CI (99.9%): [6.250, 11.514] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ops/ms
# Warmup Iteration   2: 6.421 ops/ms
# Warmup Iteration   3: 6.684 ops/ms
Iteration   1: 6.883 ops/ms
Iteration   2: 6.926 ops/ms
Iteration   3: 6.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.914 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (6.883, 6.914, 6.931), stdev = 0.026
  CI (99.9%): [6.433, 7.394] (assumes normal distribution)


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
# Warmup Iteration   1: 5.378 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.018 ms/op
Iteration   1: 3.680 ±(99.9%) 0.004 ms/op
Iteration   2: 3.647 ±(99.9%) 0.003 ms/op
Iteration   3: 3.611 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.646 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.611, 3.646, 3.680), stdev = 0.034
  CI (99.9%): [3.017, 4.275] (assumes normal distribution)


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
# Warmup Iteration   1: 5.305 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.003 ms/op
Iteration   1: 3.436 ±(99.9%) 0.002 ms/op
Iteration   2: 3.397 ±(99.9%) 0.004 ms/op
Iteration   3: 3.458 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.430 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.397, 3.430, 3.458), stdev = 0.031
  CI (99.9%): [2.870, 3.991] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.003 ms/op
Iteration   1: 3.595 ±(99.9%) 0.003 ms/op
Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
Iteration   3: 3.620 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.636 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.595, 3.636, 3.692), stdev = 0.050
  CI (99.9%): [2.726, 4.546] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.016 ms/op
Iteration   1: 4.693 ±(99.9%) 0.013 ms/op
Iteration   2: 4.733 ±(99.9%) 0.012 ms/op
Iteration   3: 4.734 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.720 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (4.693, 4.720, 4.734), stdev = 0.023
  CI (99.9%): [4.296, 5.144] (assumes normal distribution)


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
# Warmup Iteration   1: 5.722 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
Iteration   1: 3.634 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  12.303 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   2: 3.667 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.640 ms/op
                 createUser·p0.999:  9.000 ms/op
                 createUser·p0.9999: 15.177 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.679 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.715 ms/op
                 createUser·p0.999:  14.271 ms/op
                 createUser·p0.9999: 31.140 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262321
  mean =      3.660 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8245 
    [ 2.500,  5.000) = 247757 
    [ 5.000,  7.500) = 5708 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.831 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     31.400 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 5.196 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.008 ms/op
Iteration   1: 3.447 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  7.528 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 3.438 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  8.484 ms/op
                 existUser·p0.9999: 26.433 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 3.452 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 18.440 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278810
  mean =      3.446 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7712 
    [ 2.500,  5.000) = 267442 
    [ 5.000,  7.500) = 3135 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     25.895 ms/op
     p(99.9990) =     26.753 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.009 ms/op
Iteration   1: 3.617 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 15.698 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  8.194 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.610 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 19.899 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265733
  mean =      3.613 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8404 
    [ 2.500,  5.000) = 252100 
    [ 5.000,  7.500) = 4684 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.491 ms/op
     p(99.9900) =     19.080 ms/op
     p(99.9990) =     22.787 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.284 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.832 ±(99.9%) 0.015 ms/op
Iteration   1: 4.718 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.586 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  14.978 ms/op
                 listUser·p0.9999: 21.568 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 4.726 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 23.273 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.663 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.570 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  19.806 ms/op
                 listUser·p0.9999: 21.833 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204163
  mean =      4.702 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 261 
    [ 2.500,  5.000) = 161332 
    [ 5.000,  7.500) = 38181 
    [ 7.500, 10.000) = 3703 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.652 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.686 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.771 ± 1.231  ops/ms
ClientGrpc.existUser                       thrpt       3   9.367 ± 1.916  ops/ms
ClientGrpc.getUser                         thrpt       3   8.882 ± 2.632  ops/ms
ClientGrpc.listUser                        thrpt       3   6.914 ± 0.480  ops/ms
ClientGrpc.createUser                       avgt       3   3.646 ± 0.629   ms/op
ClientGrpc.existUser                        avgt       3   3.430 ± 0.561   ms/op
ClientGrpc.getUser                          avgt       3   3.636 ± 0.910   ms/op
ClientGrpc.listUser                         avgt       3   4.720 ± 0.424   ms/op
ClientGrpc.createUser                     sample  262321   3.660 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.853           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.831           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.900           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.556           ms/op
ClientGrpc.existUser                      sample  278810   3.446 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.730           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.895           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.837           ms/op
ClientGrpc.getUser                        sample  265733   3.613 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.491           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.080           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  204163   4.702 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.214           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.538           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.055           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
