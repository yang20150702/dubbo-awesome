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
# Warmup Iteration   1: 3.411 ops/ms
# Warmup Iteration   2: 7.789 ops/ms
# Warmup Iteration   3: 9.708 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 10.122 ops/ms
Iteration   3: 10.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.063 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (9.922, 10.063, 10.144), stdev = 0.122
  CI (99.9%): [7.833, 12.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.116 ops/ms
# Warmup Iteration   2: 10.097 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.905 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.745 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (10.648, 10.745, 10.905), stdev = 0.139
  CI (99.9%): [8.206, 13.284] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.874 ops/ms
# Warmup Iteration   2: 9.675 ops/ms
# Warmup Iteration   3: 10.062 ops/ms
Iteration   1: 10.017 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.161 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (10.017, 10.161, 10.290), stdev = 0.137
  CI (99.9%): [7.657, 12.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.529 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 7.885 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.975 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (7.885, 7.975, 8.060), stdev = 0.088
  CI (99.9%): [6.378, 9.572] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.302 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.004 ms/op
Iteration   1: 3.091 ±(99.9%) 0.003 ms/op
Iteration   2: 3.164 ±(99.9%) 0.003 ms/op
Iteration   3: 3.113 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.091, 3.123, 3.164), stdev = 0.037
  CI (99.9%): [2.441, 3.804] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 2.945 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.983 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (2.945, 2.983, 3.007), stdev = 0.034
  CI (99.9%): [2.368, 3.599] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.001 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.101, 3.142, 3.182), stdev = 0.041
  CI (99.9%): [2.401, 3.884] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.945 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.023 ms/op
Iteration   1: 4.010 ±(99.9%) 0.014 ms/op
Iteration   2: 3.905 ±(99.9%) 0.014 ms/op
Iteration   3: 4.005 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.905, 3.974, 4.010), stdev = 0.059
  CI (99.9%): [2.890, 5.057] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.258 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.007 ms/op
Iteration   1: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  14.526 ms/op
                 createUser·p0.9999: 24.406 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  6.832 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 21.136 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302656
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10685 
    [ 2.500,  5.000) = 289912 
    [ 5.000,  7.500) = 1365 
    [ 7.500, 10.000) = 289 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     14.342 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.453 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.254 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.444 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.629 ms/op
                 existUser·p0.9999: 22.726 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  12.647 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  9.076 ms/op
                 existUser·p0.9999: 17.377 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317446
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25376 
    [ 2.500,  5.000) = 290275 
    [ 5.000,  7.500) = 1221 
    [ 7.500, 10.000) = 267 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.444 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     23.549 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.006 ms/op
Iteration   1: 3.274 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  12.304 ms/op
                 getUser·p0.9999: 15.470 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.602 ms/op
                 getUser·p0.999:  9.735 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  10.473 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299965
  mean =      3.198 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7843 
    [ 2.500,  5.000) = 289864 
    [ 5.000,  7.500) = 1615 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.256 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.010 ms/op
Iteration   1: 4.171 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  13.554 ms/op
                 listUser·p0.9999: 18.557 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 4.091 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 26.751 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.537 ms/op
                 listUser·p0.9999: 19.696 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234596
  mean =      4.091 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1330 
    [ 2.500,  5.000) = 215390 
    [ 5.000,  7.500) = 16257 
    [ 7.500, 10.000) = 996 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.145 ms/op
     p(99.9900) =     20.962 ms/op
     p(99.9990) =     27.131 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.063 ± 2.230  ops/ms
ClientGrpc.existUser                       thrpt       3  10.745 ± 2.539  ops/ms
ClientGrpc.getUser                         thrpt       3  10.161 ± 2.503  ops/ms
ClientGrpc.listUser                        thrpt       3   7.975 ± 1.597  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.682   ms/op
ClientGrpc.existUser                        avgt       3   2.983 ± 0.616   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.742   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 1.083   ms/op
ClientGrpc.createUser                     sample  302656   3.171 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.712           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.957           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.342           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.939           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  317446   3.022 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.444           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.790           ms/op
ClientGrpc.getUser                        sample  299965   3.198 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.780           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.265           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.591           ms/op
ClientGrpc.listUser                       sample  234596   4.091 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.025           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.977           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.145           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.962           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.262           ms/op
