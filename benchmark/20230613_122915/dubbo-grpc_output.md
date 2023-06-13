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
# Warmup Iteration   1: 4.047 ops/ms
# Warmup Iteration   2: 8.860 ops/ms
# Warmup Iteration   3: 9.877 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.342 ±(99.9%) 2.170 ops/ms [Average]
  (min, avg, max) = (10.209, 10.342, 10.437), stdev = 0.119
  CI (99.9%): [8.172, 12.512] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.709 ops/ms
# Warmup Iteration   2: 10.536 ops/ms
# Warmup Iteration   3: 10.854 ops/ms
Iteration   1: 11.170 ops/ms
Iteration   2: 11.044 ops/ms
Iteration   3: 10.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.023 ±(99.9%) 2.900 ops/ms [Average]
  (min, avg, max) = (10.855, 11.023, 11.170), stdev = 0.159
  CI (99.9%): [8.123, 13.923] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ops/ms
# Warmup Iteration   2: 10.239 ops/ms
# Warmup Iteration   3: 10.448 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.520 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (10.387, 10.520, 10.638), stdev = 0.126
  CI (99.9%): [8.214, 12.826] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.250 ops/ms
# Warmup Iteration   2: 7.532 ops/ms
# Warmup Iteration   3: 7.938 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 7.785 ops/ms
Iteration   3: 7.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.869 ±(99.9%) 1.870 ops/ms [Average]
  (min, avg, max) = (7.785, 7.869, 7.984), stdev = 0.102
  CI (99.9%): [6.000, 9.739] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.264 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.077 ±(99.9%) 0.003 ms/op
Iteration   2: 3.074 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.055 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.016, 3.055, 3.077), stdev = 0.034
  CI (99.9%): [2.429, 3.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.004 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 2.939 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.937, 2.950, 2.974), stdev = 0.021
  CI (99.9%): [2.566, 3.334] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.004 ms/op
Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
Iteration   3: 3.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.055 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (3.034, 3.055, 3.086), stdev = 0.028
  CI (99.9%): [2.543, 3.566] (assumes normal distribution)


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
# Warmup Iteration   1: 5.167 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.017 ms/op
Iteration   1: 4.048 ±(99.9%) 0.034 ms/op
Iteration   2: 4.045 ±(99.9%) 0.019 ms/op
Iteration   3: 4.007 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.033 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (4.007, 4.033, 4.048), stdev = 0.023
  CI (99.9%): [3.613, 4.454] (assumes normal distribution)


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
# Warmup Iteration   1: 4.196 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.294 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.017 ms/op
                 createUser·p0.9999: 14.540 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.632 ms/op
                 createUser·p0.999:  10.350 ms/op
                 createUser·p0.9999: 26.789 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314097
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20630 
    [ 2.500,  5.000) = 291894 
    [ 5.000,  7.500) = 1064 
    [ 7.500, 10.000) = 217 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     26.234 ms/op
     p(99.9990) =     27.057 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.005 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   3.903 ms/op
                 existUser·p0.999:  6.418 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  6.606 ms/op
                 existUser·p0.9999: 15.696 ms/op
                 existUser·p1.00:   15.942 ms/op

Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  10.093 ms/op
                 existUser·p0.9999: 28.180 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326615
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31778 
    [ 2.500,  5.000) = 293845 
    [ 5.000,  7.500) = 569 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.817 ms/op
     p(99.9900) =     23.830 ms/op
     p(99.9990) =     28.303 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.143 ms/op
                 getUser·p0.9999: 16.384 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  6.903 ms/op
                 getUser·p0.9999: 14.294 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.825 ms/op
                 getUser·p0.9999: 18.862 ms/op
                 getUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313059
  mean =      3.064 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 314 
    [ 1.250,  2.500) = 16699 
    [ 2.500,  3.750) = 279589 
    [ 3.750,  5.000) = 15224 
    [ 5.000,  6.250) = 712 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     17.160 ms/op
     p(99.9990) =     19.226 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 5.648 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.011 ms/op
Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 19.660 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 4.000 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.092 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.089 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240097
  mean =      3.997 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2149 
    [ 2.500,  5.000) = 215259 
    [ 5.000,  7.500) = 21310 
    [ 7.500, 10.000) = 937 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     25.689 ms/op
     p(99.9990) =     26.778 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.342 ± 2.170  ops/ms
ClientGrpc.existUser                       thrpt       3  11.023 ± 2.900  ops/ms
ClientGrpc.getUser                         thrpt       3  10.520 ± 2.306  ops/ms
ClientGrpc.listUser                        thrpt       3   7.869 ± 1.870  ops/ms
ClientGrpc.createUser                       avgt       3   3.055 ± 0.626   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.384   ms/op
ClientGrpc.getUser                          avgt       3   3.055 ± 0.512   ms/op
ClientGrpc.listUser                         avgt       3   4.033 ± 0.420   ms/op
ClientGrpc.createUser                     sample  314097   3.054 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.820           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.814           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.234           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.165           ms/op
ClientGrpc.existUser                      sample  326615   2.939 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.566           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.817           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.830           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.344           ms/op
ClientGrpc.getUser                        sample  313059   3.064 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.622           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.160           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.366           ms/op
ClientGrpc.listUser                       sample  240097   3.997 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.812           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.689           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.903           ms/op
