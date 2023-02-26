# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.132 ops/ms
# Warmup Iteration   2: 6.067 ops/ms
# Warmup Iteration   3: 8.619 ops/ms
Iteration   1: 9.025 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.313 ±(99.9%) 5.515 ops/ms [Average]
  (min, avg, max) = (9.025, 9.313, 9.628), stdev = 0.302
  CI (99.9%): [3.798, 14.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 8.958 ops/ms
# Warmup Iteration   3: 9.389 ops/ms
Iteration   1: 9.632 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.604 ±(99.9%) 6.326 ops/ms [Average]
  (min, avg, max) = (9.244, 9.604, 9.935), stdev = 0.347
  CI (99.9%): [3.277, 15.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ops/ms
# Warmup Iteration   2: 8.204 ops/ms
# Warmup Iteration   3: 9.069 ops/ms
Iteration   1: 9.572 ops/ms
Iteration   2: 9.195 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.449 ±(99.9%) 4.028 ops/ms [Average]
  (min, avg, max) = (9.195, 9.449, 9.581), stdev = 0.221
  CI (99.9%): [5.421, 13.477] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 7.996 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 8.257 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.216 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (8.157, 8.216, 8.257), stdev = 0.052
  CI (99.9%): [7.262, 9.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.569 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.006 ms/op
Iteration   1: 3.482 ±(99.9%) 0.008 ms/op
Iteration   2: 3.447 ±(99.9%) 0.012 ms/op
Iteration   3: 3.543 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.491 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.447, 3.491, 3.543), stdev = 0.049
  CI (99.9%): [2.604, 4.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.798 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.002 ms/op
Iteration   1: 3.296 ±(99.9%) 0.006 ms/op
Iteration   2: 3.172 ±(99.9%) 0.006 ms/op
Iteration   3: 3.156 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.208 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.156, 3.208, 3.296), stdev = 0.076
  CI (99.9%): [1.814, 4.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.480 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.003 ms/op
Iteration   1: 3.507 ±(99.9%) 0.005 ms/op
Iteration   2: 3.270 ±(99.9%) 0.011 ms/op
Iteration   3: 3.448 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.408 ±(99.9%) 2.251 ms/op [Average]
  (min, avg, max) = (3.270, 3.408, 3.507), stdev = 0.123
  CI (99.9%): [1.157, 5.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.555 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 3.987 ±(99.9%) 0.007 ms/op
Iteration   2: 3.825 ±(99.9%) 0.015 ms/op
Iteration   3: 3.869 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.894 ±(99.9%) 1.528 ms/op [Average]
  (min, avg, max) = (3.825, 3.894, 3.987), stdev = 0.084
  CI (99.9%): [2.366, 5.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.430 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.009 ms/op
Iteration   1: 3.328 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.112 ms/op
                 createUser·p0.9999: 21.967 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  21.572 ms/op
                 createUser·p0.9999: 24.135 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  15.498 ms/op
                 createUser·p0.9999: 31.836 ms/op
                 createUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285045
  mean =      3.365 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10900 
    [ 2.500,  5.000) = 268459 
    [ 5.000,  7.500) = 4712 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.223 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.544 ms/op
                 existUser·p0.999:  12.740 ms/op
                 existUser·p0.9999: 24.552 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  10.502 ms/op
                 existUser·p0.9999: 25.238 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.287 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  16.198 ms/op
                 existUser·p0.9999: 39.339 ms/op
                 existUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292896
  mean =      3.278 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19575 
    [ 2.500,  5.000) = 268294 
    [ 5.000,  7.500) = 3974 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.314 ms/op
     p(99.9900) =     25.999 ms/op
     p(99.9990) =     39.846 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.240 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.523 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  20.258 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 25.276 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   3: 3.440 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  17.978 ms/op
                 getUser·p0.9999: 24.763 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279123
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6827 
    [ 2.500,  5.000) = 263752 
    [ 5.000,  7.500) = 7214 
    [ 7.500, 10.000) = 940 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     24.710 ms/op
     p(99.9990) =     26.569 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.427 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.013 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 24.143 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 4.015 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 18.123 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.928 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.564 ms/op
                 listUser·p0.9999: 16.670 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242980
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 235445 
    [ 5.000,  7.500) = 5236 
    [ 7.500, 10.000) = 1483 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.847 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     23.475 ms/op
     p(99.9990) =     24.431 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.313 ± 5.515  ops/ms
ClientPb.existUser                       thrpt       3   9.604 ± 6.326  ops/ms
ClientPb.getUser                         thrpt       3   9.449 ± 4.028  ops/ms
ClientPb.listUser                        thrpt       3   8.216 ± 0.954  ops/ms
ClientPb.createUser                       avgt       3   3.491 ± 0.887   ms/op
ClientPb.existUser                        avgt       3   3.208 ± 1.394   ms/op
ClientPb.getUser                          avgt       3   3.408 ± 2.251   ms/op
ClientPb.listUser                         avgt       3   3.894 ± 1.528   ms/op
ClientPb.createUser                     sample  285045   3.365 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.532           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.637           ms/op
ClientPb.existUser                      sample  292896   3.278 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.754           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.314           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.911           ms/op
ClientPb.getUser                        sample  279123   3.436 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.923           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.464           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.710           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.706           ms/op
ClientPb.listUser                       sample  242980   3.948 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.007           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.475           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
