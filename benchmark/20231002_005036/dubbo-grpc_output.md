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
# Warmup Iteration   1: 2.219 ops/ms
# Warmup Iteration   2: 5.434 ops/ms
# Warmup Iteration   3: 6.653 ops/ms
Iteration   1: 7.323 ops/ms
Iteration   2: 7.289 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.254 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (7.150, 7.254, 7.323), stdev = 0.092
  CI (99.9%): [5.582, 8.926] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 7.017 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.888 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 7.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.859 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (7.823, 7.859, 7.888), stdev = 0.033
  CI (99.9%): [7.256, 8.462] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.294 ops/ms
# Warmup Iteration   2: 6.757 ops/ms
# Warmup Iteration   3: 7.204 ops/ms
Iteration   1: 7.374 ops/ms
Iteration   2: 7.360 ops/ms
Iteration   3: 7.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.417 ±(99.9%) 1.564 ops/ms [Average]
  (min, avg, max) = (7.360, 7.417, 7.515), stdev = 0.086
  CI (99.9%): [5.853, 8.980] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ops/ms
# Warmup Iteration   2: 5.170 ops/ms
# Warmup Iteration   3: 5.461 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 5.685 ops/ms
Iteration   3: 5.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.627 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (5.560, 5.627, 5.685), stdev = 0.063
  CI (99.9%): [4.473, 6.782] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.386 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.626 ±(99.9%) 0.010 ms/op
Iteration   1: 4.565 ±(99.9%) 0.004 ms/op
Iteration   2: 4.402 ±(99.9%) 0.003 ms/op
Iteration   3: 4.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.466 ±(99.9%) 1.581 ms/op [Average]
  (min, avg, max) = (4.402, 4.466, 4.565), stdev = 0.087
  CI (99.9%): [2.884, 6.047] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.004 ms/op
Iteration   1: 4.058 ±(99.9%) 0.004 ms/op
Iteration   2: 4.145 ±(99.9%) 0.003 ms/op
Iteration   3: 4.146 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.116 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (4.058, 4.116, 4.146), stdev = 0.051
  CI (99.9%): [3.190, 5.043] (assumes normal distribution)


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
# Warmup Iteration   1: 6.600 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.795 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.019 ms/op
Iteration   1: 4.409 ±(99.9%) 0.004 ms/op
Iteration   2: 4.478 ±(99.9%) 0.003 ms/op
Iteration   3: 4.384 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.424 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (4.384, 4.424, 4.478), stdev = 0.048
  CI (99.9%): [3.539, 5.308] (assumes normal distribution)


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
# Warmup Iteration   1: 8.052 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.226 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.019 ms/op
Iteration   1: 5.642 ±(99.9%) 0.016 ms/op
Iteration   2: 5.737 ±(99.9%) 0.017 ms/op
Iteration   3: 5.626 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.668 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (5.626, 5.668, 5.737), stdev = 0.060
  CI (99.9%): [4.569, 6.767] (assumes normal distribution)


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
# Warmup Iteration   1: 7.201 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.898 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.016 ms/op
Iteration   1: 4.451 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 4.369 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   4.186 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   8.314 ms/op
                 createUser·p0.999:  12.913 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 4.386 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   8.331 ms/op
                 createUser·p0.999:  13.008 ms/op
                 createUser·p0.9999: 25.146 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218293
  mean =      4.402 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6836 
    [ 2.500,  5.000) = 165861 
    [ 5.000,  7.500) = 40965 
    [ 7.500, 10.000) = 3706 
    [10.000, 12.500) = 597 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     26.447 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 6.184 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.014 ms/op
Iteration   1: 4.353 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   6.160 ms/op
                 existUser·p0.99:   8.380 ms/op
                 existUser·p0.999:  13.404 ms/op
                 existUser·p0.9999: 16.886 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 4.085 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.874 ms/op
                 existUser·p0.99:   8.266 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 38.535 ms/op
                 existUser·p1.00:   38.797 ms/op

Iteration   3: 4.205 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  13.515 ms/op
                 existUser·p0.9999: 24.217 ms/op
                 existUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227874
  mean =      4.212 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7301 
    [ 2.500,  5.000) = 184609 
    [ 5.000,  7.500) = 31811 
    [ 7.500, 10.000) = 3235 
    [10.000, 12.500) = 561 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     38.104 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 6.428 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.727 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.016 ms/op
Iteration   1: 4.314 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   6.136 ms/op
                 getUser·p0.99:   8.372 ms/op
                 getUser·p0.999:  13.199 ms/op
                 getUser·p0.9999: 19.055 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 4.274 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.200 ms/op
                 getUser·p0.999:  13.030 ms/op
                 getUser·p0.9999: 19.841 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   3: 4.266 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.307 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 22.725 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223998
  mean =      4.285 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5309 
    [ 2.500,  5.000) = 180677 
    [ 5.000,  7.500) = 33822 
    [ 7.500, 10.000) = 3049 
    [10.000, 12.500) = 837 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.464 ms/op
     p(95.0000) =      6.160 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     21.411 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 8.923 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.120 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.645 ±(99.9%) 0.026 ms/op
Iteration   1: 5.802 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.969 ms/op
                 listUser·p0.999:  18.804 ms/op
                 listUser·p0.9999: 21.479 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 5.813 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  21.332 ms/op
                 listUser·p0.9999: 24.695 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   3: 5.723 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.351 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 27.153 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166148
  mean =      5.779 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176 
    [ 2.500,  5.000) = 56213 
    [ 5.000,  7.500) = 89388 
    [ 7.500, 10.000) = 15987 
    [10.000, 12.500) = 3083 
    [12.500, 15.000) = 777 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      7.832 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     21.126 ms/op
     p(99.9900) =     24.556 ms/op
     p(99.9990) =     30.017 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.254 ± 1.672  ops/ms
ClientGrpc.existUser                       thrpt       3   7.859 ± 0.603  ops/ms
ClientGrpc.getUser                         thrpt       3   7.417 ± 1.564  ops/ms
ClientGrpc.listUser                        thrpt       3   5.627 ± 1.155  ops/ms
ClientGrpc.createUser                       avgt       3   4.466 ± 1.581   ms/op
ClientGrpc.existUser                        avgt       3   4.116 ± 0.927   ms/op
ClientGrpc.getUser                          avgt       3   4.424 ± 0.885   ms/op
ClientGrpc.listUser                         avgt       3   5.668 ± 1.099   ms/op
ClientGrpc.createUser                     sample  218293   4.402 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.908           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.684           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.206           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.657           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.575           ms/op
ClientGrpc.existUser                      sample  227874   4.212 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.024           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.087           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.454           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.369           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          38.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.797           ms/op
ClientGrpc.getUser                        sample  223998   4.285 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.906           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.160           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.140           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.411           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.707           ms/op
ClientGrpc.listUser                       sample  166148   5.779 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.911           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.126           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.556           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.212           ms/op
