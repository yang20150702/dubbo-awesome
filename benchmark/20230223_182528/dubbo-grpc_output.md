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
# Warmup Iteration   1: 4.295 ops/ms
# Warmup Iteration   2: 8.868 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 10.059 ops/ms
Iteration   2: 10.076 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.057 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (10.036, 10.057, 10.076), stdev = 0.020
  CI (99.9%): [9.695, 10.419] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.118 ops/ms
# Warmup Iteration   2: 10.268 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.553 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (10.497, 10.553, 10.661), stdev = 0.094
  CI (99.9%): [8.844, 12.262] (assumes normal distribution)


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
# Warmup Iteration   1: 6.726 ops/ms
# Warmup Iteration   2: 9.940 ops/ms
# Warmup Iteration   3: 10.136 ops/ms
Iteration   1: 9.914 ops/ms
Iteration   2: 10.063 ops/ms
Iteration   3: 10.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.075 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (9.914, 10.075, 10.249), stdev = 0.168
  CI (99.9%): [7.009, 13.142] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.586 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 7.975 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 7.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.938 ±(99.9%) 0.622 ops/ms [Average]
  (min, avg, max) = (7.909, 7.938, 7.975), stdev = 0.034
  CI (99.9%): [7.316, 8.560] (assumes normal distribution)


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
# Warmup Iteration   1: 5.328 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.014 ms/op
Iteration   1: 3.208 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
Iteration   3: 3.267 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.217 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.175, 3.217, 3.267), stdev = 0.046
  CI (99.9%): [2.370, 4.064] (assumes normal distribution)


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.002 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (2.962, 3.002, 3.030), stdev = 0.036
  CI (99.9%): [2.349, 3.655] (assumes normal distribution)


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.002 ms/op
Iteration   1: 3.201 ±(99.9%) 0.002 ms/op
Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.183 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.156, 3.183, 3.201), stdev = 0.023
  CI (99.9%): [2.755, 3.611] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.850 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
Iteration   2: 3.866 ±(99.9%) 0.006 ms/op
Iteration   3: 3.929 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.866, 3.913, 3.945), stdev = 0.041
  CI (99.9%): [3.156, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
Iteration   1: 3.149 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.521 ms/op
                 createUser·p0.9999: 12.990 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.120 ms/op
                 createUser·p0.9999: 18.874 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.650 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302932
  mean =      3.170 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28118 
    [ 2.500,  5.000) = 273762 
    [ 5.000,  7.500) = 686 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     21.509 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.499 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.059 ms/op
                 existUser·p0.9999: 18.923 ms/op
                 existUser·p1.00:   20.644 ms/op

Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 28.279 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319821
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49253 
    [ 2.500,  5.000) = 269615 
    [ 5.000,  7.500) = 680 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.047 ms/op
     p(99.9900) =     26.937 ms/op
     p(99.9990) =     28.797 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.977 ms/op
                 getUser·p0.9999: 14.858 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.828 ms/op
                 getUser·p0.9999: 14.059 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 30.540 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307292
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22984 
    [ 2.500,  5.000) = 283293 
    [ 5.000,  7.500) = 704 
    [ 7.500, 10.000) = 107 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.565 ms/op
     p(99.9900) =     29.476 ms/op
     p(99.9990) =     30.865 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 5.693 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.292 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.791 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   2: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.741 ms/op
                 listUser·p0.9999: 17.178 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.124 ms/op
                 listUser·p0.9999: 28.404 ms/op
                 listUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244541
  mean =      3.926 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2985 
    [ 2.500,  5.000) = 219001 
    [ 5.000,  7.500) = 21706 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.655 ms/op
     p(99.9900) =     27.168 ms/op
     p(99.9990) =     28.614 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.057 ± 0.362  ops/ms
ClientGrpc.existUser                       thrpt       3  10.553 ± 1.709  ops/ms
ClientGrpc.getUser                         thrpt       3  10.075 ± 3.067  ops/ms
ClientGrpc.listUser                        thrpt       3   7.938 ± 0.622  ops/ms
ClientGrpc.createUser                       avgt       3   3.217 ± 0.847   ms/op
ClientGrpc.existUser                        avgt       3   3.002 ± 0.653   ms/op
ClientGrpc.getUser                          avgt       3   3.183 ± 0.428   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.757   ms/op
ClientGrpc.createUser                     sample  302932   3.170 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.614           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.158           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.509           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  319821   3.001 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.802           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.047           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.937           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.836           ms/op
ClientGrpc.getUser                        sample  307292   3.123 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.645           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.565           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.476           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.999           ms/op
ClientGrpc.listUser                       sample  244541   3.926 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.655           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.168           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.705           ms/op
