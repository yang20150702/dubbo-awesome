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
# Warmup Iteration   1: 4.125 ops/ms
# Warmup Iteration   2: 8.355 ops/ms
# Warmup Iteration   3: 9.606 ops/ms
Iteration   1: 10.370 ops/ms
Iteration   2: 9.772 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.991 ±(99.9%) 6.011 ops/ms [Average]
  (min, avg, max) = (9.772, 9.991, 10.370), stdev = 0.329
  CI (99.9%): [3.980, 16.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.218 ops/ms
# Warmup Iteration   2: 10.014 ops/ms
# Warmup Iteration   3: 10.572 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.643 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (10.440, 10.643, 10.806), stdev = 0.186
  CI (99.9%): [7.248, 14.038] (assumes normal distribution)


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
# Warmup Iteration   1: 6.353 ops/ms
# Warmup Iteration   2: 9.724 ops/ms
# Warmup Iteration   3: 10.190 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 10.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.085 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (10.013, 10.085, 10.199), stdev = 0.100
  CI (99.9%): [8.253, 11.916] (assumes normal distribution)


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
# Warmup Iteration   1: 5.432 ops/ms
# Warmup Iteration   2: 7.499 ops/ms
# Warmup Iteration   3: 7.954 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 8.214 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.164 ±(99.9%) 2.270 ops/ms [Average]
  (min, avg, max) = (8.022, 8.164, 8.255), stdev = 0.124
  CI (99.9%): [5.894, 10.434] (assumes normal distribution)


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
# Warmup Iteration   1: 4.460 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.343 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.249 ±(99.9%) 0.006 ms/op
Iteration   1: 3.139 ±(99.9%) 0.002 ms/op
Iteration   2: 3.129 ±(99.9%) 0.001 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.152 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (3.129, 3.152, 3.188), stdev = 0.031
  CI (99.9%): [2.580, 3.724] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.001 ms/op
Iteration   1: 2.985 ±(99.9%) 0.001 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.017 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (2.985, 3.017, 3.056), stdev = 0.036
  CI (99.9%): [2.361, 3.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.003 ms/op
Iteration   1: 3.217 ±(99.9%) 0.003 ms/op
Iteration   2: 3.165 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.184 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.165, 3.184, 3.217), stdev = 0.029
  CI (99.9%): [2.654, 3.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.376 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.022 ms/op
Iteration   1: 3.921 ±(99.9%) 0.009 ms/op
Iteration   2: 3.932 ±(99.9%) 0.014 ms/op
Iteration   3: 3.940 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.921, 3.931, 3.940), stdev = 0.010
  CI (99.9%): [3.754, 4.108] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  8.453 ms/op
                 createUser·p0.9999: 22.950 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  8.164 ms/op
                 createUser·p0.9999: 26.397 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.187 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  11.817 ms/op
                 createUser·p0.9999: 29.818 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305633
  mean =      3.139 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15362 
    [ 2.500,  5.000) = 287496 
    [ 5.000,  7.500) = 2180 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     29.276 ms/op
     p(99.9990) =     30.501 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.295 ms/op
                 existUser·p0.9999: 13.011 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.485 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  10.706 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317183
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 425 
    [ 1.250,  2.500) = 23349 
    [ 2.500,  3.750) = 276987 
    [ 3.750,  5.000) = 14796 
    [ 5.000,  6.250) = 817 
    [ 6.250,  7.500) = 356 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.474 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     14.731 ms/op
     p(99.9990) =     16.509 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.272 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 20.180 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  8.503 ms/op
                 getUser·p0.9999: 19.595 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.585 ms/op
                 getUser·p0.9999: 28.741 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303836
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17088 
    [ 2.500,  5.000) = 283816 
    [ 5.000,  7.500) = 2385 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.272 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.973 ms/op
     p(99.9000) =      8.604 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     29.673 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 5.580 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.162 ms/op
                 listUser·p0.9999: 19.383 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   7.166 ms/op
                 listUser·p0.999:  16.348 ms/op
                 listUser·p0.9999: 18.314 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.968 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 23.806 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243496
  mean =      3.941 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2009 
    [ 2.500,  5.000) = 220507 
    [ 5.000,  7.500) = 19119 
    [ 7.500, 10.000) = 1294 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.081 ms/op
     p(99.9900) =     22.795 ms/op
     p(99.9990) =     24.285 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.991 ± 6.011  ops/ms
ClientGrpc.existUser                       thrpt       3  10.643 ± 3.395  ops/ms
ClientGrpc.getUser                         thrpt       3  10.085 ± 1.832  ops/ms
ClientGrpc.listUser                        thrpt       3   8.164 ± 2.270  ops/ms
ClientGrpc.createUser                       avgt       3   3.152 ± 0.572   ms/op
ClientGrpc.existUser                        avgt       3   3.017 ± 0.656   ms/op
ClientGrpc.getUser                          avgt       3   3.184 ± 0.529   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.177   ms/op
ClientGrpc.createUser                     sample  305633   3.139 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.273           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.276           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.178           ms/op
ClientGrpc.existUser                      sample  317183   3.026 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.474           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.618           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.731           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.630           ms/op
ClientGrpc.getUser                        sample  303836   3.158 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.272           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.039           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.604           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.361           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.852           ms/op
ClientGrpc.listUser                       sample  243496   3.941 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.894           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.081           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.795           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.445           ms/op
