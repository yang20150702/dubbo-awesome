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
# Warmup Iteration   1: 3.159 ops/ms
# Warmup Iteration   2: 7.312 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 8.855 ops/ms
Iteration   3: 8.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.894 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (8.834, 8.894, 8.992), stdev = 0.086
  CI (99.9%): [7.331, 10.456] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.735 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 9.242 ops/ms
Iteration   1: 9.431 ops/ms
Iteration   2: 9.535 ops/ms
Iteration   3: 9.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.468 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (9.431, 9.468, 9.535), stdev = 0.058
  CI (99.9%): [8.410, 10.527] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.630 ops/ms
# Warmup Iteration   2: 8.544 ops/ms
# Warmup Iteration   3: 8.881 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 8.983 ops/ms
Iteration   3: 9.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.011 ±(99.9%) 0.632 ops/ms [Average]
  (min, avg, max) = (8.983, 9.011, 9.050), stdev = 0.035
  CI (99.9%): [8.378, 9.643] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.512 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 6.591 ops/ms
Iteration   1: 6.681 ops/ms
Iteration   2: 6.671 ops/ms
Iteration   3: 6.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.699 ±(99.9%) 0.737 ops/ms [Average]
  (min, avg, max) = (6.671, 6.699, 6.745), stdev = 0.040
  CI (99.9%): [5.962, 7.436] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.402 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.021 ms/op
Iteration   1: 3.667 ±(99.9%) 0.003 ms/op
Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
Iteration   3: 3.573 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.625 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.573, 3.625, 3.667), stdev = 0.048
  CI (99.9%): [2.756, 4.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.135 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.003 ms/op
Iteration   1: 3.512 ±(99.9%) 0.003 ms/op
Iteration   2: 3.444 ±(99.9%) 0.003 ms/op
Iteration   3: 3.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.469 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.444, 3.469, 3.512), stdev = 0.037
  CI (99.9%): [2.789, 4.150] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.719 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.004 ms/op
Iteration   1: 3.654 ±(99.9%) 0.004 ms/op
Iteration   2: 3.642 ±(99.9%) 0.003 ms/op
Iteration   3: 3.607 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.634 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.607, 3.634, 3.654), stdev = 0.025
  CI (99.9%): [3.186, 4.083] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.210 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.096 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.012 ms/op
Iteration   1: 4.881 ±(99.9%) 0.017 ms/op
Iteration   2: 4.871 ±(99.9%) 0.018 ms/op
Iteration   3: 4.777 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.843 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (4.777, 4.843, 4.881), stdev = 0.057
  CI (99.9%): [3.799, 5.887] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.304 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
Iteration   1: 3.543 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  8.092 ms/op
                 createUser·p0.9999: 16.005 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.663 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.420 ms/op
                 createUser·p0.999:  11.294 ms/op
                 createUser·p0.9999: 17.122 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.606 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  9.169 ms/op
                 createUser·p0.9999: 19.632 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266276
  mean =      3.603 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 9064 
    [ 2.500,  3.750) = 163324 
    [ 3.750,  5.000) = 88435 
    [ 5.000,  6.250) = 4248 
    [ 6.250,  7.500) = 457 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 58 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.490 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     19.149 ms/op
     p(99.9990) =     19.803 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.007 ms/op
Iteration   1: 3.498 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 14.817 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   2: 3.528 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  7.823 ms/op
                 existUser·p0.9999: 16.249 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   3: 3.459 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   3.902 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  6.455 ms/op
                 existUser·p0.9999: 20.406 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274874
  mean =      3.495 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5987 
    [ 2.500,  5.000) = 265967 
    [ 5.000,  7.500) = 2662 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      7.431 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.755 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
Iteration   1: 3.639 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  14.565 ms/op
                 getUser·p0.9999: 15.670 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   2: 3.650 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.580 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 16.235 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   3: 3.734 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  11.125 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261215
  mean =      3.674 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6314 
    [ 2.500,  5.000) = 248840 
    [ 5.000,  7.500) = 5402 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     19.001 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 6.427 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.015 ms/op
Iteration   1: 4.924 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  14.792 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.731 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.389 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.685 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  19.609 ms/op
                 listUser·p0.9999: 26.435 ms/op
                 listUser·p1.00:   26.935 ms/op

Iteration   3: 4.846 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  19.198 ms/op
                 listUser·p0.9999: 27.682 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198649
  mean =      4.833 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 380 
    [ 2.500,  5.000) = 142598 
    [ 5.000,  7.500) = 50259 
    [ 7.500, 10.000) = 4736 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     17.379 ms/op
     p(99.9900) =     26.252 ms/op
     p(99.9990) =     29.034 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.894 ± 1.563  ops/ms
ClientGrpc.existUser                       thrpt       3   9.468 ± 1.059  ops/ms
ClientGrpc.getUser                         thrpt       3   9.011 ± 0.632  ops/ms
ClientGrpc.listUser                        thrpt       3   6.699 ± 0.737  ops/ms
ClientGrpc.createUser                       avgt       3   3.625 ± 0.869   ms/op
ClientGrpc.existUser                        avgt       3   3.469 ± 0.681   ms/op
ClientGrpc.getUser                          avgt       3   3.634 ± 0.449   ms/op
ClientGrpc.listUser                         avgt       3   4.843 ± 1.044   ms/op
ClientGrpc.createUser                     sample  266276   3.603 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.817           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.490           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.290           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.149           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.988           ms/op
ClientGrpc.existUser                      sample  274874   3.495 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.981           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.046           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.448           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  261215   3.674 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.781           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.125           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.001           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  198649   4.833 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.955           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.379           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.252           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.164           ms/op
