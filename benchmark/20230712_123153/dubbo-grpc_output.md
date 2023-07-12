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
# Warmup Iteration   1: 4.874 ops/ms
# Warmup Iteration   2: 9.262 ops/ms
# Warmup Iteration   3: 10.516 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.968 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.725 ±(99.9%) 4.439 ops/ms [Average]
  (min, avg, max) = (10.481, 10.725, 10.968), stdev = 0.243
  CI (99.9%): [6.286, 15.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 10.678 ops/ms
# Warmup Iteration   3: 11.319 ops/ms
Iteration   1: 11.173 ops/ms
Iteration   2: 11.215 ops/ms
Iteration   3: 11.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.285 ±(99.9%) 2.896 ops/ms [Average]
  (min, avg, max) = (11.173, 11.285, 11.467), stdev = 0.159
  CI (99.9%): [8.389, 14.181] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.708 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.569 ops/ms
Iteration   2: 10.832 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.687 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (10.569, 10.687, 10.832), stdev = 0.134
  CI (99.9%): [8.249, 13.125] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.869 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 8.238 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.203 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (8.167, 8.203, 8.238), stdev = 0.036
  CI (99.9%): [7.549, 8.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.005 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (2.970, 2.997, 3.044), stdev = 0.040
  CI (99.9%): [2.266, 3.729] (assumes normal distribution)


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
Iteration   1: 2.865 ±(99.9%) 0.003 ms/op
Iteration   2: 2.850 ±(99.9%) 0.003 ms/op
Iteration   3: 2.857 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.857 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.850, 2.857, 2.865), stdev = 0.007
  CI (99.9%): [2.721, 2.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.985, 2.991, 3.002), stdev = 0.010
  CI (99.9%): [2.810, 3.172] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.678 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.020 ms/op
Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
Iteration   2: 3.815 ±(99.9%) 0.007 ms/op
Iteration   3: 3.883 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.815, 3.850, 3.883), stdev = 0.034
  CI (99.9%): [3.232, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.096 ms/op
                 createUser·p0.9999: 11.433 ms/op
                 createUser·p1.00:   11.649 ms/op

Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.807 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.795 ms/op
                 createUser·p0.9999: 12.869 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.967 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.391 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  7.168 ms/op
                 createUser·p0.9999: 16.670 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318788
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 805 
    [ 1.250,  2.500) = 21383 
    [ 2.500,  3.750) = 282426 
    [ 3.750,  5.000) = 12767 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     16.093 ms/op
     p(99.9990) =     16.758 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.187 ms/op
                 existUser·p0.9999: 14.040 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.479 ms/op
                 existUser·p0.9999: 24.232 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   3: 2.916 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.549 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  10.283 ms/op
                 existUser·p0.9999: 25.658 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331000
  mean =      2.899 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42370 
    [ 2.500,  5.000) = 287674 
    [ 5.000,  7.500) = 626 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     24.986 ms/op
     p(99.9990) =     25.844 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.031 ms/op
Iteration   1: 3.466 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   20.709 ms/op
                 getUser·p0.999:  26.345 ms/op
                 getUser·p0.9999: 32.707 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   2: 3.182 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   13.397 ms/op
                 getUser·p0.999:  25.178 ms/op
                 getUser·p0.9999: 31.025 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 2.969 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  14.991 ms/op
                 getUser·p0.9999: 23.026 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300880
  mean =      3.193 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21481 
    [ 2.500,  5.000) = 273983 
    [ 5.000,  7.500) = 1149 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 442 
    [15.000, 17.500) = 748 
    [17.500, 20.000) = 937 
    [20.000, 22.500) = 797 
    [22.500, 25.000) = 466 
    [25.000, 27.500) = 160 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =     15.729 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     30.853 ms/op
     p(99.9990) =     33.550 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.010 ms/op
Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 15.093 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   2: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.877 ms/op
                 listUser·p0.999:  14.836 ms/op
                 listUser·p0.9999: 24.637 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 23.051 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245962
  mean =      3.906 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4268 
    [ 2.500,  5.000) = 218693 
    [ 5.000,  7.500) = 21638 
    [ 7.500, 10.000) = 881 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.921 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.725 ± 4.439  ops/ms
ClientGrpc.existUser                       thrpt       3  11.285 ± 2.896  ops/ms
ClientGrpc.getUser                         thrpt       3  10.687 ± 2.438  ops/ms
ClientGrpc.listUser                        thrpt       3   8.203 ± 0.653  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.732   ms/op
ClientGrpc.existUser                        avgt       3   2.857 ± 0.137   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.181   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.617   ms/op
ClientGrpc.createUser                     sample  318788   3.011 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.135           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.093           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.843           ms/op
ClientGrpc.existUser                      sample  331000   2.899 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.549           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.986           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  300880   3.193 ± 0.012   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.622           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          15.729           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          24.674           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.853           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.210           ms/op
ClientGrpc.listUser                       sample  245962   3.906 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.120           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.648           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.002           ms/op
