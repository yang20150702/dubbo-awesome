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
# Warmup Iteration   1: 4.603 ops/ms
# Warmup Iteration   2: 9.273 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.786 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.784 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (10.757, 10.784, 10.808), stdev = 0.026
  CI (99.9%): [10.314, 11.254] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.969 ops/ms
# Warmup Iteration   2: 10.755 ops/ms
# Warmup Iteration   3: 11.297 ops/ms
Iteration   1: 11.244 ops/ms
Iteration   2: 11.308 ops/ms
Iteration   3: 11.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.337 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (11.244, 11.337, 11.458), stdev = 0.110
  CI (99.9%): [9.331, 13.342] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.915 ops/ms
# Warmup Iteration   2: 10.447 ops/ms
# Warmup Iteration   3: 10.661 ops/ms
Iteration   1: 10.903 ops/ms
Iteration   2: 10.904 ops/ms
Iteration   3: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.860 ±(99.9%) 1.380 ops/ms [Average]
  (min, avg, max) = (10.772, 10.860, 10.904), stdev = 0.076
  CI (99.9%): [9.480, 12.239] (assumes normal distribution)


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
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 8.099 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.290 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 8.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.387 ±(99.9%) 2.039 ops/ms [Average]
  (min, avg, max) = (8.290, 8.387, 8.509), stdev = 0.112
  CI (99.9%): [6.349, 10.426] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.004 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.989 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.969, 2.989, 3.008), stdev = 0.020
  CI (99.9%): [2.627, 3.351] (assumes normal distribution)


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.004 ms/op
Iteration   1: 2.838 ±(99.9%) 0.003 ms/op
Iteration   2: 2.846 ±(99.9%) 0.003 ms/op
Iteration   3: 2.806 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.830 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.806, 2.830, 2.846), stdev = 0.021
  CI (99.9%): [2.440, 3.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.968 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.952, 2.968, 2.984), stdev = 0.016
  CI (99.9%): [2.679, 3.257] (assumes normal distribution)


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.025 ms/op
Iteration   1: 3.758 ±(99.9%) 0.016 ms/op
Iteration   2: 3.778 ±(99.9%) 0.031 ms/op
Iteration   3: 3.818 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.784 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.758, 3.784, 3.818), stdev = 0.031
  CI (99.9%): [3.227, 4.341] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.251 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.321 ms/op
                 createUser·p0.9999: 15.991 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.716 ms/op
                 createUser·p0.9999: 15.769 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  13.370 ms/op
                 createUser·p0.9999: 27.172 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324904
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31314 
    [ 2.500,  5.000) = 292442 
    [ 5.000,  7.500) = 812 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.251 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.348 ms/op
     p(99.9900) =     21.693 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
Iteration   1: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.815 ms/op
                 existUser·p0.9999: 11.583 ms/op
                 existUser·p1.00:   11.829 ms/op

Iteration   2: 2.824 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.144 ms/op
                 existUser·p0.9999: 14.647 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.829 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 14.139 ms/op
                 existUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337521
  mean =      2.843 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3832 
    [ 1.250,  2.500) = 53142 
    [ 2.500,  3.750) = 269507 
    [ 3.750,  5.000) = 9858 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.869 ms/op
     p(99.9900) =     14.356 ms/op
     p(99.9990) =     14.936 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.164 ms/op
                 getUser·p0.9999: 15.249 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   2: 2.928 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.265 ms/op
                 getUser·p0.95:   3.367 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 12.158 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 22.126 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324500
  mean =      2.957 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20689 
    [ 2.500,  5.000) = 302906 
    [ 5.000,  7.500) = 628 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      6.975 ms/op
     p(99.9900) =     19.705 ms/op
     p(99.9990) =     22.569 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.204 ms/op
                 listUser·p0.9999: 16.347 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  17.406 ms/op
                 listUser·p0.9999: 25.763 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   3: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.900 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.259 ms/op
                 listUser·p0.9999: 21.808 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247575
  mean =      3.878 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3841 
    [ 2.500,  5.000) = 224541 
    [ 5.000,  7.500) = 18238 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.621 ms/op
     p(99.9900) =     24.829 ms/op
     p(99.9990) =     25.940 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.784 ± 0.470  ops/ms
ClientGrpc.existUser                       thrpt       3  11.337 ± 2.006  ops/ms
ClientGrpc.getUser                         thrpt       3  10.860 ± 1.380  ops/ms
ClientGrpc.listUser                        thrpt       3   8.387 ± 2.039  ops/ms
ClientGrpc.createUser                       avgt       3   2.989 ± 0.362   ms/op
ClientGrpc.existUser                        avgt       3   2.830 ± 0.390   ms/op
ClientGrpc.getUser                          avgt       3   2.968 ± 0.289   ms/op
ClientGrpc.listUser                         avgt       3   3.784 ± 0.557   ms/op
ClientGrpc.createUser                     sample  324904   2.955 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.251           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.348           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.693           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.951           ms/op
ClientGrpc.existUser                      sample  337521   2.843 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.869           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.356           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.942           ms/op
ClientGrpc.getUser                        sample  324500   2.957 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.371           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.975           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.705           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.643           ms/op
ClientGrpc.listUser                       sample  247575   3.878 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.900           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.621           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.829           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
