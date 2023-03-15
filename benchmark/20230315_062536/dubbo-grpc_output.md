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
# Warmup Iteration   1: 2.346 ops/ms
# Warmup Iteration   2: 5.094 ops/ms
# Warmup Iteration   3: 6.915 ops/ms
Iteration   1: 7.380 ops/ms
Iteration   2: 7.459 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.523 ±(99.9%) 3.345 ops/ms [Average]
  (min, avg, max) = (7.380, 7.523, 7.729), stdev = 0.183
  CI (99.9%): [4.178, 10.868] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ops/ms
# Warmup Iteration   2: 7.279 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.024 ops/ms
Iteration   2: 8.053 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.981 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (7.866, 7.981, 8.053), stdev = 0.100
  CI (99.9%): [6.149, 9.813] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.343 ops/ms
# Warmup Iteration   2: 6.877 ops/ms
# Warmup Iteration   3: 7.394 ops/ms
Iteration   1: 7.802 ops/ms
Iteration   2: 7.701 ops/ms
Iteration   3: 7.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.663 ±(99.9%) 2.932 ops/ms [Average]
  (min, avg, max) = (7.487, 7.663, 7.802), stdev = 0.161
  CI (99.9%): [4.731, 10.595] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ops/ms
# Warmup Iteration   2: 5.188 ops/ms
# Warmup Iteration   3: 5.753 ops/ms
Iteration   1: 5.747 ops/ms
Iteration   2: 5.778 ops/ms
Iteration   3: 5.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.794 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (5.747, 5.794, 5.858), stdev = 0.057
  CI (99.9%): [4.747, 6.841] (assumes normal distribution)


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
# Warmup Iteration   1: 6.971 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.386 ±(99.9%) 0.008 ms/op
Iteration   1: 4.288 ±(99.9%) 0.005 ms/op
Iteration   2: 4.266 ±(99.9%) 0.004 ms/op
Iteration   3: 4.101 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.219 ±(99.9%) 1.861 ms/op [Average]
  (min, avg, max) = (4.101, 4.219, 4.288), stdev = 0.102
  CI (99.9%): [2.357, 6.080] (assumes normal distribution)


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
# Warmup Iteration   1: 5.830 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.009 ms/op
Iteration   1: 4.011 ±(99.9%) 0.004 ms/op
Iteration   2: 4.045 ±(99.9%) 0.003 ms/op
Iteration   3: 4.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.040 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (4.011, 4.040, 4.063), stdev = 0.026
  CI (99.9%): [3.564, 4.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.844 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.004 ms/op
Iteration   1: 4.362 ±(99.9%) 0.006 ms/op
Iteration   2: 4.448 ±(99.9%) 0.004 ms/op
Iteration   3: 4.278 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.363 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (4.278, 4.363, 4.448), stdev = 0.085
  CI (99.9%): [2.816, 5.909] (assumes normal distribution)


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
# Warmup Iteration   1: 8.446 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.741 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.520 ±(99.9%) 0.021 ms/op
Iteration   1: 5.738 ±(99.9%) 0.020 ms/op
Iteration   2: 5.670 ±(99.9%) 0.014 ms/op
Iteration   3: 5.531 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.646 ±(99.9%) 1.928 ms/op [Average]
  (min, avg, max) = (5.531, 5.646, 5.738), stdev = 0.106
  CI (99.9%): [3.718, 7.575] (assumes normal distribution)


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
# Warmup Iteration   1: 6.449 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.798 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.014 ms/op
Iteration   1: 4.506 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.537 ms/op
                 createUser·p0.99:   9.354 ms/op
                 createUser·p0.999:  13.556 ms/op
                 createUser·p0.9999: 15.694 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   2: 4.354 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  13.089 ms/op
                 createUser·p0.9999: 22.641 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   3: 4.360 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  14.696 ms/op
                 createUser·p0.9999: 19.060 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 217797
  mean =      4.406 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3426 
    [ 2.500,  5.000) = 169446 
    [ 5.000,  7.500) = 41220 
    [ 7.500, 10.000) = 2729 
    [10.000, 12.500) = 658 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.571 ms/op
     p(95.0000) =      6.128 ms/op
     p(99.0000) =      8.504 ms/op
     p(99.9000) =     13.920 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 6.025 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
Iteration   1: 4.129 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.259 ms/op
                 existUser·p0.95:   5.903 ms/op
                 existUser·p0.99:   8.126 ms/op
                 existUser·p0.999:  12.650 ms/op
                 existUser·p0.9999: 15.626 ms/op
                 existUser·p1.00:   15.843 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.562 ms/op
                 existUser·p0.999:  13.298 ms/op
                 existUser·p0.9999: 16.838 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 4.073 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.666 ms/op
                 existUser·p0.999:  13.426 ms/op
                 existUser·p0.9999: 35.193 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236755
  mean =      4.053 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6419 
    [ 2.500,  5.000) = 203253 
    [ 5.000,  7.500) = 24255 
    [ 7.500, 10.000) = 2050 
    [10.000, 12.500) = 492 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     13.160 ms/op
     p(99.9900) =     30.649 ms/op
     p(99.9990) =     35.300 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 6.615 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.013 ms/op
Iteration   1: 4.238 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.322 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.217 ms/op
                 getUser·p0.999:  13.665 ms/op
                 getUser·p0.9999: 17.397 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 4.237 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   4.108 ms/op
                 getUser·p0.90:   5.284 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.946 ms/op
                 getUser·p0.999:  16.705 ms/op
                 getUser·p0.9999: 36.886 ms/op
                 getUser·p1.00:   37.356 ms/op

Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.301 ms/op
                 getUser·p0.999:  11.038 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228844
  mean =      4.199 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7423 
    [ 2.500,  5.000) = 188936 
    [ 5.000,  7.500) = 29709 
    [ 7.500, 10.000) = 2010 
    [10.000, 12.500) = 510 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     37.271 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 8.509 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.867 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.483 ±(99.9%) 0.020 ms/op
Iteration   1: 5.511 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.475 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 22.105 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 5.650 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  20.177 ms/op
                 listUser·p0.9999: 23.375 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   3: 5.530 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  19.667 ms/op
                 listUser·p0.9999: 35.039 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172474
  mean =      5.563 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 68675 
    [ 5.000,  7.500) = 87706 
    [ 7.500, 10.000) = 12812 
    [10.000, 12.500) = 2102 
    [12.500, 15.000) = 546 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     19.154 ms/op
     p(99.9900) =     32.662 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.523 ± 3.345  ops/ms
ClientGrpc.existUser                       thrpt       3   7.981 ± 1.832  ops/ms
ClientGrpc.getUser                         thrpt       3   7.663 ± 2.932  ops/ms
ClientGrpc.listUser                        thrpt       3   5.794 ± 1.047  ops/ms
ClientGrpc.createUser                       avgt       3   4.219 ± 1.861   ms/op
ClientGrpc.existUser                        avgt       3   4.040 ± 0.476   ms/op
ClientGrpc.getUser                          avgt       3   4.363 ± 1.546   ms/op
ClientGrpc.listUser                         avgt       3   5.646 ± 1.928   ms/op
ClientGrpc.createUser                     sample  217797   4.406 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.976           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.504           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.920           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.004           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.839           ms/op
ClientGrpc.existUser                      sample  236755   4.053 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.657           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.160           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.649           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.389           ms/op
ClientGrpc.getUser                        sample  228844   4.199 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.817           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.823           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.287           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.914           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.356           ms/op
ClientGrpc.listUser                       sample  172474   5.563 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.475           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.389           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.154           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.662           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.438           ms/op
