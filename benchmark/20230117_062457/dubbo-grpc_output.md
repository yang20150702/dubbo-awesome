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
# Warmup Iteration   1: 4.140 ops/ms
# Warmup Iteration   2: 9.310 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.021 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.225 ±(99.9%) 3.452 ops/ms [Average]
  (min, avg, max) = (10.021, 10.225, 10.396), stdev = 0.189
  CI (99.9%): [6.772, 13.677] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ops/ms
# Warmup Iteration   2: 10.380 ops/ms
# Warmup Iteration   3: 10.575 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.566 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (10.491, 10.566, 10.655), stdev = 0.083
  CI (99.9%): [9.055, 12.078] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ops/ms
# Warmup Iteration   2: 9.833 ops/ms
# Warmup Iteration   3: 9.824 ops/ms
Iteration   1: 10.043 ops/ms
Iteration   2: 10.178 ops/ms
Iteration   3: 9.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.038 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (9.892, 10.038, 10.178), stdev = 0.143
  CI (99.9%): [7.429, 12.647] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.400 ops/ms
# Warmup Iteration   2: 7.729 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 7.891 ops/ms
Iteration   2: 7.801 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.882 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (7.801, 7.882, 7.954), stdev = 0.077
  CI (99.9%): [6.483, 9.281] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.009 ms/op
Iteration   2: 3.167 ±(99.9%) 0.003 ms/op
Iteration   3: 3.189 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.182 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.167, 3.182, 3.190), stdev = 0.013
  CI (99.9%): [2.947, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.988 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.967, 2.988, 3.005), stdev = 0.019
  CI (99.9%): [2.637, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.004 ms/op
Iteration   1: 3.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.160 ±(99.9%) 0.002 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.087, 3.142, 3.181), stdev = 0.050
  CI (99.9%): [2.238, 4.046] (assumes normal distribution)


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
# Warmup Iteration   1: 5.244 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.023 ms/op
Iteration   1: 4.017 ±(99.9%) 0.009 ms/op
Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
Iteration   3: 3.912 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.987 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (3.912, 3.987, 4.031), stdev = 0.065
  CI (99.9%): [2.800, 5.173] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.810 ms/op
                 createUser·p0.9999: 13.968 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.686 ms/op
                 createUser·p0.9999: 14.744 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   3: 3.228 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303068
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22024 
    [ 2.500,  5.000) = 279758 
    [ 5.000,  7.500) = 836 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     27.833 ms/op
     p(99.9990) =     28.080 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.544 ms/op
                 existUser·p0.9999: 16.685 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  9.425 ms/op
                 existUser·p0.9999: 14.719 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  7.094 ms/op
                 existUser·p0.9999: 16.295 ms/op
                 existUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319658
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 973 
    [ 1.250,  2.500) = 40644 
    [ 2.500,  3.750) = 257369 
    [ 3.750,  5.000) = 19638 
    [ 5.000,  6.250) = 457 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.195 ms/op
     p(99.9900) =     16.206 ms/op
     p(99.9990) =     16.928 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.380 ms/op
                 getUser·p0.9999: 22.328 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.807 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.684 ms/op
                 getUser·p0.9999: 21.168 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307151
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27064 
    [ 2.500,  5.000) = 278980 
    [ 5.000,  7.500) = 766 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.798 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.605 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 6.279 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.546 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 16.278 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.727 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.322 ms/op
                 listUser·p0.9999: 21.203 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 21.098 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237629
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2394 
    [ 2.500,  5.000) = 209061 
    [ 5.000,  7.500) = 24974 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.571 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     22.995 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.225 ± 3.452  ops/ms
ClientGrpc.existUser                       thrpt       3  10.566 ± 1.511  ops/ms
ClientGrpc.getUser                         thrpt       3  10.038 ± 2.609  ops/ms
ClientGrpc.listUser                        thrpt       3   7.882 ± 1.399  ops/ms
ClientGrpc.createUser                       avgt       3   3.182 ± 0.235   ms/op
ClientGrpc.existUser                        avgt       3   2.988 ± 0.351   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.904   ms/op
ClientGrpc.listUser                         avgt       3   3.987 ± 1.186   ms/op
ClientGrpc.createUser                     sample  303068   3.167 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.733           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.059           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.200           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.833           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.148           ms/op
ClientGrpc.existUser                      sample  319658   3.004 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.791           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.195           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.206           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.039           ms/op
ClientGrpc.getUser                        sample  307151   3.124 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.798           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.791           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  237629   4.040 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.727           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.571           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.611           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
