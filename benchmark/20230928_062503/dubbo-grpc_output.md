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
# Warmup Iteration   1: 3.693 ops/ms
# Warmup Iteration   2: 8.527 ops/ms
# Warmup Iteration   3: 9.687 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.240 ±(99.9%) 2.668 ops/ms [Average]
  (min, avg, max) = (10.106, 10.240, 10.396), stdev = 0.146
  CI (99.9%): [7.573, 12.908] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.925 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.685 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.741 ±(99.9%) 1.480 ops/ms [Average]
  (min, avg, max) = (10.685, 10.741, 10.834), stdev = 0.081
  CI (99.9%): [9.261, 12.221] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.719 ops/ms
# Warmup Iteration   2: 9.624 ops/ms
# Warmup Iteration   3: 10.205 ops/ms
Iteration   1: 10.201 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 10.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.231 ±(99.9%) 0.746 ops/ms [Average]
  (min, avg, max) = (10.201, 10.231, 10.278), stdev = 0.041
  CI (99.9%): [9.485, 10.977] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.368 ops/ms
# Warmup Iteration   2: 7.768 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 8.017 ops/ms
Iteration   2: 8.055 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.042 ±(99.9%) 0.397 ops/ms [Average]
  (min, avg, max) = (8.017, 8.042, 8.055), stdev = 0.022
  CI (99.9%): [7.645, 8.439] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.467 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.004 ms/op
Iteration   1: 3.113 ±(99.9%) 0.004 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.138 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.113, 3.138, 3.157), stdev = 0.023
  CI (99.9%): [2.723, 3.554] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
Iteration   1: 2.957 ±(99.9%) 0.004 ms/op
Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
Iteration   3: 3.035 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (2.949, 2.980, 3.035), stdev = 0.048
  CI (99.9%): [2.111, 3.849] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.524 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.174 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.151 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.138, 3.151, 3.174), stdev = 0.020
  CI (99.9%): [2.791, 3.512] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.970 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.019 ms/op
Iteration   1: 3.929 ±(99.9%) 0.023 ms/op
Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
Iteration   3: 3.983 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.929, 3.969, 3.993), stdev = 0.035
  CI (99.9%): [3.337, 4.600] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.596 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
Iteration   1: 3.201 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.410 ms/op
                 createUser·p0.9999: 13.272 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.737 ms/op
                 createUser·p0.999:  11.127 ms/op
                 createUser·p0.9999: 16.067 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  15.436 ms/op
                 createUser·p0.9999: 17.545 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303826
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 372 
    [ 1.250,  2.500) = 9733 
    [ 2.500,  3.750) = 261545 
    [ 3.750,  5.000) = 30276 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 470 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 99 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.645 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.610 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  8.152 ms/op
                 existUser·p0.9999: 17.646 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.279 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 14.686 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.915 ms/op
                 existUser·p0.9999: 26.573 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316376
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23890 
    [ 2.500,  5.000) = 290755 
    [ 5.000,  7.500) = 1303 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.360 ms/op
     p(99.9900) =     18.313 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.543 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.290 ms/op
                 getUser·p0.9999: 17.398 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.063 ms/op
                 getUser·p0.9999: 18.396 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  13.937 ms/op
                 getUser·p0.9999: 20.472 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304618
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7964 
    [ 2.500,  5.000) = 294740 
    [ 5.000,  7.500) = 1473 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.252 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.610 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.756 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.009 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 18.516 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.048 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 15.991 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  17.047 ms/op
                 listUser·p0.9999: 35.129 ms/op
                 listUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238007
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2443 
    [ 2.500,  5.000) = 217780 
    [ 5.000,  7.500) = 16255 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     33.266 ms/op
     p(99.9990) =     35.889 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.240 ± 2.668  ops/ms
ClientGrpc.existUser                       thrpt       3  10.741 ± 1.480  ops/ms
ClientGrpc.getUser                         thrpt       3  10.231 ± 0.746  ops/ms
ClientGrpc.listUser                        thrpt       3   8.042 ± 0.397  ops/ms
ClientGrpc.createUser                       avgt       3   3.138 ± 0.416   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.869   ms/op
ClientGrpc.getUser                          avgt       3   3.151 ± 0.360   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.632   ms/op
ClientGrpc.createUser                     sample  303826   3.160 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.754           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.645           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.678           ms/op
ClientGrpc.existUser                      sample  316376   3.033 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.360           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.313           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.066           ms/op
ClientGrpc.getUser                        sample  304618   3.150 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.543           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.252           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  238007   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.996           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.266           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.045           ms/op
