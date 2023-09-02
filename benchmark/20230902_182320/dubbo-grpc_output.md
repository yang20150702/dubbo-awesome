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
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 4.454 ops/ms
# Warmup Iteration   3: 5.986 ops/ms
Iteration   1: 6.298 ops/ms
Iteration   2: 6.173 ops/ms
Iteration   3: 6.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.241 ±(99.9%) 1.146 ops/ms [Average]
  (min, avg, max) = (6.173, 6.241, 6.298), stdev = 0.063
  CI (99.9%): [5.095, 7.387] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ops/ms
# Warmup Iteration   2: 5.982 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 6.738 ops/ms
Iteration   2: 6.572 ops/ms
Iteration   3: 6.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.719 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (6.572, 6.719, 6.846), stdev = 0.138
  CI (99.9%): [4.197, 9.241] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.796 ops/ms
# Warmup Iteration   2: 5.819 ops/ms
# Warmup Iteration   3: 6.172 ops/ms
Iteration   1: 6.244 ops/ms
Iteration   2: 6.507 ops/ms
Iteration   3: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.414 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (6.244, 6.414, 6.507), stdev = 0.147
  CI (99.9%): [3.724, 9.104] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.137 ops/ms
# Warmup Iteration   2: 4.560 ops/ms
# Warmup Iteration   3: 4.863 ops/ms
Iteration   1: 4.745 ops/ms
Iteration   2: 5.032 ops/ms
Iteration   3: 4.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.871 ±(99.9%) 2.669 ops/ms [Average]
  (min, avg, max) = (4.745, 4.871, 5.032), stdev = 0.146
  CI (99.9%): [2.202, 7.540] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.110 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.012 ms/op
Iteration   1: 5.393 ±(99.9%) 0.003 ms/op
Iteration   2: 5.319 ±(99.9%) 0.004 ms/op
Iteration   3: 5.142 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.285 ±(99.9%) 2.346 ms/op [Average]
  (min, avg, max) = (5.142, 5.285, 5.393), stdev = 0.129
  CI (99.9%): [2.938, 7.631] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.364 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.013 ms/op
Iteration   1: 5.073 ±(99.9%) 0.004 ms/op
Iteration   2: 5.129 ±(99.9%) 0.005 ms/op
Iteration   3: 5.172 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  5.125 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (5.073, 5.125, 5.172), stdev = 0.050
  CI (99.9%): [4.221, 6.029] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.324 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.302 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.830 ±(99.9%) 0.012 ms/op
Iteration   1: 5.712 ±(99.9%) 0.004 ms/op
Iteration   2: 5.603 ±(99.9%) 0.006 ms/op
Iteration   3: 5.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.595 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (5.468, 5.595, 5.712), stdev = 0.122
  CI (99.9%): [3.367, 7.822] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 12.129 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 8.181 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.888 ±(99.9%) 0.018 ms/op
Iteration   1: 6.865 ±(99.9%) 0.016 ms/op
Iteration   2: 6.914 ±(99.9%) 0.018 ms/op
Iteration   3: 7.113 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.964 ±(99.9%) 2.396 ms/op [Average]
  (min, avg, max) = (6.865, 6.964, 7.113), stdev = 0.131
  CI (99.9%): [4.568, 9.360] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 9.272 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 6.460 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.020 ms/op
Iteration   1: 5.540 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   7.987 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  15.130 ms/op
                 createUser·p0.9999: 22.665 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 5.421 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.496 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  15.253 ms/op
                 createUser·p0.9999: 21.240 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 5.628 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   7.283 ms/op
                 createUser·p0.95:   8.110 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  21.514 ms/op
                 createUser·p0.9999: 32.768 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 173618
  mean =      5.529 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1012 
    [ 2.500,  5.000) = 66261 
    [ 5.000,  7.500) = 94320 
    [ 7.500, 10.000) = 10022 
    [10.000, 12.500) = 1380 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     17.609 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     33.314 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 8.318 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.475 ±(99.9%) 0.020 ms/op
Iteration   1: 5.348 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  15.254 ms/op
                 existUser·p0.9999: 18.187 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   2: 5.355 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.742 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   10.320 ms/op
                 existUser·p0.999:  16.633 ms/op
                 existUser·p0.9999: 20.146 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 5.307 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.561 ms/op
                 existUser·p0.99:   10.052 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 37.157 ms/op
                 existUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 179826
  mean =      5.337 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1647 
    [ 2.500,  5.000) = 78675 
    [ 5.000,  7.500) = 90523 
    [ 7.500, 10.000) = 7102 
    [10.000, 12.500) = 1141 
    [12.500, 15.000) = 411 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     17.111 ms/op
     p(99.9900) =     36.505 ms/op
     p(99.9990) =     37.828 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 9.195 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 5.949 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.087 ±(99.9%) 0.017 ms/op
Iteration   1: 4.949 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   4.792 ms/op
                 getUser·p0.90:   6.480 ms/op
                 getUser·p0.95:   7.184 ms/op
                 getUser·p0.99:   9.634 ms/op
                 getUser·p0.999:  18.970 ms/op
                 getUser·p0.9999: 22.532 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 4.981 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   10.193 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 34.706 ms/op
                 getUser·p1.00:   35.193 ms/op

Iteration   3: 5.000 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.012 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  25.950 ms/op
                 getUser·p0.9999: 30.232 ms/op
                 getUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 192938
  mean =      4.977 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2692 
    [ 2.500,  5.000) = 111498 
    [ 5.000,  7.500) = 71539 
    [ 7.500, 10.000) = 5550 
    [10.000, 12.500) = 1042 
    [12.500, 15.000) = 384 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.431 ms/op
     p(95.0000) =      7.135 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     15.680 ms/op
     p(99.9900) =     33.113 ms/op
     p(99.9990) =     35.071 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 9.393 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 7.136 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.504 ±(99.9%) 0.027 ms/op
Iteration   1: 6.637 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   9.142 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.436 ms/op
                 listUser·p0.999:  21.227 ms/op
                 listUser·p0.9999: 30.724 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   2: 6.247 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.677 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 26.796 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   3: 6.354 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  26.354 ms/op
                 listUser·p0.9999: 31.716 ms/op
                 listUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 149727
  mean =      6.409 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 26996 
    [ 5.000,  7.500) = 92701 
    [ 7.500, 10.000) = 22748 
    [10.000, 12.500) = 5528 
    [12.500, 15.000) = 1110 
    [15.000, 17.500) = 270 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      8.782 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     12.742 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     30.678 ms/op
     p(99.9990) =     33.281 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.241 ± 1.146  ops/ms
ClientGrpc.existUser                       thrpt       3   6.719 ± 2.522  ops/ms
ClientGrpc.getUser                         thrpt       3   6.414 ± 2.690  ops/ms
ClientGrpc.listUser                        thrpt       3   4.871 ± 2.669  ops/ms
ClientGrpc.createUser                       avgt       3   5.285 ± 2.346   ms/op
ClientGrpc.existUser                        avgt       3   5.125 ± 0.904   ms/op
ClientGrpc.getUser                          avgt       3   5.595 ± 2.228   ms/op
ClientGrpc.listUser                         avgt       3   6.964 ± 2.396   ms/op
ClientGrpc.createUser                     sample  173618   5.529 ± 0.012   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.192           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           7.119           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           7.873           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          10.240           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          17.609           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.671           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.013           ms/op
ClientGrpc.existUser                      sample  179826   5.337 ± 0.011   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.035           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           5.136           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.99      sample          10.093           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          17.111           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          36.505           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.142           ms/op
ClientGrpc.getUser                        sample  192938   4.977 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.431           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.135           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.680           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          33.113           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.193           ms/op
ClientGrpc.listUser                       sample  149727   6.409 ± 0.016   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.505           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.782           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.945           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.987           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.678           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
