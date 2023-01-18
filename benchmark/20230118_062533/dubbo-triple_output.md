# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.882 ops/ms
# Warmup Iteration   2: 2.073 ops/ms
# Warmup Iteration   3: 4.805 ops/ms
Iteration   1: 5.313 ops/ms
Iteration   2: 5.405 ops/ms
Iteration   3: 5.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.392 ±(99.9%) 1.333 ops/ms [Average]
  (min, avg, max) = (5.313, 5.392, 5.457), stdev = 0.073
  CI (99.9%): [4.059, 6.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.423 ops/ms
# Warmup Iteration   2: 4.501 ops/ms
# Warmup Iteration   3: 5.693 ops/ms
Iteration   1: 5.718 ops/ms
Iteration   2: 5.691 ops/ms
Iteration   3: 6.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.842 ±(99.9%) 4.368 ops/ms [Average]
  (min, avg, max) = (5.691, 5.842, 6.118), stdev = 0.239
  CI (99.9%): [1.474, 10.210] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.545 ops/ms
# Warmup Iteration   2: 4.107 ops/ms
# Warmup Iteration   3: 5.074 ops/ms
Iteration   1: 5.667 ops/ms
Iteration   2: 5.671 ops/ms
Iteration   3: 5.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.643 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (5.592, 5.643, 5.671), stdev = 0.044
  CI (99.9%): [4.832, 6.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.490 ops/ms
# Warmup Iteration   2: 3.603 ops/ms
# Warmup Iteration   3: 4.582 ops/ms
Iteration   1: 4.689 ops/ms
Iteration   2: 5.055 ops/ms
Iteration   3: 5.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.944 ±(99.9%) 4.035 ops/ms [Average]
  (min, avg, max) = (4.689, 4.944, 5.088), stdev = 0.221
  CI (99.9%): [0.909, 8.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.644 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.178 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.889 ±(99.9%) 0.010 ms/op
Iteration   1: 6.478 ±(99.9%) 0.016 ms/op
Iteration   2: 5.866 ±(99.9%) 0.015 ms/op
Iteration   3: 5.435 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.926 ±(99.9%) 9.560 ms/op [Average]
  (min, avg, max) = (5.435, 5.926, 6.478), stdev = 0.524
  CI (99.9%): [≈ 0, 15.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 19.394 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 6.162 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.236 ±(99.9%) 0.011 ms/op
Iteration   1: 5.497 ±(99.9%) 0.011 ms/op
Iteration   2: 5.307 ±(99.9%) 0.008 ms/op
Iteration   3: 5.222 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.342 ±(99.9%) 2.564 ms/op [Average]
  (min, avg, max) = (5.222, 5.342, 5.497), stdev = 0.141
  CI (99.9%): [2.778, 7.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.221 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 7.857 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.013 ±(99.9%) 0.010 ms/op
Iteration   1: 5.784 ±(99.9%) 0.011 ms/op
Iteration   2: 6.138 ±(99.9%) 0.012 ms/op
Iteration   3: 5.706 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.876 ±(99.9%) 4.197 ms/op [Average]
  (min, avg, max) = (5.706, 5.876, 6.138), stdev = 0.230
  CI (99.9%): [1.679, 10.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.035 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 8.014 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.129 ±(99.9%) 0.018 ms/op
Iteration   1: 6.305 ±(99.9%) 0.021 ms/op
Iteration   2: 6.203 ±(99.9%) 0.017 ms/op
Iteration   3: 6.273 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.260 ±(99.9%) 0.956 ms/op [Average]
  (min, avg, max) = (6.203, 6.260, 6.305), stdev = 0.052
  CI (99.9%): [5.305, 7.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.757 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 7.489 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.156 ±(99.9%) 0.032 ms/op
Iteration   1: 5.637 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.482 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  25.030 ms/op
                 createUser·p0.9999: 29.655 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   2: 5.502 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.692 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  24.866 ms/op
                 createUser·p0.9999: 30.513 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 5.677 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.560 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   12.113 ms/op
                 createUser·p0.999:  28.070 ms/op
                 createUser·p0.9999: 31.210 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171221
  mean =      5.605 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 63991 
    [ 5.000,  7.500) = 95789 
    [ 7.500, 10.000) = 8376 
    [10.000, 12.500) = 1990 
    [12.500, 15.000) = 543 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     25.257 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     32.114 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.836 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.264 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.246 ±(99.9%) 0.020 ms/op
Iteration   1: 5.483 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.363 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   12.633 ms/op
                 existUser·p0.999:  23.312 ms/op
                 existUser·p0.9999: 36.591 ms/op
                 existUser·p1.00:   45.548 ms/op

Iteration   2: 5.432 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   8.045 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  23.207 ms/op
                 existUser·p0.9999: 26.485 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 5.270 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.617 ms/op
                 existUser·p0.999:  15.308 ms/op
                 existUser·p0.9999: 28.408 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177712
  mean =      5.393 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 82154 
    [ 5.000, 10.000) = 92699 
    [10.000, 15.000) = 2426 
    [15.000, 20.000) = 232 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 73 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.766 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     22.193 ms/op
     p(99.9900) =     34.728 ms/op
     p(99.9990) =     38.927 ms/op
     p(99.9999) =     45.548 ms/op
    p(100.0000) =     45.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.322 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 6.990 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.638 ±(99.9%) 0.021 ms/op
Iteration   1: 5.498 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   7.750 ms/op
                 getUser·p0.99:   11.043 ms/op
                 getUser·p0.999:  16.368 ms/op
                 getUser·p0.9999: 30.028 ms/op
                 getUser·p1.00:   30.540 ms/op

Iteration   2: 5.697 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  26.108 ms/op
                 getUser·p0.9999: 32.350 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   3: 5.564 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.671 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.939 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  26.571 ms/op
                 getUser·p0.9999: 32.448 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171944
  mean =      5.585 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 59723 
    [ 5.000,  7.500) = 100288 
    [ 7.500, 10.000) = 8054 
    [10.000, 12.500) = 2432 
    [12.500, 15.000) = 943 
    [15.000, 17.500) = 253 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     23.666 ms/op
     p(99.9900) =     31.871 ms/op
     p(99.9990) =     33.610 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.396 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 8.508 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.667 ±(99.9%) 0.028 ms/op
Iteration   1: 6.469 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  32.787 ms/op
                 listUser·p0.9999: 39.784 ms/op
                 listUser·p1.00:   40.174 ms/op

Iteration   2: 6.221 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.404 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  28.047 ms/op
                 listUser·p0.9999: 31.092 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   3: 6.181 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.795 ms/op
                 listUser·p0.999:  25.723 ms/op
                 listUser·p0.9999: 28.863 ms/op
                 listUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152591
  mean =      6.288 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7692 
    [ 5.000, 10.000) = 140879 
    [10.000, 15.000) = 3399 
    [15.000, 20.000) = 296 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 189 
    [30.000, 35.000) = 59 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.462 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     28.063 ms/op
     p(99.9900) =     36.945 ms/op
     p(99.9990) =     40.105 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.392 ± 1.333  ops/ms
ClientPb.existUser                       thrpt       3   5.842 ± 4.368  ops/ms
ClientPb.getUser                         thrpt       3   5.643 ± 0.811  ops/ms
ClientPb.listUser                        thrpt       3   4.944 ± 4.035  ops/ms
ClientPb.createUser                       avgt       3   5.926 ± 9.560   ms/op
ClientPb.existUser                        avgt       3   5.342 ± 2.564   ms/op
ClientPb.getUser                          avgt       3   5.876 ± 4.197   ms/op
ClientPb.listUser                         avgt       3   6.260 ± 0.956   ms/op
ClientPb.createUser                     sample  171221   5.605 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.683           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.485           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.604           ms/op
ClientPb.existUser                      sample  177712   5.393 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.478           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.054           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.636           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.766           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.370           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.193           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.728           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.548           ms/op
ClientPb.getUser                        sample  171944   5.585 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.266           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.666           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.871           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  152591   6.288 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.462           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.063           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.945           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.174           ms/op
