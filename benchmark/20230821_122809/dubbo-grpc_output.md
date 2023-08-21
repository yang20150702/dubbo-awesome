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
# Warmup Iteration   1: 2.033 ops/ms
# Warmup Iteration   2: 4.816 ops/ms
# Warmup Iteration   3: 6.379 ops/ms
Iteration   1: 6.413 ops/ms
Iteration   2: 6.916 ops/ms
Iteration   3: 7.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.798 ±(99.9%) 6.240 ops/ms [Average]
  (min, avg, max) = (6.413, 6.798, 7.066), stdev = 0.342
  CI (99.9%): [0.559, 13.038] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.367 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 7.605 ops/ms
Iteration   1: 7.699 ops/ms
Iteration   2: 7.751 ops/ms
Iteration   3: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.794 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (7.699, 7.794, 7.933), stdev = 0.123
  CI (99.9%): [5.553, 10.036] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ops/ms
# Warmup Iteration   2: 6.782 ops/ms
# Warmup Iteration   3: 6.762 ops/ms
Iteration   1: 7.452 ops/ms
Iteration   2: 7.711 ops/ms
Iteration   3: 7.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.508 ±(99.9%) 3.331 ops/ms [Average]
  (min, avg, max) = (7.359, 7.508, 7.711), stdev = 0.183
  CI (99.9%): [4.176, 10.839] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 5.057 ops/ms
# Warmup Iteration   3: 5.506 ops/ms
Iteration   1: 5.499 ops/ms
Iteration   2: 5.328 ops/ms
Iteration   3: 5.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.440 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (5.328, 5.440, 5.499), stdev = 0.097
  CI (99.9%): [3.670, 7.210] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.944 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.856 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.013 ms/op
Iteration   1: 4.324 ±(99.9%) 0.004 ms/op
Iteration   2: 4.464 ±(99.9%) 0.004 ms/op
Iteration   3: 4.351 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.380 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (4.324, 4.380, 4.464), stdev = 0.074
  CI (99.9%): [3.024, 5.736] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.658 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.004 ms/op
Iteration   1: 3.947 ±(99.9%) 0.004 ms/op
Iteration   2: 4.080 ±(99.9%) 0.002 ms/op
Iteration   3: 4.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.009 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.947, 4.009, 4.080), stdev = 0.067
  CI (99.9%): [2.787, 5.230] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.872 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.404 ±(99.9%) 0.014 ms/op
Iteration   1: 4.262 ±(99.9%) 0.003 ms/op
Iteration   2: 4.151 ±(99.9%) 0.005 ms/op
Iteration   3: 4.378 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.264 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (4.151, 4.264, 4.378), stdev = 0.113
  CI (99.9%): [2.194, 6.334] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.963 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.013 ms/op
Iteration   1: 5.594 ±(99.9%) 0.016 ms/op
Iteration   2: 5.925 ±(99.9%) 0.018 ms/op
Iteration   3: 5.890 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.803 ±(99.9%) 3.318 ms/op [Average]
  (min, avg, max) = (5.594, 5.803, 5.925), stdev = 0.182
  CI (99.9%): [2.484, 9.121] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.687 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.431 ±(99.9%) 0.017 ms/op
Iteration   1: 4.219 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  13.295 ms/op
                 createUser·p0.9999: 17.427 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 4.173 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  15.118 ms/op
                 createUser·p0.9999: 22.588 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.376 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  12.691 ms/op
                 createUser·p0.9999: 25.092 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228793
  mean =      4.195 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9609 
    [ 2.500,  5.000) = 183673 
    [ 5.000,  7.500) = 31077 
    [ 7.500, 10.000) = 3033 
    [10.000, 12.500) = 1018 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     23.466 ms/op
     p(99.9990) =     25.489 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.099 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.013 ms/op
Iteration   1: 4.032 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 25.397 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 4.220 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   4.057 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.849 ms/op
                 existUser·p0.99:   8.983 ms/op
                 existUser·p0.999:  14.287 ms/op
                 existUser·p0.9999: 20.259 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  12.093 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236603
  mean =      4.060 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9727 
    [ 2.500,  5.000) = 196753 
    [ 5.000,  7.500) = 26617 
    [ 7.500, 10.000) = 2551 
    [10.000, 12.500) = 670 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.307 ms/op
     p(99.9000) =     12.770 ms/op
     p(99.9900) =     24.489 ms/op
     p(99.9990) =     25.645 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.802 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.014 ms/op
Iteration   1: 4.480 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   6.382 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  13.200 ms/op
                 getUser·p0.9999: 17.811 ms/op
                 getUser·p1.00:   18.383 ms/op

Iteration   2: 4.031 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  17.361 ms/op
                 getUser·p0.9999: 26.710 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 4.054 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 22.131 ms/op
                 getUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229801
  mean =      4.179 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11961 
    [ 2.500,  5.000) = 179905 
    [ 5.000,  7.500) = 34240 
    [ 7.500, 10.000) = 2633 
    [10.000, 12.500) = 713 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     14.208 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.563 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.830 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.665 ±(99.9%) 0.022 ms/op
Iteration   1: 5.871 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.314 ms/op
                 listUser·p0.999:  19.283 ms/op
                 listUser·p0.9999: 21.415 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 5.702 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   5.308 ms/op
                 listUser·p0.90:   7.736 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  20.533 ms/op
                 listUser·p0.9999: 32.391 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   3: 5.562 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.495 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   12.003 ms/op
                 listUser·p0.999:  21.675 ms/op
                 listUser·p0.9999: 27.263 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168208
  mean =      5.709 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 230 
    [ 2.500,  5.000) = 64199 
    [ 5.000,  7.500) = 84003 
    [ 7.500, 10.000) = 15268 
    [10.000, 12.500) = 3192 
    [12.500, 15.000) = 778 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.758 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     31.573 ms/op
     p(99.9990) =     32.975 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.798 ± 6.240  ops/ms
ClientGrpc.existUser                       thrpt       3   7.794 ± 2.241  ops/ms
ClientGrpc.getUser                         thrpt       3   7.508 ± 3.331  ops/ms
ClientGrpc.listUser                        thrpt       3   5.440 ± 1.770  ops/ms
ClientGrpc.createUser                       avgt       3   4.380 ± 1.356   ms/op
ClientGrpc.existUser                        avgt       3   4.009 ± 1.221   ms/op
ClientGrpc.getUser                          avgt       3   4.264 ± 2.070   ms/op
ClientGrpc.listUser                         avgt       3   5.803 ± 3.318   ms/op
ClientGrpc.createUser                     sample  228793   4.195 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.933           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.423           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.700           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.008           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.466           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.625           ms/op
ClientGrpc.existUser                      sample  236603   4.060 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.778           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.865           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.307           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.770           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.489           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.887           ms/op
ClientGrpc.getUser                        sample  229801   4.179 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.872           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.087           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.339           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.952           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.296           ms/op
ClientGrpc.listUser                       sample  168208   5.709 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.758           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.911           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.120           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.997           ms/op
