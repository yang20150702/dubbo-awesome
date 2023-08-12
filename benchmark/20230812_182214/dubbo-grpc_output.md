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
# Warmup Iteration   1: 3.975 ops/ms
# Warmup Iteration   2: 8.863 ops/ms
# Warmup Iteration   3: 9.870 ops/ms
Iteration   1: 10.200 ops/ms
Iteration   2: 10.327 ops/ms
Iteration   3: 10.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.320 ±(99.9%) 2.129 ops/ms [Average]
  (min, avg, max) = (10.200, 10.320, 10.433), stdev = 0.117
  CI (99.9%): [8.191, 12.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ops/ms
# Warmup Iteration   2: 10.289 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.776 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 11.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.828 ±(99.9%) 3.628 ops/ms [Average]
  (min, avg, max) = (10.661, 10.828, 11.048), stdev = 0.199
  CI (99.9%): [7.201, 14.456] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.619 ops/ms
# Warmup Iteration   2: 10.040 ops/ms
# Warmup Iteration   3: 10.208 ops/ms
Iteration   1: 10.328 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.374 ±(99.9%) 0.943 ops/ms [Average]
  (min, avg, max) = (10.328, 10.374, 10.430), stdev = 0.052
  CI (99.9%): [9.431, 11.317] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ops/ms
# Warmup Iteration   2: 7.353 ops/ms
# Warmup Iteration   3: 7.510 ops/ms
Iteration   1: 7.616 ops/ms
Iteration   2: 7.652 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.659 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (7.616, 7.659, 7.708), stdev = 0.046
  CI (99.9%): [6.817, 8.501] (assumes normal distribution)


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
# Warmup Iteration   1: 4.495 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.003 ms/op
Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.082, 3.111, 3.147), stdev = 0.033
  CI (99.9%): [2.508, 3.713] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 3.003 ±(99.9%) 0.002 ms/op
Iteration   2: 2.900 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (2.900, 2.963, 3.003), stdev = 0.055
  CI (99.9%): [1.960, 3.966] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.005 ms/op
Iteration   1: 3.078 ±(99.9%) 0.004 ms/op
Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
Iteration   3: 3.099 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (3.078, 3.087, 3.099), stdev = 0.011
  CI (99.9%): [2.886, 3.288] (assumes normal distribution)


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.230 ±(99.9%) 0.019 ms/op
Iteration   1: 4.201 ±(99.9%) 0.015 ms/op
Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
Iteration   3: 4.156 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.154 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (4.105, 4.154, 4.201), stdev = 0.048
  CI (99.9%): [3.277, 5.032] (assumes normal distribution)


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  9.016 ms/op
                 createUser·p0.9999: 16.149 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 26.110 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 21.359 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305547
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11980 
    [ 2.500,  5.000) = 290989 
    [ 5.000,  7.500) = 1795 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      9.428 ms/op
     p(99.9900) =     24.780 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 15.239 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.588 ms/op
                 existUser·p0.9999: 21.464 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 18.416 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324852
  mean =      2.952 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31787 
    [ 2.500,  5.000) = 291430 
    [ 5.000,  7.500) = 1087 
    [ 7.500, 10.000) = 282 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     20.217 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 4.382 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  8.125 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.092 ms/op
                 getUser·p0.999:  8.951 ms/op
                 getUser·p0.9999: 32.497 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.774 ms/op
                 getUser·p0.9999: 23.063 ms/op
                 getUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304922
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13353 
    [ 2.500,  5.000) = 288532 
    [ 5.000,  7.500) = 2535 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     32.825 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 5.662 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.012 ms/op
Iteration   1: 4.206 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  12.402 ms/op
                 listUser·p0.9999: 21.928 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 4.189 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  19.929 ms/op
                 listUser·p0.9999: 23.310 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.158 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 20.214 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229453
  mean =      4.184 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1470 
    [ 2.500,  5.000) = 198656 
    [ 5.000,  7.500) = 26937 
    [ 7.500, 10.000) = 1851 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     16.281 ms/op
     p(99.9900) =     22.808 ms/op
     p(99.9990) =     23.761 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.320 ± 2.129  ops/ms
ClientGrpc.existUser                       thrpt       3  10.828 ± 3.628  ops/ms
ClientGrpc.getUser                         thrpt       3  10.374 ± 0.943  ops/ms
ClientGrpc.listUser                        thrpt       3   7.659 ± 0.842  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 0.603   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 1.003   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.201   ms/op
ClientGrpc.listUser                         avgt       3   4.154 ± 0.878   ms/op
ClientGrpc.createUser                     sample  305547   3.142 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.792           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.428           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.780           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  324852   2.952 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.564           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.217           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.823           ms/op
ClientGrpc.getUser                        sample  304922   3.148 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.818           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.063           ms/op
ClientGrpc.listUser                       sample  229453   4.184 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.281           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.808           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
