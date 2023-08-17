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
# Warmup Iteration   1: 2.625 ops/ms
# Warmup Iteration   2: 5.858 ops/ms
# Warmup Iteration   3: 7.306 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 7.670 ops/ms
Iteration   3: 7.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.680 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (7.613, 7.680, 7.757), stdev = 0.072
  CI (99.9%): [6.361, 8.999] (assumes normal distribution)


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
# Warmup Iteration   1: 5.177 ops/ms
# Warmup Iteration   2: 7.768 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.337 ops/ms
Iteration   2: 8.422 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.424 ±(99.9%) 1.595 ops/ms [Average]
  (min, avg, max) = (8.337, 8.424, 8.512), stdev = 0.087
  CI (99.9%): [6.828, 10.019] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.226 ops/ms
# Warmup Iteration   2: 6.981 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 7.848 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 7.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.875 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (7.801, 7.875, 7.977), stdev = 0.091
  CI (99.9%): [6.213, 9.537] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ops/ms
# Warmup Iteration   2: 5.612 ops/ms
# Warmup Iteration   3: 5.956 ops/ms
Iteration   1: 6.055 ops/ms
Iteration   2: 6.262 ops/ms
Iteration   3: 6.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.155 ±(99.9%) 1.894 ops/ms [Average]
  (min, avg, max) = (6.055, 6.155, 6.262), stdev = 0.104
  CI (99.9%): [4.261, 8.048] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.024 ms/op
Iteration   1: 4.081 ±(99.9%) 0.002 ms/op
Iteration   2: 4.037 ±(99.9%) 0.003 ms/op
Iteration   3: 4.097 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.072 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (4.037, 4.072, 4.097), stdev = 0.031
  CI (99.9%): [3.510, 4.633] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.533 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.903 ±(99.9%) 0.004 ms/op
Iteration   1: 3.798 ±(99.9%) 0.002 ms/op
Iteration   2: 3.738 ±(99.9%) 0.003 ms/op
Iteration   3: 3.765 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.767 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (3.738, 3.767, 3.798), stdev = 0.030
  CI (99.9%): [3.227, 4.308] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.851 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.005 ms/op
Iteration   1: 4.160 ±(99.9%) 0.003 ms/op
Iteration   2: 4.121 ±(99.9%) 0.005 ms/op
Iteration   3: 4.100 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.127 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (4.100, 4.127, 4.160), stdev = 0.031
  CI (99.9%): [3.570, 4.684] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.334 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.222 ±(99.9%) 0.017 ms/op
Iteration   1: 5.133 ±(99.9%) 0.011 ms/op
Iteration   2: 5.153 ±(99.9%) 0.012 ms/op
Iteration   3: 5.315 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.200 ±(99.9%) 1.820 ms/op [Average]
  (min, avg, max) = (5.133, 5.200, 5.315), stdev = 0.100
  CI (99.9%): [3.380, 7.021] (assumes normal distribution)


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
# Warmup Iteration   1: 6.293 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.014 ms/op
Iteration   1: 4.181 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  14.369 ms/op
                 createUser·p0.9999: 28.651 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 4.196 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.349 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  11.002 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 4.080 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  13.070 ms/op
                 createUser·p0.9999: 31.036 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231164
  mean =      4.151 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4400 
    [ 2.500,  5.000) = 193363 
    [ 5.000,  7.500) = 31510 
    [ 7.500, 10.000) = 1476 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     13.042 ms/op
     p(99.9900) =     30.667 ms/op
     p(99.9990) =     31.218 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.467 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.011 ms/op
Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.603 ms/op
                 existUser·p0.999:  10.539 ms/op
                 existUser·p0.9999: 15.330 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 19.361 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 3.841 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.735 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  12.340 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248484
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6679 
    [ 2.500,  5.000) = 222969 
    [ 5.000,  7.500) = 17522 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     10.838 ms/op
     p(99.9900) =     20.981 ms/op
     p(99.9990) =     22.283 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 6.104 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.012 ms/op
Iteration   1: 4.060 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.094 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  9.298 ms/op
                 getUser·p0.9999: 15.931 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.942 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  10.828 ms/op
                 getUser·p0.9999: 18.756 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  11.065 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236108
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4792 
    [ 2.500,  5.000) = 202504 
    [ 5.000,  7.500) = 27550 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     21.363 ms/op
     p(99.9990) =     22.476 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 8.202 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.571 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.292 ±(99.9%) 0.019 ms/op
Iteration   1: 5.305 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   5.054 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  25.213 ms/op
                 listUser·p0.9999: 28.868 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   2: 5.208 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.352 ms/op
                 listUser·p0.99:   9.437 ms/op
                 listUser·p0.999:  17.704 ms/op
                 listUser·p0.9999: 26.766 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   3: 5.067 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.537 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  20.802 ms/op
                 listUser·p0.9999: 28.629 ms/op
                 listUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184876
  mean =      5.191 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 251 
    [ 2.500,  5.000) = 94861 
    [ 5.000,  7.500) = 79885 
    [ 7.500, 10.000) = 8418 
    [10.000, 12.500) = 981 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.723 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.680 ± 1.319  ops/ms
ClientGrpc.existUser                       thrpt       3   8.424 ± 1.595  ops/ms
ClientGrpc.getUser                         thrpt       3   7.875 ± 1.662  ops/ms
ClientGrpc.listUser                        thrpt       3   6.155 ± 1.894  ops/ms
ClientGrpc.createUser                       avgt       3   4.072 ± 0.562   ms/op
ClientGrpc.existUser                        avgt       3   3.767 ± 0.540   ms/op
ClientGrpc.getUser                          avgt       3   4.127 ± 0.557   ms/op
ClientGrpc.listUser                         avgt       3   5.200 ± 1.820   ms/op
ClientGrpc.createUser                     sample  231164   4.151 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.520           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.250           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.042           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.667           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.293           ms/op
ClientGrpc.existUser                      sample  248484   3.862 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.874           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.825           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.838           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.981           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  236108   4.067 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.892           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.816           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  184876   5.191 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.918           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.152           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.606           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.835           ms/op
