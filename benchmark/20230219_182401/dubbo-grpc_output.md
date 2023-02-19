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
# Warmup Iteration   1: 3.935 ops/ms
# Warmup Iteration   2: 9.345 ops/ms
# Warmup Iteration   3: 10.222 ops/ms
Iteration   1: 10.085 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.240 ±(99.9%) 2.618 ops/ms [Average]
  (min, avg, max) = (10.085, 10.240, 10.369), stdev = 0.144
  CI (99.9%): [7.622, 12.859] (assumes normal distribution)


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
# Warmup Iteration   1: 7.416 ops/ms
# Warmup Iteration   2: 9.947 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.611 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (10.541, 10.611, 10.656), stdev = 0.061
  CI (99.9%): [9.495, 11.727] (assumes normal distribution)


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
# Warmup Iteration   1: 6.786 ops/ms
# Warmup Iteration   2: 9.977 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.239 ±(99.9%) 0.535 ops/ms [Average]
  (min, avg, max) = (10.213, 10.239, 10.271), stdev = 0.029
  CI (99.9%): [9.704, 10.774] (assumes normal distribution)


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
# Warmup Iteration   1: 5.297 ops/ms
# Warmup Iteration   2: 7.755 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 7.832 ops/ms
Iteration   2: 7.927 ops/ms
Iteration   3: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.865 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (7.832, 7.865, 7.927), stdev = 0.053
  CI (99.9%): [6.894, 8.837] (assumes normal distribution)


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
Iteration   2: 3.173 ±(99.9%) 0.002 ms/op
Iteration   3: 3.125 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.133 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.100, 3.133, 3.173), stdev = 0.037
  CI (99.9%): [2.452, 3.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.005, 3.048, 3.108), stdev = 0.053
  CI (99.9%): [2.078, 4.018] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.002 ms/op
Iteration   1: 3.163 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.148 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.127, 3.148, 3.163), stdev = 0.019
  CI (99.9%): [2.807, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 5.141 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.008 ms/op
Iteration   1: 4.012 ±(99.9%) 0.031 ms/op
Iteration   2: 4.099 ±(99.9%) 0.014 ms/op
Iteration   3: 4.022 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.044 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (4.012, 4.044, 4.099), stdev = 0.048
  CI (99.9%): [3.177, 4.911] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.170 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.048 ms/op
                 createUser·p0.9999: 16.905 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.053 ms/op
                 createUser·p0.9999: 18.708 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.754 ms/op
                 createUser·p0.9999: 21.337 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304459
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25351 
    [ 2.500,  5.000) = 277969 
    [ 5.000,  7.500) = 739 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.610 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 14.039 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.861 ms/op
                 existUser·p0.9999: 12.674 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.817 ms/op
                 existUser·p0.9999: 17.678 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317823
  mean =      3.019 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1422 
    [ 1.250,  2.500) = 45803 
    [ 2.500,  3.750) = 239088 
    [ 3.750,  5.000) = 30610 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.686 ms/op
     p(99.9900) =     16.437 ms/op
     p(99.9990) =     17.853 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 12.346 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   2: 3.077 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.445 ms/op
                 getUser·p0.9999: 14.480 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.171 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.362 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.898 ms/op
                 getUser·p0.9999: 16.186 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307089
  mean =      3.125 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 391 
    [ 1.250,  2.500) = 20818 
    [ 2.500,  3.750) = 254096 
    [ 3.750,  5.000) = 30826 
    [ 5.000,  6.250) = 487 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.003 ms/op
     p(99.9900) =     14.624 ms/op
     p(99.9990) =     16.528 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 5.896 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
Iteration   1: 4.019 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.477 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 4.131 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.968 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   19.005 ms/op

Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.498 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234908
  mean =      4.087 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2889 
    [ 2.500,  5.000) = 200270 
    [ 5.000,  7.500) = 30421 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.192 ms/op
     p(99.9900) =     21.480 ms/op
     p(99.9990) =     22.795 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.240 ± 2.618  ops/ms
ClientGrpc.existUser                       thrpt       3  10.611 ± 1.116  ops/ms
ClientGrpc.getUser                         thrpt       3  10.239 ± 0.535  ops/ms
ClientGrpc.listUser                        thrpt       3   7.865 ± 0.971  ops/ms
ClientGrpc.createUser                       avgt       3   3.133 ± 0.681   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 0.970   ms/op
ClientGrpc.getUser                          avgt       3   3.148 ± 0.341   ms/op
ClientGrpc.listUser                         avgt       3   4.044 ± 0.867   ms/op
ClientGrpc.createUser                     sample  304459   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.598           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.610           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.890           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.561           ms/op
ClientGrpc.existUser                      sample  317823   3.019 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.615           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.686           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.437           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  307089   3.125 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.362           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.003           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.624           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.663           ms/op
ClientGrpc.listUser                       sample  234908   4.087 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.944           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.192           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.480           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.839           ms/op
