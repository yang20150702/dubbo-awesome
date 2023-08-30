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
# Warmup Iteration   1: 4.142 ops/ms
# Warmup Iteration   2: 8.957 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 10.282 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.312 ±(99.9%) 4.734 ops/ms [Average]
  (min, avg, max) = (10.069, 10.312, 10.585), stdev = 0.259
  CI (99.9%): [5.579, 15.046] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.169 ops/ms
# Warmup Iteration   2: 10.409 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 11.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.888 ±(99.9%) 2.104 ops/ms [Average]
  (min, avg, max) = (10.811, 10.888, 11.021), stdev = 0.115
  CI (99.9%): [8.784, 12.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.480 ops/ms
# Warmup Iteration   2: 9.987 ops/ms
# Warmup Iteration   3: 10.305 ops/ms
Iteration   1: 10.460 ops/ms
Iteration   2: 10.313 ops/ms
Iteration   3: 10.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.389 ±(99.9%) 1.341 ops/ms [Average]
  (min, avg, max) = (10.313, 10.389, 10.460), stdev = 0.074
  CI (99.9%): [9.048, 11.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.566 ops/ms
# Warmup Iteration   2: 7.434 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 7.664 ops/ms
Iteration   2: 7.911 ops/ms
Iteration   3: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.779 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (7.664, 7.779, 7.911), stdev = 0.124
  CI (99.9%): [5.511, 10.048] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.645 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.003 ms/op
Iteration   1: 3.112 ±(99.9%) 0.003 ms/op
Iteration   2: 3.161 ±(99.9%) 0.001 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 0.997 ms/op [Average]
  (min, avg, max) = (3.052, 3.108, 3.161), stdev = 0.055
  CI (99.9%): [2.111, 4.105] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.003 ms/op
Iteration   2: 2.903 ±(99.9%) 0.003 ms/op
Iteration   3: 2.923 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.925 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.903, 2.925, 2.951), stdev = 0.024
  CI (99.9%): [2.486, 3.364] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.364 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.005 ms/op
Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
Iteration   3: 3.073 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.203 ms/op [Average]
  (min, avg, max) = (3.073, 3.085, 3.096), stdev = 0.011
  CI (99.9%): [2.882, 3.288] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.476 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.025 ms/op
Iteration   1: 4.103 ±(99.9%) 0.025 ms/op
Iteration   2: 4.097 ±(99.9%) 0.024 ms/op
Iteration   3: 4.086 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.096 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (4.086, 4.096, 4.103), stdev = 0.009
  CI (99.9%): [3.939, 4.252] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.505 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 14.134 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  10.694 ms/op
                 createUser·p0.9999: 14.955 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.490 ms/op
                 createUser·p0.999:  8.387 ms/op
                 createUser·p0.9999: 17.393 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307388
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 525 
    [ 1.250,  2.500) = 13300 
    [ 2.500,  3.750) = 271769 
    [ 3.750,  5.000) = 19189 
    [ 5.000,  6.250) = 1443 
    [ 6.250,  7.500) = 597 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      9.690 ms/op
     p(99.9900) =     15.849 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 12.324 ms/op
                 existUser·p1.00:   12.501 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.406 ms/op
                 existUser·p0.9999: 15.254 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  11.283 ms/op
                 existUser·p0.9999: 17.072 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322331
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1058 
    [ 1.250,  2.500) = 25371 
    [ 2.500,  3.750) = 284168 
    [ 3.750,  5.000) = 9962 
    [ 5.000,  6.250) = 858 
    [ 6.250,  7.500) = 429 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     15.299 ms/op
     p(99.9990) =     17.694 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.511 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
Iteration   1: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 12.773 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   2: 3.112 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.678 ms/op
                 getUser·p0.9999: 15.539 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.717 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310200
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14501 
    [ 2.500,  5.000) = 293397 
    [ 5.000,  7.500) = 1829 
    [ 7.500, 10.000) = 244 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.002 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     27.125 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 5.749 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.271 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.011 ms/op
Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.425 ms/op
                 listUser·p0.999:  14.514 ms/op
                 listUser·p0.9999: 17.835 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 4.012 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 20.778 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.088 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.411 ms/op
                 listUser·p0.9999: 28.397 ms/op
                 listUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236126
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2461 
    [ 2.500,  5.000) = 207964 
    [ 5.000,  7.500) = 23731 
    [ 7.500, 10.000) = 1438 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     26.477 ms/op
     p(99.9990) =     33.147 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.312 ± 4.734  ops/ms
ClientGrpc.existUser                       thrpt       3  10.888 ± 2.104  ops/ms
ClientGrpc.getUser                         thrpt       3  10.389 ± 1.341  ops/ms
ClientGrpc.listUser                        thrpt       3   7.779 ± 2.268  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 0.997   ms/op
ClientGrpc.existUser                        avgt       3   2.925 ± 0.439   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.203   ms/op
ClientGrpc.listUser                         avgt       3   4.096 ± 0.157   ms/op
ClientGrpc.createUser                     sample  307388   3.122 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.690           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.849           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.760           ms/op
ClientGrpc.existUser                      sample  322331   2.978 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.299           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  310200   3.092 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.002           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.985           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.819           ms/op
ClientGrpc.listUser                       sample  236126   4.063 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.477           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.751           ms/op
