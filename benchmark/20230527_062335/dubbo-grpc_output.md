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
# Warmup Iteration   1: 4.259 ops/ms
# Warmup Iteration   2: 8.703 ops/ms
# Warmup Iteration   3: 9.593 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 10.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.115 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (10.020, 10.115, 10.175), stdev = 0.083
  CI (99.9%): [8.595, 11.635] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.691 ops/ms
# Warmup Iteration   2: 10.438 ops/ms
# Warmup Iteration   3: 10.688 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.939 ops/ms
Iteration   3: 10.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.720 ±(99.9%) 3.456 ops/ms [Average]
  (min, avg, max) = (10.605, 10.720, 10.939), stdev = 0.189
  CI (99.9%): [7.265, 14.176] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.239 ops/ms
# Warmup Iteration   2: 9.667 ops/ms
# Warmup Iteration   3: 10.193 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.396 ±(99.9%) 1.745 ops/ms [Average]
  (min, avg, max) = (10.294, 10.396, 10.484), stdev = 0.096
  CI (99.9%): [8.651, 12.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.244 ops/ms
# Warmup Iteration   2: 7.479 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.595 ops/ms
Iteration   2: 7.690 ops/ms
Iteration   3: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.719 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (7.595, 7.719, 7.874), stdev = 0.142
  CI (99.9%): [5.133, 10.306] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.643 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.003 ms/op
Iteration   1: 2.889 ±(99.9%) 0.004 ms/op
Iteration   2: 2.900 ±(99.9%) 0.003 ms/op
Iteration   3: 2.839 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.876 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (2.839, 2.876, 2.900), stdev = 0.032
  CI (99.9%): [2.285, 3.467] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.002 ms/op
Iteration   1: 2.884 ±(99.9%) 0.001 ms/op
Iteration   2: 2.730 ±(99.9%) 0.002 ms/op
Iteration   3: 2.748 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.787 ±(99.9%) 1.533 ms/op [Average]
  (min, avg, max) = (2.730, 2.787, 2.884), stdev = 0.084
  CI (99.9%): [1.254, 4.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.018 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (2.984, 3.018, 3.080), stdev = 0.053
  CI (99.9%): [2.049, 3.988] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.786 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
Iteration   1: 3.841 ±(99.9%) 0.022 ms/op
Iteration   2: 3.797 ±(99.9%) 0.028 ms/op
Iteration   3: 3.834 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.824 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.797, 3.824, 3.841), stdev = 0.024
  CI (99.9%): [3.393, 4.255] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.449 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
Iteration   1: 2.904 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.867 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.652 ms/op
                 createUser·p0.99:   4.185 ms/op
                 createUser·p0.999:  7.298 ms/op
                 createUser·p0.9999: 17.432 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 2.859 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.830 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.125 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  6.600 ms/op
                 createUser·p0.9999: 21.596 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 331278
  mean =      2.897 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66887 
    [ 2.500,  5.000) = 263404 
    [ 5.000,  7.500) = 667 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.311 ms/op
     p(99.9900) =     21.590 ms/op
     p(99.9990) =     22.010 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.887 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.006 ms/op
Iteration   1: 2.778 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.744 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 18.202 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.378 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336427
  mean =      2.853 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 982 
    [ 1.250,  2.500) = 74673 
    [ 2.500,  3.750) = 250466 
    [ 3.750,  5.000) = 9111 
    [ 5.000,  6.250) = 760 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.750 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.763 ms/op
                 getUser·p0.9999: 12.456 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   2: 2.872 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.855 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.159 ms/op
                 getUser·p0.9999: 22.098 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   3: 2.901 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.928 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 330467
  mean =      2.904 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71485 
    [ 2.500,  5.000) = 257676 
    [ 5.000,  7.500) = 1002 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     18.506 ms/op
     p(99.9990) =     22.338 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 4.934 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.012 ms/op
Iteration   1: 3.941 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  13.824 ms/op
                 listUser·p0.9999: 18.444 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.858 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.766 ms/op
                 listUser·p0.9999: 20.044 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.905 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.585 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 22.892 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246157
  mean =      3.901 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6344 
    [ 2.500,  5.000) = 215349 
    [ 5.000,  7.500) = 22726 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.803 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     23.621 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.115 ± 1.520  ops/ms
ClientGrpc.existUser                       thrpt       3  10.720 ± 3.456  ops/ms
ClientGrpc.getUser                         thrpt       3  10.396 ± 1.745  ops/ms
ClientGrpc.listUser                        thrpt       3   7.719 ± 2.587  ops/ms
ClientGrpc.createUser                       avgt       3   2.876 ± 0.591   ms/op
ClientGrpc.existUser                        avgt       3   2.787 ± 1.533   ms/op
ClientGrpc.getUser                          avgt       3   3.018 ± 0.969   ms/op
ClientGrpc.listUser                         avgt       3   3.824 ± 0.431   ms/op
ClientGrpc.createUser                     sample  331278   2.897 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.513           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.867           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.311           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.590           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.086           ms/op
ClientGrpc.existUser                      sample  336427   2.853 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.750           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.990           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  330467   2.904 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.871           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.127           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.506           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.381           ms/op
ClientGrpc.listUser                       sample  246157   3.901 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.585           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.803           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.019           ms/op
