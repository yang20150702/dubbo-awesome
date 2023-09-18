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
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 8.370 ops/ms
# Warmup Iteration   3: 9.650 ops/ms
Iteration   1: 10.093 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.131 ±(99.9%) 0.640 ops/ms [Average]
  (min, avg, max) = (10.093, 10.131, 10.162), stdev = 0.035
  CI (99.9%): [9.491, 10.771] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.144 ops/ms
# Warmup Iteration   2: 10.449 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.696 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.628 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (10.562, 10.628, 10.696), stdev = 0.067
  CI (99.9%): [9.405, 11.850] (assumes normal distribution)


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
# Warmup Iteration   1: 6.863 ops/ms
# Warmup Iteration   2: 9.951 ops/ms
# Warmup Iteration   3: 10.187 ops/ms
Iteration   1: 10.312 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 10.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.258 ±(99.9%) 3.514 ops/ms [Average]
  (min, avg, max) = (10.044, 10.258, 10.418), stdev = 0.193
  CI (99.9%): [6.745, 13.772] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ops/ms
# Warmup Iteration   2: 8.048 ops/ms
# Warmup Iteration   3: 8.131 ops/ms
Iteration   1: 8.249 ops/ms
Iteration   2: 8.249 ops/ms
Iteration   3: 8.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.281 ±(99.9%) 0.998 ops/ms [Average]
  (min, avg, max) = (8.249, 8.281, 8.344), stdev = 0.055
  CI (99.9%): [7.283, 9.278] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.002 ms/op
Iteration   1: 3.211 ±(99.9%) 0.014 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.158 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.138, 3.169, 3.211), stdev = 0.038
  CI (99.9%): [2.480, 3.858] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 3.003 ±(99.9%) 0.002 ms/op
Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.980 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (2.950, 2.980, 3.003), stdev = 0.027
  CI (99.9%): [2.483, 3.477] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.139 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.077 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.077, 3.129, 3.171), stdev = 0.048
  CI (99.9%): [2.258, 4.000] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.354 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.024 ms/op
Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
Iteration   2: 3.894 ±(99.9%) 0.007 ms/op
Iteration   3: 3.819 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.865 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (3.819, 3.865, 3.894), stdev = 0.040
  CI (99.9%): [3.133, 4.598] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.234 ms/op
                 createUser·p0.9999: 16.021 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.024 ms/op
                 createUser·p0.9999: 18.476 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 20.095 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304932
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8412 
    [ 2.500,  5.000) = 294666 
    [ 5.000,  7.500) = 1421 
    [ 7.500, 10.000) = 105 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  7.517 ms/op
                 existUser·p0.9999: 11.874 ms/op
                 existUser·p1.00:   12.288 ms/op

Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.446 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  10.420 ms/op
                 existUser·p0.9999: 18.534 ms/op
                 existUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320114
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22080 
    [ 2.500,  5.000) = 296680 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.233 ms/op
     p(99.9900) =     17.385 ms/op
     p(99.9990) =     20.598 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
Iteration   1: 3.136 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 15.774 ms/op
                 getUser·p1.00:   16.155 ms/op

Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.228 ms/op
                 getUser·p0.999:  7.353 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.298 ms/op
                 getUser·p0.999:  7.027 ms/op
                 getUser·p0.9999: 20.043 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307668
  mean =      3.121 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7168 
    [ 2.500,  5.000) = 298676 
    [ 5.000,  7.500) = 1506 
    [ 7.500, 10.000) = 126 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.010 ms/op
Iteration   1: 3.933 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  12.818 ms/op
                 listUser·p0.9999: 14.510 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   2: 3.761 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.938 ms/op
                 listUser·p0.9999: 18.866 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247547
  mean =      3.875 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2488 
    [ 2.500,  3.750) = 107807 
    [ 3.750,  5.000) = 124397 
    [ 5.000,  6.250) = 8430 
    [ 6.250,  7.500) = 3588 
    [ 7.500,  8.750) = 332 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 111 
    [15.000, 16.250) = 95 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     17.703 ms/op
     p(99.9990) =     19.335 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.131 ± 0.640  ops/ms
ClientGrpc.existUser                       thrpt       3  10.628 ± 1.223  ops/ms
ClientGrpc.getUser                         thrpt       3  10.258 ± 3.514  ops/ms
ClientGrpc.listUser                        thrpt       3   8.281 ± 0.998  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 0.689   ms/op
ClientGrpc.existUser                        avgt       3   2.980 ± 0.497   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.871   ms/op
ClientGrpc.listUser                         avgt       3   3.865 ± 0.732   ms/op
ClientGrpc.createUser                     sample  304932   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.738           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.674           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.240           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.497           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.594           ms/op
ClientGrpc.existUser                      sample  320114   3.000 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.493           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.233           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.385           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  307668   3.121 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.785           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.602           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.595           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  247547   3.875 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.202           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.391           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.943           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.703           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.464           ms/op
