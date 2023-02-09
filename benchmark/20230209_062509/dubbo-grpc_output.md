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
# Warmup Iteration   1: 4.952 ops/ms
# Warmup Iteration   2: 9.706 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 10.183 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.226 ±(99.9%) 0.849 ops/ms [Average]
  (min, avg, max) = (10.183, 10.226, 10.275), stdev = 0.047
  CI (99.9%): [9.378, 11.075] (assumes normal distribution)


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
# Warmup Iteration   1: 8.128 ops/ms
# Warmup Iteration   2: 10.726 ops/ms
# Warmup Iteration   3: 10.569 ops/ms
Iteration   1: 10.799 ops/ms
Iteration   2: 10.872 ops/ms
Iteration   3: 10.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.866 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (10.799, 10.866, 10.926), stdev = 0.064
  CI (99.9%): [9.702, 12.029] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ops/ms
# Warmup Iteration   2: 10.481 ops/ms
# Warmup Iteration   3: 10.552 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.104 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.347 ±(99.9%) 4.002 ops/ms [Average]
  (min, avg, max) = (10.104, 10.347, 10.530), stdev = 0.219
  CI (99.9%): [6.345, 14.349] (assumes normal distribution)


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
# Warmup Iteration   1: 6.180 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.009 ops/ms
Iteration   2: 8.309 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (8.009, 8.171, 8.309), stdev = 0.151
  CI (99.9%): [5.410, 10.932] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.009 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.188 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.114 ±(99.9%) 2.267 ms/op [Average]
  (min, avg, max) = (2.970, 3.114, 3.188), stdev = 0.124
  CI (99.9%): [0.847, 5.380] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.997 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (2.926, 2.962, 2.997), stdev = 0.036
  CI (99.9%): [2.308, 3.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.004 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.024, 3.064, 3.107), stdev = 0.041
  CI (99.9%): [2.307, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.037 ms/op
Iteration   1: 3.904 ±(99.9%) 0.021 ms/op
Iteration   2: 4.101 ±(99.9%) 0.012 ms/op
Iteration   3: 3.923 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.976 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (3.904, 3.976, 4.101), stdev = 0.109
  CI (99.9%): [1.992, 5.961] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.148 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.632 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.392 ms/op
                 createUser·p0.9999: 17.908 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.871 ms/op
                 createUser·p0.9999: 21.388 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.372 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.766 ms/op
                 createUser·p0.9999: 17.106 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312404
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23943 
    [ 2.500,  5.000) = 287446 
    [ 5.000,  7.500) = 533 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      3.058 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.516 ms/op
                 existUser·p0.9999: 11.321 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.837 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.653 ms/op
                 existUser·p0.9999: 14.675 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.649 ms/op
                 existUser·p0.9999: 15.586 ms/op
                 existUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330563
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4284 
    [ 1.250,  2.500) = 44436 
    [ 2.500,  3.750) = 266896 
    [ 3.750,  5.000) = 14217 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.434 ms/op
     p(99.9900) =     14.466 ms/op
     p(99.9990) =     16.020 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.158 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  9.318 ms/op
                 getUser·p0.9999: 17.670 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.951 ms/op
                 getUser·p0.9999: 16.461 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306459
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21982 
    [ 2.500,  5.000) = 283490 
    [ 5.000,  7.500) = 602 
    [ 7.500, 10.000) = 154 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.612 ms/op
     p(99.9900) =     19.017 ms/op
     p(99.9990) =     19.951 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 5.630 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.012 ms/op
Iteration   1: 4.065 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.908 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.089 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.036 ms/op
                 listUser·p0.9999: 24.009 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 23.327 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238017
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5391 
    [ 2.500,  5.000) = 201069 
    [ 5.000,  7.500) = 30221 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     23.219 ms/op
     p(99.9990) =     24.317 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.226 ± 0.849  ops/ms
ClientGrpc.existUser                       thrpt       3  10.866 ± 1.163  ops/ms
ClientGrpc.getUser                         thrpt       3  10.347 ± 4.002  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 2.761  ops/ms
ClientGrpc.createUser                       avgt       3   3.114 ± 2.267   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.654   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.757   ms/op
ClientGrpc.listUser                         avgt       3   3.976 ± 1.985   ms/op
ClientGrpc.createUser                     sample  312404   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.372           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.058           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.709           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.955           ms/op
ClientGrpc.existUser                      sample  330563   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.524           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.434           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.171           ms/op
ClientGrpc.getUser                        sample  306459   3.133 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.726           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.612           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.017           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.054           ms/op
ClientGrpc.listUser                       sample  238017   4.032 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.883           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.219           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.379           ms/op
