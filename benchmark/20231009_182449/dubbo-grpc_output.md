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
# Warmup Iteration   1: 2.312 ops/ms
# Warmup Iteration   2: 6.074 ops/ms
# Warmup Iteration   3: 7.807 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.204 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (8.073, 8.204, 8.396), stdev = 0.170
  CI (99.9%): [5.097, 11.311] (assumes normal distribution)


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
# Warmup Iteration   1: 5.197 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.733 ops/ms
Iteration   1: 8.767 ops/ms
Iteration   2: 8.800 ops/ms
Iteration   3: 8.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.824 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (8.767, 8.824, 8.907), stdev = 0.073
  CI (99.9%): [7.491, 10.157] (assumes normal distribution)


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
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.115 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.152 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (8.057, 8.152, 8.284), stdev = 0.118
  CI (99.9%): [6.000, 10.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ops/ms
# Warmup Iteration   2: 6.527 ops/ms
# Warmup Iteration   3: 6.828 ops/ms
Iteration   1: 6.654 ops/ms
Iteration   2: 6.286 ops/ms
Iteration   3: 6.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.337 ±(99.9%) 5.390 ops/ms [Average]
  (min, avg, max) = (6.070, 6.337, 6.654), stdev = 0.295
  CI (99.9%): [0.946, 11.727] (assumes normal distribution)


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
# Warmup Iteration   1: 5.845 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.003 ms/op
Iteration   1: 3.699 ±(99.9%) 0.003 ms/op
Iteration   2: 3.727 ±(99.9%) 0.002 ms/op
Iteration   3: 3.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.649 ±(99.9%) 2.041 ms/op [Average]
  (min, avg, max) = (3.521, 3.649, 3.727), stdev = 0.112
  CI (99.9%): [1.608, 5.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.072 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.002 ms/op
Iteration   1: 3.400 ±(99.9%) 0.002 ms/op
Iteration   2: 3.495 ±(99.9%) 0.001 ms/op
Iteration   3: 3.576 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.490 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (3.400, 3.490, 3.576), stdev = 0.088
  CI (99.9%): [1.880, 5.100] (assumes normal distribution)


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.003 ms/op
Iteration   1: 3.757 ±(99.9%) 0.003 ms/op
Iteration   2: 3.841 ±(99.9%) 0.002 ms/op
Iteration   3: 3.676 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.758 ±(99.9%) 1.505 ms/op [Average]
  (min, avg, max) = (3.676, 3.758, 3.841), stdev = 0.082
  CI (99.9%): [2.254, 5.263] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.924 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.709 ±(99.9%) 0.010 ms/op
Iteration   1: 4.691 ±(99.9%) 0.017 ms/op
Iteration   2: 4.600 ±(99.9%) 0.005 ms/op
Iteration   3: 4.745 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.679 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (4.600, 4.679, 4.745), stdev = 0.073
  CI (99.9%): [3.344, 6.013] (assumes normal distribution)


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
# Warmup Iteration   1: 5.090 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.010 ms/op
Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.138 ms/op
                 createUser·p0.99:   6.659 ms/op
                 createUser·p0.999:  10.504 ms/op
                 createUser·p0.9999: 13.707 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 3.721 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  10.757 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.671 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259116
  mean =      3.705 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5303 
    [ 2.500,  5.000) = 239197 
    [ 5.000,  7.500) = 13177 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.966 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.135 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
Iteration   1: 3.476 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.465 ms/op
                 existUser·p0.9999: 14.300 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 3.457 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.685 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  12.327 ms/op
                 existUser·p0.9999: 17.326 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  7.418 ms/op
                 existUser·p0.9999: 16.490 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280176
  mean =      3.426 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 10497 
    [ 2.500,  3.750) = 201031 
    [ 3.750,  5.000) = 60696 
    [ 5.000,  6.250) = 5800 
    [ 6.250,  7.500) = 1201 
    [ 7.500,  8.750) = 319 
    [ 8.750, 10.000) = 147 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.664 ms/op
     p(99.9900) =     16.695 ms/op
     p(99.9990) =     17.589 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.010 ms/op
Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  11.754 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   2: 3.700 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  8.545 ms/op
                 getUser·p0.9999: 28.773 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 29.293 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255598
  mean =      3.755 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4716 
    [ 2.500,  5.000) = 234248 
    [ 5.000,  7.500) = 15138 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     11.443 ms/op
     p(99.9900) =     28.523 ms/op
     p(99.9990) =     30.230 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 7.020 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.019 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.015 ms/op
Iteration   1: 4.888 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.127 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  15.738 ms/op
                 listUser·p0.9999: 18.267 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 4.953 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.316 ms/op
                 listUser·p0.95:   7.132 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 20.730 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.963 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  16.605 ms/op
                 listUser·p0.9999: 19.908 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194456
  mean =      4.934 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 390 
    [ 2.500,  5.000) = 124879 
    [ 5.000,  7.500) = 61680 
    [ 7.500, 10.000) = 6141 
    [10.000, 12.500) = 710 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     20.240 ms/op
     p(99.9990) =     22.674 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.204 ± 3.107  ops/ms
ClientGrpc.existUser                       thrpt       3   8.824 ± 1.333  ops/ms
ClientGrpc.getUser                         thrpt       3   8.152 ± 2.152  ops/ms
ClientGrpc.listUser                        thrpt       3   6.337 ± 5.390  ops/ms
ClientGrpc.createUser                       avgt       3   3.649 ± 2.041   ms/op
ClientGrpc.existUser                        avgt       3   3.490 ± 1.610   ms/op
ClientGrpc.getUser                          avgt       3   3.758 ± 1.505   ms/op
ClientGrpc.listUser                         avgt       3   4.679 ± 1.335   ms/op
ClientGrpc.createUser                     sample  259116   3.705 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.807           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.071           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.480           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.054           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.070           ms/op
ClientGrpc.existUser                      sample  280176   3.426 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.805           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.664           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.695           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  255598   3.755 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.734           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.443           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.523           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.752           ms/op
ClientGrpc.listUser                       sample  194456   4.934 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.227           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.322           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.646           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.240           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.200           ms/op
