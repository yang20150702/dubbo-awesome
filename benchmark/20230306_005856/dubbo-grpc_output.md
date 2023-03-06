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
# Warmup Iteration   1: 3.847 ops/ms
# Warmup Iteration   2: 8.667 ops/ms
# Warmup Iteration   3: 9.842 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.959 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (9.805, 9.959, 10.053), stdev = 0.134
  CI (99.9%): [7.508, 12.410] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.073 ops/ms
# Warmup Iteration   2: 9.860 ops/ms
# Warmup Iteration   3: 10.284 ops/ms
Iteration   1: 10.100 ops/ms
Iteration   2: 10.297 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.195 ±(99.9%) 1.801 ops/ms [Average]
  (min, avg, max) = (10.100, 10.195, 10.297), stdev = 0.099
  CI (99.9%): [8.394, 11.995] (assumes normal distribution)


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
# Warmup Iteration   1: 6.782 ops/ms
# Warmup Iteration   2: 9.689 ops/ms
# Warmup Iteration   3: 9.839 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.079 ops/ms
Iteration   3: 10.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.006 ±(99.9%) 1.421 ops/ms [Average]
  (min, avg, max) = (9.924, 10.006, 10.079), stdev = 0.078
  CI (99.9%): [8.585, 11.427] (assumes normal distribution)


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
# Warmup Iteration   1: 5.770 ops/ms
# Warmup Iteration   2: 7.590 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 8.024 ops/ms
Iteration   2: 7.950 ops/ms
Iteration   3: 8.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (7.950, 8.010, 8.057), stdev = 0.055
  CI (99.9%): [7.006, 9.014] (assumes normal distribution)


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.008 ms/op
Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.130 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.068, 3.130, 3.168), stdev = 0.054
  CI (99.9%): [2.141, 4.120] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.057 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.038, 3.057, 3.076), stdev = 0.019
  CI (99.9%): [2.713, 3.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.003 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.144 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.108, 3.144, 3.171), stdev = 0.033
  CI (99.9%): [2.549, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 5.754 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.152 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.009 ms/op
Iteration   1: 4.061 ±(99.9%) 0.007 ms/op
Iteration   2: 4.043 ±(99.9%) 0.014 ms/op
Iteration   3: 4.031 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.045 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (4.031, 4.045, 4.061), stdev = 0.015
  CI (99.9%): [3.767, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.034 ms/op
                 createUser·p0.9999: 17.494 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.103 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.193 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  11.236 ms/op
                 createUser·p0.9999: 28.310 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302173
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23267 
    [ 2.500,  5.000) = 277962 
    [ 5.000,  7.500) = 656 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.289 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     29.097 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 17.223 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.040 ms/op
                 existUser·p0.9999: 14.393 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  8.185 ms/op
                 existUser·p0.9999: 16.920 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312180
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 583 
    [ 1.250,  2.500) = 36488 
    [ 2.500,  3.750) = 243069 
    [ 3.750,  5.000) = 31175 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.027 ms/op
     p(99.9900) =     17.065 ms/op
     p(99.9990) =     17.330 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.691 ms/op
                 getUser·p0.9999: 15.126 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.750 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.662 ms/op

Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.528 ms/op
                 getUser·p0.9999: 17.468 ms/op
                 getUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299909
  mean =      3.202 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 17826 
    [ 2.500,  3.750) = 239794 
    [ 3.750,  5.000) = 40867 
    [ 5.000,  6.250) = 447 
    [ 6.250,  7.500) = 388 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 84 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.252 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
Iteration   1: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.038 ms/op
                 listUser·p0.999:  13.899 ms/op
                 listUser·p0.9999: 15.993 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.956 ms/op
                 listUser·p0.9999: 19.244 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.821 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235904
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1848 
    [ 2.500,  5.000) = 205009 
    [ 5.000,  7.500) = 27583 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.304 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.810 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.959 ± 2.451  ops/ms
ClientGrpc.existUser                       thrpt       3  10.195 ± 1.801  ops/ms
ClientGrpc.getUser                         thrpt       3  10.006 ± 1.421  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 1.004  ops/ms
ClientGrpc.createUser                       avgt       3   3.130 ± 0.989   ms/op
ClientGrpc.existUser                        avgt       3   3.057 ± 0.344   ms/op
ClientGrpc.getUser                          avgt       3   3.144 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   4.045 ± 0.278   ms/op
ClientGrpc.createUser                     sample  302173   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.708           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.164           ms/op
ClientGrpc.existUser                      sample  312180   3.075 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.609           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.027           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.065           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  299909   3.202 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.732           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.334           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  235904   4.068 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.304           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.560           ms/op
