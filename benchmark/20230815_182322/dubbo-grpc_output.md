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
# Warmup Iteration   1: 3.315 ops/ms
# Warmup Iteration   2: 6.675 ops/ms
# Warmup Iteration   3: 8.501 ops/ms
Iteration   1: 8.767 ops/ms
Iteration   2: 8.933 ops/ms
Iteration   3: 8.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.891 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (8.767, 8.891, 8.974), stdev = 0.110
  CI (99.9%): [6.890, 10.893] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.830 ops/ms
# Warmup Iteration   2: 9.518 ops/ms
# Warmup Iteration   3: 9.891 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.595 ops/ms
Iteration   3: 9.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.778 ±(99.9%) 3.594 ops/ms [Average]
  (min, avg, max) = (9.595, 9.778, 9.987), stdev = 0.197
  CI (99.9%): [6.184, 13.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.690 ops/ms
# Warmup Iteration   2: 8.574 ops/ms
# Warmup Iteration   3: 9.319 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.128 ops/ms
Iteration   3: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.223 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (9.128, 9.223, 9.316), stdev = 0.094
  CI (99.9%): [7.506, 10.940] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.050 ops/ms
# Warmup Iteration   2: 6.342 ops/ms
# Warmup Iteration   3: 6.987 ops/ms
Iteration   1: 6.989 ops/ms
Iteration   2: 6.880 ops/ms
Iteration   3: 6.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.894 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (6.813, 6.894, 6.989), stdev = 0.089
  CI (99.9%): [5.274, 8.513] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.276 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
Iteration   1: 3.480 ±(99.9%) 0.005 ms/op
Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
Iteration   3: 3.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.488 ±(99.9%) 0.261 ms/op [Average]
  (min, avg, max) = (3.479, 3.488, 3.505), stdev = 0.014
  CI (99.9%): [3.227, 3.749] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.002 ms/op
Iteration   1: 3.282 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.004 ms/op
Iteration   3: 3.249 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.230 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (3.160, 3.230, 3.282), stdev = 0.064
  CI (99.9%): [2.072, 4.389] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.642 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.003 ms/op
Iteration   1: 3.434 ±(99.9%) 0.004 ms/op
Iteration   2: 3.392 ±(99.9%) 0.004 ms/op
Iteration   3: 3.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.458 ±(99.9%) 1.461 ms/op [Average]
  (min, avg, max) = (3.392, 3.458, 3.547), stdev = 0.080
  CI (99.9%): [1.997, 4.918] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.913 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.013 ms/op
Iteration   1: 4.734 ±(99.9%) 0.009 ms/op
Iteration   2: 4.681 ±(99.9%) 0.006 ms/op
Iteration   3: 4.780 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.732 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (4.681, 4.732, 4.780), stdev = 0.050
  CI (99.9%): [3.825, 5.638] (assumes normal distribution)


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.008 ms/op
Iteration   1: 3.481 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  10.637 ms/op
                 createUser·p0.9999: 14.759 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  13.245 ms/op
                 createUser·p0.9999: 25.844 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.352 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  10.325 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280634
  mean =      3.421 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11208 
    [ 2.500,  5.000) = 264429 
    [ 5.000,  7.500) = 4163 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     10.787 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     27.308 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.007 ms/op
Iteration   1: 3.380 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  8.821 ms/op
                 existUser·p0.9999: 14.312 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  9.067 ms/op
                 existUser·p0.9999: 15.576 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.274 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  8.287 ms/op
                 existUser·p0.9999: 17.906 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 290564
  mean =      3.303 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 540 
    [ 1.250,  2.500) = 12083 
    [ 2.500,  3.750) = 239325 
    [ 3.750,  5.000) = 35760 
    [ 5.000,  6.250) = 1775 
    [ 6.250,  7.500) = 506 
    [ 7.500,  8.750) = 292 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =      8.714 ms/op
     p(99.9900) =     15.871 ms/op
     p(99.9990) =     18.258 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.760 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.009 ms/op
Iteration   1: 3.525 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  9.622 ms/op
                 getUser·p0.9999: 20.180 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.455 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  12.590 ms/op
                 getUser·p0.9999: 14.966 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 3.360 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.413 ms/op
                 getUser·p0.999:  8.810 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 278407
  mean =      3.445 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7605 
    [ 2.500,  5.000) = 266702 
    [ 5.000,  7.500) = 3273 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      9.693 ms/op
     p(99.9900) =     18.978 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 6.045 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.676 ±(99.9%) 0.014 ms/op
Iteration   1: 4.596 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  15.092 ms/op
                 listUser·p0.9999: 22.218 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.655 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 17.965 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.529 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  18.134 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208997
  mean =      4.593 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 435 
    [ 2.500,  5.000) = 169420 
    [ 5.000,  7.500) = 35129 
    [ 7.500, 10.000) = 3345 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.521 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     21.499 ms/op
     p(99.9990) =     22.378 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.891 ± 2.001  ops/ms
ClientGrpc.existUser                       thrpt       3   9.778 ± 3.594  ops/ms
ClientGrpc.getUser                         thrpt       3   9.223 ± 1.717  ops/ms
ClientGrpc.listUser                        thrpt       3   6.894 ± 1.620  ops/ms
ClientGrpc.createUser                       avgt       3   3.488 ± 0.261   ms/op
ClientGrpc.existUser                        avgt       3   3.230 ± 1.159   ms/op
ClientGrpc.getUser                          avgt       3   3.458 ± 1.461   ms/op
ClientGrpc.listUser                         avgt       3   4.732 ± 0.906   ms/op
ClientGrpc.createUser                     sample  280634   3.421 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.890           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.787           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.608           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.492           ms/op
ClientGrpc.existUser                      sample  290564   3.303 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.842           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.084           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.989           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.714           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.871           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  278407   3.445 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.522           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.387           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.350           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.382           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.693           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.978           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.546           ms/op
ClientGrpc.listUser                       sample  208997   4.593 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.200           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.581           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.499           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
