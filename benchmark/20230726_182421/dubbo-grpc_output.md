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
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 8.075 ops/ms
# Warmup Iteration   3: 9.686 ops/ms
Iteration   1: 10.143 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 10.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.034 ±(99.9%) 3.178 ops/ms [Average]
  (min, avg, max) = (9.833, 10.034, 10.143), stdev = 0.174
  CI (99.9%): [6.855, 13.212] (assumes normal distribution)


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
# Warmup Iteration   1: 7.099 ops/ms
# Warmup Iteration   2: 10.179 ops/ms
# Warmup Iteration   3: 10.553 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.808 ops/ms
Iteration   3: 10.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.770 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (10.678, 10.770, 10.825), stdev = 0.080
  CI (99.9%): [9.309, 12.232] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.333 ops/ms
# Warmup Iteration   2: 9.654 ops/ms
# Warmup Iteration   3: 9.965 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.350 ±(99.9%) 3.449 ops/ms [Average]
  (min, avg, max) = (10.132, 10.350, 10.473), stdev = 0.189
  CI (99.9%): [6.901, 13.799] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.955 ops/ms
# Warmup Iteration   2: 7.122 ops/ms
# Warmup Iteration   3: 7.202 ops/ms
Iteration   1: 6.757 ops/ms
Iteration   2: 7.088 ops/ms
Iteration   3: 7.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.039 ±(99.9%) 4.761 ops/ms [Average]
  (min, avg, max) = (6.757, 7.039, 7.272), stdev = 0.261
  CI (99.9%): [2.278, 11.800] (assumes normal distribution)


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
# Warmup Iteration   1: 5.853 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
Iteration   3: 3.199 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.179 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.140, 3.179, 3.199), stdev = 0.034
  CI (99.9%): [2.565, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.002 ms/op
Iteration   1: 2.931 ±(99.9%) 0.003 ms/op
Iteration   2: 3.239 ±(99.9%) 0.002 ms/op
Iteration   3: 2.973 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.048 ±(99.9%) 3.043 ms/op [Average]
  (min, avg, max) = (2.931, 3.048, 3.239), stdev = 0.167
  CI (99.9%): [0.005, 6.091] (assumes normal distribution)


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.003 ms/op
Iteration   3: 3.230 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.181 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.137, 3.181, 3.230), stdev = 0.047
  CI (99.9%): [2.327, 4.036] (assumes normal distribution)


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
# Warmup Iteration   1: 6.762 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.013 ms/op
Iteration   1: 4.265 ±(99.9%) 0.021 ms/op
Iteration   2: 4.331 ±(99.9%) 0.019 ms/op
Iteration   3: 4.359 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.318 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (4.265, 4.318, 4.359), stdev = 0.048
  CI (99.9%): [3.436, 5.201] (assumes normal distribution)


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
# Warmup Iteration   1: 4.907 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.159 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.012 ms/op
Iteration   1: 3.802 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.840 ms/op
                 createUser·p0.999:  12.710 ms/op
                 createUser·p0.9999: 23.678 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.535 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 24.603 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.504 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  11.338 ms/op
                 createUser·p0.9999: 30.441 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265925
  mean =      3.609 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14113 
    [ 2.500,  5.000) = 235804 
    [ 5.000,  7.500) = 13519 
    [ 7.500, 10.000) = 1776 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     29.597 ms/op
     p(99.9990) =     30.529 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  12.137 ms/op
                 existUser·p0.9999: 24.319 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.264 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  9.268 ms/op
                 existUser·p0.9999: 30.940 ms/op
                 existUser·p1.00:   31.883 ms/op

Iteration   3: 3.289 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 25.600 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291621
  mean =      3.293 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15869 
    [ 2.500,  5.000) = 268132 
    [ 5.000,  7.500) = 6174 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     11.295 ms/op
     p(99.9900) =     29.579 ms/op
     p(99.9990) =     31.698 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 5.561 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.011 ms/op
Iteration   1: 3.483 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  11.634 ms/op
                 getUser·p0.9999: 16.250 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   2: 3.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.974 ms/op
                 getUser·p0.999:  10.299 ms/op
                 getUser·p0.9999: 17.979 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  10.240 ms/op
                 getUser·p0.9999: 20.854 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 280593
  mean =      3.421 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14162 
    [ 2.500,  5.000) = 258696 
    [ 5.000,  7.500) = 6177 
    [ 7.500, 10.000) = 1186 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     20.281 ms/op
     p(99.9990) =     21.410 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.313 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.992 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.019 ms/op
Iteration   1: 4.668 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 18.229 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.833 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   10.666 ms/op
                 listUser·p0.999:  19.567 ms/op
                 listUser·p0.9999: 28.532 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   3: 4.503 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   6.955 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  24.978 ms/op
                 listUser·p0.9999: 30.955 ms/op
                 listUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206058
  mean =      4.664 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 943 
    [ 2.500,  5.000) = 149061 
    [ 5.000,  7.500) = 48065 
    [ 7.500, 10.000) = 6297 
    [10.000, 12.500) = 980 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      6.365 ms/op
     p(95.0000) =      7.184 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.069 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     31.060 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.034 ± 3.178  ops/ms
ClientGrpc.existUser                       thrpt       3  10.770 ± 1.461  ops/ms
ClientGrpc.getUser                         thrpt       3  10.350 ± 3.449  ops/ms
ClientGrpc.listUser                        thrpt       3   7.039 ± 4.761  ops/ms
ClientGrpc.createUser                       avgt       3   3.179 ± 0.614   ms/op
ClientGrpc.existUser                        avgt       3   3.048 ± 3.043   ms/op
ClientGrpc.getUser                          avgt       3   3.181 ± 0.855   ms/op
ClientGrpc.listUser                         avgt       3   4.318 ± 0.882   ms/op
ClientGrpc.createUser                     sample  265925   3.609 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.381           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.042           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.597           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.638           ms/op
ClientGrpc.existUser                      sample  291621   3.293 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.174           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.295           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.579           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.883           ms/op
ClientGrpc.getUser                        sample  280593   3.421 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.322           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.715           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.281           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  206058   4.664 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.836           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.365           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.585           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.069           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.491           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.261           ms/op
