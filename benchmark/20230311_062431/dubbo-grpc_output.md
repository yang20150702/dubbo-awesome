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
# Warmup Iteration   1: 3.573 ops/ms
# Warmup Iteration   2: 8.091 ops/ms
# Warmup Iteration   3: 9.450 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.738 ±(99.9%) 3.756 ops/ms [Average]
  (min, avg, max) = (9.524, 9.738, 9.935), stdev = 0.206
  CI (99.9%): [5.982, 13.493] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.646 ops/ms
# Warmup Iteration   2: 9.560 ops/ms
# Warmup Iteration   3: 9.940 ops/ms
Iteration   1: 9.868 ops/ms
Iteration   2: 9.731 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.812 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (9.731, 9.812, 9.868), stdev = 0.072
  CI (99.9%): [8.507, 11.118] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.006 ops/ms
# Warmup Iteration   2: 9.227 ops/ms
# Warmup Iteration   3: 9.372 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 9.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.822 ±(99.9%) 0.319 ops/ms [Average]
  (min, avg, max) = (9.805, 9.822, 9.840), stdev = 0.017
  CI (99.9%): [9.503, 10.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ops/ms
# Warmup Iteration   2: 6.978 ops/ms
# Warmup Iteration   3: 7.314 ops/ms
Iteration   1: 7.399 ops/ms
Iteration   2: 7.443 ops/ms
Iteration   3: 7.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.422 ±(99.9%) 0.402 ops/ms [Average]
  (min, avg, max) = (7.399, 7.422, 7.443), stdev = 0.022
  CI (99.9%): [7.019, 7.824] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.004 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.225 ±(99.9%) 0.002 ms/op
Iteration   3: 3.324 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.259 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.225, 3.259, 3.324), stdev = 0.057
  CI (99.9%): [2.225, 4.292] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.279 ±(99.9%) 0.002 ms/op
Iteration   2: 3.279 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.220 ±(99.9%) 1.864 ms/op [Average]
  (min, avg, max) = (3.102, 3.220, 3.279), stdev = 0.102
  CI (99.9%): [1.356, 5.084] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.860 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.004 ms/op
Iteration   1: 3.218 ±(99.9%) 0.003 ms/op
Iteration   2: 3.237 ±(99.9%) 0.003 ms/op
Iteration   3: 3.228 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.228 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (3.218, 3.228, 3.237), stdev = 0.010
  CI (99.9%): [3.053, 3.402] (assumes normal distribution)


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
# Warmup Iteration   1: 6.079 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.330 ±(99.9%) 0.013 ms/op
Iteration   1: 4.296 ±(99.9%) 0.026 ms/op
Iteration   2: 4.170 ±(99.9%) 0.014 ms/op
Iteration   3: 4.298 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.255 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (4.170, 4.255, 4.298), stdev = 0.073
  CI (99.9%): [2.920, 5.590] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.377 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 16.450 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  13.415 ms/op
                 createUser·p0.9999: 16.375 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   3: 3.329 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.495 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  8.061 ms/op
                 createUser·p0.9999: 17.347 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 286074
  mean =      3.355 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 12838 
    [ 2.500,  3.750) = 215219 
    [ 3.750,  5.000) = 53375 
    [ 5.000,  6.250) = 2960 
    [ 6.250,  7.500) = 742 
    [ 7.500,  8.750) = 326 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 80 
    [16.250, 17.500) = 83 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.484 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.207 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  8.034 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  7.232 ms/op
                 existUser·p0.9999: 17.176 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.412 ms/op
                 existUser·p0.9999: 18.639 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 304428
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 964 
    [ 1.250,  2.500) = 23754 
    [ 2.500,  3.750) = 247150 
    [ 3.750,  5.000) = 29863 
    [ 5.000,  6.250) = 1902 
    [ 6.250,  7.500) = 459 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 75 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.623 ms/op
     p(99.9900) =     17.713 ms/op
     p(99.9990) =     19.168 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.007 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  9.321 ms/op
                 getUser·p0.9999: 19.041 ms/op
                 getUser·p1.00:   19.759 ms/op

Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  10.542 ms/op
                 getUser·p0.9999: 14.880 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  12.492 ms/op
                 getUser·p0.9999: 18.233 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 293078
  mean =      3.276 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14559 
    [ 2.500,  5.000) = 274796 
    [ 5.000,  7.500) = 3155 
    [ 7.500, 10.000) = 288 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     19.829 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.013 ms/op
Iteration   1: 4.411 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.529 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  14.098 ms/op
                 listUser·p0.9999: 15.855 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   2: 4.246 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 27.801 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 4.435 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.190 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.275 ms/op
                 listUser·p0.999:  18.305 ms/op
                 listUser·p0.9999: 28.028 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 220006
  mean =      4.363 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1611 
    [ 2.500,  5.000) = 179546 
    [ 5.000,  7.500) = 34460 
    [ 7.500, 10.000) = 3463 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      4.137 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.423 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.738 ± 3.756  ops/ms
ClientGrpc.existUser                       thrpt       3   9.812 ± 1.306  ops/ms
ClientGrpc.getUser                         thrpt       3   9.822 ± 0.319  ops/ms
ClientGrpc.listUser                        thrpt       3   7.422 ± 0.402  ops/ms
ClientGrpc.createUser                       avgt       3   3.259 ± 1.033   ms/op
ClientGrpc.existUser                        avgt       3   3.220 ± 1.864   ms/op
ClientGrpc.getUser                          avgt       3   3.228 ± 0.175   ms/op
ClientGrpc.listUser                         avgt       3   4.255 ± 1.335   ms/op
ClientGrpc.createUser                     sample  286074   3.355 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.495           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.289           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.519           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.777           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.957           ms/op
ClientGrpc.existUser                      sample  304428   3.153 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.719           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.113           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.623           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.713           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.169           ms/op
ClientGrpc.getUser                        sample  293078   3.276 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.529           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.207           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.227           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.880           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.121           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  220006   4.363 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.137           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.339           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.761           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.230           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
