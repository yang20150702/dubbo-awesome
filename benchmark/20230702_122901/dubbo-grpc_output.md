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
# Warmup Iteration   1: 4.089 ops/ms
# Warmup Iteration   2: 8.928 ops/ms
# Warmup Iteration   3: 10.026 ops/ms
Iteration   1: 10.436 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.445 ±(99.9%) 0.156 ops/ms [Average]
  (min, avg, max) = (10.436, 10.445, 10.450), stdev = 0.009
  CI (99.9%): [10.290, 10.601] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.907 ops/ms
# Warmup Iteration   2: 10.292 ops/ms
# Warmup Iteration   3: 11.076 ops/ms
Iteration   1: 10.984 ops/ms
Iteration   2: 10.959 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.925 ±(99.9%) 1.481 ops/ms [Average]
  (min, avg, max) = (10.833, 10.925, 10.984), stdev = 0.081
  CI (99.9%): [9.444, 12.406] (assumes normal distribution)


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
# Warmup Iteration   1: 6.416 ops/ms
# Warmup Iteration   2: 9.782 ops/ms
# Warmup Iteration   3: 10.363 ops/ms
Iteration   1: 10.528 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 10.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.367 ±(99.9%) 2.986 ops/ms [Average]
  (min, avg, max) = (10.201, 10.367, 10.528), stdev = 0.164
  CI (99.9%): [7.382, 13.353] (assumes normal distribution)


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
# Warmup Iteration   1: 5.817 ops/ms
# Warmup Iteration   2: 7.424 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 7.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.923 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (7.784, 7.923, 8.025), stdev = 0.125
  CI (99.9%): [5.650, 10.196] (assumes normal distribution)


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.003 ms/op
Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.062, 3.082, 3.113), stdev = 0.027
  CI (99.9%): [2.592, 3.572] (assumes normal distribution)


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.003 ms/op
Iteration   1: 2.965 ±(99.9%) 0.003 ms/op
Iteration   2: 2.887 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.945 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (2.887, 2.945, 2.984), stdev = 0.051
  CI (99.9%): [2.007, 3.883] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.004 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.059, 3.080, 3.109), stdev = 0.026
  CI (99.9%): [2.598, 3.562] (assumes normal distribution)


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.295 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.041 ms/op
Iteration   1: 4.211 ±(99.9%) 0.011 ms/op
Iteration   2: 4.151 ±(99.9%) 0.014 ms/op
Iteration   3: 4.058 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.140 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (4.058, 4.140, 4.211), stdev = 0.077
  CI (99.9%): [2.734, 5.546] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.438 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 15.709 ms/op
                 createUser·p1.00:   16.220 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.424 ms/op
                 createUser·p0.9999: 18.001 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  9.029 ms/op
                 createUser·p0.9999: 29.622 ms/op
                 createUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311776
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23777 
    [ 2.500,  5.000) = 286043 
    [ 5.000,  7.500) = 1444 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      9.949 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     29.946 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.819 ms/op
                 existUser·p0.9999: 13.429 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  7.076 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.806 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  7.047 ms/op
                 existUser·p0.9999: 18.289 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320986
  mean =      2.990 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 993 
    [ 1.250,  2.500) = 26342 
    [ 2.500,  3.750) = 281399 
    [ 3.750,  5.000) = 11284 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 255 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     19.254 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.006 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  9.303 ms/op
                 getUser·p0.9999: 15.087 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.983 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  10.357 ms/op
                 getUser·p0.9999: 15.577 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  7.684 ms/op
                 getUser·p0.9999: 24.855 ms/op
                 getUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309058
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17459 
    [ 2.500,  5.000) = 288942 
    [ 5.000,  7.500) = 2164 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     25.130 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 5.654 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.011 ms/op
Iteration   1: 4.137 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.236 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 16.935 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   2: 4.083 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.478 ms/op
                 listUser·p0.9999: 18.148 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 19.502 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233954
  mean =      4.101 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1376 
    [ 2.500,  3.750) = 73530 
    [ 3.750,  5.000) = 135049 
    [ 5.000,  6.250) = 16685 
    [ 6.250,  7.500) = 5845 
    [ 7.500,  8.750) = 840 
    [ 8.750, 10.000) = 160 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 133 
    [15.000, 16.250) = 88 
    [16.250, 17.500) = 66 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.996 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.106 ms/op
     p(99.9000) =     14.599 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.824 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.445 ± 0.156  ops/ms
ClientGrpc.existUser                       thrpt       3  10.925 ± 1.481  ops/ms
ClientGrpc.getUser                         thrpt       3  10.367 ± 2.986  ops/ms
ClientGrpc.listUser                        thrpt       3   7.923 ± 2.273  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.490   ms/op
ClientGrpc.existUser                        avgt       3   2.945 ± 0.938   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.482   ms/op
ClientGrpc.listUser                         avgt       3   4.140 ± 1.406   ms/op
ClientGrpc.createUser                     sample  311776   3.077 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.438           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.949           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.246           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.081           ms/op
ClientGrpc.existUser                      sample  320986   2.990 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.551           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.039           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  309058   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.795           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.759           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.264           ms/op
ClientGrpc.listUser                       sample  233954   4.101 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.996           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.944           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.106           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.890           ms/op
