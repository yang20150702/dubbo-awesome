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
# Warmup Iteration   1: 3.898 ops/ms
# Warmup Iteration   2: 8.673 ops/ms
# Warmup Iteration   3: 9.927 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.067 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.070 ±(99.9%) 5.398 ops/ms [Average]
  (min, avg, max) = (9.776, 10.070, 10.367), stdev = 0.296
  CI (99.9%): [4.672, 15.468] (assumes normal distribution)


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
# Warmup Iteration   1: 7.428 ops/ms
# Warmup Iteration   2: 10.045 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.288 ±(99.9%) 3.508 ops/ms [Average]
  (min, avg, max) = (10.069, 10.288, 10.431), stdev = 0.192
  CI (99.9%): [6.779, 13.796] (assumes normal distribution)


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
# Warmup Iteration   1: 6.114 ops/ms
# Warmup Iteration   2: 9.478 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.108 ±(99.9%) 4.370 ops/ms [Average]
  (min, avg, max) = (9.833, 10.108, 10.267), stdev = 0.240
  CI (99.9%): [5.738, 14.479] (assumes normal distribution)


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
# Warmup Iteration   1: 5.161 ops/ms
# Warmup Iteration   2: 7.461 ops/ms
# Warmup Iteration   3: 7.679 ops/ms
Iteration   1: 7.713 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.722 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (7.674, 7.722, 7.780), stdev = 0.053
  CI (99.9%): [6.748, 8.697] (assumes normal distribution)


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.002 ms/op
Iteration   1: 3.254 ±(99.9%) 0.002 ms/op
Iteration   2: 3.192 ±(99.9%) 0.003 ms/op
Iteration   3: 3.169 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.205 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.169, 3.205, 3.254), stdev = 0.044
  CI (99.9%): [2.407, 4.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.077 ±(99.9%) 0.002 ms/op
Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.035 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (2.991, 3.035, 3.077), stdev = 0.043
  CI (99.9%): [2.249, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.004 ms/op
Iteration   1: 3.182 ±(99.9%) 0.003 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.275 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.222 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.182, 3.222, 3.275), stdev = 0.048
  CI (99.9%): [2.350, 4.095] (assumes normal distribution)


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
# Warmup Iteration   1: 5.743 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.027 ms/op
Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
Iteration   2: 4.094 ±(99.9%) 0.005 ms/op
Iteration   3: 4.072 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.087 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (4.072, 4.087, 4.095), stdev = 0.013
  CI (99.9%): [3.853, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  6.734 ms/op
                 createUser·p0.9999: 20.514 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.165 ms/op
                 createUser·p0.9999: 22.414 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 25.042 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296755
  mean =      3.238 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17041 
    [ 2.500,  5.000) = 278739 
    [ 5.000,  7.500) = 619 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.057 ms/op
     p(99.9900) =     24.401 ms/op
     p(99.9990) =     25.561 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  6.630 ms/op
                 existUser·p0.9999: 13.975 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.777 ms/op
                 existUser·p0.9999: 14.974 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.428 ms/op
                 existUser·p0.9999: 18.370 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312628
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1070 
    [ 1.250,  2.500) = 38691 
    [ 2.500,  3.750) = 240167 
    [ 3.750,  5.000) = 31999 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.516 ms/op
     p(99.9900) =     16.621 ms/op
     p(99.9990) =     18.604 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  9.295 ms/op
                 getUser·p0.9999: 16.333 ms/op
                 getUser·p1.00:   16.712 ms/op

Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  8.016 ms/op
                 getUser·p0.9999: 21.985 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.189 ms/op
                 getUser·p0.999:  5.718 ms/op
                 getUser·p0.9999: 23.992 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304130
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18441 
    [ 2.500,  5.000) = 284137 
    [ 5.000,  7.500) = 1180 
    [ 7.500, 10.000) = 211 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.750 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     24.345 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 5.683 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.012 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.699 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.450 ms/op
                 listUser·p0.9999: 21.623 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.929 ms/op
                 listUser·p0.9999: 17.683 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.201 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  18.117 ms/op
                 listUser·p0.9999: 24.949 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232176
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1915 
    [ 2.500,  5.000) = 201101 
    [ 5.000,  7.500) = 27366 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     15.818 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     25.090 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.070 ± 5.398  ops/ms
ClientGrpc.existUser                       thrpt       3  10.288 ± 3.508  ops/ms
ClientGrpc.getUser                         thrpt       3  10.108 ± 4.370  ops/ms
ClientGrpc.listUser                        thrpt       3   7.722 ± 0.975  ops/ms
ClientGrpc.createUser                       avgt       3   3.205 ± 0.798   ms/op
ClientGrpc.existUser                        avgt       3   3.035 ± 0.786   ms/op
ClientGrpc.getUser                          avgt       3   3.222 ± 0.872   ms/op
ClientGrpc.listUser                         avgt       3   4.087 ± 0.235   ms/op
ClientGrpc.createUser                     sample  296755   3.238 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.650           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.116           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.057           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.401           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  312628   3.070 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.516           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.621           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  304130   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.741           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.750           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.938           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  232176   4.134 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.957           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.818           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.052           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
