# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.603 ops/ms
# Warmup Iteration   2: 8.556 ops/ms
# Warmup Iteration   3: 9.752 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 9.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.800 ±(99.9%) 3.254 ops/ms [Average]
  (min, avg, max) = (9.621, 9.800, 9.978), stdev = 0.178
  CI (99.9%): [6.547, 13.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.568 ops/ms
# Warmup Iteration   2: 10.163 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.752 ±(99.9%) 0.445 ops/ms [Average]
  (min, avg, max) = (10.724, 10.752, 10.767), stdev = 0.024
  CI (99.9%): [10.307, 11.198] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 9.913 ops/ms
# Warmup Iteration   3: 9.785 ops/ms
Iteration   1: 9.942 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 10.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.986 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (9.942, 9.986, 10.068), stdev = 0.071
  CI (99.9%): [8.687, 11.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.840 ops/ms
# Warmup Iteration   2: 7.354 ops/ms
# Warmup Iteration   3: 7.812 ops/ms
Iteration   1: 7.663 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.818 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (7.663, 7.818, 7.904), stdev = 0.135
  CI (99.9%): [5.363, 10.272] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.451 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.004 ms/op
Iteration   1: 3.149 ±(99.9%) 0.002 ms/op
Iteration   2: 3.223 ±(99.9%) 0.001 ms/op
Iteration   3: 3.182 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.184 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.149, 3.184, 3.223), stdev = 0.037
  CI (99.9%): [2.509, 3.860] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 3.042 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.037 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (3.006, 3.037, 3.065), stdev = 0.030
  CI (99.9%): [2.494, 3.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.262 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.003 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.195 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.194 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (3.188, 3.194, 3.198), stdev = 0.005
  CI (99.9%): [3.103, 3.285] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.308 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.010 ms/op
Iteration   1: 4.074 ±(99.9%) 0.017 ms/op
Iteration   2: 4.107 ±(99.9%) 0.010 ms/op
Iteration   3: 4.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.088 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (4.074, 4.088, 4.107), stdev = 0.017
  CI (99.9%): [3.776, 4.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.211 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.861 ms/op
                 createUser·p0.9999: 17.329 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  13.728 ms/op
                 createUser·p0.9999: 22.184 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297082
  mean =      3.229 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17537 
    [ 2.500,  5.000) = 277981 
    [ 5.000,  7.500) = 1062 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     23.612 ms/op
     p(99.9990) =     24.250 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.202 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  7.668 ms/op
                 existUser·p0.9999: 13.380 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.838 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.237 ms/op
                 existUser·p0.9999: 15.172 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.275 ms/op
                 existUser·p0.9999: 16.731 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316075
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1229 
    [ 1.250,  2.500) = 40617 
    [ 2.500,  3.750) = 245425 
    [ 3.750,  5.000) = 27176 
    [ 5.000,  6.250) = 898 
    [ 6.250,  7.500) = 414 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.503 ms/op
     p(99.9900) =     16.128 ms/op
     p(99.9990) =     17.056 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.489 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.008 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  8.900 ms/op
                 getUser·p0.9999: 16.286 ms/op
                 getUser·p1.00:   16.597 ms/op

Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.722 ms/op
                 getUser·p0.999:  7.553 ms/op
                 getUser·p0.9999: 20.280 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  7.863 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301044
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21599 
    [ 2.500,  5.000) = 276501 
    [ 5.000,  7.500) = 2489 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      8.134 ms/op
     p(99.9900) =     20.051 ms/op
     p(99.9990) =     21.954 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.011 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 20.445 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.256 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  17.755 ms/op
                 listUser·p0.9999: 26.222 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   3: 4.172 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  18.506 ms/op
                 listUser·p0.9999: 29.295 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234967
  mean =      4.085 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2384 
    [ 2.500,  5.000) = 201911 
    [ 5.000,  7.500) = 28651 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     29.676 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.800 ± 3.254  ops/ms
ClientGrpc.existUser                       thrpt       3  10.752 ± 0.445  ops/ms
ClientGrpc.getUser                         thrpt       3   9.986 ± 1.298  ops/ms
ClientGrpc.listUser                        thrpt       3   7.818 ± 2.455  ops/ms
ClientGrpc.createUser                       avgt       3   3.184 ± 0.675   ms/op
ClientGrpc.existUser                        avgt       3   3.037 ± 0.543   ms/op
ClientGrpc.getUser                          avgt       3   3.194 ± 0.091   ms/op
ClientGrpc.listUser                         avgt       3   4.088 ± 0.312   ms/op
ClientGrpc.createUser                     sample  297082   3.229 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.554           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.612           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.412           ms/op
ClientGrpc.existUser                      sample  316075   3.037 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.827           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.916           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.128           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  301044   3.187 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.134           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.051           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.184           ms/op
ClientGrpc.listUser                       sample  234967   4.085 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.784           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.548           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.558           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
