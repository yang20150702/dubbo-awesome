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
# Warmup Iteration   1: 1.167 ops/ms
# Warmup Iteration   2: 2.473 ops/ms
# Warmup Iteration   3: 5.277 ops/ms
Iteration   1: 5.650 ops/ms
Iteration   2: 5.749 ops/ms
Iteration   3: 5.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.778 ±(99.9%) 2.658 ops/ms [Average]
  (min, avg, max) = (5.650, 5.778, 5.936), stdev = 0.146
  CI (99.9%): [3.121, 8.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.637 ops/ms
# Warmup Iteration   2: 4.969 ops/ms
# Warmup Iteration   3: 5.851 ops/ms
Iteration   1: 6.163 ops/ms
Iteration   2: 5.986 ops/ms
Iteration   3: 6.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.100 ±(99.9%) 1.815 ops/ms [Average]
  (min, avg, max) = (5.986, 6.100, 6.163), stdev = 0.100
  CI (99.9%): [4.285, 7.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.608 ops/ms
# Warmup Iteration   2: 4.720 ops/ms
# Warmup Iteration   3: 5.536 ops/ms
Iteration   1: 5.609 ops/ms
Iteration   2: 6.104 ops/ms
Iteration   3: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.911 ±(99.9%) 4.830 ops/ms [Average]
  (min, avg, max) = (5.609, 5.911, 6.104), stdev = 0.265
  CI (99.9%): [1.081, 10.741] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.685 ops/ms
# Warmup Iteration   2: 4.104 ops/ms
# Warmup Iteration   3: 5.011 ops/ms
Iteration   1: 5.244 ops/ms
Iteration   2: 5.272 ops/ms
Iteration   3: 5.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.192 ±(99.9%) 2.101 ops/ms [Average]
  (min, avg, max) = (5.060, 5.192, 5.272), stdev = 0.115
  CI (99.9%): [3.092, 7.293] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.495 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 6.274 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.725 ±(99.9%) 0.012 ms/op
Iteration   1: 5.280 ±(99.9%) 0.018 ms/op
Iteration   2: 5.317 ±(99.9%) 0.013 ms/op
Iteration   3: 5.441 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.346 ±(99.9%) 1.541 ms/op [Average]
  (min, avg, max) = (5.280, 5.346, 5.441), stdev = 0.084
  CI (99.9%): [3.805, 6.887] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.913 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.573 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.265 ±(99.9%) 0.006 ms/op
Iteration   1: 5.084 ±(99.9%) 0.017 ms/op
Iteration   2: 5.165 ±(99.9%) 0.011 ms/op
Iteration   3: 5.325 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.191 ±(99.9%) 2.235 ms/op [Average]
  (min, avg, max) = (5.084, 5.191, 5.325), stdev = 0.123
  CI (99.9%): [2.956, 7.426] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.384 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.879 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.010 ms/op
Iteration   1: 5.352 ±(99.9%) 0.008 ms/op
Iteration   2: 5.451 ±(99.9%) 0.011 ms/op
Iteration   3: 5.643 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.482 ±(99.9%) 2.701 ms/op [Average]
  (min, avg, max) = (5.352, 5.482, 5.643), stdev = 0.148
  CI (99.9%): [2.781, 8.184] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.143 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.379 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.216 ±(99.9%) 0.017 ms/op
Iteration   1: 6.336 ±(99.9%) 0.017 ms/op
Iteration   2: 6.443 ±(99.9%) 0.017 ms/op
Iteration   3: 6.018 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.266 ±(99.9%) 4.034 ms/op [Average]
  (min, avg, max) = (6.018, 6.266, 6.443), stdev = 0.221
  CI (99.9%): [2.232, 10.300] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.681 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 7.513 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.901 ±(99.9%) 0.028 ms/op
Iteration   1: 5.661 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   8.167 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  28.672 ms/op
                 createUser·p0.9999: 33.797 ms/op
                 createUser·p1.00:   36.504 ms/op

Iteration   2: 5.240 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   9.286 ms/op
                 createUser·p0.999:  27.292 ms/op
                 createUser·p0.9999: 30.942 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   3: 5.551 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  14.280 ms/op
                 createUser·p0.9999: 31.621 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175187
  mean =      5.478 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 63707 
    [ 5.000,  7.500) = 101986 
    [ 7.500, 10.000) = 7340 
    [10.000, 12.500) = 1515 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.273 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     20.408 ms/op
     p(99.9900) =     32.522 ms/op
     p(99.9990) =     36.405 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.269 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.667 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.429 ±(99.9%) 0.021 ms/op
Iteration   1: 5.255 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  15.126 ms/op
                 existUser·p0.9999: 26.531 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 5.098 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.075 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  25.583 ms/op
                 existUser·p0.9999: 30.840 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 5.222 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  27.104 ms/op
                 existUser·p0.9999: 31.453 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184909
  mean =      5.191 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 100359 
    [ 5.000,  7.500) = 76103 
    [ 7.500, 10.000) = 6607 
    [10.000, 12.500) = 1277 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.316 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     17.695 ms/op
     p(99.9900) =     30.884 ms/op
     p(99.9990) =     31.679 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.058 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.038 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.549 ±(99.9%) 0.020 ms/op
Iteration   1: 5.188 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.045 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  22.560 ms/op
                 getUser·p0.9999: 25.811 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   2: 5.369 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.572 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   12.347 ms/op
                 getUser·p0.999:  26.986 ms/op
                 getUser·p0.9999: 30.738 ms/op
                 getUser·p1.00:   31.850 ms/op

Iteration   3: 5.671 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   8.036 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  18.077 ms/op
                 getUser·p0.9999: 33.261 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177552
  mean =      5.402 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 80407 
    [ 5.000,  7.500) = 86612 
    [ 7.500, 10.000) = 7504 
    [10.000, 12.500) = 1807 
    [12.500, 15.000) = 738 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     20.331 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     34.239 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.985 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 8.525 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.981 ±(99.9%) 0.027 ms/op
Iteration   1: 6.493 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.741 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  28.828 ms/op
                 listUser·p0.9999: 35.793 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   2: 6.452 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.867 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  28.410 ms/op
                 listUser·p0.9999: 31.326 ms/op
                 listUser·p1.00:   36.962 ms/op

Iteration   3: 6.407 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.569 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  22.433 ms/op
                 listUser·p0.9999: 29.492 ms/op
                 listUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148764
  mean =      6.451 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 4591 
    [ 5.000,  7.500) = 127345 
    [ 7.500, 10.000) = 12630 
    [10.000, 12.500) = 3010 
    [12.500, 15.000) = 644 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      7.651 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     27.853 ms/op
     p(99.9900) =     32.103 ms/op
     p(99.9990) =     36.803 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.778 ± 2.658  ops/ms
ClientPb.existUser                       thrpt       3   6.100 ± 1.815  ops/ms
ClientPb.getUser                         thrpt       3   5.911 ± 4.830  ops/ms
ClientPb.listUser                        thrpt       3   5.192 ± 2.101  ops/ms
ClientPb.createUser                       avgt       3   5.346 ± 1.541   ms/op
ClientPb.existUser                        avgt       3   5.191 ± 2.235   ms/op
ClientPb.getUser                          avgt       3   5.482 ± 2.701   ms/op
ClientPb.listUser                         avgt       3   6.266 ± 4.034   ms/op
ClientPb.createUser                     sample  175187   5.478 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.273           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.387           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.408           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.522           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.504           ms/op
ClientPb.existUser                      sample  184909   5.191 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.316           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.945           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.375           ms/op
ClientPb.getUser                        sample  177552   5.402 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.190           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.506           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  148764   6.451 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.853           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.103           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.962           ms/op
