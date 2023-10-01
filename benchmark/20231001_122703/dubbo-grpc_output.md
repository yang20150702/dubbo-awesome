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
# Warmup Iteration   1: 3.737 ops/ms
# Warmup Iteration   2: 8.282 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 10.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.858 ±(99.9%) 3.741 ops/ms [Average]
  (min, avg, max) = (9.721, 9.858, 10.094), stdev = 0.205
  CI (99.9%): [6.117, 13.599] (assumes normal distribution)


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
# Warmup Iteration   1: 7.008 ops/ms
# Warmup Iteration   2: 9.984 ops/ms
# Warmup Iteration   3: 10.681 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.578 ±(99.9%) 2.938 ops/ms [Average]
  (min, avg, max) = (10.392, 10.578, 10.679), stdev = 0.161
  CI (99.9%): [7.640, 13.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 9.392 ops/ms
# Warmup Iteration   3: 9.722 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 10.151 ops/ms
Iteration   3: 10.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.024 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (9.913, 10.024, 10.151), stdev = 0.120
  CI (99.9%): [7.837, 12.211] (assumes normal distribution)


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
# Warmup Iteration   1: 5.475 ops/ms
# Warmup Iteration   2: 7.688 ops/ms
# Warmup Iteration   3: 7.703 ops/ms
Iteration   1: 7.853 ops/ms
Iteration   2: 7.933 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.920 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (7.853, 7.920, 7.976), stdev = 0.062
  CI (99.9%): [6.782, 9.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
Iteration   2: 3.139 ±(99.9%) 0.005 ms/op
Iteration   3: 3.140 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (3.139, 3.141, 3.145), stdev = 0.003
  CI (99.9%): [3.082, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.397 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.000 ±(99.9%) 0.004 ms/op
Iteration   2: 2.906 ±(99.9%) 0.002 ms/op
Iteration   3: 3.051 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.986 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (2.906, 2.986, 3.051), stdev = 0.074
  CI (99.9%): [1.642, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.565 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.004 ms/op
Iteration   1: 3.172 ±(99.9%) 0.004 ms/op
Iteration   2: 3.054 ±(99.9%) 0.004 ms/op
Iteration   3: 3.100 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.054, 3.109, 3.172), stdev = 0.060
  CI (99.9%): [2.020, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.839 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.024 ms/op
Iteration   1: 4.029 ±(99.9%) 0.023 ms/op
Iteration   2: 3.952 ±(99.9%) 0.007 ms/op
Iteration   3: 3.999 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.994 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.952, 3.994, 4.029), stdev = 0.039
  CI (99.9%): [3.279, 4.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.345 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.009 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.803 ms/op
                 createUser·p0.999:  7.819 ms/op
                 createUser·p0.9999: 17.149 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  9.786 ms/op
                 createUser·p0.9999: 17.811 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  11.145 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309625
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14804 
    [ 2.500,  5.000) = 292450 
    [ 5.000,  7.500) = 1923 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      9.419 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     21.689 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.600 ms/op
                 existUser·p0.999:  10.163 ms/op
                 existUser·p0.9999: 13.557 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.530 ms/op
                 existUser·p0.9999: 20.212 ms/op
                 existUser·p1.00:   20.873 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  8.105 ms/op
                 existUser·p0.9999: 17.319 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316382
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21008 
    [ 2.500,  5.000) = 293115 
    [ 5.000,  7.500) = 1710 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     17.084 ms/op
     p(99.9990) =     20.726 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
Iteration   1: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  13.062 ms/op
                 getUser·p0.9999: 19.201 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  9.631 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 3.168 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  13.260 ms/op
                 getUser·p0.9999: 24.765 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303348
  mean =      3.166 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11860 
    [ 2.500,  5.000) = 287842 
    [ 5.000,  7.500) = 2741 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     12.588 ms/op
     p(99.9900) =     23.451 ms/op
     p(99.9990) =     25.229 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 5.402 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.011 ms/op
Iteration   1: 4.074 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.211 ms/op
                 listUser·p0.9999: 23.288 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 4.078 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 22.826 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.074 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  19.140 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235585
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1597 
    [ 2.500,  5.000) = 213867 
    [ 5.000,  7.500) = 18082 
    [ 7.500, 10.000) = 1313 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     15.464 ms/op
     p(99.9900) =     31.489 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.858 ± 3.741  ops/ms
ClientGrpc.existUser                       thrpt       3  10.578 ± 2.938  ops/ms
ClientGrpc.getUser                         thrpt       3  10.024 ± 2.187  ops/ms
ClientGrpc.listUser                        thrpt       3   7.920 ± 1.138  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 0.059   ms/op
ClientGrpc.existUser                        avgt       3   2.986 ± 1.343   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 1.088   ms/op
ClientGrpc.listUser                         avgt       3   3.994 ± 0.714   ms/op
ClientGrpc.createUser                     sample  309625   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.419           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.513           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  316382   3.034 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.585           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.645           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.084           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.873           ms/op
ClientGrpc.getUser                        sample  303348   3.166 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.588           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.451           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  235585   4.075 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.831           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.315           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.464           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.489           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.537           ms/op
