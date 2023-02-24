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
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 7.828 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.175 ±(99.9%) 7.036 ops/ms [Average]
  (min, avg, max) = (7.731, 8.175, 8.433), stdev = 0.386
  CI (99.9%): [1.138, 15.211] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.237 ops/ms
# Warmup Iteration   2: 7.701 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.374 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.281 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (8.167, 8.281, 8.374), stdev = 0.105
  CI (99.9%): [6.366, 10.196] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ops/ms
# Warmup Iteration   2: 7.486 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 7.675 ops/ms
Iteration   2: 7.646 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.658 ±(99.9%) 0.280 ops/ms [Average]
  (min, avg, max) = (7.646, 7.658, 7.675), stdev = 0.015
  CI (99.9%): [7.379, 7.938] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.382 ops/ms
# Warmup Iteration   2: 6.208 ops/ms
# Warmup Iteration   3: 6.437 ops/ms
Iteration   1: 6.434 ops/ms
Iteration   2: 6.434 ops/ms
Iteration   3: 6.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.418 ±(99.9%) 0.511 ops/ms [Average]
  (min, avg, max) = (6.385, 6.418, 6.434), stdev = 0.028
  CI (99.9%): [5.906, 6.929] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.002 ms/op
Iteration   1: 4.210 ±(99.9%) 0.003 ms/op
Iteration   2: 3.937 ±(99.9%) 0.002 ms/op
Iteration   3: 4.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.082 ±(99.9%) 2.509 ms/op [Average]
  (min, avg, max) = (3.937, 4.082, 4.210), stdev = 0.138
  CI (99.9%): [1.573, 6.592] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.171 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.002 ms/op
Iteration   1: 3.884 ±(99.9%) 0.003 ms/op
Iteration   2: 3.896 ±(99.9%) 0.002 ms/op
Iteration   3: 3.765 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.848 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.765, 3.848, 3.896), stdev = 0.072
  CI (99.9%): [2.532, 5.165] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.002 ms/op
Iteration   1: 4.054 ±(99.9%) 0.004 ms/op
Iteration   2: 4.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.027 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.989, 4.027, 4.054), stdev = 0.034
  CI (99.9%): [3.409, 4.644] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.565 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.190 ±(99.9%) 0.009 ms/op
Iteration   1: 5.114 ±(99.9%) 0.023 ms/op
Iteration   2: 4.907 ±(99.9%) 0.015 ms/op
Iteration   3: 4.963 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.995 ±(99.9%) 1.954 ms/op [Average]
  (min, avg, max) = (4.907, 4.995, 5.114), stdev = 0.107
  CI (99.9%): [3.041, 6.949] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.794 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.277 ±(99.9%) 0.013 ms/op
Iteration   1: 4.139 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 14.632 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 4.141 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  13.346 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  9.732 ms/op
                 createUser·p0.9999: 18.920 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232516
  mean =      4.129 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 5725 
    [ 2.500,  3.750) = 79874 
    [ 3.750,  5.000) = 109246 
    [ 5.000,  6.250) = 33437 
    [ 6.250,  7.500) = 2780 
    [ 7.500,  8.750) = 715 
    [ 8.750, 10.000) = 350 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     11.837 ms/op
     p(99.9900) =     18.161 ms/op
     p(99.9990) =     19.377 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.034 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.620 ms/op
                 existUser·p0.9999: 15.867 ms/op
                 existUser·p1.00:   16.548 ms/op

Iteration   2: 3.893 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.393 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  12.591 ms/op
                 existUser·p0.9999: 19.687 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  10.308 ms/op
                 existUser·p0.9999: 19.596 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 241443
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11646 
    [ 2.500,  5.000) = 197692 
    [ 5.000,  7.500) = 31216 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     19.394 ms/op
     p(99.9990) =     20.308 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.011 ms/op
Iteration   1: 4.045 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.579 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  11.433 ms/op
                 getUser·p0.9999: 17.894 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.480 ms/op
                 getUser·p0.99:   6.479 ms/op
                 getUser·p0.999:  9.902 ms/op
                 getUser·p0.9999: 18.567 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 19.655 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236232
  mean =      4.061 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4996 
    [ 2.500,  5.000) = 198943 
    [ 5.000,  7.500) = 31178 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     18.997 ms/op
     p(99.9990) =     22.410 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 7.239 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.489 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.040 ±(99.9%) 0.017 ms/op
Iteration   1: 5.043 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  17.012 ms/op
                 listUser·p0.9999: 24.925 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   2: 5.104 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.406 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  17.275 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.929 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.119 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  23.240 ms/op
                 listUser·p0.9999: 33.359 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191072
  mean =      5.024 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 243 
    [ 2.500,  5.000) = 113731 
    [ 5.000,  7.500) = 69222 
    [ 7.500, 10.000) = 6862 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     17.786 ms/op
     p(99.9900) =     32.928 ms/op
     p(99.9990) =     33.834 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.175 ± 7.036  ops/ms
ClientGrpc.existUser                       thrpt       3   8.281 ± 1.915  ops/ms
ClientGrpc.getUser                         thrpt       3   7.658 ± 0.280  ops/ms
ClientGrpc.listUser                        thrpt       3   6.418 ± 0.511  ops/ms
ClientGrpc.createUser                       avgt       3   4.082 ± 2.509   ms/op
ClientGrpc.existUser                        avgt       3   3.848 ± 1.316   ms/op
ClientGrpc.getUser                          avgt       3   4.027 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   4.995 ± 1.954   ms/op
ClientGrpc.createUser                     sample  232516   4.129 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.838           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.837           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.161           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.497           ms/op
ClientGrpc.existUser                      sample  241443   3.973 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.393           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.699           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.394           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  236232   4.061 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.851           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.554           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.537           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.256           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.997           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.544           ms/op
ClientGrpc.listUser                       sample  191072   5.024 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.405           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.786           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.928           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.013           ms/op
