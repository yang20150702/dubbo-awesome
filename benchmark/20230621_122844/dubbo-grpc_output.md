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
# Warmup Iteration   1: 4.727 ops/ms
# Warmup Iteration   2: 9.182 ops/ms
# Warmup Iteration   3: 10.190 ops/ms
Iteration   1: 10.608 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.518 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (10.400, 10.518, 10.608), stdev = 0.107
  CI (99.9%): [8.569, 12.468] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 9.613 ops/ms
# Warmup Iteration   2: 10.539 ops/ms
# Warmup Iteration   3: 10.909 ops/ms
Iteration   1: 11.129 ops/ms
Iteration   2: 10.976 ops/ms
Iteration   3: 11.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.100 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.976, 11.100, 11.195), stdev = 0.112
  CI (99.9%): [9.051, 13.149] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.130 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.670 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.595 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.685 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (10.595, 10.685, 10.752), stdev = 0.081
  CI (99.9%): [9.212, 12.159] (assumes normal distribution)


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
# Warmup Iteration   1: 6.263 ops/ms
# Warmup Iteration   2: 7.564 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 8.207 ops/ms
Iteration   3: 7.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.996 ±(99.9%) 3.564 ops/ms [Average]
  (min, avg, max) = (7.822, 7.996, 8.207), stdev = 0.195
  CI (99.9%): [4.432, 11.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.004 ms/op
Iteration   1: 3.057 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.003 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.024, 3.040, 3.057), stdev = 0.017
  CI (99.9%): [2.739, 3.342] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.005 ms/op
Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
Iteration   3: 2.936 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (2.852, 2.908, 2.937), stdev = 0.049
  CI (99.9%): [2.014, 3.803] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.015 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.005, 3.015, 3.034), stdev = 0.016
  CI (99.9%): [2.720, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 5.485 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 3.978 ±(99.9%) 0.015 ms/op
Iteration   2: 4.056 ±(99.9%) 0.015 ms/op
Iteration   3: 3.889 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (3.889, 3.974, 4.056), stdev = 0.084
  CI (99.9%): [2.450, 5.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
Iteration   1: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.545 ms/op
                 createUser·p0.9999: 13.489 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 3.003 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.204 ms/op
                 createUser·p0.9999: 13.064 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   3: 3.041 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  11.249 ms/op
                 createUser·p0.9999: 46.365 ms/op
                 createUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318972
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 317893 
    [ 5.000, 10.000) = 805 
    [10.000, 15.000) = 210 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 26 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     37.231 ms/op
     p(99.9990) =     46.596 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.005 ms/op
Iteration   1: 2.915 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.627 ms/op
                 existUser·p0.9999: 11.453 ms/op
                 existUser·p1.00:   11.813 ms/op

Iteration   2: 2.847 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.095 ms/op
                 existUser·p0.9999: 12.444 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.904 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.003 ms/op
                 existUser·p0.9999: 26.503 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332378
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38641 
    [ 2.500,  5.000) = 292437 
    [ 5.000,  7.500) = 1058 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      6.641 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     26.663 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.779 ms/op
                 getUser·p0.9999: 10.912 ms/op
                 getUser·p1.00:   11.108 ms/op

Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.784 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.782 ms/op
                 getUser·p0.9999: 15.269 ms/op
                 getUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314834
  mean =      3.047 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1214 
    [ 1.250,  2.500) = 17316 
    [ 2.500,  3.750) = 280959 
    [ 3.750,  5.000) = 14185 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     14.870 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 5.277 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
Iteration   1: 3.981 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.706 ms/op
                 listUser·p0.9999: 16.656 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.370 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.483 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.763 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 26.149 ms/op
                 listUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241223
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3095 
    [ 2.500,  5.000) = 218312 
    [ 5.000,  7.500) = 18620 
    [ 7.500, 10.000) = 758 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.464 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.338 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.518 ± 1.950  ops/ms
ClientGrpc.existUser                       thrpt       3  11.100 ± 2.049  ops/ms
ClientGrpc.getUser                         thrpt       3  10.685 ± 1.474  ops/ms
ClientGrpc.listUser                        thrpt       3   7.996 ± 3.564  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.894   ms/op
ClientGrpc.getUser                          avgt       3   3.015 ± 0.295   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 1.524   ms/op
ClientGrpc.createUser                     sample  318972   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.523           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.441           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.594           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          37.231           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          46.662           ms/op
ClientGrpc.existUser                      sample  332378   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.548           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.641           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.333           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  314834   3.047 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.545           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.870           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.647           ms/op
ClientGrpc.listUser                       sample  241223   3.981 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.483           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.464           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.625           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.444           ms/op
