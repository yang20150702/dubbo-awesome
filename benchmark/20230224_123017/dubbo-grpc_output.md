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
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 9.385 ops/ms
# Warmup Iteration   3: 10.157 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.383 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.257, 10.383, 10.472), stdev = 0.112
  CI (99.9%): [8.335, 12.432] (assumes normal distribution)


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
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 10.770 ops/ms
# Warmup Iteration   3: 10.754 ops/ms
Iteration   1: 10.917 ops/ms
Iteration   2: 11.163 ops/ms
Iteration   3: 10.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.978 ±(99.9%) 2.979 ops/ms [Average]
  (min, avg, max) = (10.854, 10.978, 11.163), stdev = 0.163
  CI (99.9%): [7.999, 13.957] (assumes normal distribution)


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
# Warmup Iteration   1: 8.078 ops/ms
# Warmup Iteration   2: 10.193 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.297 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 10.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.418 ±(99.9%) 3.007 ops/ms [Average]
  (min, avg, max) = (10.297, 10.418, 10.605), stdev = 0.165
  CI (99.9%): [7.411, 13.425] (assumes normal distribution)


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
# Warmup Iteration   1: 6.705 ops/ms
# Warmup Iteration   2: 7.754 ops/ms
# Warmup Iteration   3: 7.963 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 8.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.134 ±(99.9%) 3.009 ops/ms [Average]
  (min, avg, max) = (7.966, 8.134, 8.296), stdev = 0.165
  CI (99.9%): [5.125, 11.143] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.136 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (3.077, 3.105, 3.136), stdev = 0.029
  CI (99.9%): [2.567, 3.643] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.853 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (2.853, 2.931, 3.001), stdev = 0.074
  CI (99.9%): [1.575, 4.287] (assumes normal distribution)


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.002 ms/op
Iteration   2: 3.107 ±(99.9%) 0.003 ms/op
Iteration   3: 3.073 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.032, 3.071, 3.107), stdev = 0.038
  CI (99.9%): [2.384, 3.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.007 ms/op
Iteration   1: 4.029 ±(99.9%) 0.028 ms/op
Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
Iteration   3: 3.934 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.001 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.934, 4.001, 4.041), stdev = 0.059
  CI (99.9%): [2.928, 5.075] (assumes normal distribution)


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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.435 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.646 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.873 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.049 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313332
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30769 
    [ 2.500,  5.000) = 281610 
    [ 5.000,  7.500) = 596 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.954 ms/op
     p(99.9900) =     22.501 ms/op
     p(99.9990) =     24.342 ms/op
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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.916 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.322 ms/op
                 existUser·p0.9999: 13.349 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.861 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.096 ms/op
                 existUser·p0.9999: 15.414 ms/op
                 existUser·p1.00:   15.614 ms/op

Iteration   3: 2.840 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.355 ms/op
                 existUser·p0.9999: 14.908 ms/op
                 existUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335762
  mean =      2.859 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4431 
    [ 1.250,  2.500) = 55166 
    [ 2.500,  3.750) = 261960 
    [ 3.750,  5.000) = 13401 
    [ 5.000,  6.250) = 410 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.597 ms/op
     p(99.9900) =     15.218 ms/op
     p(99.9990) =     15.586 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 11.099 ms/op
                 getUser·p1.00:   11.272 ms/op

Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.881 ms/op
                 getUser·p0.9999: 12.489 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  5.266 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313393
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27936 
    [ 2.500,  5.000) = 284631 
    [ 5.000,  7.500) = 542 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.279 ms/op
                 listUser·p0.9999: 19.818 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  18.429 ms/op
                 listUser·p0.9999: 24.614 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240261
  mean =      3.997 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3921 
    [ 2.500,  5.000) = 209596 
    [ 5.000,  7.500) = 25589 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     16.228 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.048 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.383 ± 2.049  ops/ms
ClientGrpc.existUser                       thrpt       3  10.978 ± 2.979  ops/ms
ClientGrpc.getUser                         thrpt       3  10.418 ± 3.007  ops/ms
ClientGrpc.listUser                        thrpt       3   8.134 ± 3.009  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.538   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 1.356   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.687   ms/op
ClientGrpc.listUser                         avgt       3   4.001 ± 1.074   ms/op
ClientGrpc.createUser                     sample  313332   3.061 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.435           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.954           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.501           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  335762   2.859 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.597           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.218           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.614           ms/op
ClientGrpc.getUser                        sample  313393   3.062 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.570           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  240261   3.997 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.697           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.228           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.298           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
