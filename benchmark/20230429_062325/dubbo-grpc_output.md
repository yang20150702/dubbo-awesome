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
# Warmup Iteration   1: 3.546 ops/ms
# Warmup Iteration   2: 8.169 ops/ms
# Warmup Iteration   3: 9.717 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 10.503 ops/ms
Iteration   3: 10.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.405 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (10.307, 10.405, 10.503), stdev = 0.098
  CI (99.9%): [8.617, 12.192] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.930 ops/ms
# Warmup Iteration   2: 10.359 ops/ms
# Warmup Iteration   3: 10.587 ops/ms
Iteration   1: 10.933 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.882 ±(99.9%) 0.920 ops/ms [Average]
  (min, avg, max) = (10.832, 10.882, 10.933), stdev = 0.050
  CI (99.9%): [9.962, 11.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.245 ops/ms
# Warmup Iteration   2: 9.687 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.315 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.331 ±(99.9%) 0.322 ops/ms [Average]
  (min, avg, max) = (10.315, 10.331, 10.350), stdev = 0.018
  CI (99.9%): [10.009, 10.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.881 ops/ms
# Warmup Iteration   2: 7.183 ops/ms
# Warmup Iteration   3: 7.485 ops/ms
Iteration   1: 7.539 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 7.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.590 ±(99.9%) 2.538 ops/ms [Average]
  (min, avg, max) = (7.483, 7.590, 7.747), stdev = 0.139
  CI (99.9%): [5.052, 10.128] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.651 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.003 ms/op
Iteration   2: 3.148 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.108, 3.133, 3.148), stdev = 0.021
  CI (99.9%): [2.742, 3.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.003 ms/op
Iteration   1: 2.940 ±(99.9%) 0.003 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.996 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (2.940, 2.996, 3.037), stdev = 0.050
  CI (99.9%): [2.075, 3.916] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.888 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.003 ms/op
Iteration   1: 3.203 ±(99.9%) 0.002 ms/op
Iteration   2: 3.153 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.177 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (3.153, 3.177, 3.203), stdev = 0.025
  CI (99.9%): [2.727, 3.628] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.150 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.810 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.016 ms/op
Iteration   1: 4.424 ±(99.9%) 0.022 ms/op
Iteration   2: 4.453 ±(99.9%) 0.022 ms/op
Iteration   3: 4.400 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.426 ±(99.9%) 0.486 ms/op [Average]
  (min, avg, max) = (4.400, 4.426, 4.453), stdev = 0.027
  CI (99.9%): [3.940, 4.912] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.149 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.007 ms/op
Iteration   1: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   3: 3.219 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 290795
  mean =      3.299 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7900 
    [ 2.500,  5.000) = 280338 
    [ 5.000,  7.500) = 1810 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     10.833 ms/op
     p(99.9900) =     25.262 ms/op
     p(99.9990) =     26.769 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.230 ms/op
                 existUser·p0.9999: 13.650 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  11.875 ms/op
                 existUser·p0.9999: 15.537 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  12.163 ms/op
                 existUser·p0.9999: 21.516 ms/op
                 existUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313719
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18789 
    [ 2.500,  5.000) = 293594 
    [ 5.000,  7.500) = 958 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     11.033 ms/op
     p(99.9900) =     20.288 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.657 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  8.445 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.487 ms/op
                 getUser·p0.9999: 15.754 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.440 ms/op
                 getUser·p0.9999: 16.368 ms/op
                 getUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308454
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17357 
    [ 2.500,  5.000) = 289031 
    [ 5.000,  7.500) = 1716 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     16.059 ms/op
     p(99.9990) =     16.661 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 6.163 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.012 ms/op
Iteration   1: 4.188 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 19.892 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.256 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  19.468 ms/op
                 listUser·p0.9999: 27.181 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 4.223 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  19.179 ms/op
                 listUser·p0.9999: 26.486 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227345
  mean =      4.222 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1544 
    [ 2.500,  5.000) = 194694 
    [ 5.000,  7.500) = 29091 
    [ 7.500, 10.000) = 1518 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     16.799 ms/op
     p(99.9900) =     26.199 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.405 ± 1.787  ops/ms
ClientGrpc.existUser                       thrpt       3  10.882 ± 0.920  ops/ms
ClientGrpc.getUser                         thrpt       3  10.331 ± 0.322  ops/ms
ClientGrpc.listUser                        thrpt       3   7.590 ± 2.538  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.391   ms/op
ClientGrpc.existUser                        avgt       3   2.996 ± 0.921   ms/op
ClientGrpc.getUser                          avgt       3   3.177 ± 0.450   ms/op
ClientGrpc.listUser                         avgt       3   4.426 ± 0.486   ms/op
ClientGrpc.createUser                     sample  290795   3.299 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.496           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.236           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.170           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.833           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.262           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.197           ms/op
ClientGrpc.existUser                      sample  313719   3.058 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.033           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.288           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  308454   3.112 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.860           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.059           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  227345   4.222 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.974           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.022           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.333           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.078           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.389           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.799           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
