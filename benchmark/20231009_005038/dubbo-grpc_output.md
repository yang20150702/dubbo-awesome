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
# Warmup Iteration   1: 3.490 ops/ms
# Warmup Iteration   2: 8.079 ops/ms
# Warmup Iteration   3: 9.500 ops/ms
Iteration   1: 9.896 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 10.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.039 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (9.896, 10.039, 10.132), stdev = 0.125
  CI (99.9%): [7.754, 12.324] (assumes normal distribution)


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
# Warmup Iteration   1: 6.552 ops/ms
# Warmup Iteration   2: 9.916 ops/ms
# Warmup Iteration   3: 10.388 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.526 ±(99.9%) 1.441 ops/ms [Average]
  (min, avg, max) = (10.477, 10.526, 10.617), stdev = 0.079
  CI (99.9%): [9.085, 11.966] (assumes normal distribution)


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
# Warmup Iteration   1: 5.811 ops/ms
# Warmup Iteration   2: 9.494 ops/ms
# Warmup Iteration   3: 9.791 ops/ms
Iteration   1: 9.897 ops/ms
Iteration   2: 10.054 ops/ms
Iteration   3: 10.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.006 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (9.897, 10.006, 10.068), stdev = 0.095
  CI (99.9%): [8.275, 11.737] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 6.879 ops/ms
# Warmup Iteration   3: 7.704 ops/ms
Iteration   1: 7.929 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.879 ±(99.9%) 0.933 ops/ms [Average]
  (min, avg, max) = (7.827, 7.879, 7.929), stdev = 0.051
  CI (99.9%): [6.946, 8.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.834 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.004 ms/op
Iteration   1: 3.267 ±(99.9%) 0.002 ms/op
Iteration   2: 3.375 ±(99.9%) 0.004 ms/op
Iteration   3: 3.325 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.322 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.267, 3.322, 3.375), stdev = 0.054
  CI (99.9%): [2.332, 4.313] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.004 ms/op
Iteration   1: 3.195 ±(99.9%) 0.004 ms/op
Iteration   2: 3.321 ±(99.9%) 0.002 ms/op
Iteration   3: 3.206 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.241 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.195, 3.241, 3.321), stdev = 0.070
  CI (99.9%): [1.968, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.005 ms/op
Iteration   1: 3.412 ±(99.9%) 0.005 ms/op
Iteration   2: 3.473 ±(99.9%) 0.003 ms/op
Iteration   3: 3.494 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.460 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.412, 3.460, 3.494), stdev = 0.042
  CI (99.9%): [2.688, 4.231] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.005 ms/op
Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
Iteration   2: 4.146 ±(99.9%) 0.023 ms/op
Iteration   3: 4.048 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.129 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (4.048, 4.129, 4.193), stdev = 0.074
  CI (99.9%): [2.784, 5.474] (assumes normal distribution)


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
# Warmup Iteration   1: 5.121 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.007 ms/op
Iteration   1: 3.329 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  13.094 ms/op
                 createUser·p0.9999: 18.887 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 3.292 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  9.318 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  15.008 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 287183
  mean =      3.345 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9062 
    [ 2.500,  5.000) = 275031 
    [ 5.000,  7.500) = 2310 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     10.955 ms/op
     p(99.9900) =     26.256 ms/op
     p(99.9990) =     26.841 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.799 ms/op
                 existUser·p0.9999: 14.089 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  8.429 ms/op
                 existUser·p0.9999: 15.883 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  10.019 ms/op
                 existUser·p0.9999: 16.843 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311541
  mean =      3.081 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1061 
    [ 1.250,  2.500) = 17000 
    [ 2.500,  3.750) = 273272 
    [ 3.750,  5.000) = 18317 
    [ 5.000,  6.250) = 908 
    [ 6.250,  7.500) = 498 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.002 ms/op
     p(99.9900) =     16.594 ms/op
     p(99.9990) =     17.861 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
Iteration   1: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.214 ms/op
                 getUser·p0.999:  9.769 ms/op
                 getUser·p0.9999: 27.569 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.235 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 30.835 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  9.802 ms/op
                 getUser·p0.9999: 32.985 ms/op
                 getUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 290065
  mean =      3.306 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15438 
    [ 2.500,  5.000) = 271024 
    [ 5.000,  7.500) = 2898 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     31.260 ms/op
     p(99.9990) =     33.305 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 6.507 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.014 ms/op
Iteration   1: 4.226 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.446 ms/op
                 listUser·p0.9999: 15.703 ms/op
                 listUser·p1.00:   16.007 ms/op

Iteration   2: 4.164 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  15.946 ms/op
                 listUser·p0.9999: 19.289 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  17.605 ms/op
                 listUser·p0.9999: 22.150 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229267
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1503 
    [ 2.500,  5.000) = 199010 
    [ 5.000,  7.500) = 26358 
    [ 7.500, 10.000) = 1849 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     15.429 ms/op
     p(99.9900) =     21.382 ms/op
     p(99.9990) =     24.098 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.039 ± 2.285  ops/ms
ClientGrpc.existUser                       thrpt       3  10.526 ± 1.441  ops/ms
ClientGrpc.getUser                         thrpt       3  10.006 ± 1.731  ops/ms
ClientGrpc.listUser                        thrpt       3   7.879 ± 0.933  ops/ms
ClientGrpc.createUser                       avgt       3   3.322 ± 0.991   ms/op
ClientGrpc.existUser                        avgt       3   3.241 ± 1.272   ms/op
ClientGrpc.getUser                          avgt       3   3.460 ± 0.772   ms/op
ClientGrpc.listUser                         avgt       3   4.129 ± 1.345   ms/op
ClientGrpc.createUser                     sample  287183   3.345 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.297           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.955           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.256           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  311541   3.081 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.723           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.052           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.002           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.594           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  290065   3.306 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.670           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.269           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.177           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.159           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.260           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.979           ms/op
ClientGrpc.listUser                       sample  229267   4.185 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.071           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.994           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.429           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.382           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
