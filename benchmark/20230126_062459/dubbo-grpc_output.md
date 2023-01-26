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
# Warmup Iteration   1: 4.744 ops/ms
# Warmup Iteration   2: 9.844 ops/ms
# Warmup Iteration   3: 10.367 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.231 ±(99.9%) 0.437 ops/ms [Average]
  (min, avg, max) = (10.205, 10.231, 10.252), stdev = 0.024
  CI (99.9%): [9.794, 10.667] (assumes normal distribution)


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
# Warmup Iteration   1: 7.715 ops/ms
# Warmup Iteration   2: 10.693 ops/ms
# Warmup Iteration   3: 10.781 ops/ms
Iteration   1: 10.901 ops/ms
Iteration   2: 11.414 ops/ms
Iteration   3: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.023 ±(99.9%) 6.309 ops/ms [Average]
  (min, avg, max) = (10.756, 11.023, 11.414), stdev = 0.346
  CI (99.9%): [4.714, 17.333] (assumes normal distribution)


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
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 10.203 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 10.400 ops/ms
Iteration   2: 10.324 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.390 ±(99.9%) 1.111 ops/ms [Average]
  (min, avg, max) = (10.324, 10.390, 10.444), stdev = 0.061
  CI (99.9%): [9.279, 11.500] (assumes normal distribution)


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
# Warmup Iteration   1: 6.388 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.819 ops/ms
Iteration   1: 7.679 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.928 ±(99.9%) 3.950 ops/ms [Average]
  (min, avg, max) = (7.679, 7.928, 8.070), stdev = 0.217
  CI (99.9%): [3.977, 11.878] (assumes normal distribution)


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 2.947 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (2.947, 3.013, 3.072), stdev = 0.063
  CI (99.9%): [1.868, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.004 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.003 ms/op
Iteration   3: 2.926 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (2.923, 2.949, 2.999), stdev = 0.043
  CI (99.9%): [2.165, 3.734] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.002 ms/op
Iteration   1: 3.093 ±(99.9%) 0.001 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.014, 3.064, 3.093), stdev = 0.044
  CI (99.9%): [2.263, 3.865] (assumes normal distribution)


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.016 ms/op
Iteration   1: 4.001 ±(99.9%) 0.008 ms/op
Iteration   2: 3.873 ±(99.9%) 0.013 ms/op
Iteration   3: 4.071 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.982 ±(99.9%) 1.836 ms/op [Average]
  (min, avg, max) = (3.873, 3.982, 4.071), stdev = 0.101
  CI (99.9%): [2.146, 5.818] (assumes normal distribution)


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  9.061 ms/op
                 createUser·p0.9999: 13.327 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.419 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.712 ms/op
                 createUser·p0.9999: 12.987 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 3.076 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.013 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310495
  mean =      3.092 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1048 
    [ 1.250,  2.500) = 21449 
    [ 2.500,  3.750) = 263417 
    [ 3.750,  5.000) = 23627 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 152 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.541 ms/op
     p(99.9900) =     16.531 ms/op
     p(99.9990) =     17.032 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 14.071 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.276 ms/op
                 existUser·p0.9999: 13.229 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  5.923 ms/op
                 existUser·p0.9999: 26.771 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318561
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35206 
    [ 2.500,  5.000) = 282605 
    [ 5.000,  7.500) = 486 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.840 ms/op
     p(99.9900) =     26.079 ms/op
     p(99.9990) =     27.081 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 17.577 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.176 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.323 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 14.071 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.820 ms/op
                 getUser·p0.9999: 15.090 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313159
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2176 
    [ 1.250,  2.500) = 23112 
    [ 2.500,  3.750) = 263104 
    [ 3.750,  5.000) = 23789 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 224 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.183 ms/op
     p(99.9900) =     16.822 ms/op
     p(99.9990) =     17.789 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 5.139 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.012 ms/op
Iteration   1: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.119 ms/op
                 listUser·p0.9999: 16.600 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.954 ms/op
                 listUser·p0.999:  19.598 ms/op
                 listUser·p0.9999: 25.154 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.013 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  18.108 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236891
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4525 
    [ 2.500,  5.000) = 201212 
    [ 5.000,  7.500) = 29810 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     16.457 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     25.568 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.231 ± 0.437  ops/ms
ClientGrpc.existUser                       thrpt       3  11.023 ± 6.309  ops/ms
ClientGrpc.getUser                         thrpt       3  10.390 ± 1.111  ops/ms
ClientGrpc.listUser                        thrpt       3   7.928 ± 3.950  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 1.145   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.785   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.801   ms/op
ClientGrpc.listUser                         avgt       3   3.982 ± 1.836   ms/op
ClientGrpc.createUser                     sample  310495   3.092 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.419           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.541           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.531           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  318561   3.012 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.840           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.079           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.836           ms/op
ClientGrpc.getUser                        sample  313159   3.065 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.594           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.183           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.822           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.826           ms/op
ClientGrpc.listUser                       sample  236891   4.054 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.911           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.457           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
