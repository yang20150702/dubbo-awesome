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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 9.048 ops/ms
# Warmup Iteration   3: 10.210 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.542 ±(99.9%) 1.515 ops/ms [Average]
  (min, avg, max) = (10.453, 10.542, 10.617), stdev = 0.083
  CI (99.9%): [9.027, 12.058] (assumes normal distribution)


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
# Warmup Iteration   1: 7.648 ops/ms
# Warmup Iteration   2: 10.958 ops/ms
# Warmup Iteration   3: 11.080 ops/ms
Iteration   1: 11.231 ops/ms
Iteration   2: 11.167 ops/ms
Iteration   3: 11.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.182 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (11.147, 11.182, 11.231), stdev = 0.044
  CI (99.9%): [10.380, 11.984] (assumes normal distribution)


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
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 10.234 ops/ms
# Warmup Iteration   3: 10.502 ops/ms
Iteration   1: 10.778 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.703 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (10.531, 10.703, 10.799), stdev = 0.149
  CI (99.9%): [7.987, 13.418] (assumes normal distribution)


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
# Warmup Iteration   1: 5.779 ops/ms
# Warmup Iteration   2: 8.018 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.313 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.361 ±(99.9%) 1.044 ops/ms [Average]
  (min, avg, max) = (8.313, 8.361, 8.424), stdev = 0.057
  CI (99.9%): [7.317, 9.406] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.025 ms/op
Iteration   2: 2.997 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (2.985, 3.016, 3.066), stdev = 0.044
  CI (99.9%): [2.211, 3.821] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.002 ms/op
Iteration   1: 2.834 ±(99.9%) 0.003 ms/op
Iteration   2: 2.853 ±(99.9%) 0.003 ms/op
Iteration   3: 2.865 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.851 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.834, 2.851, 2.865), stdev = 0.016
  CI (99.9%): [2.559, 3.142] (assumes normal distribution)


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.004 ms/op
Iteration   1: 3.099 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.010, 3.054, 3.099), stdev = 0.044
  CI (99.9%): [2.244, 3.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.024 ms/op
Iteration   1: 3.892 ±(99.9%) 0.014 ms/op
Iteration   2: 3.903 ±(99.9%) 0.016 ms/op
Iteration   3: 3.920 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (3.892, 3.905, 3.920), stdev = 0.014
  CI (99.9%): [3.651, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.008 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.485 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.781 ms/op
                 createUser·p0.9999: 16.508 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.779 ms/op
                 createUser·p0.9999: 15.829 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.538 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.712 ms/op
                 createUser·p0.9999: 21.734 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321925
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29744 
    [ 2.500,  5.000) = 290653 
    [ 5.000,  7.500) = 1179 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     18.850 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 17.630 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.899 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.664 ms/op
                 existUser·p0.9999: 24.871 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.773 ms/op
                 existUser·p0.9999: 18.802 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330632
  mean =      2.902 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44253 
    [ 2.500,  5.000) = 284677 
    [ 5.000,  7.500) = 1377 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     19.954 ms/op
     p(99.9990) =     25.156 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.007 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 13.293 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.098 ms/op
                 getUser·p0.9999: 16.153 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.774 ms/op
                 getUser·p0.9999: 14.909 ms/op
                 getUser·p1.00:   15.270 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319633
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1426 
    [ 1.250,  2.500) = 20065 
    [ 2.500,  3.750) = 283982 
    [ 3.750,  5.000) = 12408 
    [ 5.000,  6.250) = 1000 
    [ 6.250,  7.500) = 415 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     15.568 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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
# Warmup Iteration   1: 5.554 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  12.206 ms/op
                 listUser·p0.9999: 15.189 ms/op
                 listUser·p1.00:   15.663 ms/op

Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.099 ms/op
                 listUser·p0.9999: 23.021 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 3.944 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  21.300 ms/op
                 listUser·p0.9999: 27.388 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246318
  mean =      3.893 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6339 
    [ 2.500,  5.000) = 216953 
    [ 5.000,  7.500) = 21301 
    [ 7.500, 10.000) = 1175 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     26.796 ms/op
     p(99.9990) =     27.676 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.542 ± 1.515  ops/ms
ClientGrpc.existUser                       thrpt       3  11.182 ± 0.802  ops/ms
ClientGrpc.getUser                         thrpt       3  10.703 ± 2.715  ops/ms
ClientGrpc.listUser                        thrpt       3   8.361 ± 1.044  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.805   ms/op
ClientGrpc.existUser                        avgt       3   2.851 ± 0.292   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 0.810   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 0.254   ms/op
ClientGrpc.createUser                     sample  321925   2.980 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.538           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.695           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.741           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.850           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.889           ms/op
ClientGrpc.existUser                      sample  330632   2.902 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.534           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.954           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.264           ms/op
ClientGrpc.getUser                        sample  319633   3.003 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.568           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.384           ms/op
ClientGrpc.listUser                       sample  246318   3.893 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.776           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.796           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
