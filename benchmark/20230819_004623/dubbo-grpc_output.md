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
# Warmup Iteration   1: 4.258 ops/ms
# Warmup Iteration   2: 9.088 ops/ms
# Warmup Iteration   3: 10.122 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.565 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (10.490, 10.565, 10.658), stdev = 0.086
  CI (99.9%): [9.003, 12.128] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.548 ops/ms
# Warmup Iteration   2: 10.897 ops/ms
# Warmup Iteration   3: 10.994 ops/ms
Iteration   1: 10.947 ops/ms
Iteration   2: 11.070 ops/ms
Iteration   3: 11.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.098 ±(99.9%) 3.032 ops/ms [Average]
  (min, avg, max) = (10.947, 11.098, 11.276), stdev = 0.166
  CI (99.9%): [8.066, 14.129] (assumes normal distribution)


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
# Warmup Iteration   1: 7.686 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.584 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.638 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (10.498, 10.638, 10.784), stdev = 0.143
  CI (99.9%): [8.024, 13.251] (assumes normal distribution)


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
# Warmup Iteration   1: 5.896 ops/ms
# Warmup Iteration   2: 8.196 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.274 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.323 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (8.235, 8.323, 8.458), stdev = 0.119
  CI (99.9%): [6.146, 10.499] (assumes normal distribution)


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 2.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.002 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.970, 3.002, 3.025), stdev = 0.029
  CI (99.9%): [2.479, 3.524] (assumes normal distribution)


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.945 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.003 ms/op
Iteration   1: 2.847 ±(99.9%) 0.004 ms/op
Iteration   2: 2.936 ±(99.9%) 0.004 ms/op
Iteration   3: 2.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.912 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (2.847, 2.912, 2.953), stdev = 0.057
  CI (99.9%): [1.875, 3.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.988 ±(99.9%) 0.270 ms/op [Average]
  (min, avg, max) = (2.971, 2.988, 2.999), stdev = 0.015
  CI (99.9%): [2.718, 3.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.036 ms/op
Iteration   1: 3.951 ±(99.9%) 0.016 ms/op
Iteration   2: 3.900 ±(99.9%) 0.014 ms/op
Iteration   3: 3.907 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.919 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.900, 3.919, 3.951), stdev = 0.028
  CI (99.9%): [3.417, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  10.487 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.979 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.385 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.669 ms/op
                 createUser·p0.999:  10.916 ms/op
                 createUser·p0.9999: 21.135 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316048
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21374 
    [ 2.500,  5.000) = 292478 
    [ 5.000,  7.500) = 1573 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     10.632 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     21.458 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
Iteration   1: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.456 ms/op
                 existUser·p0.9999: 18.404 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.362 ms/op
                 existUser·p0.9999: 14.582 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.491 ms/op
                 existUser·p0.9999: 16.240 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332553
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41511 
    [ 2.500,  5.000) = 289450 
    [ 5.000,  7.500) = 1319 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =     16.716 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.159 ms/op
                 getUser·p0.9999: 13.236 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.326 ms/op
                 getUser·p0.9999: 18.753 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317914
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1491 
    [ 1.250,  2.500) = 25203 
    [ 2.500,  3.750) = 274271 
    [ 3.750,  5.000) = 15006 
    [ 5.000,  6.250) = 1171 
    [ 6.250,  7.500) = 455 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.491 ms/op
     p(99.9900) =     16.551 ms/op
     p(99.9990) =     19.131 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.010 ms/op
Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.101 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 23.882 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.835 ms/op
                 listUser·p0.9999: 24.849 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.235 ms/op
                 listUser·p0.999:  16.229 ms/op
                 listUser·p0.9999: 19.354 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245853
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4799 
    [ 2.500,  5.000) = 217444 
    [ 5.000,  7.500) = 21928 
    [ 7.500, 10.000) = 1150 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     23.967 ms/op
     p(99.9990) =     25.902 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.565 ± 1.563  ops/ms
ClientGrpc.existUser                       thrpt       3  11.098 ± 3.032  ops/ms
ClientGrpc.getUser                         thrpt       3  10.638 ± 2.614  ops/ms
ClientGrpc.listUser                        thrpt       3   8.323 ± 2.176  ops/ms
ClientGrpc.createUser                       avgt       3   3.002 ± 0.522   ms/op
ClientGrpc.existUser                        avgt       3   2.912 ± 1.037   ms/op
ClientGrpc.getUser                          avgt       3   2.988 ± 0.270   ms/op
ClientGrpc.listUser                         avgt       3   3.919 ± 0.502   ms/op
ClientGrpc.createUser                     sample  316048   3.037 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.385           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.632           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.070           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  332553   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.503           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.324           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.716           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.087           ms/op
ClientGrpc.getUser                        sample  317914   3.018 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.491           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.551           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  245853   3.905 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.697           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.967           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
