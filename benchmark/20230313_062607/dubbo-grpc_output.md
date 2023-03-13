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
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 8.438 ops/ms
# Warmup Iteration   3: 10.189 ops/ms
Iteration   1: 10.373 ops/ms
Iteration   2: 10.380 ops/ms
Iteration   3: 10.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.411 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (10.373, 10.411, 10.480), stdev = 0.060
  CI (99.9%): [9.319, 11.504] (assumes normal distribution)


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
# Warmup Iteration   1: 6.813 ops/ms
# Warmup Iteration   2: 10.215 ops/ms
# Warmup Iteration   3: 10.917 ops/ms
Iteration   1: 11.305 ops/ms
Iteration   2: 11.736 ops/ms
Iteration   3: 11.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.500 ±(99.9%) 3.991 ops/ms [Average]
  (min, avg, max) = (11.305, 11.500, 11.736), stdev = 0.219
  CI (99.9%): [7.509, 15.491] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.325 ops/ms
# Warmup Iteration   2: 10.407 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.839 ±(99.9%) 1.781 ops/ms [Average]
  (min, avg, max) = (10.727, 10.839, 10.903), stdev = 0.098
  CI (99.9%): [9.058, 12.620] (assumes normal distribution)


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
# Warmup Iteration   1: 7.255 ops/ms
# Warmup Iteration   2: 8.190 ops/ms
# Warmup Iteration   3: 8.218 ops/ms
Iteration   1: 8.460 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.429 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (8.319, 8.429, 8.507), stdev = 0.098
  CI (99.9%): [6.644, 10.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.002 ms/op
Iteration   3: 2.926 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.935 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.918, 2.935, 2.960), stdev = 0.023
  CI (99.9%): [2.523, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.004 ms/op
Iteration   1: 2.866 ±(99.9%) 0.003 ms/op
Iteration   2: 2.906 ±(99.9%) 0.002 ms/op
Iteration   3: 2.900 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.866, 2.891, 2.906), stdev = 0.021
  CI (99.9%): [2.502, 3.279] (assumes normal distribution)


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.017 ms/op
Iteration   1: 2.985 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.982 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (2.952, 2.982, 3.009), stdev = 0.029
  CI (99.9%): [2.459, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
Iteration   1: 3.930 ±(99.9%) 0.012 ms/op
Iteration   2: 3.813 ±(99.9%) 0.027 ms/op
Iteration   3: 3.912 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.885 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (3.813, 3.885, 3.930), stdev = 0.063
  CI (99.9%): [2.735, 5.034] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.087 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.177 ms/op
                 createUser·p0.9999: 13.774 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 22.359 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320259
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25432 
    [ 2.500,  5.000) = 293541 
    [ 5.000,  7.500) = 895 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.370 ms/op
     p(99.9900) =     21.603 ms/op
     p(99.9990) =     22.603 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.330 ms/op
                 existUser·p0.9999: 12.193 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.892 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 12.287 ms/op
                 existUser·p1.00:   13.730 ms/op

Iteration   3: 2.846 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.378 ms/op
                 existUser·p0.999:  6.289 ms/op
                 existUser·p0.9999: 26.633 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331944
  mean =      2.890 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43818 
    [ 2.500,  5.000) = 286937 
    [ 5.000,  7.500) = 994 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      6.506 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     26.794 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 11.346 ms/op
                 getUser·p1.00:   11.747 ms/op

Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.237 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.983 ms/op
                 getUser·p0.9999: 17.523 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 2.937 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.246 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320476
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28597 
    [ 2.500,  5.000) = 290567 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.237 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.729 ms/op
     p(99.9900) =     22.335 ms/op
     p(99.9990) =     23.907 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 4.900 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.010 ms/op
Iteration   1: 3.712 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  12.009 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.364 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 3.830 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.343 ms/op
                 listUser·p0.9999: 15.750 ms/op
                 listUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252053
  mean =      3.811 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5339 
    [ 2.500,  5.000) = 228413 
    [ 5.000,  7.500) = 17220 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     13.888 ms/op
     p(99.9900) =     21.227 ms/op
     p(99.9990) =     21.936 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.411 ± 1.093  ops/ms
ClientGrpc.existUser                       thrpt       3  11.500 ± 3.991  ops/ms
ClientGrpc.getUser                         thrpt       3  10.839 ± 1.781  ops/ms
ClientGrpc.listUser                        thrpt       3   8.429 ± 1.784  ops/ms
ClientGrpc.createUser                       avgt       3   2.935 ± 0.412   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.389   ms/op
ClientGrpc.getUser                          avgt       3   2.982 ± 0.524   ms/op
ClientGrpc.listUser                         avgt       3   3.885 ± 1.150   ms/op
ClientGrpc.createUser                     sample  320259   2.998 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.468           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.370           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.603           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  331944   2.890 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.506           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.804           ms/op
ClientGrpc.getUser                        sample  320476   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.237           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.729           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.335           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  252053   3.811 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.870           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.888           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.227           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.086           ms/op
