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
# Warmup Iteration   1: 4.251 ops/ms
# Warmup Iteration   2: 9.083 ops/ms
# Warmup Iteration   3: 9.713 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 10.099 ops/ms
Iteration   3: 10.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.081 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (10.042, 10.081, 10.103), stdev = 0.034
  CI (99.9%): [9.456, 10.706] (assumes normal distribution)


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
# Warmup Iteration   1: 7.729 ops/ms
# Warmup Iteration   2: 10.487 ops/ms
# Warmup Iteration   3: 10.508 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.453 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (10.421, 10.453, 10.511), stdev = 0.050
  CI (99.9%): [9.542, 11.365] (assumes normal distribution)


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
# Warmup Iteration   1: 6.466 ops/ms
# Warmup Iteration   2: 9.749 ops/ms
# Warmup Iteration   3: 9.949 ops/ms
Iteration   1: 10.180 ops/ms
Iteration   2: 9.735 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.993 ±(99.9%) 4.207 ops/ms [Average]
  (min, avg, max) = (9.735, 9.993, 10.180), stdev = 0.231
  CI (99.9%): [5.786, 14.200] (assumes normal distribution)


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
# Warmup Iteration   1: 5.042 ops/ms
# Warmup Iteration   2: 7.519 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.829 ±(99.9%) 1.235 ops/ms [Average]
  (min, avg, max) = (7.788, 7.829, 7.907), stdev = 0.068
  CI (99.9%): [6.594, 9.064] (assumes normal distribution)


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.003 ms/op
Iteration   1: 3.214 ±(99.9%) 0.001 ms/op
Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.674 ms/op [Average]
  (min, avg, max) = (3.140, 3.176, 3.214), stdev = 0.037
  CI (99.9%): [2.502, 3.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.038 ±(99.9%) 0.652 ms/op [Average]
  (min, avg, max) = (3.002, 3.038, 3.073), stdev = 0.036
  CI (99.9%): [2.386, 3.690] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.006 ms/op
Iteration   1: 3.181 ±(99.9%) 0.003 ms/op
Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
Iteration   3: 3.182 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.165 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.133, 3.165, 3.182), stdev = 0.028
  CI (99.9%): [2.659, 3.671] (assumes normal distribution)


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
# Warmup Iteration   1: 5.619 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
Iteration   1: 4.077 ±(99.9%) 0.020 ms/op
Iteration   2: 4.184 ±(99.9%) 0.007 ms/op
Iteration   3: 4.096 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.119 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (4.077, 4.119, 4.184), stdev = 0.057
  CI (99.9%): [3.077, 5.161] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.267 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.390 ms/op
                 createUser·p0.9999: 14.851 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  8.168 ms/op
                 createUser·p0.9999: 15.051 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  10.778 ms/op
                 createUser·p0.9999: 20.981 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298241
  mean =      3.218 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20261 
    [ 2.500,  5.000) = 276327 
    [ 5.000,  7.500) = 1147 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.040 ms/op
     p(99.9900) =     20.617 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 4.021 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 14.439 ms/op
                 existUser·p1.00:   14.844 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.749 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 15.288 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 18.579 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313337
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33459 
    [ 2.500,  5.000) = 278690 
    [ 5.000,  7.500) = 822 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.886 ms/op
     p(99.9900) =     17.127 ms/op
     p(99.9990) =     20.115 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  9.310 ms/op
                 getUser·p0.9999: 15.828 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.601 ms/op
                 getUser·p0.9999: 24.598 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   3: 3.247 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.972 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 296716
  mean =      3.235 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16163 
    [ 2.500,  5.000) = 279192 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.875 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     25.201 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 4.723 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.013 ms/op
Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.477 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 17.406 ms/op
                 listUser·p1.00:   17.826 ms/op

Iteration   2: 4.027 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  19.123 ms/op
                 listUser·p0.9999: 26.712 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.974 ms/op
                 listUser·p0.999:  16.740 ms/op
                 listUser·p0.9999: 30.409 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236696
  mean =      4.051 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2161 
    [ 2.500,  5.000) = 207351 
    [ 5.000,  7.500) = 25554 
    [ 7.500, 10.000) = 1121 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     26.826 ms/op
     p(99.9990) =     30.733 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.081 ± 0.625  ops/ms
ClientGrpc.existUser                       thrpt       3  10.453 ± 0.911  ops/ms
ClientGrpc.getUser                         thrpt       3   9.993 ± 4.207  ops/ms
ClientGrpc.listUser                        thrpt       3   7.829 ± 1.235  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.674   ms/op
ClientGrpc.existUser                        avgt       3   3.038 ± 0.652   ms/op
ClientGrpc.getUser                          avgt       3   3.165 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   4.119 ± 1.042   ms/op
ClientGrpc.createUser                     sample  298241   3.218 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.609           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.040           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.617           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  313337   3.065 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.749           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.886           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.127           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  296716   3.235 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.195           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.112           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.875           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.560           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.330           ms/op
ClientGrpc.listUser                       sample  236696   4.051 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.884           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.086           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.613           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.826           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.933           ms/op
