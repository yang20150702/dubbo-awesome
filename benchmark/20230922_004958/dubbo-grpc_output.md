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
# Warmup Iteration   1: 2.965 ops/ms
# Warmup Iteration   2: 6.523 ops/ms
# Warmup Iteration   3: 7.655 ops/ms
Iteration   1: 8.344 ops/ms
Iteration   2: 8.434 ops/ms
Iteration   3: 8.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.400 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (8.344, 8.400, 8.434), stdev = 0.049
  CI (99.9%): [7.507, 9.293] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.427 ops/ms
# Warmup Iteration   2: 8.478 ops/ms
# Warmup Iteration   3: 8.758 ops/ms
Iteration   1: 8.987 ops/ms
Iteration   2: 8.616 ops/ms
Iteration   3: 8.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.802 ±(99.9%) 3.382 ops/ms [Average]
  (min, avg, max) = (8.616, 8.802, 8.987), stdev = 0.185
  CI (99.9%): [5.420, 12.184] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.156 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.289 ops/ms
Iteration   2: 8.322 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.335 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (8.289, 8.335, 8.395), stdev = 0.054
  CI (99.9%): [7.347, 9.323] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.681 ops/ms
# Warmup Iteration   2: 5.878 ops/ms
# Warmup Iteration   3: 6.717 ops/ms
Iteration   1: 6.786 ops/ms
Iteration   2: 6.669 ops/ms
Iteration   3: 6.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.710 ±(99.9%) 1.196 ops/ms [Average]
  (min, avg, max) = (6.669, 6.710, 6.786), stdev = 0.066
  CI (99.9%): [5.514, 7.906] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.017 ms/op
Iteration   1: 3.820 ±(99.9%) 0.003 ms/op
Iteration   2: 3.852 ±(99.9%) 0.003 ms/op
Iteration   3: 3.822 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.831 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.820, 3.831, 3.852), stdev = 0.018
  CI (99.9%): [3.508, 4.155] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.265 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.002 ms/op
Iteration   1: 3.670 ±(99.9%) 0.003 ms/op
Iteration   2: 3.529 ±(99.9%) 0.003 ms/op
Iteration   3: 3.733 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.644 ±(99.9%) 1.909 ms/op [Average]
  (min, avg, max) = (3.529, 3.644, 3.733), stdev = 0.105
  CI (99.9%): [1.735, 5.554] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.466 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.004 ms/op
Iteration   1: 3.990 ±(99.9%) 0.004 ms/op
Iteration   2: 3.910 ±(99.9%) 0.004 ms/op
Iteration   3: 3.831 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.910 ±(99.9%) 1.452 ms/op [Average]
  (min, avg, max) = (3.831, 3.910, 3.990), stdev = 0.080
  CI (99.9%): [2.459, 5.362] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.746 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.186 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.744 ±(99.9%) 0.012 ms/op
Iteration   1: 4.814 ±(99.9%) 0.012 ms/op
Iteration   2: 4.783 ±(99.9%) 0.015 ms/op
Iteration   3: 4.795 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.797 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (4.783, 4.797, 4.814), stdev = 0.015
  CI (99.9%): [4.516, 5.079] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.569 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.011 ms/op
Iteration   1: 4.058 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   8.036 ms/op
                 createUser·p0.999:  15.263 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  10.696 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.814 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  20.550 ms/op
                 createUser·p0.9999: 32.557 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245221
  mean =      3.912 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4289 
    [ 2.500,  5.000) = 227071 
    [ 5.000,  7.500) = 11938 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     28.539 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.008 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.134 ms/op
                 existUser·p0.999:  9.496 ms/op
                 existUser·p0.9999: 21.629 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.619 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  9.054 ms/op
                 existUser·p0.9999: 18.431 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.688 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  10.554 ms/op
                 existUser·p0.9999: 22.270 ms/op
                 existUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264650
  mean =      3.629 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3494 
    [ 2.500,  5.000) = 254202 
    [ 5.000,  7.500) = 6096 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      9.328 ms/op
     p(99.9900) =     21.596 ms/op
     p(99.9990) =     23.092 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.410 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.010 ms/op
Iteration   1: 3.852 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  10.943 ms/op
                 getUser·p0.9999: 15.882 ms/op
                 getUser·p1.00:   16.351 ms/op

Iteration   2: 3.775 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.811 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  9.636 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251854
  mean =      3.812 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3081 
    [ 2.500,  5.000) = 240092 
    [ 5.000,  7.500) = 7579 
    [ 7.500, 10.000) = 771 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     10.947 ms/op
     p(99.9900) =     19.217 ms/op
     p(99.9990) =     21.478 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.712 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.206 ±(99.9%) 0.020 ms/op
Iteration   1: 4.906 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   7.143 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 20.234 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.830 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   7.086 ms/op
                 listUser·p0.99:   9.123 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.654 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  21.266 ms/op
                 listUser·p0.9999: 25.383 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200222
  mean =      4.794 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 205 
    [ 2.500,  5.000) = 148978 
    [ 5.000,  7.500) = 44676 
    [ 7.500, 10.000) = 5347 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     18.605 ms/op
     p(99.9900) =     23.853 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.400 ± 0.893  ops/ms
ClientGrpc.existUser                       thrpt       3   8.802 ± 3.382  ops/ms
ClientGrpc.getUser                         thrpt       3   8.335 ± 0.988  ops/ms
ClientGrpc.listUser                        thrpt       3   6.710 ± 1.196  ops/ms
ClientGrpc.createUser                       avgt       3   3.831 ± 0.324   ms/op
ClientGrpc.existUser                        avgt       3   3.644 ± 1.909   ms/op
ClientGrpc.getUser                          avgt       3   3.910 ± 1.452   ms/op
ClientGrpc.listUser                         avgt       3   4.797 ± 0.282   ms/op
ClientGrpc.createUser                     sample  245221   3.912 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.922           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.079           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.053           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.533           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.539           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.079           ms/op
ClientGrpc.existUser                      sample  264650   3.629 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.511           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.328           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.596           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.331           ms/op
ClientGrpc.getUser                        sample  251854   3.812 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.894           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.947           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.217           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  200222   4.794 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.995           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.605           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.853           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
