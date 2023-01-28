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
# Warmup Iteration   1: 4.785 ops/ms
# Warmup Iteration   2: 8.905 ops/ms
# Warmup Iteration   3: 10.296 ops/ms
Iteration   1: 10.392 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 10.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.417 ±(99.9%) 4.157 ops/ms [Average]
  (min, avg, max) = (10.203, 10.417, 10.657), stdev = 0.228
  CI (99.9%): [6.260, 14.574] (assumes normal distribution)


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
# Warmup Iteration   1: 7.745 ops/ms
# Warmup Iteration   2: 10.638 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 10.697 ops/ms
Iteration   2: 10.552 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.625 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (10.552, 10.625, 10.697), stdev = 0.072
  CI (99.9%): [9.304, 11.946] (assumes normal distribution)


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
# Warmup Iteration   1: 7.638 ops/ms
# Warmup Iteration   2: 10.297 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.295 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 9.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.186 ±(99.9%) 3.427 ops/ms [Average]
  (min, avg, max) = (9.969, 10.186, 10.295), stdev = 0.188
  CI (99.9%): [6.758, 13.613] (assumes normal distribution)


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
# Warmup Iteration   1: 5.304 ops/ms
# Warmup Iteration   2: 7.499 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 7.611 ops/ms
Iteration   2: 7.634 ops/ms
Iteration   3: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.634 ±(99.9%) 0.436 ops/ms [Average]
  (min, avg, max) = (7.611, 7.634, 7.658), stdev = 0.024
  CI (99.9%): [7.199, 8.070] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.104, 3.154, 3.181), stdev = 0.043
  CI (99.9%): [2.362, 3.946] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.003 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.002 ms/op
Iteration   3: 2.975 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (2.975, 3.011, 3.032), stdev = 0.031
  CI (99.9%): [2.436, 3.585] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.179 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.120, 3.179, 3.224), stdev = 0.053
  CI (99.9%): [2.205, 4.152] (assumes normal distribution)


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.017 ms/op
Iteration   1: 4.146 ±(99.9%) 0.019 ms/op
Iteration   2: 4.004 ±(99.9%) 0.020 ms/op
Iteration   3: 4.165 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.105 ±(99.9%) 1.606 ms/op [Average]
  (min, avg, max) = (4.004, 4.105, 4.165), stdev = 0.088
  CI (99.9%): [2.499, 5.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.195 ms/op
                 createUser·p0.9999: 12.317 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.322 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  5.673 ms/op
                 createUser·p0.9999: 12.123 ms/op
                 createUser·p1.00:   12.403 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 16.007 ms/op
                 createUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307028
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1424 
    [ 1.250,  2.500) = 19002 
    [ 2.500,  3.750) = 253296 
    [ 3.750,  5.000) = 32467 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     16.086 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 11.239 ms/op
                 existUser·p1.00:   11.518 ms/op

Iteration   2: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  9.448 ms/op
                 existUser·p0.9999: 12.961 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  5.806 ms/op
                 existUser·p0.9999: 15.630 ms/op
                 existUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324950
  mean =      2.955 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4252 
    [ 1.250,  2.500) = 41633 
    [ 2.500,  3.750) = 260841 
    [ 3.750,  5.000) = 17445 
    [ 5.000,  6.250) = 445 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      6.308 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     16.052 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.136 ms/op
                 getUser·p0.9999: 12.132 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 3.169 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 13.122 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.104 ms/op
                 getUser·p0.9999: 14.480 ms/op
                 getUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304457
  mean =      3.153 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 763 
    [ 1.250,  2.500) = 15651 
    [ 2.500,  3.750) = 255474 
    [ 3.750,  5.000) = 31484 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.070 ms/op
     p(99.9900) =     13.788 ms/op
     p(99.9990) =     14.761 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.487 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.285 ms/op
                 listUser·p0.9999: 15.140 ms/op
                 listUser·p1.00:   15.417 ms/op

Iteration   2: 4.033 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.299 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.080 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.503 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 29.262 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237405
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3695 
    [ 2.500,  5.000) = 199730 
    [ 5.000,  7.500) = 32746 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.001 ms/op
     p(99.9900) =     26.747 ms/op
     p(99.9990) =     29.487 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.417 ± 4.157  ops/ms
ClientGrpc.existUser                       thrpt       3  10.625 ± 1.321  ops/ms
ClientGrpc.getUser                         thrpt       3  10.186 ± 3.427  ops/ms
ClientGrpc.listUser                        thrpt       3   7.634 ± 0.436  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 0.792   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.574   ms/op
ClientGrpc.getUser                          avgt       3   3.179 ± 0.974   ms/op
ClientGrpc.listUser                         avgt       3   4.105 ± 1.606   ms/op
ClientGrpc.createUser                     sample  307028   3.126 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.322           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.958           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.286           ms/op
ClientGrpc.existUser                      sample  324950   2.955 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.308           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.105           ms/op
ClientGrpc.getUser                        sample  304457   3.153 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.541           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.070           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.788           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.860           ms/op
ClientGrpc.listUser                       sample  237405   4.043 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.503           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.001           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.747           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.524           ms/op
