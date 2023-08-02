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
# Warmup Iteration   1: 4.785 ops/ms
# Warmup Iteration   2: 9.565 ops/ms
# Warmup Iteration   3: 10.745 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.696 ±(99.9%) 2.962 ops/ms [Average]
  (min, avg, max) = (10.511, 10.696, 10.817), stdev = 0.162
  CI (99.9%): [7.734, 13.658] (assumes normal distribution)


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
# Warmup Iteration   1: 9.099 ops/ms
# Warmup Iteration   2: 10.763 ops/ms
# Warmup Iteration   3: 10.999 ops/ms
Iteration   1: 11.213 ops/ms
Iteration   2: 11.115 ops/ms
Iteration   3: 11.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.140 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (11.093, 11.140, 11.213), stdev = 0.064
  CI (99.9%): [9.978, 12.303] (assumes normal distribution)


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
# Warmup Iteration   1: 7.339 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.666 ops/ms
Iteration   1: 10.642 ops/ms
Iteration   2: 10.743 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.683 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (10.642, 10.683, 10.743), stdev = 0.053
  CI (99.9%): [9.708, 11.658] (assumes normal distribution)


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
# Warmup Iteration   1: 6.521 ops/ms
# Warmup Iteration   2: 7.896 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.234 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (8.123, 8.234, 8.349), stdev = 0.113
  CI (99.9%): [6.164, 10.303] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.004 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.013 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (2.977, 3.013, 3.034), stdev = 0.031
  CI (99.9%): [2.447, 3.579] (assumes normal distribution)


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.004 ms/op
Iteration   1: 2.852 ±(99.9%) 0.004 ms/op
Iteration   2: 2.853 ±(99.9%) 0.002 ms/op
Iteration   3: 2.899 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (2.852, 2.868, 2.899), stdev = 0.027
  CI (99.9%): [2.374, 3.362] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.950 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.938, 2.950, 2.973), stdev = 0.020
  CI (99.9%): [2.585, 3.314] (assumes normal distribution)


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
# Warmup Iteration   1: 5.111 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.026 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
Iteration   2: 3.894 ±(99.9%) 0.017 ms/op
Iteration   3: 3.905 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.919 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (3.894, 3.919, 3.958), stdev = 0.034
  CI (99.9%): [3.294, 4.545] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.007 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.177 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.681 ms/op

Iteration   2: 2.960 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.570 ms/op
                 createUser·p0.9999: 22.020 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 27.338 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322061
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34323 
    [ 2.500,  5.000) = 285682 
    [ 5.000,  7.500) = 1530 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     24.945 ms/op
     p(99.9990) =     27.609 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 16.042 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.210 ms/op
                 existUser·p0.9999: 15.396 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 28.026 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328803
  mean =      2.919 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39490 
    [ 2.500,  5.000) = 287463 
    [ 5.000,  7.500) = 1522 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.500 ms/op
     p(99.9900) =     17.378 ms/op
     p(99.9990) =     28.391 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.534 ms/op
                 getUser·p0.9999: 12.333 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.513 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.717 ms/op
                 getUser·p0.9999: 16.492 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 26.103 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315263
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23001 
    [ 2.500,  5.000) = 290538 
    [ 5.000,  7.500) = 1364 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 5.028 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.011 ms/op
Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  16.189 ms/op
                 listUser·p0.9999: 18.574 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.868 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 22.175 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  19.465 ms/op
                 listUser·p0.9999: 22.246 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244502
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4812 
    [ 2.500,  5.000) = 217665 
    [ 5.000,  7.500) = 20310 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     16.957 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.696 ± 2.962  ops/ms
ClientGrpc.existUser                       thrpt       3  11.140 ± 1.163  ops/ms
ClientGrpc.getUser                         thrpt       3  10.683 ± 0.975  ops/ms
ClientGrpc.listUser                        thrpt       3   8.234 ± 2.069  ops/ms
ClientGrpc.createUser                       avgt       3   3.013 ± 0.566   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.494   ms/op
ClientGrpc.getUser                          avgt       3   2.950 ± 0.364   ms/op
ClientGrpc.listUser                         avgt       3   3.919 ± 0.626   ms/op
ClientGrpc.createUser                     sample  322061   2.980 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.603           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.945           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.689           ms/op
ClientGrpc.existUser                      sample  328803   2.919 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.500           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.378           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.508           ms/op
ClientGrpc.getUser                        sample  315263   3.043 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.513           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.494           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.345           ms/op
ClientGrpc.listUser                       sample  244502   3.927 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.957           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.118           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.544           ms/op
