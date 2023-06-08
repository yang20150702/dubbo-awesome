# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 4.940 ops/ms
# Warmup Iteration   3: 8.577 ops/ms
Iteration   1: 9.125 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.200 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (9.125, 9.200, 9.279), stdev = 0.077
  CI (99.9%): [7.800, 10.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.937 ops/ms
# Warmup Iteration   2: 8.292 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.808 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.749 ±(99.9%) 2.276 ops/ms [Average]
  (min, avg, max) = (9.606, 9.749, 9.834), stdev = 0.125
  CI (99.9%): [7.474, 12.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 8.340 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.260 ops/ms
Iteration   2: 9.069 ops/ms
Iteration   3: 9.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.167 ±(99.9%) 1.743 ops/ms [Average]
  (min, avg, max) = (9.069, 9.167, 9.260), stdev = 0.096
  CI (99.9%): [7.423, 10.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 7.143 ops/ms
# Warmup Iteration   3: 7.909 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 8.144 ops/ms
Iteration   3: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.921 ±(99.9%) 3.570 ops/ms [Average]
  (min, avg, max) = (7.781, 7.921, 8.144), stdev = 0.196
  CI (99.9%): [4.351, 11.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.506 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.007 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
Iteration   3: 3.290 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.369 ±(99.9%) 1.339 ms/op [Average]
  (min, avg, max) = (3.290, 3.369, 3.434), stdev = 0.073
  CI (99.9%): [2.030, 4.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.254 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.004 ms/op
Iteration   1: 3.281 ±(99.9%) 0.002 ms/op
Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
Iteration   3: 3.247 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.252 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (3.229, 3.252, 3.281), stdev = 0.026
  CI (99.9%): [2.774, 3.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.885 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.007 ms/op
Iteration   1: 3.385 ±(99.9%) 0.004 ms/op
Iteration   2: 3.485 ±(99.9%) 0.003 ms/op
Iteration   3: 3.369 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.369, 3.413, 3.485), stdev = 0.063
  CI (99.9%): [2.265, 4.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.850 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.009 ms/op
Iteration   1: 3.909 ±(99.9%) 0.016 ms/op
Iteration   2: 3.854 ±(99.9%) 0.016 ms/op
Iteration   3: 3.977 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.913 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.854, 3.913, 3.977), stdev = 0.061
  CI (99.9%): [2.792, 5.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.882 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.015 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.757 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.069 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  20.237 ms/op
                 createUser·p0.9999: 24.908 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  21.859 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.405 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.353 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  19.726 ms/op
                 createUser·p0.9999: 27.709 ms/op
                 createUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278179
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13059 
    [ 2.500,  5.000) = 257857 
    [ 5.000,  7.500) = 6412 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     20.146 ms/op
     p(99.9900) =     27.457 ms/op
     p(99.9990) =     29.545 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.754 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.009 ms/op
Iteration   1: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  20.081 ms/op
                 existUser·p0.9999: 22.989 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 3.262 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  15.536 ms/op
                 existUser·p0.9999: 26.712 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   3: 3.444 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 26.609 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285045
  mean =      3.367 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11397 
    [ 2.500,  5.000) = 269062 
    [ 5.000,  7.500) = 3833 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.959 ms/op
     p(99.9900) =     25.805 ms/op
     p(99.9990) =     27.043 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.199 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
Iteration   1: 3.573 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  19.956 ms/op
                 getUser·p0.9999: 23.465 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.464 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  21.565 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  18.784 ms/op
                 getUser·p0.9999: 28.364 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273159
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5952 
    [ 2.500,  5.000) = 258576 
    [ 5.000,  7.500) = 7127 
    [ 7.500, 10.000) = 1065 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     19.033 ms/op
     p(99.9900) =     26.751 ms/op
     p(99.9990) =     28.930 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.234 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.014 ms/op
Iteration   1: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  17.024 ms/op
                 listUser·p0.9999: 27.933 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 3.915 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.138 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.939 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241293
  mean =      3.976 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 234162 
    [ 5.000,  7.500) = 5183 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     26.108 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.200 ± 1.400  ops/ms
ClientPb.existUser                       thrpt       3   9.749 ± 2.276  ops/ms
ClientPb.getUser                         thrpt       3   9.167 ± 1.743  ops/ms
ClientPb.listUser                        thrpt       3   7.921 ± 3.570  ops/ms
ClientPb.createUser                       avgt       3   3.369 ± 1.339   ms/op
ClientPb.existUser                        avgt       3   3.252 ± 0.479   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 1.148   ms/op
ClientPb.listUser                         avgt       3   3.913 ± 1.122   ms/op
ClientPb.createUser                     sample  278179   3.451 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.353           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.146           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.457           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  285045   3.367 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.389           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.805           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  273159   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.059           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.033           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.751           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  241293   3.976 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672           ms/op
