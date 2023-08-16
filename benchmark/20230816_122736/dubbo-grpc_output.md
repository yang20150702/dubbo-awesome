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
# Warmup Iteration   1: 4.965 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 10.140 ops/ms
Iteration   1: 10.863 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.805 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (10.756, 10.805, 10.863), stdev = 0.054
  CI (99.9%): [9.812, 11.797] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.887 ops/ms
# Warmup Iteration   2: 10.953 ops/ms
# Warmup Iteration   3: 11.330 ops/ms
Iteration   1: 11.419 ops/ms
Iteration   2: 11.399 ops/ms
Iteration   3: 11.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.381 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (11.327, 11.381, 11.419), stdev = 0.049
  CI (99.9%): [10.494, 12.269] (assumes normal distribution)


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
# Warmup Iteration   1: 7.619 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.807 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 10.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.887 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (10.833, 10.887, 10.944), stdev = 0.056
  CI (99.9%): [9.865, 11.909] (assumes normal distribution)


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
# Warmup Iteration   1: 6.163 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.289 ops/ms
Iteration   1: 8.307 ops/ms
Iteration   2: 8.505 ops/ms
Iteration   3: 8.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.407 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (8.307, 8.407, 8.505), stdev = 0.099
  CI (99.9%): [6.601, 10.212] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.004 ms/op
Iteration   1: 2.944 ±(99.9%) 0.004 ms/op
Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.956 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.944, 2.956, 2.969), stdev = 0.013
  CI (99.9%): [2.723, 3.189] (assumes normal distribution)


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.816 ±(99.9%) 0.003 ms/op
Iteration   1: 2.846 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.002 ms/op
Iteration   3: 2.826 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.851 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.826, 2.851, 2.882), stdev = 0.028
  CI (99.9%): [2.338, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.952 ±(99.9%) 0.059 ms/op [Average]
  (min, avg, max) = (2.948, 2.952, 2.955), stdev = 0.003
  CI (99.9%): [2.893, 3.011] (assumes normal distribution)


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
# Warmup Iteration   1: 5.087 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.025 ms/op
Iteration   1: 3.810 ±(99.9%) 0.013 ms/op
Iteration   2: 3.739 ±(99.9%) 0.020 ms/op
Iteration   3: 3.786 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.778 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.739, 3.778, 3.810), stdev = 0.036
  CI (99.9%): [3.120, 4.436] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.008 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.550 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.339 ms/op
                 createUser·p0.9999: 15.202 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.749 ms/op
                 createUser·p0.9999: 15.799 ms/op
                 createUser·p1.00:   16.155 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  10.663 ms/op
                 createUser·p0.9999: 19.661 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320010
  mean =      3.002 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1564 
    [ 1.250,  2.500) = 25964 
    [ 2.500,  3.750) = 275140 
    [ 3.750,  5.000) = 15253 
    [ 5.000,  6.250) = 1112 
    [ 6.250,  7.500) = 505 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     18.447 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.916 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
Iteration   1: 2.894 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.487 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.409 ms/op
                 existUser·p0.9999: 11.565 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   2: 2.896 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 13.204 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   3: 2.865 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.258 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.354 ms/op
                 existUser·p0.9999: 25.619 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332858
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49140 
    [ 2.500,  5.000) = 282134 
    [ 5.000,  7.500) = 1229 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.258 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.587 ms/op
     p(99.9900) =     13.524 ms/op
     p(99.9990) =     25.843 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.483 ms/op
                 getUser·p0.9999: 13.817 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.193 ms/op
                 getUser·p0.9999: 16.676 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.940 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.194 ms/op
                 getUser·p0.9999: 17.830 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322426
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1521 
    [ 1.250,  2.500) = 28313 
    [ 2.500,  3.750) = 279144 
    [ 3.750,  5.000) = 11940 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 154 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 68 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.664 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  12.928 ms/op
                 listUser·p0.9999: 16.966 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.855 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  16.551 ms/op
                 listUser·p0.9999: 23.223 ms/op
                 listUser·p1.00:   30.474 ms/op

Iteration   3: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.563 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  16.287 ms/op
                 listUser·p0.9999: 22.057 ms/op
                 listUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248346
  mean =      3.866 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5962 
    [ 2.500,  5.000) = 220010 
    [ 5.000,  7.500) = 20923 
    [ 7.500, 10.000) = 997 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.893 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     27.306 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.805 ± 0.992  ops/ms
ClientGrpc.existUser                       thrpt       3  11.381 ± 0.888  ops/ms
ClientGrpc.getUser                         thrpt       3  10.887 ± 1.022  ops/ms
ClientGrpc.listUser                        thrpt       3   8.407 ± 1.806  ops/ms
ClientGrpc.createUser                       avgt       3   2.956 ± 0.233   ms/op
ClientGrpc.existUser                        avgt       3   2.851 ± 0.513   ms/op
ClientGrpc.getUser                          avgt       3   2.952 ± 0.059   ms/op
ClientGrpc.listUser                         avgt       3   3.778 ± 0.658   ms/op
ClientGrpc.createUser                     sample  320010   3.002 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.683           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.716           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.447           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.759           ms/op
ClientGrpc.existUser                      sample  332858   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.258           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.587           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.524           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  322426   2.973 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.664           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  248346   3.866 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.563           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.893           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.474           ms/op
