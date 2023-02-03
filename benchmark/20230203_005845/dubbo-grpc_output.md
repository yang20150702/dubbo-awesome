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
# Warmup Iteration   1: 2.377 ops/ms
# Warmup Iteration   2: 6.005 ops/ms
# Warmup Iteration   3: 7.118 ops/ms
Iteration   1: 7.272 ops/ms
Iteration   2: 7.491 ops/ms
Iteration   3: 7.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.307 ±(99.9%) 3.088 ops/ms [Average]
  (min, avg, max) = (7.158, 7.307, 7.491), stdev = 0.169
  CI (99.9%): [4.219, 10.395] (assumes normal distribution)


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
# Warmup Iteration   1: 4.756 ops/ms
# Warmup Iteration   2: 7.214 ops/ms
# Warmup Iteration   3: 7.484 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 7.929 ops/ms
Iteration   3: 8.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.940 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (7.876, 7.940, 8.015), stdev = 0.070
  CI (99.9%): [6.662, 9.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.467 ops/ms
# Warmup Iteration   2: 7.378 ops/ms
# Warmup Iteration   3: 7.210 ops/ms
Iteration   1: 7.370 ops/ms
Iteration   2: 7.404 ops/ms
Iteration   3: 7.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.333 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (7.226, 7.333, 7.404), stdev = 0.094
  CI (99.9%): [5.616, 9.051] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ops/ms
# Warmup Iteration   2: 5.347 ops/ms
# Warmup Iteration   3: 5.859 ops/ms
Iteration   1: 6.032 ops/ms
Iteration   2: 6.099 ops/ms
Iteration   3: 6.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.125 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (6.032, 6.125, 6.242), stdev = 0.107
  CI (99.9%): [4.166, 8.084] (assumes normal distribution)


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
# Warmup Iteration   1: 6.153 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.003 ms/op
Iteration   1: 4.484 ±(99.9%) 0.003 ms/op
Iteration   2: 4.623 ±(99.9%) 0.003 ms/op
Iteration   3: 4.370 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.493 ±(99.9%) 2.311 ms/op [Average]
  (min, avg, max) = (4.370, 4.493, 4.623), stdev = 0.127
  CI (99.9%): [2.182, 6.803] (assumes normal distribution)


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
# Warmup Iteration   1: 6.232 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.007 ms/op
Iteration   1: 4.179 ±(99.9%) 0.003 ms/op
Iteration   2: 4.180 ±(99.9%) 0.002 ms/op
Iteration   3: 4.155 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.172 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (4.155, 4.172, 4.180), stdev = 0.014
  CI (99.9%): [3.913, 4.430] (assumes normal distribution)


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
# Warmup Iteration   1: 6.420 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.358 ±(99.9%) 0.004 ms/op
Iteration   1: 4.403 ±(99.9%) 0.002 ms/op
Iteration   2: 4.221 ±(99.9%) 0.003 ms/op
Iteration   3: 4.349 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.324 ±(99.9%) 1.707 ms/op [Average]
  (min, avg, max) = (4.221, 4.324, 4.403), stdev = 0.094
  CI (99.9%): [2.618, 6.031] (assumes normal distribution)


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
# Warmup Iteration   1: 7.342 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.464 ±(99.9%) 0.017 ms/op
Iteration   1: 5.299 ±(99.9%) 0.013 ms/op
Iteration   2: 5.145 ±(99.9%) 0.010 ms/op
Iteration   3: 5.009 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.151 ±(99.9%) 2.645 ms/op [Average]
  (min, avg, max) = (5.009, 5.151, 5.299), stdev = 0.145
  CI (99.9%): [2.506, 7.796] (assumes normal distribution)


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
# Warmup Iteration   1: 6.151 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.014 ms/op
Iteration   1: 4.419 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.612 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  11.070 ms/op
                 createUser·p0.9999: 21.505 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   2: 4.238 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  12.699 ms/op
                 createUser·p0.9999: 24.082 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 26.381 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222446
  mean =      4.316 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3533 
    [ 2.500,  5.000) = 174293 
    [ 5.000,  7.500) = 42714 
    [ 7.500, 10.000) = 1394 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.241 ms/op
     p(99.9900) =     25.903 ms/op
     p(99.9990) =     26.848 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 5.667 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.012 ms/op
Iteration   1: 4.222 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   5.751 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  9.199 ms/op
                 existUser·p0.9999: 15.960 ms/op
                 existUser·p1.00:   16.417 ms/op

Iteration   2: 4.108 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.317 ms/op
                 existUser·p0.95:   5.726 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 19.510 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 4.158 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.786 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230638
  mean =      4.162 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5828 
    [ 2.500,  5.000) = 186336 
    [ 5.000,  7.500) = 36948 
    [ 7.500, 10.000) = 1182 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     11.442 ms/op
     p(99.9900) =     23.884 ms/op
     p(99.9990) =     25.103 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 6.525 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.014 ms/op
Iteration   1: 4.434 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  11.563 ms/op
                 getUser·p0.9999: 15.633 ms/op
                 getUser·p1.00:   15.909 ms/op

Iteration   2: 4.292 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  13.399 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 4.420 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  11.917 ms/op
                 getUser·p0.9999: 20.498 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 219040
  mean =      4.381 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5007 
    [ 2.500,  5.000) = 162543 
    [ 5.000,  7.500) = 49651 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     20.057 ms/op
     p(99.9990) =     20.801 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 7.357 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.990 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.359 ±(99.9%) 0.018 ms/op
Iteration   1: 5.224 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.744 ms/op
                 listUser·p0.999:  16.606 ms/op
                 listUser·p0.9999: 21.988 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 5.208 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 19.638 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 5.176 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.709 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  19.042 ms/op
                 listUser·p0.9999: 22.473 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184507
  mean =      5.203 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 94656 
    [ 5.000,  7.500) = 78624 
    [ 7.500, 10.000) = 9377 
    [10.000, 12.500) = 1097 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     22.136 ms/op
     p(99.9990) =     24.203 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.307 ± 3.088  ops/ms
ClientGrpc.existUser                       thrpt       3   7.940 ± 1.278  ops/ms
ClientGrpc.getUser                         thrpt       3   7.333 ± 1.717  ops/ms
ClientGrpc.listUser                        thrpt       3   6.125 ± 1.959  ops/ms
ClientGrpc.createUser                       avgt       3   4.493 ± 2.311   ms/op
ClientGrpc.existUser                        avgt       3   4.172 ± 0.258   ms/op
ClientGrpc.getUser                          avgt       3   4.324 ± 1.707   ms/op
ClientGrpc.listUser                         avgt       3   5.151 ± 2.645   ms/op
ClientGrpc.createUser                     sample  222446   4.316 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.920           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.456           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.258           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.241           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.903           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.001           ms/op
ClientGrpc.existUser                      sample  230638   4.162 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.717           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.442           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.231           ms/op
ClientGrpc.getUser                        sample  219040   4.381 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.925           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.571           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.108           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.057           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  184507   5.203 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.280           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.709           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.302           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.136           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.314           ms/op
