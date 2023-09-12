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
# Warmup Iteration   1: 4.009 ops/ms
# Warmup Iteration   2: 8.885 ops/ms
# Warmup Iteration   3: 10.117 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.455 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (10.367, 10.455, 10.558), stdev = 0.096
  CI (99.9%): [8.697, 12.212] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.280 ops/ms
# Warmup Iteration   2: 10.715 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.001 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 11.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.049 ±(99.9%) 0.754 ops/ms [Average]
  (min, avg, max) = (11.001, 11.049, 11.073), stdev = 0.041
  CI (99.9%): [10.295, 11.803] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 10.150 ops/ms
# Warmup Iteration   3: 10.329 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.481 ±(99.9%) 0.644 ops/ms [Average]
  (min, avg, max) = (10.442, 10.481, 10.510), stdev = 0.035
  CI (99.9%): [9.837, 11.124] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.100 ops/ms
Iteration   2: 8.078 ops/ms
Iteration   3: 8.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.113 ±(99.9%) 0.781 ops/ms [Average]
  (min, avg, max) = (8.078, 8.113, 8.161), stdev = 0.043
  CI (99.9%): [7.332, 8.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.003 ms/op
Iteration   2: 3.073 ±(99.9%) 0.003 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.077 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.038, 3.077, 3.122), stdev = 0.042
  CI (99.9%): [2.309, 3.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.002 ms/op
Iteration   1: 2.879 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.875 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (2.875, 2.892, 2.923), stdev = 0.027
  CI (99.9%): [2.402, 3.383] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.010 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.017, 3.040, 3.062), stdev = 0.023
  CI (99.9%): [2.628, 3.451] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.012 ms/op
Iteration   1: 3.970 ±(99.9%) 0.016 ms/op
Iteration   2: 3.891 ±(99.9%) 0.043 ms/op
Iteration   3: 3.913 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (3.891, 3.925, 3.970), stdev = 0.041
  CI (99.9%): [3.178, 4.671] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.267 ms/op
                 createUser·p0.9999: 13.446 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.318 ms/op
                 createUser·p0.9999: 14.081 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.296 ms/op
                 createUser·p0.9999: 16.657 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313812
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 548 
    [ 1.250,  2.500) = 21658 
    [ 2.500,  3.750) = 272015 
    [ 3.750,  5.000) = 17466 
    [ 5.000,  6.250) = 960 
    [ 6.250,  7.500) = 637 
    [ 7.500,  8.750) = 274 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     17.434 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.006 ms/op
Iteration   1: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.393 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   2: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.409 ms/op
                 existUser·p0.9999: 14.168 ms/op
                 existUser·p1.00:   14.434 ms/op

Iteration   3: 2.931 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  11.558 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330751
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40235 
    [ 2.500,  5.000) = 288556 
    [ 5.000,  7.500) = 1573 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.608 ms/op
     p(99.9000) =      7.717 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     22.262 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.302 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 12.377 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.703 ms/op
                 getUser·p0.9999: 14.112 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.305 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  7.733 ms/op
                 getUser·p0.9999: 16.551 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319222
  mean =      3.006 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 860 
    [ 1.250,  2.500) = 24533 
    [ 2.500,  3.750) = 277424 
    [ 3.750,  5.000) = 14443 
    [ 5.000,  6.250) = 1040 
    [ 6.250,  7.500) = 464 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     17.617 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.619 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.073 ms/op
                 listUser·p0.999:  12.390 ms/op
                 listUser·p0.9999: 20.327 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 3.815 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.241 ms/op
                 listUser·p0.9999: 19.046 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 23.457 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246816
  mean =      3.887 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3468 
    [ 2.500,  5.000) = 221064 
    [ 5.000,  7.500) = 20688 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     22.729 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.455 ± 1.757  ops/ms
ClientGrpc.existUser                       thrpt       3  11.049 ± 0.754  ops/ms
ClientGrpc.getUser                         thrpt       3  10.481 ± 0.644  ops/ms
ClientGrpc.listUser                        thrpt       3   8.113 ± 0.781  ops/ms
ClientGrpc.createUser                       avgt       3   3.077 ± 0.768   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.490   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.411   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.747   ms/op
ClientGrpc.createUser                     sample  313812   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.758           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.307           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.318           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.662           ms/op
ClientGrpc.existUser                      sample  330751   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.608           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.717           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  319222   3.006 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.305           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  246816   3.887 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.636           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.729           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.216           ms/op
