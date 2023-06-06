# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.176 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 10.287 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.509 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.635 ±(99.9%) 1.996 ops/ms [Average]
  (min, avg, max) = (10.509, 10.635, 10.708), stdev = 0.109
  CI (99.9%): [8.638, 12.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.544 ops/ms
# Warmup Iteration   2: 10.690 ops/ms
# Warmup Iteration   3: 11.191 ops/ms
Iteration   1: 11.330 ops/ms
Iteration   2: 11.245 ops/ms
Iteration   3: 11.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.395 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (11.245, 11.395, 11.611), stdev = 0.192
  CI (99.9%): [7.896, 14.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.965 ops/ms
# Warmup Iteration   2: 10.428 ops/ms
# Warmup Iteration   3: 10.730 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.794 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.675 ±(99.9%) 1.867 ops/ms [Average]
  (min, avg, max) = (10.615, 10.675, 10.794), stdev = 0.102
  CI (99.9%): [8.808, 12.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.334 ops/ms
# Warmup Iteration   2: 7.988 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 8.412 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.294 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (8.233, 8.294, 8.412), stdev = 0.102
  CI (99.9%): [6.435, 10.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (2.974, 3.016, 3.057), stdev = 0.041
  CI (99.9%): [2.260, 3.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.803 ±(99.9%) 0.003 ms/op
Iteration   1: 2.834 ±(99.9%) 0.003 ms/op
Iteration   2: 2.803 ±(99.9%) 0.003 ms/op
Iteration   3: 2.807 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.815 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.803, 2.815, 2.834), stdev = 0.017
  CI (99.9%): [2.504, 3.125] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.172 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.954 ±(99.9%) 0.004 ms/op
Iteration   2: 3.006 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.985 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.954, 2.985, 3.006), stdev = 0.027
  CI (99.9%): [2.486, 3.485] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.815 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.022 ms/op
Iteration   1: 3.802 ±(99.9%) 0.017 ms/op
Iteration   2: 3.801 ±(99.9%) 0.017 ms/op
Iteration   3: 3.910 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.838 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.801, 3.838, 3.910), stdev = 0.062
  CI (99.9%): [2.698, 4.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.471 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  7.701 ms/op
                 createUser·p0.9999: 12.899 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  6.824 ms/op
                 createUser·p0.9999: 14.369 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   3: 2.985 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  12.660 ms/op
                 createUser·p0.9999: 23.864 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319231
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27194 
    [ 2.500,  5.000) = 290974 
    [ 5.000,  7.500) = 743 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.520 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.013 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.005 ms/op
Iteration   1: 2.798 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   3.981 ms/op
                 existUser·p0.999:  6.394 ms/op
                 existUser·p0.9999: 15.647 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 2.860 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.709 ms/op
                 existUser·p0.9999: 20.474 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.275 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.104 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338667
  mean =      2.836 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60913 
    [ 2.500,  5.000) = 276642 
    [ 5.000,  7.500) = 755 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.632 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     21.241 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.500 ms/op
                 getUser·p0.999:  6.927 ms/op
                 getUser·p0.9999: 13.015 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.075 ms/op
                 getUser·p0.9999: 15.390 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   3: 2.941 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.285 ms/op
                 getUser·p0.95:   3.494 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 23.400 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323505
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25236 
    [ 2.500,  5.000) = 297174 
    [ 5.000,  7.500) = 891 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.808 ms/op
     p(99.9900) =     20.300 ms/op
     p(99.9990) =     23.487 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.400 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.012 ms/op
Iteration   1: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.360 ms/op
                 listUser·p0.9999: 21.051 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.951 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  17.732 ms/op
                 listUser·p0.9999: 27.585 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.543 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.989 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242890
  mean =      3.952 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3131 
    [ 2.500,  5.000) = 216005 
    [ 5.000,  7.500) = 22428 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     15.452 ms/op
     p(99.9900) =     26.860 ms/op
     p(99.9990) =     28.054 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.635 ± 1.996  ops/ms
ClientGrpc.existUser                       thrpt       3  11.395 ± 3.499  ops/ms
ClientGrpc.getUser                         thrpt       3  10.675 ± 1.867  ops/ms
ClientGrpc.listUser                        thrpt       3   8.294 ± 1.859  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.757   ms/op
ClientGrpc.existUser                        avgt       3   2.815 ± 0.311   ms/op
ClientGrpc.getUser                          avgt       3   2.985 ± 0.500   ms/op
ClientGrpc.listUser                         avgt       3   3.838 ± 1.139   ms/op
ClientGrpc.createUser                     sample  319231   3.007 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.713           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.520           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.331           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  338667   2.836 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.275           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.632           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.120           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  323505   2.965 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.553           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.808           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.527           ms/op
ClientGrpc.listUser                       sample  242890   3.952 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.543           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.452           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.860           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
