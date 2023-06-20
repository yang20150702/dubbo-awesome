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
# Warmup Iteration   1: 4.322 ops/ms
# Warmup Iteration   2: 8.891 ops/ms
# Warmup Iteration   3: 10.265 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.478 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.474 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (10.344, 10.474, 10.600), stdev = 0.128
  CI (99.9%): [8.138, 12.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.549 ops/ms
# Warmup Iteration   2: 10.574 ops/ms
# Warmup Iteration   3: 11.006 ops/ms
Iteration   1: 11.371 ops/ms
Iteration   2: 11.037 ops/ms
Iteration   3: 11.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.162 ±(99.9%) 3.323 ops/ms [Average]
  (min, avg, max) = (11.037, 11.162, 11.371), stdev = 0.182
  CI (99.9%): [7.839, 14.484] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ops/ms
# Warmup Iteration   2: 10.182 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.437 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (10.325, 10.437, 10.545), stdev = 0.110
  CI (99.9%): [8.429, 12.444] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.589 ops/ms
# Warmup Iteration   2: 7.884 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.266 ops/ms
Iteration   3: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.201 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (8.160, 8.201, 8.266), stdev = 0.057
  CI (99.9%): [7.161, 9.240] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.004 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.034 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.002, 3.034, 3.058), stdev = 0.029
  CI (99.9%): [2.509, 3.559] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.116 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.004 ms/op
Iteration   1: 2.878 ±(99.9%) 0.004 ms/op
Iteration   2: 2.891 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.200 ms/op [Average]
  (min, avg, max) = (2.878, 2.890, 2.899), stdev = 0.011
  CI (99.9%): [2.690, 3.090] (assumes normal distribution)


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.999, 3.008, 3.017), stdev = 0.009
  CI (99.9%): [2.852, 3.164] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.018 ms/op
Iteration   1: 3.942 ±(99.9%) 0.016 ms/op
Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
Iteration   3: 3.941 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.934 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (3.918, 3.934, 3.942), stdev = 0.014
  CI (99.9%): [3.684, 4.184] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.499 ms/op
                 createUser·p0.9999: 13.355 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.609 ms/op
                 createUser·p0.9999: 14.301 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.075 ms/op
                 createUser·p0.9999: 18.651 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314000
  mean =      3.058 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 871 
    [ 1.250,  2.500) = 14722 
    [ 2.500,  3.750) = 284229 
    [ 3.750,  5.000) = 12965 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 285 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.963 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.087 ms/op
                 existUser·p0.9999: 13.585 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.522 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  12.097 ms/op
                 existUser·p0.9999: 29.109 ms/op
                 existUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326338
  mean =      2.942 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32090 
    [ 2.500,  5.000) = 293036 
    [ 5.000,  7.500) = 824 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     21.650 ms/op
     p(99.9990) =     29.384 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  10.429 ms/op
                 getUser·p0.9999: 18.046 ms/op
                 getUser·p1.00:   18.940 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.230 ms/op
                 getUser·p0.9999: 26.394 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.471 ms/op
                 getUser·p0.9999: 21.015 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316083
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22645 
    [ 2.500,  5.000) = 291856 
    [ 5.000,  7.500) = 1146 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     26.031 ms/op
     p(99.9990) =     26.930 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.975 ms/op
                 listUser·p0.999:  13.961 ms/op
                 listUser·p0.9999: 16.524 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   2: 3.916 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  15.750 ms/op
                 listUser·p0.9999: 24.652 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 3.821 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 22.160 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246817
  mean =      3.887 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4155 
    [ 2.500,  5.000) = 221351 
    [ 5.000,  7.500) = 19955 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.474 ± 2.336  ops/ms
ClientGrpc.existUser                       thrpt       3  11.162 ± 3.323  ops/ms
ClientGrpc.getUser                         thrpt       3  10.437 ± 2.008  ops/ms
ClientGrpc.listUser                        thrpt       3   8.201 ± 1.040  ops/ms
ClientGrpc.createUser                       avgt       3   3.034 ± 0.525   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.200   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.156   ms/op
ClientGrpc.listUser                         avgt       3   3.934 ± 0.250   ms/op
ClientGrpc.createUser                     sample  314000   3.058 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.549           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.438           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.317           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.071           ms/op
ClientGrpc.existUser                      sample  326338   2.942 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.503           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.650           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.491           ms/op
ClientGrpc.getUser                        sample  316083   3.035 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.468           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.031           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.230           ms/op
ClientGrpc.listUser                       sample  246817   3.887 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.852           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
