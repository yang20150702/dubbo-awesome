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
# Warmup Iteration   1: 4.358 ops/ms
# Warmup Iteration   2: 8.939 ops/ms
# Warmup Iteration   3: 10.102 ops/ms
Iteration   1: 10.415 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.476 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.415, 10.476, 10.529), stdev = 0.057
  CI (99.9%): [9.427, 11.525] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 10.790 ops/ms
# Warmup Iteration   3: 11.107 ops/ms
Iteration   1: 11.354 ops/ms
Iteration   2: 11.397 ops/ms
Iteration   3: 11.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.338 ±(99.9%) 1.233 ops/ms [Average]
  (min, avg, max) = (11.265, 11.338, 11.397), stdev = 0.068
  CI (99.9%): [10.106, 12.571] (assumes normal distribution)


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
# Warmup Iteration   1: 7.399 ops/ms
# Warmup Iteration   2: 10.211 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 10.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.737 ±(99.9%) 0.770 ops/ms [Average]
  (min, avg, max) = (10.691, 10.737, 10.774), stdev = 0.042
  CI (99.9%): [9.967, 11.508] (assumes normal distribution)


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
# Warmup Iteration   1: 6.270 ops/ms
# Warmup Iteration   2: 7.710 ops/ms
# Warmup Iteration   3: 8.064 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.085 ops/ms
Iteration   3: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.141 ±(99.9%) 1.595 ops/ms [Average]
  (min, avg, max) = (8.085, 8.141, 8.242), stdev = 0.087
  CI (99.9%): [6.546, 9.736] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
Iteration   2: 2.990 ±(99.9%) 0.016 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.989 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (2.949, 2.989, 3.026), stdev = 0.038
  CI (99.9%): [2.288, 3.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.781 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.882, 2.899, 2.909), stdev = 0.015
  CI (99.9%): [2.634, 3.164] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.981 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.963, 2.981, 2.994), stdev = 0.016
  CI (99.9%): [2.686, 3.277] (assumes normal distribution)


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
# Warmup Iteration   1: 5.034 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.041 ms/op
Iteration   1: 4.020 ±(99.9%) 0.005 ms/op
Iteration   2: 4.027 ±(99.9%) 0.024 ms/op
Iteration   3: 4.021 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.023 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (4.020, 4.023, 4.027), stdev = 0.004
  CI (99.9%): [3.951, 4.094] (assumes normal distribution)


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.723 ms/op
                 createUser·p0.9999: 12.630 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.265 ms/op
                 createUser·p0.9999: 16.080 ms/op
                 createUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317239
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1906 
    [ 1.250,  2.500) = 19888 
    [ 2.500,  3.750) = 278439 
    [ 3.750,  5.000) = 15028 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 487 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.089 ms/op
     p(99.9900) =     16.475 ms/op
     p(99.9990) =     17.132 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.206 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.616 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.836 ms/op
                 existUser·p0.9999: 26.290 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329283
  mean =      2.916 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29417 
    [ 2.500,  5.000) = 298629 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     18.134 ms/op
     p(99.9990) =     26.588 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.206 ms/op
                 getUser·p0.9999: 14.552 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 16.597 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.615 ms/op
                 getUser·p0.9999: 32.217 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317392
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23196 
    [ 2.500,  5.000) = 292538 
    [ 5.000,  7.500) = 1156 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     31.466 ms/op
     p(99.9990) =     32.467 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  13.487 ms/op
                 listUser·p0.9999: 22.478 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  14.837 ms/op
                 listUser·p0.9999: 27.622 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   3: 3.922 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.886 ms/op
                 listUser·p0.9999: 22.919 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242113
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4142 
    [ 2.500,  5.000) = 214932 
    [ 5.000,  7.500) = 21547 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.857 ms/op
     p(99.9900) =     26.830 ms/op
     p(99.9990) =     28.689 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.476 ± 1.049  ops/ms
ClientGrpc.existUser                       thrpt       3  11.338 ± 1.233  ops/ms
ClientGrpc.getUser                         thrpt       3  10.737 ± 0.770  ops/ms
ClientGrpc.listUser                        thrpt       3   8.141 ± 1.595  ops/ms
ClientGrpc.createUser                       avgt       3   2.989 ± 0.701   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 0.265   ms/op
ClientGrpc.getUser                          avgt       3   2.981 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   4.023 ± 0.072   ms/op
ClientGrpc.createUser                     sample  317239   3.023 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.089           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.475           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.170           ms/op
ClientGrpc.existUser                      sample  329283   2.916 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.313           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.134           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.673           ms/op
ClientGrpc.getUser                        sample  317392   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.569           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.167           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.466           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.571           ms/op
ClientGrpc.listUser                       sample  242113   3.965 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.760           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.980           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.857           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.830           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.934           ms/op
