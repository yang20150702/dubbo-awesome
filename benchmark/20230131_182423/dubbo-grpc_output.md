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
# Warmup Iteration   1: 4.926 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 10.250 ops/ms
Iteration   1: 10.233 ops/ms
Iteration   2: 9.926 ops/ms
Iteration   3: 10.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.059 ±(99.9%) 2.875 ops/ms [Average]
  (min, avg, max) = (9.926, 10.059, 10.233), stdev = 0.158
  CI (99.9%): [7.184, 12.933] (assumes normal distribution)


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
# Warmup Iteration   1: 8.415 ops/ms
# Warmup Iteration   2: 10.362 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.544 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (10.425, 10.544, 10.678), stdev = 0.127
  CI (99.9%): [8.219, 12.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.281 ops/ms
# Warmup Iteration   2: 9.771 ops/ms
# Warmup Iteration   3: 10.527 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 10.158 ops/ms
Iteration   3: 9.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.057 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (9.884, 10.057, 10.158), stdev = 0.151
  CI (99.9%): [7.310, 12.803] (assumes normal distribution)


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
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 7.185 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.643 ops/ms
Iteration   2: 7.572 ops/ms
Iteration   3: 7.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.685 ±(99.9%) 2.534 ops/ms [Average]
  (min, avg, max) = (7.572, 7.685, 7.840), stdev = 0.139
  CI (99.9%): [5.151, 10.219] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.002 ms/op
Iteration   1: 3.226 ±(99.9%) 0.002 ms/op
Iteration   2: 3.050 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.044, 3.106, 3.226), stdev = 0.103
  CI (99.9%): [1.220, 4.993] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
Iteration   3: 3.116 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.066 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.015, 3.066, 3.116), stdev = 0.050
  CI (99.9%): [2.150, 3.982] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.002 ms/op
Iteration   1: 3.225 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.163 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.198 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.163, 3.198, 3.225), stdev = 0.032
  CI (99.9%): [2.617, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.020 ms/op
Iteration   1: 4.022 ±(99.9%) 0.024 ms/op
Iteration   2: 4.169 ±(99.9%) 0.009 ms/op
Iteration   3: 4.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.088 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (4.022, 4.088, 4.169), stdev = 0.074
  CI (99.9%): [2.736, 5.441] (assumes normal distribution)


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
Iteration   1: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.643 ms/op
                 createUser·p0.999:  8.776 ms/op
                 createUser·p0.9999: 17.766 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   2: 3.284 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  11.712 ms/op
                 createUser·p0.9999: 19.735 ms/op
                 createUser·p1.00:   20.218 ms/op

Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 21.840 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296802
  mean =      3.235 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16512 
    [ 2.500,  5.000) = 279038 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 177 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     20.851 ms/op
     p(99.9990) =     22.551 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 12.365 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.364 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  11.197 ms/op
                 existUser·p0.9999: 15.712 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  5.816 ms/op
                 existUser·p0.9999: 18.316 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320495
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3500 
    [ 1.250,  2.500) = 36097 
    [ 2.500,  3.750) = 257232 
    [ 3.750,  5.000) = 22343 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 45 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.430 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     18.730 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 13.403 ms/op
                 getUser·p1.00:   13.713 ms/op

Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  5.743 ms/op
                 getUser·p0.9999: 16.183 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.238 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.438 ms/op
                 getUser·p0.9999: 16.901 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309610
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1545 
    [ 1.250,  2.500) = 20913 
    [ 2.500,  3.750) = 261558 
    [ 3.750,  5.000) = 24286 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 237 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.238 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     16.124 ms/op
     p(99.9990) =     17.131 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.011 ms/op
Iteration   1: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.765 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.195 ms/op
                 listUser·p0.999:  14.306 ms/op
                 listUser·p0.9999: 20.664 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 4.155 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  15.228 ms/op
                 listUser·p0.9999: 24.211 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 4.151 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.009 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 21.745 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232136
  mean =      4.137 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3063 
    [ 2.500,  5.000) = 196972 
    [ 5.000,  7.500) = 30311 
    [ 7.500, 10.000) = 1268 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.907 ms/op
     p(99.9900) =     22.926 ms/op
     p(99.9990) =     24.741 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.059 ± 2.875  ops/ms
ClientGrpc.existUser                       thrpt       3  10.544 ± 2.324  ops/ms
ClientGrpc.getUser                         thrpt       3  10.057 ± 2.747  ops/ms
ClientGrpc.listUser                        thrpt       3   7.685 ± 2.534  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 1.886   ms/op
ClientGrpc.existUser                        avgt       3   3.066 ± 0.916   ms/op
ClientGrpc.getUser                          avgt       3   3.198 ± 0.581   ms/op
ClientGrpc.listUser                         avgt       3   4.088 ± 1.352   ms/op
ClientGrpc.createUser                     sample  296802   3.235 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.207           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.765           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.851           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.741           ms/op
ClientGrpc.existUser                      sample  320495   2.995 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.364           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  309610   3.102 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.238           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.094           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.124           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.236           ms/op
ClientGrpc.listUser                       sample  232136   4.137 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.765           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.907           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.926           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
