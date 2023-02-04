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
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 5.962 ops/ms
# Warmup Iteration   3: 6.961 ops/ms
Iteration   1: 7.094 ops/ms
Iteration   2: 7.172 ops/ms
Iteration   3: 7.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.107 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (7.055, 7.107, 7.172), stdev = 0.060
  CI (99.9%): [6.012, 8.201] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.126 ops/ms
# Warmup Iteration   2: 7.047 ops/ms
# Warmup Iteration   3: 7.453 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 8.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.919 ±(99.9%) 3.576 ops/ms [Average]
  (min, avg, max) = (7.732, 7.919, 8.123), stdev = 0.196
  CI (99.9%): [4.343, 11.495] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.619 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 7.478 ops/ms
Iteration   1: 7.545 ops/ms
Iteration   2: 7.477 ops/ms
Iteration   3: 7.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.514 ±(99.9%) 0.625 ops/ms [Average]
  (min, avg, max) = (7.477, 7.514, 7.545), stdev = 0.034
  CI (99.9%): [6.889, 8.139] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ops/ms
# Warmup Iteration   2: 5.078 ops/ms
# Warmup Iteration   3: 5.725 ops/ms
Iteration   1: 5.820 ops/ms
Iteration   2: 5.992 ops/ms
Iteration   3: 6.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.940 ±(99.9%) 1.905 ops/ms [Average]
  (min, avg, max) = (5.820, 5.940, 6.009), stdev = 0.104
  CI (99.9%): [4.035, 7.845] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.172 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.009 ms/op
Iteration   1: 4.264 ±(99.9%) 0.003 ms/op
Iteration   2: 4.351 ±(99.9%) 0.003 ms/op
Iteration   3: 4.122 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.246 ±(99.9%) 2.116 ms/op [Average]
  (min, avg, max) = (4.122, 4.246, 4.351), stdev = 0.116
  CI (99.9%): [2.129, 6.362] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.802 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.004 ms/op
Iteration   1: 4.230 ±(99.9%) 0.003 ms/op
Iteration   2: 4.094 ±(99.9%) 0.003 ms/op
Iteration   3: 4.156 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.160 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (4.094, 4.160, 4.230), stdev = 0.068
  CI (99.9%): [2.916, 5.404] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.335 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.006 ms/op
Iteration   1: 4.298 ±(99.9%) 0.003 ms/op
Iteration   2: 4.232 ±(99.9%) 0.003 ms/op
Iteration   3: 4.226 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.252 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (4.226, 4.252, 4.298), stdev = 0.040
  CI (99.9%): [3.527, 4.978] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.069 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.664 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.017 ms/op
Iteration   1: 5.303 ±(99.9%) 0.012 ms/op
Iteration   2: 5.322 ±(99.9%) 0.016 ms/op
Iteration   3: 5.287 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.304 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (5.287, 5.304, 5.322), stdev = 0.017
  CI (99.9%): [4.988, 5.621] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.991 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.014 ms/op
Iteration   1: 4.177 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.827 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 16.018 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 4.343 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  10.716 ms/op
                 createUser·p0.9999: 20.170 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 4.472 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   4.334 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.169 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  17.598 ms/op
                 createUser·p0.9999: 31.719 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221721
  mean =      4.327 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3091 
    [ 2.500,  5.000) = 172194 
    [ 5.000,  7.500) = 44125 
    [ 7.500, 10.000) = 1924 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     11.478 ms/op
     p(99.9900) =     31.222 ms/op
     p(99.9990) =     31.902 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 5.362 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.014 ms/op
Iteration   1: 3.991 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   5.112 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.626 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 17.497 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 4.061 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.961 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  11.280 ms/op
                 existUser·p0.9999: 17.183 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   3: 4.094 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   4.026 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  11.871 ms/op
                 existUser·p0.9999: 23.046 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236968
  mean =      4.048 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9791 
    [ 2.500,  5.000) = 193611 
    [ 5.000,  7.500) = 31483 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     21.866 ms/op
     p(99.9990) =     23.824 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 6.026 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.013 ms/op
Iteration   1: 4.247 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  11.823 ms/op
                 getUser·p0.9999: 22.544 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 4.355 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.276 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.021 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  11.018 ms/op
                 getUser·p0.9999: 19.748 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   3: 4.244 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  14.942 ms/op
                 getUser·p0.9999: 23.608 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224276
  mean =      4.281 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5897 
    [ 2.500,  5.000) = 171528 
    [ 5.000,  7.500) = 44929 
    [ 7.500, 10.000) = 1411 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     13.168 ms/op
     p(99.9900) =     23.120 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 8.036 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.773 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.377 ±(99.9%) 0.019 ms/op
Iteration   1: 5.340 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  20.979 ms/op
                 listUser·p0.9999: 27.820 ms/op
                 listUser·p1.00:   28.377 ms/op

Iteration   2: 5.193 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  20.228 ms/op
                 listUser·p0.9999: 22.877 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 5.554 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.748 ms/op
                 listUser·p0.999:  26.608 ms/op
                 listUser·p0.9999: 55.342 ms/op
                 listUser·p1.00:   55.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179343
  mean =      5.359 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 82232 
    [ 5.000, 10.000) = 95220 
    [10.000, 15.000) = 1554 
    [15.000, 20.000) = 95 
    [20.000, 25.000) = 131 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 9 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     21.452 ms/op
     p(99.9900) =     53.630 ms/op
     p(99.9990) =     55.771 ms/op
     p(99.9999) =     55.771 ms/op
    p(100.0000) =     55.771 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.107 ± 1.094  ops/ms
ClientGrpc.existUser                       thrpt       3   7.919 ± 3.576  ops/ms
ClientGrpc.getUser                         thrpt       3   7.514 ± 0.625  ops/ms
ClientGrpc.listUser                        thrpt       3   5.940 ± 1.905  ops/ms
ClientGrpc.createUser                       avgt       3   4.246 ± 2.116   ms/op
ClientGrpc.existUser                        avgt       3   4.160 ± 1.244   ms/op
ClientGrpc.getUser                          avgt       3   4.252 ± 0.725   ms/op
ClientGrpc.listUser                         avgt       3   5.304 ± 0.317   ms/op
ClientGrpc.createUser                     sample  221721   4.327 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.727           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.561           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.478           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.222           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.949           ms/op
ClientGrpc.existUser                      sample  236968   4.048 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.842           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.636           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.616           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.866           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.084           ms/op
ClientGrpc.getUser                        sample  224276   4.281 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.057           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.489           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.168           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.120           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.019           ms/op
ClientGrpc.listUser                       sample  179343   5.359 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.237           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.452           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          53.630           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          55.771           ms/op
