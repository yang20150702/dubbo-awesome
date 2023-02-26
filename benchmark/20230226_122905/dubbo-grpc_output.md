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
# Warmup Iteration   1: 4.067 ops/ms
# Warmup Iteration   2: 8.416 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 9.935 ops/ms
Iteration   2: 10.098 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.023 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (9.935, 10.023, 10.098), stdev = 0.082
  CI (99.9%): [8.525, 11.520] (assumes normal distribution)


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
# Warmup Iteration   1: 7.442 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.867 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.566 ±(99.9%) 4.801 ops/ms [Average]
  (min, avg, max) = (10.381, 10.566, 10.867), stdev = 0.263
  CI (99.9%): [5.765, 15.367] (assumes normal distribution)


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
# Warmup Iteration   1: 6.656 ops/ms
# Warmup Iteration   2: 9.576 ops/ms
# Warmup Iteration   3: 9.773 ops/ms
Iteration   1: 10.054 ops/ms
Iteration   2: 10.016 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.999 ±(99.9%) 1.183 ops/ms [Average]
  (min, avg, max) = (9.927, 9.999, 10.054), stdev = 0.065
  CI (99.9%): [8.816, 11.182] (assumes normal distribution)


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
# Warmup Iteration   1: 5.490 ops/ms
# Warmup Iteration   2: 7.525 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.762 ops/ms
Iteration   2: 7.702 ops/ms
Iteration   3: 7.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.816 ±(99.9%) 2.707 ops/ms [Average]
  (min, avg, max) = (7.702, 7.816, 7.984), stdev = 0.148
  CI (99.9%): [5.109, 10.523] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.234 ±(99.9%) 0.001 ms/op
Iteration   3: 3.193 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.208 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (3.193, 3.208, 3.234), stdev = 0.023
  CI (99.9%): [2.791, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.002 ms/op
Iteration   1: 3.094 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.018 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.121 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.094, 3.121, 3.142), stdev = 0.025
  CI (99.9%): [2.670, 3.572] (assumes normal distribution)


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.002 ms/op
Iteration   1: 3.243 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.174 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.110, 3.174, 3.243), stdev = 0.066
  CI (99.9%): [1.961, 4.387] (assumes normal distribution)


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
# Warmup Iteration   1: 5.866 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.021 ms/op
Iteration   1: 4.022 ±(99.9%) 0.007 ms/op
Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
Iteration   3: 3.919 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (3.919, 3.983, 4.022), stdev = 0.056
  CI (99.9%): [2.964, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  10.164 ms/op
                 createUser·p0.9999: 13.908 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  7.905 ms/op
                 createUser·p0.9999: 15.359 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 20.026 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299526
  mean =      3.206 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24239 
    [ 2.500,  5.000) = 271791 
    [ 5.000,  7.500) = 2691 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     10.534 ms/op
     p(99.9900) =     19.335 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  7.578 ms/op
                 existUser·p0.9999: 12.981 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.134 ms/op
                 existUser·p0.999:  8.731 ms/op
                 existUser·p0.9999: 14.785 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  9.405 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312493
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 775 
    [ 1.250,  2.500) = 34777 
    [ 2.500,  3.750) = 246963 
    [ 3.750,  5.000) = 27480 
    [ 5.000,  6.250) = 1405 
    [ 6.250,  7.500) = 608 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.067 ms/op
                 getUser·p0.999:  10.136 ms/op
                 getUser·p0.9999: 15.387 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.587 ms/op
                 getUser·p0.999:  7.751 ms/op
                 getUser·p0.9999: 16.706 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  10.389 ms/op
                 getUser·p0.9999: 18.190 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300996
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 303 
    [ 1.250,  2.500) = 18098 
    [ 2.500,  3.750) = 245385 
    [ 3.750,  5.000) = 34539 
    [ 5.000,  6.250) = 1373 
    [ 6.250,  7.500) = 614 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     17.102 ms/op
     p(99.9990) =     18.546 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.343 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
Iteration   1: 4.126 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.680 ms/op
                 listUser·p0.999:  14.731 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 4.089 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  22.540 ms/op
                 listUser·p0.9999: 26.784 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  20.776 ms/op
                 listUser·p0.9999: 26.729 ms/op
                 listUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236744
  mean =      4.053 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2466 
    [ 2.500,  5.000) = 206147 
    [ 5.000,  7.500) = 26182 
    [ 7.500, 10.000) = 1368 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     26.563 ms/op
     p(99.9990) =     27.555 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.023 ± 1.498  ops/ms
ClientGrpc.existUser                       thrpt       3  10.566 ± 4.801  ops/ms
ClientGrpc.getUser                         thrpt       3   9.999 ± 1.183  ops/ms
ClientGrpc.listUser                        thrpt       3   7.816 ± 2.707  ops/ms
ClientGrpc.createUser                       avgt       3   3.208 ± 0.417   ms/op
ClientGrpc.existUser                        avgt       3   3.121 ± 0.451   ms/op
ClientGrpc.getUser                          avgt       3   3.174 ± 1.213   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 1.019   ms/op
ClientGrpc.createUser                     sample  299526   3.206 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.699           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.154           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.335           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  312493   3.072 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.690           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.957           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.760           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.667           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.203           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  300996   3.190 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.490           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.142           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.102           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  236744   4.053 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.011           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.612           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.563           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.245           ms/op
