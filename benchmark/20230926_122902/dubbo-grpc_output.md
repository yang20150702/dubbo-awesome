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
# Warmup Iteration   1: 3.018 ops/ms
# Warmup Iteration   2: 6.158 ops/ms
# Warmup Iteration   3: 7.675 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.297 ops/ms
Iteration   3: 8.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.267 ±(99.9%) 2.611 ops/ms [Average]
  (min, avg, max) = (8.112, 8.267, 8.393), stdev = 0.143
  CI (99.9%): [5.657, 10.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.215 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 8.887 ops/ms
Iteration   1: 9.003 ops/ms
Iteration   2: 8.567 ops/ms
Iteration   3: 8.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.814 ±(99.9%) 4.083 ops/ms [Average]
  (min, avg, max) = (8.567, 8.814, 9.003), stdev = 0.224
  CI (99.9%): [4.731, 12.897] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.353 ops/ms
# Warmup Iteration   2: 7.743 ops/ms
# Warmup Iteration   3: 8.202 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.266 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (8.209, 8.266, 8.295), stdev = 0.049
  CI (99.9%): [7.371, 9.160] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ops/ms
# Warmup Iteration   2: 5.656 ops/ms
# Warmup Iteration   3: 6.215 ops/ms
Iteration   1: 6.462 ops/ms
Iteration   2: 6.455 ops/ms
Iteration   3: 6.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.483 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (6.455, 6.483, 6.532), stdev = 0.043
  CI (99.9%): [5.704, 7.262] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.816 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.020 ms/op
Iteration   1: 4.054 ±(99.9%) 0.003 ms/op
Iteration   2: 4.049 ±(99.9%) 0.002 ms/op
Iteration   3: 3.939 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.014 ±(99.9%) 1.181 ms/op [Average]
  (min, avg, max) = (3.939, 4.014, 4.054), stdev = 0.065
  CI (99.9%): [2.833, 5.195] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.004 ms/op
Iteration   1: 3.744 ±(99.9%) 0.002 ms/op
Iteration   2: 3.838 ±(99.9%) 0.002 ms/op
Iteration   3: 3.770 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.784 ±(99.9%) 0.885 ms/op [Average]
  (min, avg, max) = (3.744, 3.784, 3.838), stdev = 0.048
  CI (99.9%): [2.899, 4.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.704 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.002 ms/op
Iteration   1: 4.122 ±(99.9%) 0.003 ms/op
Iteration   2: 4.127 ±(99.9%) 0.003 ms/op
Iteration   3: 3.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.074 ±(99.9%) 1.615 ms/op [Average]
  (min, avg, max) = (3.971, 4.074, 4.127), stdev = 0.089
  CI (99.9%): [2.458, 5.689] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.328 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.861 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.131 ±(99.9%) 0.018 ms/op
Iteration   1: 5.077 ±(99.9%) 0.033 ms/op
Iteration   2: 5.050 ±(99.9%) 0.009 ms/op
Iteration   3: 4.888 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.005 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (4.888, 5.005, 5.077), stdev = 0.103
  CI (99.9%): [3.132, 6.879] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.011 ms/op
Iteration   1: 4.139 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  10.189 ms/op
                 createUser·p0.9999: 15.913 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.975 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  13.601 ms/op
                 createUser·p0.9999: 18.740 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   3: 3.859 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.268 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240591
  mean =      3.988 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4650 
    [ 2.500,  5.000) = 215740 
    [ 5.000,  7.500) = 18727 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     12.308 ms/op
     p(99.9900) =     28.637 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.241 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
Iteration   1: 3.683 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 14.969 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   2: 3.811 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 17.787 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.573 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  13.982 ms/op
                 existUser·p0.9999: 21.677 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253048
  mean =      3.793 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6876 
    [ 2.500,  5.000) = 235312 
    [ 5.000,  7.500) = 9416 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     20.810 ms/op
     p(99.9990) =     22.099 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 6.100 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.010 ms/op
Iteration   1: 3.747 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 15.121 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 3.789 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 23.096 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   3: 3.930 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  10.610 ms/op
                 getUser·p0.9999: 21.585 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251404
  mean =      3.820 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6311 
    [ 2.500,  5.000) = 232931 
    [ 5.000,  7.500) = 10940 
    [ 7.500, 10.000) = 981 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =      9.971 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     23.412 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 6.599 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.470 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.966 ±(99.9%) 0.015 ms/op
Iteration   1: 4.931 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  15.345 ms/op
                 listUser·p0.9999: 18.843 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 5.110 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.610 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  18.053 ms/op
                 listUser·p0.9999: 26.736 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   3: 4.916 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.882 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  18.896 ms/op
                 listUser·p0.9999: 23.166 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192650
  mean =      4.984 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 126071 
    [ 5.000,  7.500) = 59090 
    [ 7.500, 10.000) = 6245 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     23.126 ms/op
     p(99.9990) =     27.270 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.267 ± 2.611  ops/ms
ClientGrpc.existUser                       thrpt       3   8.814 ± 4.083  ops/ms
ClientGrpc.getUser                         thrpt       3   8.266 ± 0.895  ops/ms
ClientGrpc.listUser                        thrpt       3   6.483 ± 0.779  ops/ms
ClientGrpc.createUser                       avgt       3   4.014 ± 1.181   ms/op
ClientGrpc.existUser                        avgt       3   3.784 ± 0.885   ms/op
ClientGrpc.getUser                          avgt       3   4.074 ± 1.615   ms/op
ClientGrpc.listUser                         avgt       3   5.005 ± 1.874   ms/op
ClientGrpc.createUser                     sample  240591   3.988 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.723           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.775           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.308           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.637           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.557           ms/op
ClientGrpc.existUser                      sample  253048   3.793 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.877           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.488           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.435           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  251404   3.820 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.357           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.496           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  192650   4.984 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.300           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.070           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.186           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.126           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
