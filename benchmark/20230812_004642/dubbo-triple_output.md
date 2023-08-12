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
# Warmup Iteration   1: 1.847 ops/ms
# Warmup Iteration   2: 4.618 ops/ms
# Warmup Iteration   3: 8.216 ops/ms
Iteration   1: 8.982 ops/ms
Iteration   2: 8.959 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.110 ±(99.9%) 4.411 ops/ms [Average]
  (min, avg, max) = (8.959, 9.110, 9.389), stdev = 0.242
  CI (99.9%): [4.699, 13.521] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 8.003 ops/ms
# Warmup Iteration   3: 9.609 ops/ms
Iteration   1: 9.496 ops/ms
Iteration   2: 9.596 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.531 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (9.496, 9.531, 9.596), stdev = 0.057
  CI (99.9%): [8.491, 10.570] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.664 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 8.861 ops/ms
Iteration   1: 9.239 ops/ms
Iteration   2: 8.894 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.117 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (8.894, 9.117, 9.239), stdev = 0.194
  CI (99.9%): [5.581, 12.654] (assumes normal distribution)


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
# Warmup Iteration   1: 2.735 ops/ms
# Warmup Iteration   2: 6.805 ops/ms
# Warmup Iteration   3: 7.615 ops/ms
Iteration   1: 7.735 ops/ms
Iteration   2: 7.781 ops/ms
Iteration   3: 7.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.796 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (7.735, 7.796, 7.872), stdev = 0.070
  CI (99.9%): [6.527, 9.065] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.041 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.923 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.004 ms/op
Iteration   1: 3.509 ±(99.9%) 0.010 ms/op
Iteration   2: 3.483 ±(99.9%) 0.006 ms/op
Iteration   3: 3.572 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.521 ±(99.9%) 0.833 ms/op [Average]
  (min, avg, max) = (3.483, 3.521, 3.572), stdev = 0.046
  CI (99.9%): [2.688, 4.354] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.005 ms/op
Iteration   1: 3.454 ±(99.9%) 0.007 ms/op
Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
Iteration   3: 3.352 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.270, 3.359, 3.454), stdev = 0.092
  CI (99.9%): [1.685, 5.033] (assumes normal distribution)


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
# Warmup Iteration   1: 9.360 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.007 ms/op
Iteration   1: 3.643 ±(99.9%) 0.005 ms/op
Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
Iteration   3: 3.462 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.523 ±(99.9%) 1.904 ms/op [Average]
  (min, avg, max) = (3.462, 3.523, 3.643), stdev = 0.104
  CI (99.9%): [1.619, 5.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.638 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.006 ms/op
Iteration   1: 4.099 ±(99.9%) 0.006 ms/op
Iteration   2: 4.057 ±(99.9%) 0.010 ms/op
Iteration   3: 4.019 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (4.019, 4.058, 4.099), stdev = 0.040
  CI (99.9%): [3.332, 4.784] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.527 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
Iteration   1: 3.521 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  19.487 ms/op
                 createUser·p0.9999: 23.230 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.540 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.559 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  24.696 ms/op
                 createUser·p0.9999: 28.374 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  18.588 ms/op
                 createUser·p0.9999: 28.046 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272512
  mean =      3.521 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11169 
    [ 2.500,  5.000) = 252783 
    [ 5.000,  7.500) = 6686 
    [ 7.500, 10.000) = 1295 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     19.347 ms/op
     p(99.9900) =     28.115 ms/op
     p(99.9990) =     29.354 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 9.971 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
Iteration   1: 3.480 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  21.201 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  22.101 ms/op
                 existUser·p0.9999: 26.091 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 3.401 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  14.401 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279226
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5195 
    [ 2.500,  5.000) = 263479 
    [ 5.000,  7.500) = 8776 
    [ 7.500, 10.000) = 1232 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.189 ms/op
     p(99.9900) =     26.610 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 9.835 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.012 ms/op
Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   7.023 ms/op
                 getUser·p0.999:  20.750 ms/op
                 getUser·p0.9999: 23.267 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.413 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  23.818 ms/op
                 getUser·p0.9999: 27.939 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  17.564 ms/op
                 getUser·p0.9999: 31.523 ms/op
                 getUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275477
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8861 
    [ 2.500,  5.000) = 256082 
    [ 5.000,  7.500) = 8757 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     18.400 ms/op
     p(99.9900) =     28.654 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 12.025 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.016 ms/op
Iteration   1: 4.152 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  21.853 ms/op
                 listUser·p0.9999: 24.356 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.931 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  16.182 ms/op
                 listUser·p0.9999: 21.403 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.747 ms/op
                 listUser·p0.9999: 21.241 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233269
  mean =      4.116 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 220773 
    [ 5.000,  7.500) = 9109 
    [ 7.500, 10.000) = 2085 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.358 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     24.991 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.110 ± 4.411  ops/ms
ClientPb.existUser                       thrpt       3   9.531 ± 1.040  ops/ms
ClientPb.getUser                         thrpt       3   9.117 ± 3.537  ops/ms
ClientPb.listUser                        thrpt       3   7.796 ± 1.269  ops/ms
ClientPb.createUser                       avgt       3   3.521 ± 0.833   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 1.674   ms/op
ClientPb.getUser                          avgt       3   3.523 ± 1.904   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 0.726   ms/op
ClientPb.createUser                     sample  272512   3.521 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.347           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.115           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  279226   3.436 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.004           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  275477   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.400           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.654           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.982           ms/op
ClientPb.listUser                       sample  233269   4.116 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.358           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.822           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.100           ms/op
