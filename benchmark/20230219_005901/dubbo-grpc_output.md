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
# Warmup Iteration   1: 4.746 ops/ms
# Warmup Iteration   2: 9.679 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.314 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.564 ±(99.9%) 5.554 ops/ms [Average]
  (min, avg, max) = (10.314, 10.564, 10.903), stdev = 0.304
  CI (99.9%): [5.010, 16.118] (assumes normal distribution)


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
# Warmup Iteration   1: 7.948 ops/ms
# Warmup Iteration   2: 10.838 ops/ms
# Warmup Iteration   3: 11.079 ops/ms
Iteration   1: 11.119 ops/ms
Iteration   2: 10.920 ops/ms
Iteration   3: 10.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.986 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (10.919, 10.986, 11.119), stdev = 0.115
  CI (99.9%): [8.886, 13.086] (assumes normal distribution)


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
# Warmup Iteration   1: 7.423 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.434 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (10.340, 10.434, 10.490), stdev = 0.082
  CI (99.9%): [8.940, 11.928] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.059 ops/ms
# Warmup Iteration   2: 7.861 ops/ms
# Warmup Iteration   3: 8.145 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.030 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.162 ±(99.9%) 2.680 ops/ms [Average]
  (min, avg, max) = (8.030, 8.162, 8.320), stdev = 0.147
  CI (99.9%): [5.481, 10.842] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.002 ms/op
Iteration   1: 3.144 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.001 ms/op
Iteration   3: 3.140 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.149 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.140, 3.149, 3.163), stdev = 0.012
  CI (99.9%): [2.923, 3.374] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.965 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (2.919, 2.965, 2.989), stdev = 0.040
  CI (99.9%): [2.244, 3.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.047 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.002 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.067, 3.085, 3.099), stdev = 0.016
  CI (99.9%): [2.785, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.019 ms/op
Iteration   1: 3.931 ±(99.9%) 0.041 ms/op
Iteration   2: 4.052 ±(99.9%) 0.016 ms/op
Iteration   3: 3.808 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (3.808, 3.930, 4.052), stdev = 0.122
  CI (99.9%): [1.703, 6.158] (assumes normal distribution)


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.062 ms/op
                 createUser·p0.9999: 15.721 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.791 ms/op
                 createUser·p0.9999: 21.349 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.291 ms/op
                 createUser·p0.9999: 29.819 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309382
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30444 
    [ 2.500,  5.000) = 277716 
    [ 5.000,  7.500) = 892 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.692 ms/op
     p(99.9900) =     28.051 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 3.607 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
Iteration   1: 2.954 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.172 ms/op
                 existUser·p0.999:  7.598 ms/op
                 existUser·p0.9999: 18.100 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.139 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.612 ms/op
                 existUser·p0.9999: 15.287 ms/op
                 existUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323566
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2343 
    [ 1.250,  2.500) = 48001 
    [ 2.500,  3.750) = 253566 
    [ 3.750,  5.000) = 18814 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 176 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.032 ms/op
     p(99.9900) =     17.323 ms/op
     p(99.9990) =     18.367 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  5.795 ms/op
                 getUser·p0.9999: 11.888 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  5.895 ms/op
                 getUser·p0.9999: 14.244 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  7.771 ms/op
                 getUser·p0.9999: 15.770 ms/op
                 getUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314782
  mean =      3.049 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1657 
    [ 1.250,  2.500) = 28705 
    [ 2.500,  3.750) = 260079 
    [ 3.750,  5.000) = 23561 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.342 ms/op
     p(99.9900) =     15.000 ms/op
     p(99.9990) =     15.888 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.010 ms/op
Iteration   1: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 18.516 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.637 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.810 ms/op
                 listUser·p0.9999: 22.439 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 23.254 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243133
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4924 
    [ 2.500,  5.000) = 211566 
    [ 5.000,  7.500) = 25440 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.793 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.481 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.564 ± 5.554  ops/ms
ClientGrpc.existUser                       thrpt       3  10.986 ± 2.100  ops/ms
ClientGrpc.getUser                         thrpt       3  10.434 ± 1.494  ops/ms
ClientGrpc.listUser                        thrpt       3   8.162 ± 2.680  ops/ms
ClientGrpc.createUser                       avgt       3   3.149 ± 0.226   ms/op
ClientGrpc.existUser                        avgt       3   2.965 ± 0.721   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.301   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 2.228   ms/op
ClientGrpc.createUser                     sample  309382   3.103 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.397           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.692           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.051           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.179           ms/op
ClientGrpc.existUser                      sample  323566   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.530           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.032           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.323           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  314782   3.049 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.551           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.342           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.000           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.974           ms/op
ClientGrpc.listUser                       sample  243133   3.947 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.637           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.793           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
