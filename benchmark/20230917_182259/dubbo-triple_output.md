# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 4.917 ops/ms
# Warmup Iteration   3: 8.536 ops/ms
Iteration   1: 8.810 ops/ms
Iteration   2: 9.208 ops/ms
Iteration   3: 9.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.174 ±(99.9%) 6.356 ops/ms [Average]
  (min, avg, max) = (8.810, 9.174, 9.504), stdev = 0.348
  CI (99.9%): [2.818, 15.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.641 ops/ms
# Warmup Iteration   2: 8.433 ops/ms
# Warmup Iteration   3: 9.297 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.901 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.705 ±(99.9%) 7.235 ops/ms [Average]
  (min, avg, max) = (9.248, 9.705, 9.965), stdev = 0.397
  CI (99.9%): [2.470, 16.939] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.789 ops/ms
# Warmup Iteration   2: 8.160 ops/ms
# Warmup Iteration   3: 9.058 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.220 ±(99.9%) 2.297 ops/ms [Average]
  (min, avg, max) = (9.090, 9.220, 9.341), stdev = 0.126
  CI (99.9%): [6.923, 11.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.687 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 7.577 ops/ms
Iteration   1: 7.565 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 7.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.738 ±(99.9%) 2.774 ops/ms [Average]
  (min, avg, max) = (7.565, 7.738, 7.852), stdev = 0.152
  CI (99.9%): [4.964, 10.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.407 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.003 ms/op
Iteration   1: 3.489 ±(99.9%) 0.004 ms/op
Iteration   2: 3.481 ±(99.9%) 0.004 ms/op
Iteration   3: 3.502 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.491 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (3.481, 3.491, 3.502), stdev = 0.010
  CI (99.9%): [3.300, 3.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.706 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.004 ms/op
Iteration   1: 3.367 ±(99.9%) 0.004 ms/op
Iteration   2: 3.401 ±(99.9%) 0.003 ms/op
Iteration   3: 3.341 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.370 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.341, 3.370, 3.401), stdev = 0.030
  CI (99.9%): [2.819, 3.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.555 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.003 ms/op
Iteration   1: 3.346 ±(99.9%) 0.008 ms/op
Iteration   2: 3.412 ±(99.9%) 0.003 ms/op
Iteration   3: 3.402 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.387 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.346, 3.387, 3.412), stdev = 0.035
  CI (99.9%): [2.743, 4.031] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.322 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.003 ms/op
Iteration   1: 4.074 ±(99.9%) 0.007 ms/op
Iteration   2: 4.058 ±(99.9%) 0.006 ms/op
Iteration   3: 4.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.067 ±(99.9%) 0.157 ms/op [Average]
  (min, avg, max) = (4.058, 4.067, 4.074), stdev = 0.009
  CI (99.9%): [3.910, 4.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.184 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.542 ±(99.9%) 0.010 ms/op
Iteration   1: 3.506 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  13.084 ms/op
                 createUser·p0.9999: 23.209 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.447 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  15.683 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.519 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.343 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  19.578 ms/op
                 createUser·p0.9999: 26.766 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274829
  mean =      3.490 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6967 
    [ 2.500,  5.000) = 263198 
    [ 5.000,  7.500) = 3651 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.343 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     28.009 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  12.496 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  22.212 ms/op
                 existUser·p0.9999: 24.754 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.390 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288175
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7782 
    [ 2.500,  5.000) = 274849 
    [ 5.000,  7.500) = 4424 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     17.294 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.579 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.132 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.010 ms/op
Iteration   1: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   7.211 ms/op
                 getUser·p0.999:  19.406 ms/op
                 getUser·p0.9999: 24.318 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.541 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  20.139 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.474 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  17.753 ms/op
                 getUser·p0.9999: 23.364 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272248
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4655 
    [ 2.500,  5.000) = 260690 
    [ 5.000,  7.500) = 5613 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     19.227 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     24.880 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.011 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.013 ms/op
Iteration   1: 4.166 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  20.823 ms/op
                 listUser·p0.9999: 24.978 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 4.153 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.484 ms/op
                 listUser·p0.999:  15.332 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.146 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.378 ms/op
                 listUser·p0.999:  15.497 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230935
  mean =      4.155 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 222691 
    [ 5.000,  7.500) = 6093 
    [ 7.500, 10.000) = 1271 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.812 ms/op
     p(99.9900) =     23.787 ms/op
     p(99.9990) =     25.713 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.174 ± 6.356  ops/ms
ClientPb.existUser                       thrpt       3   9.705 ± 7.235  ops/ms
ClientPb.getUser                         thrpt       3   9.220 ± 2.297  ops/ms
ClientPb.listUser                        thrpt       3   7.738 ± 2.774  ops/ms
ClientPb.createUser                       avgt       3   3.491 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   3.370 ± 0.551   ms/op
ClientPb.getUser                          avgt       3   3.387 ± 0.644   ms/op
ClientPb.listUser                         avgt       3   4.067 ± 0.157   ms/op
ClientPb.createUser                     sample  274829   3.490 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.730           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  288175   3.328 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.280           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.294           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.231           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  272248   3.525 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.227           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.331           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.936           ms/op
ClientPb.listUser                       sample  230935   4.155 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.283           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.812           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.787           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
