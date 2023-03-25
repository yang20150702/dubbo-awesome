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
# Warmup Iteration   1: 4.697 ops/ms
# Warmup Iteration   2: 9.573 ops/ms
# Warmup Iteration   3: 10.703 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.907 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.676 ±(99.9%) 4.076 ops/ms [Average]
  (min, avg, max) = (10.461, 10.676, 10.907), stdev = 0.223
  CI (99.9%): [6.599, 14.752] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.827 ops/ms
# Warmup Iteration   2: 11.004 ops/ms
# Warmup Iteration   3: 11.290 ops/ms
Iteration   1: 11.179 ops/ms
Iteration   2: 10.991 ops/ms
Iteration   3: 11.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.212 ±(99.9%) 4.367 ops/ms [Average]
  (min, avg, max) = (10.991, 11.212, 11.467), stdev = 0.239
  CI (99.9%): [6.845, 15.580] (assumes normal distribution)


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
# Warmup Iteration   1: 7.782 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.822 ops/ms
Iteration   1: 10.728 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.748 ±(99.9%) 0.339 ops/ms [Average]
  (min, avg, max) = (10.728, 10.748, 10.764), stdev = 0.019
  CI (99.9%): [10.409, 11.087] (assumes normal distribution)


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
# Warmup Iteration   1: 5.929 ops/ms
# Warmup Iteration   2: 8.244 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.429 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (8.312, 8.429, 8.535), stdev = 0.112
  CI (99.9%): [6.392, 10.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 2.975 ±(99.9%) 0.002 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.980 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (2.967, 2.980, 2.997), stdev = 0.016
  CI (99.9%): [2.690, 3.269] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.002 ms/op
Iteration   2: 2.840 ±(99.9%) 0.003 ms/op
Iteration   3: 2.833 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.835 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.832, 2.835, 2.840), stdev = 0.005
  CI (99.9%): [2.750, 2.920] (assumes normal distribution)


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
# Warmup Iteration   1: 3.613 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 2.944 ±(99.9%) 0.004 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.977 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (2.944, 2.977, 3.022), stdev = 0.040
  CI (99.9%): [2.242, 3.711] (assumes normal distribution)


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
# Warmup Iteration   1: 4.440 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.017 ms/op
Iteration   1: 3.867 ±(99.9%) 0.021 ms/op
Iteration   2: 3.810 ±(99.9%) 0.016 ms/op
Iteration   3: 3.843 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.840 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.810, 3.840, 3.867), stdev = 0.029
  CI (99.9%): [3.313, 4.367] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  8.314 ms/op
                 createUser·p0.9999: 16.482 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 12.534 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.933 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.128 ms/op
                 createUser·p0.9999: 16.418 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326944
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2859 
    [ 1.250,  2.500) = 31874 
    [ 2.500,  3.750) = 279766 
    [ 3.750,  5.000) = 11174 
    [ 5.000,  6.250) = 670 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.660 ms/op
     p(99.9900) =     16.318 ms/op
     p(99.9990) =     16.703 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.005 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  6.089 ms/op
                 existUser·p0.9999: 19.431 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   4.163 ms/op
                 existUser·p0.999:  9.289 ms/op
                 existUser·p0.9999: 11.977 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   3: 2.801 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  5.882 ms/op
                 existUser·p0.9999: 18.645 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336101
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2137 
    [ 1.250,  2.500) = 38681 
    [ 2.500,  3.750) = 289707 
    [ 3.750,  5.000) = 4838 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      4.088 ms/op
     p(99.9000) =      6.356 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 3.623 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.673 ms/op
                 getUser·p0.9999: 12.105 ms/op
                 getUser·p1.00:   12.435 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  10.786 ms/op
                 getUser·p0.9999: 17.343 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  6.128 ms/op
                 getUser·p0.9999: 14.052 ms/op
                 getUser·p1.00:   14.549 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322878
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1230 
    [ 1.250,  2.500) = 23158 
    [ 2.500,  3.750) = 286215 
    [ 3.750,  5.000) = 11280 
    [ 5.000,  6.250) = 546 
    [ 6.250,  7.500) = 194 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.677 ms/op
     p(99.9900) =     16.390 ms/op
     p(99.9990) =     17.556 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 5.286 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.963 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.010 ms/op
Iteration   1: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.291 ms/op
                 listUser·p0.9999: 15.214 ms/op
                 listUser·p1.00:   15.712 ms/op

Iteration   2: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  13.798 ms/op
                 listUser·p0.9999: 18.768 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.066 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  14.876 ms/op
                 listUser·p0.9999: 20.990 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250820
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3529 
    [ 2.500,  5.000) = 231388 
    [ 5.000,  7.500) = 14947 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     20.510 ms/op
     p(99.9990) =     21.379 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.676 ± 4.076  ops/ms
ClientGrpc.existUser                       thrpt       3  11.212 ± 4.367  ops/ms
ClientGrpc.getUser                         thrpt       3  10.748 ± 0.339  ops/ms
ClientGrpc.listUser                        thrpt       3   8.429 ± 2.038  ops/ms
ClientGrpc.createUser                       avgt       3   2.980 ± 0.289   ms/op
ClientGrpc.existUser                        avgt       3   2.835 ± 0.085   ms/op
ClientGrpc.getUser                          avgt       3   2.977 ± 0.734   ms/op
ClientGrpc.listUser                         avgt       3   3.840 ± 0.527   ms/op
ClientGrpc.createUser                     sample  326944   2.935 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.587           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.666           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.660           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.318           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.777           ms/op
ClientGrpc.existUser                      sample  336101   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.356           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.711           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  322878   2.970 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.673           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.677           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.390           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.629           ms/op
ClientGrpc.listUser                       sample  250820   3.824 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.871           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.707           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.561           ms/op
