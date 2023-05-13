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
# Warmup Iteration   1: 4.413 ops/ms
# Warmup Iteration   2: 9.550 ops/ms
# Warmup Iteration   3: 10.240 ops/ms
Iteration   1: 10.783 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.800 ±(99.9%) 2.549 ops/ms [Average]
  (min, avg, max) = (10.669, 10.800, 10.947), stdev = 0.140
  CI (99.9%): [8.250, 13.349] (assumes normal distribution)


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
# Warmup Iteration   1: 8.692 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 11.589 ops/ms
Iteration   1: 11.367 ops/ms
Iteration   2: 11.195 ops/ms
Iteration   3: 11.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.301 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (11.195, 11.301, 11.367), stdev = 0.093
  CI (99.9%): [9.606, 12.996] (assumes normal distribution)


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
# Warmup Iteration   1: 8.292 ops/ms
# Warmup Iteration   2: 10.376 ops/ms
# Warmup Iteration   3: 10.865 ops/ms
Iteration   1: 10.686 ops/ms
Iteration   2: 10.813 ops/ms
Iteration   3: 10.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.800 ±(99.9%) 1.971 ops/ms [Average]
  (min, avg, max) = (10.686, 10.800, 10.901), stdev = 0.108
  CI (99.9%): [8.828, 12.771] (assumes normal distribution)


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
# Warmup Iteration   1: 5.941 ops/ms
# Warmup Iteration   2: 8.170 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.368 ops/ms
Iteration   3: 8.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.459 ±(99.9%) 3.420 ops/ms [Average]
  (min, avg, max) = (8.334, 8.459, 8.674), stdev = 0.187
  CI (99.9%): [5.039, 11.878] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.002 ms/op
Iteration   3: 2.968 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.977 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.968, 2.977, 2.988), stdev = 0.010
  CI (99.9%): [2.793, 3.160] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.824 ±(99.9%) 0.004 ms/op
Iteration   1: 2.820 ±(99.9%) 0.005 ms/op
Iteration   2: 2.824 ±(99.9%) 0.003 ms/op
Iteration   3: 2.857 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.834 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.820, 2.834, 2.857), stdev = 0.020
  CI (99.9%): [2.470, 3.198] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.932 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.952 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.932, 2.952, 2.969), stdev = 0.019
  CI (99.9%): [2.607, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.047 ms/op
Iteration   1: 3.813 ±(99.9%) 0.007 ms/op
Iteration   2: 3.824 ±(99.9%) 0.012 ms/op
Iteration   3: 3.812 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.817 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (3.812, 3.817, 3.824), stdev = 0.007
  CI (99.9%): [3.696, 3.937] (assumes normal distribution)


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.577 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.338 ms/op
                 createUser·p0.999:  6.672 ms/op
                 createUser·p0.9999: 14.166 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  7.323 ms/op
                 createUser·p0.9999: 15.475 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  12.123 ms/op
                 createUser·p0.9999: 22.256 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319953
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26125 
    [ 2.500,  5.000) = 292810 
    [ 5.000,  7.500) = 657 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      8.069 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     22.820 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.852 ±(99.9%) 0.005 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 11.076 ms/op
                 existUser·p1.00:   11.370 ms/op

Iteration   2: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 12.398 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 13.740 ms/op
                 existUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332879
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3378 
    [ 1.250,  2.500) = 39522 
    [ 2.500,  3.750) = 279210 
    [ 3.750,  5.000) = 9759 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.472 ms/op
     p(99.9900) =     12.733 ms/op
     p(99.9990) =     13.981 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.679 ms/op
                 getUser·p0.9999: 20.266 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.534 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.060 ms/op
                 getUser·p0.9999: 18.678 ms/op
                 getUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322204
  mean =      2.979 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25764 
    [ 2.500,  5.000) = 295109 
    [ 5.000,  7.500) = 996 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.615 ms/op
     p(99.9900) =     21.830 ms/op
     p(99.9990) =     23.251 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.960 ms/op
                 listUser·p0.9999: 16.755 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.437 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 18.701 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.940 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250543
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6992 
    [ 2.500,  5.000) = 223995 
    [ 5.000,  7.500) = 18709 
    [ 7.500, 10.000) = 415 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     14.114 ms/op
     p(99.9900) =     19.233 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.800 ± 2.549  ops/ms
ClientGrpc.existUser                       thrpt       3  11.301 ± 1.695  ops/ms
ClientGrpc.getUser                         thrpt       3  10.800 ± 1.971  ops/ms
ClientGrpc.listUser                        thrpt       3   8.459 ± 3.420  ops/ms
ClientGrpc.createUser                       avgt       3   2.977 ± 0.184   ms/op
ClientGrpc.existUser                        avgt       3   2.834 ± 0.364   ms/op
ClientGrpc.getUser                          avgt       3   2.952 ± 0.346   ms/op
ClientGrpc.listUser                         avgt       3   3.817 ± 0.121   ms/op
ClientGrpc.createUser                     sample  319953   2.999 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.069           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  332879   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.510           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.733           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.074           ms/op
ClientGrpc.getUser                        sample  322204   2.979 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.538           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.615           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.830           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  250543   3.832 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.772           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.114           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.233           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.299           ms/op
