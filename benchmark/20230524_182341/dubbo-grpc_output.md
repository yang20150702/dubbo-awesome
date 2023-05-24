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
# Warmup Iteration   1: 4.806 ops/ms
# Warmup Iteration   2: 9.362 ops/ms
# Warmup Iteration   3: 10.323 ops/ms
Iteration   1: 10.650 ops/ms
Iteration   2: 10.793 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.690 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (10.626, 10.690, 10.793), stdev = 0.090
  CI (99.9%): [9.041, 12.339] (assumes normal distribution)


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
# Warmup Iteration   1: 8.095 ops/ms
# Warmup Iteration   2: 10.823 ops/ms
# Warmup Iteration   3: 11.204 ops/ms
Iteration   1: 11.310 ops/ms
Iteration   2: 11.073 ops/ms
Iteration   3: 11.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.173 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (11.073, 11.173, 11.310), stdev = 0.123
  CI (99.9%): [8.937, 13.410] (assumes normal distribution)


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
# Warmup Iteration   1: 7.597 ops/ms
# Warmup Iteration   2: 10.282 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.757 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.723 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (10.614, 10.723, 10.798), stdev = 0.096
  CI (99.9%): [8.963, 12.483] (assumes normal distribution)


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
# Warmup Iteration   1: 7.007 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.003 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.063 ±(99.9%) 1.357 ops/ms [Average]
  (min, avg, max) = (8.003, 8.063, 8.146), stdev = 0.074
  CI (99.9%): [6.706, 9.419] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 3.041 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.022, 3.040, 3.057), stdev = 0.018
  CI (99.9%): [2.719, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.003 ms/op
Iteration   3: 2.946 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.946, 2.955, 2.964), stdev = 0.009
  CI (99.9%): [2.788, 3.121] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (3.025, 3.034, 3.041), stdev = 0.008
  CI (99.9%): [2.891, 3.177] (assumes normal distribution)


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
# Warmup Iteration   1: 5.737 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.024 ms/op
Iteration   2: 3.979 ±(99.9%) 0.038 ms/op
Iteration   3: 3.957 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.951, 3.962, 3.979), stdev = 0.015
  CI (99.9%): [3.694, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.652 ms/op
                 createUser·p0.9999: 19.327 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 27.114 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.090 ms/op
                 createUser·p0.9999: 19.430 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314510
  mean =      3.053 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22004 
    [ 2.500,  5.000) = 290985 
    [ 5.000,  7.500) = 1112 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.773 ms/op
     p(99.9900) =     26.626 ms/op
     p(99.9990) =     27.324 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.864 ms/op
                 existUser·p0.9999: 18.751 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  6.169 ms/op
                 existUser·p0.9999: 26.158 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.540 ms/op
                 existUser·p0.9999: 16.883 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322783
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33386 
    [ 2.500,  5.000) = 287849 
    [ 5.000,  7.500) = 1174 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     23.737 ms/op
     p(99.9990) =     26.338 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 13.156 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.253 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.961 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.942 ms/op
                 getUser·p0.9999: 30.573 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310449
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16443 
    [ 2.500,  5.000) = 292563 
    [ 5.000,  7.500) = 1102 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.253 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     28.834 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
Iteration   1: 3.931 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.298 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.093 ms/op
                 listUser·p0.9999: 17.076 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 4.054 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 24.216 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239033
  mean =      4.014 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4758 
    [ 2.500,  5.000) = 209312 
    [ 5.000,  7.500) = 23546 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.285 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     24.669 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.690 ± 1.649  ops/ms
ClientGrpc.existUser                       thrpt       3  11.173 ± 2.237  ops/ms
ClientGrpc.getUser                         thrpt       3  10.723 ± 1.760  ops/ms
ClientGrpc.listUser                        thrpt       3   8.063 ± 1.357  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.321   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.166   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.143   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.269   ms/op
ClientGrpc.createUser                     sample  314510   3.053 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.551           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.773           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.361           ms/op
ClientGrpc.existUser                      sample  322783   2.977 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.741           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.737           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.444           ms/op
ClientGrpc.getUser                        sample  310449   3.092 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.253           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.834           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.195           ms/op
ClientGrpc.listUser                       sample  239033   4.014 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.904           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.285           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.953           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.936           ms/op
