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
# Warmup Iteration   1: 3.090 ops/ms
# Warmup Iteration   2: 7.046 ops/ms
# Warmup Iteration   3: 8.288 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.854 ops/ms
Iteration   3: 8.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.649 ±(99.9%) 4.352 ops/ms [Average]
  (min, avg, max) = (8.387, 8.649, 8.854), stdev = 0.239
  CI (99.9%): [4.297, 13.001] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.073 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 9.260 ops/ms
Iteration   1: 9.095 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.186 ±(99.9%) 2.414 ops/ms [Average]
  (min, avg, max) = (9.095, 9.186, 9.337), stdev = 0.132
  CI (99.9%): [6.772, 11.600] (assumes normal distribution)


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
# Warmup Iteration   1: 5.364 ops/ms
# Warmup Iteration   2: 7.932 ops/ms
# Warmup Iteration   3: 8.488 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.570 ±(99.9%) 1.175 ops/ms [Average]
  (min, avg, max) = (8.509, 8.570, 8.637), stdev = 0.064
  CI (99.9%): [7.395, 9.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.781 ops/ms
# Warmup Iteration   2: 6.026 ops/ms
# Warmup Iteration   3: 6.830 ops/ms
Iteration   1: 6.797 ops/ms
Iteration   2: 6.697 ops/ms
Iteration   3: 6.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.758 ±(99.9%) 0.980 ops/ms [Average]
  (min, avg, max) = (6.697, 6.758, 6.797), stdev = 0.054
  CI (99.9%): [5.778, 7.738] (assumes normal distribution)


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
# Warmup Iteration   1: 5.520 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.004 ms/op
Iteration   1: 3.686 ±(99.9%) 0.005 ms/op
Iteration   2: 3.695 ±(99.9%) 0.004 ms/op
Iteration   3: 3.691 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.691 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (3.686, 3.691, 3.695), stdev = 0.004
  CI (99.9%): [3.615, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 5.373 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.007 ms/op
Iteration   1: 3.498 ±(99.9%) 0.004 ms/op
Iteration   2: 3.480 ±(99.9%) 0.003 ms/op
Iteration   3: 3.588 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.522 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.480, 3.522, 3.588), stdev = 0.058
  CI (99.9%): [2.459, 4.585] (assumes normal distribution)


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.004 ms/op
Iteration   1: 3.728 ±(99.9%) 0.003 ms/op
Iteration   2: 3.743 ±(99.9%) 0.007 ms/op
Iteration   3: 3.687 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.719 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.687, 3.719, 3.743), stdev = 0.029
  CI (99.9%): [3.188, 4.250] (assumes normal distribution)


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
# Warmup Iteration   1: 6.855 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.084 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.776 ±(99.9%) 0.013 ms/op
Iteration   1: 4.675 ±(99.9%) 0.024 ms/op
Iteration   2: 4.608 ±(99.9%) 0.008 ms/op
Iteration   3: 4.717 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.667 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (4.608, 4.667, 4.717), stdev = 0.055
  CI (99.9%): [3.671, 5.663] (assumes normal distribution)


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
# Warmup Iteration   1: 5.643 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.008 ms/op
Iteration   1: 3.680 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  11.607 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.683 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.633 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  13.544 ms/op
                 createUser·p0.9999: 29.774 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   3: 3.684 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 34.425 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260575
  mean =      3.682 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6230 
    [ 2.500,  5.000) = 246859 
    [ 5.000,  7.500) = 6647 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     32.895 ms/op
     p(99.9990) =     34.825 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.009 ms/op
Iteration   1: 3.448 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.428 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   2: 3.499 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.927 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  7.586 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 275757
  mean =      3.479 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9584 
    [ 2.500,  5.000) = 261487 
    [ 5.000,  7.500) = 4140 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     21.051 ms/op
     p(99.9990) =     21.537 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 5.688 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.009 ms/op
Iteration   1: 3.677 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.935 ms/op
                 getUser·p0.999:  10.670 ms/op
                 getUser·p0.9999: 15.340 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   2: 3.750 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  9.610 ms/op
                 getUser·p0.9999: 16.432 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.748 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.137 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257709
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8690 
    [ 2.500,  5.000) = 241301 
    [ 5.000,  7.500) = 7038 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      9.529 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     19.983 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 6.894 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.782 ±(99.9%) 0.015 ms/op
Iteration   1: 4.781 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.865 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  16.581 ms/op
                 listUser·p0.9999: 23.338 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 4.646 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  15.797 ms/op
                 listUser·p0.9999: 23.859 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.800 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.905 ms/op
                 listUser·p0.999:  19.595 ms/op
                 listUser·p0.9999: 22.490 ms/op
                 listUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202478
  mean =      4.742 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 454 
    [ 2.500,  5.000) = 156355 
    [ 5.000,  7.500) = 40665 
    [ 7.500, 10.000) = 4143 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     23.708 ms/op
     p(99.9990) =     24.737 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.649 ± 4.352  ops/ms
ClientGrpc.existUser                       thrpt       3   9.186 ± 2.414  ops/ms
ClientGrpc.getUser                         thrpt       3   8.570 ± 1.175  ops/ms
ClientGrpc.listUser                        thrpt       3   6.758 ± 0.980  ops/ms
ClientGrpc.createUser                       avgt       3   3.691 ± 0.076   ms/op
ClientGrpc.existUser                        avgt       3   3.522 ± 1.063   ms/op
ClientGrpc.getUser                          avgt       3   3.719 ± 0.531   ms/op
ClientGrpc.listUser                         avgt       3   4.667 ± 0.996   ms/op
ClientGrpc.createUser                     sample  260575   3.682 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.969           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.849           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.977           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.895           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.931           ms/op
ClientGrpc.existUser                      sample  275757   3.479 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.847           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.011           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.051           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.594           ms/op
ClientGrpc.getUser                        sample  257709   3.725 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.855           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.529           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.383           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  202478   4.742 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.167           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.708           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
