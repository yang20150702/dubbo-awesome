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
# Warmup Iteration   1: 2.456 ops/ms
# Warmup Iteration   2: 5.837 ops/ms
# Warmup Iteration   3: 7.279 ops/ms
Iteration   1: 7.537 ops/ms
Iteration   2: 7.718 ops/ms
Iteration   3: 7.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.623 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (7.537, 7.623, 7.718), stdev = 0.091
  CI (99.9%): [5.962, 9.285] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.106 ops/ms
# Warmup Iteration   2: 7.506 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.074 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (7.902, 8.074, 8.222), stdev = 0.162
  CI (99.9%): [5.127, 11.021] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ops/ms
# Warmup Iteration   2: 6.975 ops/ms
# Warmup Iteration   3: 7.428 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 7.775 ops/ms
Iteration   3: 7.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.725 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (7.646, 7.725, 7.775), stdev = 0.069
  CI (99.9%): [6.460, 8.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.524 ops/ms
# Warmup Iteration   2: 5.504 ops/ms
# Warmup Iteration   3: 5.946 ops/ms
Iteration   1: 5.943 ops/ms
Iteration   2: 6.135 ops/ms
Iteration   3: 6.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.028 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (5.943, 6.028, 6.135), stdev = 0.098
  CI (99.9%): [4.245, 7.812] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.640 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.004 ms/op
Iteration   1: 4.065 ±(99.9%) 0.004 ms/op
Iteration   2: 4.218 ±(99.9%) 0.003 ms/op
Iteration   3: 4.250 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.177 ±(99.9%) 1.807 ms/op [Average]
  (min, avg, max) = (4.065, 4.177, 4.250), stdev = 0.099
  CI (99.9%): [2.371, 5.984] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.237 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.008 ms/op
Iteration   1: 4.010 ±(99.9%) 0.004 ms/op
Iteration   2: 4.051 ±(99.9%) 0.003 ms/op
Iteration   3: 3.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.005 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (3.955, 4.005, 4.051), stdev = 0.048
  CI (99.9%): [3.122, 4.888] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.227 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.422 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.003 ms/op
Iteration   1: 4.117 ±(99.9%) 0.003 ms/op
Iteration   2: 4.290 ±(99.9%) 0.003 ms/op
Iteration   3: 4.087 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.165 ±(99.9%) 1.993 ms/op [Average]
  (min, avg, max) = (4.087, 4.165, 4.290), stdev = 0.109
  CI (99.9%): [2.171, 6.158] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.590 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.698 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.014 ms/op
Iteration   1: 5.298 ±(99.9%) 0.010 ms/op
Iteration   2: 5.304 ±(99.9%) 0.019 ms/op
Iteration   3: 5.085 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.229 ±(99.9%) 2.270 ms/op [Average]
  (min, avg, max) = (5.085, 5.229, 5.304), stdev = 0.124
  CI (99.9%): [2.959, 7.499] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.389 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.375 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.014 ms/op
Iteration   1: 4.162 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  11.384 ms/op
                 createUser·p0.9999: 16.555 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   2: 4.153 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   7.813 ms/op
                 createUser·p0.999:  15.515 ms/op
                 createUser·p0.9999: 26.903 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 4.243 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.162 ms/op
                 createUser·p0.999:  12.515 ms/op
                 createUser·p0.9999: 19.132 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 229235
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4578 
    [ 2.500,  5.000) = 192306 
    [ 5.000,  7.500) = 29994 
    [ 7.500, 10.000) = 1866 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     13.382 ms/op
     p(99.9900) =     21.236 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.794 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.012 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  14.548 ms/op
                 existUser·p0.9999: 16.037 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 21.784 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.968 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.940 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  14.532 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243331
  mean =      3.943 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7743 
    [ 2.500,  5.000) = 213613 
    [ 5.000,  7.500) = 20000 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.083 ms/op
     p(99.9000) =     13.872 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.448 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.550 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.013 ms/op
Iteration   1: 4.192 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  13.582 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 4.154 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.827 ms/op
                 getUser·p0.999:  9.537 ms/op
                 getUser·p0.9999: 22.554 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 4.148 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.046 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  11.140 ms/op
                 getUser·p0.9999: 22.985 ms/op
                 getUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230455
  mean =      4.164 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4049 
    [ 2.500,  5.000) = 198427 
    [ 5.000,  7.500) = 26399 
    [ 7.500, 10.000) = 1168 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.926 ms/op
     p(99.9000) =     11.470 ms/op
     p(99.9900) =     22.707 ms/op
     p(99.9990) =     29.842 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.074 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.137 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.451 ±(99.9%) 0.021 ms/op
Iteration   1: 5.446 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  17.699 ms/op
                 listUser·p0.9999: 19.173 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 5.444 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.143 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  21.480 ms/op
                 listUser·p0.9999: 28.267 ms/op
                 listUser·p1.00:   32.014 ms/op

Iteration   3: 5.456 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  20.611 ms/op
                 listUser·p0.9999: 25.993 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176329
  mean =      5.449 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 74681 
    [ 5.000,  7.500) = 87562 
    [ 7.500, 10.000) = 11841 
    [10.000, 12.500) = 1433 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     31.964 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.623 ± 1.662  ops/ms
ClientGrpc.existUser                       thrpt       3   8.074 ± 2.947  ops/ms
ClientGrpc.getUser                         thrpt       3   7.725 ± 1.265  ops/ms
ClientGrpc.listUser                        thrpt       3   6.028 ± 1.783  ops/ms
ClientGrpc.createUser                       avgt       3   4.177 ± 1.807   ms/op
ClientGrpc.existUser                        avgt       3   4.005 ± 0.883   ms/op
ClientGrpc.getUser                          avgt       3   4.165 ± 1.993   ms/op
ClientGrpc.listUser                         avgt       3   5.229 ± 2.270   ms/op
ClientGrpc.createUser                     sample  229235   4.185 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.879           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.210           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.553           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.382           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.236           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.903           ms/op
ClientGrpc.existUser                      sample  243331   3.943 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.773           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.932           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.083           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.872           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.856           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.347           ms/op
ClientGrpc.getUser                        sample  230455   4.164 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.092           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.112           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.521           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.926           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.470           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.707           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.983           ms/op
ClientGrpc.listUser                       sample  176329   5.449 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.273           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.014           ms/op
