# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.858 ops/ms
# Warmup Iteration   2: 4.558 ops/ms
# Warmup Iteration   3: 6.274 ops/ms
Iteration   1: 6.687 ops/ms
Iteration   2: 7.233 ops/ms
Iteration   3: 7.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.994 ±(99.9%) 5.089 ops/ms [Average]
  (min, avg, max) = (6.687, 6.994, 7.233), stdev = 0.279
  CI (99.9%): [1.905, 12.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.016 ops/ms
# Warmup Iteration   2: 6.755 ops/ms
# Warmup Iteration   3: 7.120 ops/ms
Iteration   1: 7.229 ops/ms
Iteration   2: 7.325 ops/ms
Iteration   3: 7.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.331 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (7.229, 7.331, 7.437), stdev = 0.104
  CI (99.9%): [5.431, 9.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 6.417 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 6.918 ops/ms
Iteration   2: 7.165 ops/ms
Iteration   3: 6.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.025 ±(99.9%) 2.312 ops/ms [Average]
  (min, avg, max) = (6.918, 7.025, 7.165), stdev = 0.127
  CI (99.9%): [4.712, 9.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 5.239 ops/ms
Iteration   1: 5.523 ops/ms
Iteration   2: 5.726 ops/ms
Iteration   3: 5.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.617 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (5.523, 5.617, 5.726), stdev = 0.102
  CI (99.9%): [3.750, 7.484] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.722 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.537 ±(99.9%) 0.013 ms/op
Iteration   1: 4.466 ±(99.9%) 0.003 ms/op
Iteration   2: 4.564 ±(99.9%) 0.004 ms/op
Iteration   3: 4.395 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.475 ±(99.9%) 1.544 ms/op [Average]
  (min, avg, max) = (4.395, 4.475, 4.564), stdev = 0.085
  CI (99.9%): [2.931, 6.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.421 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.006 ms/op
Iteration   1: 4.251 ±(99.9%) 0.005 ms/op
Iteration   2: 4.177 ±(99.9%) 0.003 ms/op
Iteration   3: 4.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.145 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (4.009, 4.145, 4.251), stdev = 0.124
  CI (99.9%): [1.882, 6.409] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.004 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.954 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.003 ms/op
Iteration   1: 4.587 ±(99.9%) 0.005 ms/op
Iteration   2: 4.671 ±(99.9%) 0.004 ms/op
Iteration   3: 4.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.599 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (4.540, 4.599, 4.671), stdev = 0.066
  CI (99.9%): [3.392, 5.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.159 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.010 ms/op
Iteration   1: 6.032 ±(99.9%) 0.015 ms/op
Iteration   2: 5.781 ±(99.9%) 0.016 ms/op
Iteration   3: 5.971 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.928 ±(99.9%) 2.381 ms/op [Average]
  (min, avg, max) = (5.781, 5.928, 6.032), stdev = 0.131
  CI (99.9%): [3.547, 8.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.414 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 5.135 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.698 ±(99.9%) 0.017 ms/op
Iteration   1: 4.509 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.290 ms/op
                 createUser·p0.999:  13.418 ms/op
                 createUser·p0.9999: 26.912 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.522 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   4.366 ms/op
                 createUser·p0.90:   5.734 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  17.475 ms/op
                 createUser·p0.9999: 43.179 ms/op
                 createUser·p1.00:   43.844 ms/op

Iteration   3: 4.413 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   7.985 ms/op
                 createUser·p0.999:  12.002 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214151
  mean =      4.480 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 166056 
    [ 5.000, 10.000) = 47322 
    [10.000, 15.000) = 635 
    [15.000, 20.000) = 10 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     42.309 ms/op
     p(99.9990) =     43.759 ms/op
     p(99.9999) =     43.844 ms/op
    p(100.0000) =     43.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.978 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.605 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.015 ms/op
Iteration   1: 4.640 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 17.924 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 4.617 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   4.268 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.733 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  13.795 ms/op
                 existUser·p0.9999: 25.105 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 4.398 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.250 ms/op
                 existUser·p0.99:   8.530 ms/op
                 existUser·p0.999:  18.195 ms/op
                 existUser·p0.9999: 21.517 ms/op
                 existUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 210944
  mean =      4.549 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6097 
    [ 2.500,  5.000) = 151093 
    [ 5.000,  7.500) = 45681 
    [ 7.500, 10.000) = 6282 
    [10.000, 12.500) = 1354 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     13.845 ms/op
     p(99.9900) =     22.273 ms/op
     p(99.9990) =     25.581 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.889 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.014 ms/op
Iteration   1: 4.369 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   4.178 ms/op
                 getUser·p0.90:   5.677 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  13.301 ms/op
                 getUser·p0.9999: 16.047 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   2: 4.548 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   4.350 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.701 ms/op
                 getUser·p0.99:   9.060 ms/op
                 getUser·p0.999:  13.347 ms/op
                 getUser·p0.9999: 27.491 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 4.528 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.882 ms/op
                 getUser·p0.95:   6.586 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  13.079 ms/op
                 getUser·p0.9999: 25.587 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 214351
  mean =      4.480 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6469 
    [ 2.500,  5.000) = 158125 
    [ 5.000,  7.500) = 44442 
    [ 7.500, 10.000) = 4331 
    [10.000, 12.500) = 662 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     26.677 ms/op
     p(99.9990) =     27.586 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.411 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 6.587 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.030 ±(99.9%) 0.024 ms/op
Iteration   1: 5.959 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   8.176 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  18.273 ms/op
                 listUser·p0.9999: 21.025 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 5.996 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   8.257 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 32.026 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   3: 5.892 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.015 ms/op
                 listUser·p0.999:  24.189 ms/op
                 listUser·p0.9999: 25.774 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161260
  mean =      5.949 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 46074 
    [ 5.000,  7.500) = 92464 
    [ 7.500, 10.000) = 17527 
    [10.000, 12.500) = 3741 
    [12.500, 15.000) = 699 
    [15.000, 17.500) = 268 
    [17.500, 20.000) = 197 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      8.061 ms/op
     p(95.0000) =      9.208 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     30.114 ms/op
     p(99.9990) =     32.831 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.994 ± 5.089  ops/ms
ClientGrpc.existUser                       thrpt       3   7.331 ± 1.900  ops/ms
ClientGrpc.getUser                         thrpt       3   7.025 ± 2.312  ops/ms
ClientGrpc.listUser                        thrpt       3   5.617 ± 1.867  ops/ms
ClientGrpc.createUser                       avgt       3   4.475 ± 1.544   ms/op
ClientGrpc.existUser                        avgt       3   4.145 ± 2.263   ms/op
ClientGrpc.getUser                          avgt       3   4.599 ± 1.207   ms/op
ClientGrpc.listUser                         avgt       3   5.928 ± 2.381   ms/op
ClientGrpc.createUser                     sample  214151   4.480 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.914           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.185           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.266           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.353           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          42.309           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          43.844           ms/op
ClientGrpc.existUser                      sample  210944   4.549 ± 0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.775           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.021           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.053           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.683           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.845           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.273           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.690           ms/op
ClientGrpc.getUser                        sample  214351   4.480 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.985           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.798           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.189           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.677           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  161260   5.949 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.563           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.061           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.208           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.124           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.677           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.114           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.932           ms/op
