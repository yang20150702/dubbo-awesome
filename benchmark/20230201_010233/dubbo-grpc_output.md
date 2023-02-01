# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ops/ms
# Warmup Iteration   2: 8.750 ops/ms
# Warmup Iteration   3: 9.613 ops/ms
Iteration   1: 10.039 ops/ms
Iteration   2: 9.824 ops/ms
Iteration   3: 9.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.942 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (9.824, 9.942, 10.039), stdev = 0.109
  CI (99.9%): [7.955, 11.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.002 ops/ms
# Warmup Iteration   2: 9.801 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.205 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.258 ±(99.9%) 1.114 ops/ms [Average]
  (min, avg, max) = (10.205, 10.258, 10.324), stdev = 0.061
  CI (99.9%): [9.144, 11.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.349 ops/ms
# Warmup Iteration   2: 9.396 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 9.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.090 ±(99.9%) 2.750 ops/ms [Average]
  (min, avg, max) = (9.928, 10.090, 10.227), stdev = 0.151
  CI (99.9%): [7.340, 12.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.923 ops/ms
# Warmup Iteration   2: 7.520 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 7.693 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 7.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.756 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (7.693, 7.756, 7.812), stdev = 0.060
  CI (99.9%): [6.666, 8.845] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.004 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 3.282 ±(99.9%) 0.002 ms/op
Iteration   3: 3.304 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.233 ±(99.9%) 1.910 ms/op [Average]
  (min, avg, max) = (3.112, 3.233, 3.304), stdev = 0.105
  CI (99.9%): [1.322, 5.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.379 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.113 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (3.019, 3.113, 3.197), stdev = 0.089
  CI (99.9%): [1.487, 4.740] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.924 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.199 ±(99.9%) 0.002 ms/op
Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
Iteration   3: 3.281 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.239 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.199, 3.239, 3.281), stdev = 0.041
  CI (99.9%): [2.498, 3.980] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.013 ms/op
Iteration   1: 4.006 ±(99.9%) 0.021 ms/op
Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
Iteration   3: 3.956 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (3.956, 4.032, 4.135), stdev = 0.092
  CI (99.9%): [2.349, 5.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.512 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.244 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.966 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.561 ms/op
                 createUser·p0.9999: 15.291 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 3.215 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 15.860 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.855 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  10.174 ms/op
                 createUser·p0.9999: 18.677 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298198
  mean =      3.220 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 18208 
    [ 2.500,  3.750) = 231894 
    [ 3.750,  5.000) = 46637 
    [ 5.000,  6.250) = 439 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 100 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.158 ms/op
     p(99.9900) =     18.165 ms/op
     p(99.9990) =     19.564 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.187 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.700 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.942 ms/op
                 existUser·p0.9999: 15.295 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   3: 3.175 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  5.876 ms/op
                 existUser·p0.9999: 16.169 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 307581
  mean =      3.119 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1446 
    [ 1.250,  2.500) = 30980 
    [ 2.500,  3.750) = 232616 
    [ 3.750,  5.000) = 41622 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.335 ms/op
     p(99.9900) =     15.733 ms/op
     p(99.9990) =     16.602 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  12.039 ms/op
                 getUser·p0.9999: 17.952 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  9.033 ms/op
                 getUser·p0.9999: 21.856 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301595
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21031 
    [ 2.500,  5.000) = 279449 
    [ 5.000,  7.500) = 761 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.007 ms/op
     p(99.9900) =     32.932 ms/op
     p(99.9990) =     34.404 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.011 ms/op
Iteration   1: 4.126 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  14.685 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 4.055 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 20.582 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 4.049 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.680 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235480
  mean =      4.076 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1352 
    [ 2.500,  5.000) = 208931 
    [ 5.000,  7.500) = 23711 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.983 ms/op
     p(99.9900) =     25.127 ms/op
     p(99.9990) =     26.511 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.942 ± 1.987  ops/ms
ClientGrpc.existUser                       thrpt       3  10.258 ± 1.114  ops/ms
ClientGrpc.getUser                         thrpt       3  10.090 ± 2.750  ops/ms
ClientGrpc.listUser                        thrpt       3   7.756 ± 1.090  ops/ms
ClientGrpc.createUser                       avgt       3   3.233 ± 1.910   ms/op
ClientGrpc.existUser                        avgt       3   3.113 ± 1.627   ms/op
ClientGrpc.getUser                          avgt       3   3.239 ± 0.741   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 1.683   ms/op
ClientGrpc.createUser                     sample  298198   3.220 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.191           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.158           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.165           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  307581   3.119 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.105           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.335           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.733           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  301595   3.181 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.614           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.043           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.007           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.932           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.472           ms/op
ClientGrpc.listUser                       sample  235480   4.076 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.932           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.912           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.983           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.127           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.837           ms/op
