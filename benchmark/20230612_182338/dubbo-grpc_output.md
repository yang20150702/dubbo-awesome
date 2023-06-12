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
# Warmup Iteration   1: 3.841 ops/ms
# Warmup Iteration   2: 8.980 ops/ms
# Warmup Iteration   3: 10.171 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.281 ±(99.9%) 3.133 ops/ms [Average]
  (min, avg, max) = (10.114, 10.281, 10.457), stdev = 0.172
  CI (99.9%): [7.148, 13.413] (assumes normal distribution)


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
# Warmup Iteration   1: 7.548 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.816 ops/ms
Iteration   1: 10.829 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 11.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.926 ±(99.9%) 4.073 ops/ms [Average]
  (min, avg, max) = (10.768, 10.926, 11.182), stdev = 0.223
  CI (99.9%): [6.853, 14.999] (assumes normal distribution)


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
# Warmup Iteration   1: 7.094 ops/ms
# Warmup Iteration   2: 9.758 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.429 ops/ms
Iteration   2: 10.434 ops/ms
Iteration   3: 9.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.256 ±(99.9%) 5.527 ops/ms [Average]
  (min, avg, max) = (9.906, 10.256, 10.434), stdev = 0.303
  CI (99.9%): [4.729, 15.783] (assumes normal distribution)


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
# Warmup Iteration   1: 5.097 ops/ms
# Warmup Iteration   2: 7.603 ops/ms
# Warmup Iteration   3: 7.835 ops/ms
Iteration   1: 8.062 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.961 ±(99.9%) 1.598 ops/ms [Average]
  (min, avg, max) = (7.907, 7.961, 8.062), stdev = 0.088
  CI (99.9%): [6.363, 9.559] (assumes normal distribution)


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.001 ms/op
Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.054 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.021, 3.054, 3.084), stdev = 0.032
  CI (99.9%): [2.478, 3.631] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.003 ms/op
Iteration   1: 2.920 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (2.920, 2.980, 3.025), stdev = 0.054
  CI (99.9%): [1.995, 3.965] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.005 ms/op
Iteration   3: 3.068 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.068, 3.097, 3.121), stdev = 0.026
  CI (99.9%): [2.617, 3.577] (assumes normal distribution)


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.260 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.018 ms/op
Iteration   1: 4.065 ±(99.9%) 0.019 ms/op
Iteration   2: 4.116 ±(99.9%) 0.018 ms/op
Iteration   3: 3.973 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.051 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (3.973, 4.051, 4.116), stdev = 0.072
  CI (99.9%): [2.734, 5.369] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.513 ms/op
                 createUser·p0.999:  6.143 ms/op
                 createUser·p0.9999: 13.536 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  7.723 ms/op
                 createUser·p0.9999: 37.063 ms/op
                 createUser·p1.00:   40.436 ms/op

Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  13.969 ms/op
                 createUser·p0.9999: 18.403 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313358
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 311694 
    [ 5.000, 10.000) = 1376 
    [10.000, 15.000) = 132 
    [15.000, 20.000) = 122 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.350 ms/op
     p(99.9900) =     36.285 ms/op
     p(99.9990) =     37.583 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.684 ms/op
                 existUser·p0.9999: 17.698 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 19.177 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  10.563 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327019
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1760 
    [ 1.250,  2.500) = 32468 
    [ 2.500,  3.750) = 281976 
    [ 3.750,  5.000) = 9532 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 276 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     18.393 ms/op
     p(99.9990) =     19.405 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.142 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.639 ms/op
                 getUser·p0.999:  11.259 ms/op
                 getUser·p0.9999: 13.331 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.944 ms/op
                 getUser·p0.9999: 14.461 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  9.216 ms/op
                 getUser·p0.9999: 18.369 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309919
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 596 
    [ 1.250,  2.500) = 16361 
    [ 2.500,  3.750) = 270458 
    [ 3.750,  5.000) = 20668 
    [ 5.000,  6.250) = 1078 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.652 ms/op
     p(99.9900) =     17.466 ms/op
     p(99.9990) =     18.638 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.011 ms/op
Iteration   1: 4.057 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  14.930 ms/op
                 listUser·p0.9999: 17.251 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  18.821 ms/op
                 listUser·p0.9999: 23.498 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.066 ms/op
                 listUser·p0.9999: 28.212 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238281
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2046 
    [ 2.500,  5.000) = 213333 
    [ 5.000,  7.500) = 21163 
    [ 7.500, 10.000) = 1198 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     27.465 ms/op
     p(99.9990) =     29.171 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.281 ± 3.133  ops/ms
ClientGrpc.existUser                       thrpt       3  10.926 ± 4.073  ops/ms
ClientGrpc.getUser                         thrpt       3  10.256 ± 5.527  ops/ms
ClientGrpc.listUser                        thrpt       3   7.961 ± 1.598  ops/ms
ClientGrpc.createUser                       avgt       3   3.054 ± 0.576   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.985   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 0.480   ms/op
ClientGrpc.listUser                         avgt       3   4.051 ± 1.318   ms/op
ClientGrpc.createUser                     sample  313358   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.350           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.285           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.436           ms/op
ClientGrpc.existUser                      sample  327019   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.685           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.847           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.393           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  309919   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.795           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.776           ms/op
ClientGrpc.listUser                       sample  238281   4.027 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.465           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
