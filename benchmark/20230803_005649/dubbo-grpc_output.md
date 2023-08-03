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
# Warmup Iteration   1: 4.010 ops/ms
# Warmup Iteration   2: 8.792 ops/ms
# Warmup Iteration   3: 9.665 ops/ms
Iteration   1: 10.512 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.529 ±(99.9%) 0.624 ops/ms [Average]
  (min, avg, max) = (10.506, 10.529, 10.568), stdev = 0.034
  CI (99.9%): [9.904, 11.153] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.556 ops/ms
# Warmup Iteration   2: 10.476 ops/ms
# Warmup Iteration   3: 11.153 ops/ms
Iteration   1: 11.490 ops/ms
Iteration   2: 11.423 ops/ms
Iteration   3: 10.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.244 ±(99.9%) 6.749 ops/ms [Average]
  (min, avg, max) = (10.818, 11.244, 11.490), stdev = 0.370
  CI (99.9%): [4.494, 17.993] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.155 ops/ms
# Warmup Iteration   2: 10.196 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.499 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.507 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (10.423, 10.507, 10.599), stdev = 0.088
  CI (99.9%): [8.903, 12.111] (assumes normal distribution)


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
# Warmup Iteration   1: 5.695 ops/ms
# Warmup Iteration   2: 7.521 ops/ms
# Warmup Iteration   3: 7.742 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.806 ±(99.9%) 0.661 ops/ms [Average]
  (min, avg, max) = (7.768, 7.806, 7.840), stdev = 0.036
  CI (99.9%): [7.144, 8.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.317 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.984, 3.006, 3.027), stdev = 0.022
  CI (99.9%): [2.611, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.003 ms/op
Iteration   1: 2.906 ±(99.9%) 0.002 ms/op
Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
Iteration   3: 2.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.904 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (2.891, 2.904, 2.914), stdev = 0.012
  CI (99.9%): [2.691, 3.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.004 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.049 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (3.008, 3.049, 3.078), stdev = 0.037
  CI (99.9%): [2.376, 3.722] (assumes normal distribution)


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
Iteration   1: 4.120 ±(99.9%) 0.015 ms/op
Iteration   2: 4.038 ±(99.9%) 0.009 ms/op
Iteration   3: 4.036 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.065 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (4.036, 4.065, 4.120), stdev = 0.048
  CI (99.9%): [3.192, 4.937] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.930 ms/op
                 createUser·p0.9999: 18.300 ms/op
                 createUser·p1.00:   18.874 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.008 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.822 ms/op
                 createUser·p0.999:  9.501 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313926
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16477 
    [ 2.500,  5.000) = 295650 
    [ 5.000,  7.500) = 1193 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     21.273 ms/op
     p(99.9990) =     21.721 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.010 ms/op
                 existUser·p0.9999: 13.193 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.448 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.452 ms/op
                 existUser·p0.9999: 15.894 ms/op
                 existUser·p1.00:   16.400 ms/op

Iteration   3: 2.894 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  8.353 ms/op
                 existUser·p0.9999: 19.233 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328391
  mean =      2.921 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2003 
    [ 1.250,  2.500) = 36128 
    [ 2.500,  3.750) = 279369 
    [ 3.750,  5.000) = 9269 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 414 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.258 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     19.544 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.249 ms/op
                 getUser·p0.999:  8.649 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.466 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.265 ms/op
                 getUser·p0.9999: 15.819 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.013 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313245
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22088 
    [ 2.500,  5.000) = 288177 
    [ 5.000,  7.500) = 2412 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.948 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     26.204 ms/op
     p(99.9990) =     27.565 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 5.989 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.011 ms/op
Iteration   1: 4.131 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 21.209 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.121 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  15.173 ms/op
                 listUser·p0.9999: 17.604 ms/op
                 listUser·p1.00:   17.859 ms/op

Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  16.707 ms/op
                 listUser·p0.9999: 27.796 ms/op
                 listUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233690
  mean =      4.106 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2063 
    [ 2.500,  5.000) = 207129 
    [ 5.000,  7.500) = 22577 
    [ 7.500, 10.000) = 1329 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.160 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     27.875 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.529 ± 0.624  ops/ms
ClientGrpc.existUser                       thrpt       3  11.244 ± 6.749  ops/ms
ClientGrpc.getUser                         thrpt       3  10.507 ± 1.604  ops/ms
ClientGrpc.listUser                        thrpt       3   7.806 ± 0.661  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.395   ms/op
ClientGrpc.existUser                        avgt       3   2.904 ± 0.213   ms/op
ClientGrpc.getUser                          avgt       3   3.049 ± 0.673   ms/op
ClientGrpc.listUser                         avgt       3   4.065 ± 0.873   ms/op
ClientGrpc.createUser                     sample  313926   3.059 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.273           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.856           ms/op
ClientGrpc.existUser                      sample  328391   2.921 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.448           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.258           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.727           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  313245   3.062 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.948           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.290           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.204           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  233690   4.106 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.108           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.307           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.160           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.149           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.951           ms/op
