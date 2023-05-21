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
# Warmup Iteration   1: 1.015 ops/ms
# Warmup Iteration   2: 2.233 ops/ms
# Warmup Iteration   3: 4.702 ops/ms
Iteration   1: 5.432 ops/ms
Iteration   2: 5.607 ops/ms
Iteration   3: 5.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.584 ±(99.9%) 2.588 ops/ms [Average]
  (min, avg, max) = (5.432, 5.584, 5.713), stdev = 0.142
  CI (99.9%): [2.997, 8.172] (assumes normal distribution)


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
# Warmup Iteration   1: 1.401 ops/ms
# Warmup Iteration   2: 4.122 ops/ms
# Warmup Iteration   3: 5.830 ops/ms
Iteration   1: 5.956 ops/ms
Iteration   2: 6.078 ops/ms
Iteration   3: 6.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.048 ±(99.9%) 1.484 ops/ms [Average]
  (min, avg, max) = (5.956, 6.048, 6.110), stdev = 0.081
  CI (99.9%): [4.565, 7.532] (assumes normal distribution)


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
# Warmup Iteration   1: 1.621 ops/ms
# Warmup Iteration   2: 4.844 ops/ms
# Warmup Iteration   3: 5.909 ops/ms
Iteration   1: 5.577 ops/ms
Iteration   2: 5.863 ops/ms
Iteration   3: 5.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.737 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (5.577, 5.737, 5.863), stdev = 0.146
  CI (99.9%): [3.068, 8.407] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.567 ops/ms
# Warmup Iteration   2: 3.628 ops/ms
# Warmup Iteration   3: 4.727 ops/ms
Iteration   1: 4.846 ops/ms
Iteration   2: 4.975 ops/ms
Iteration   3: 5.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.995 ±(99.9%) 2.926 ops/ms [Average]
  (min, avg, max) = (4.846, 4.995, 5.165), stdev = 0.160
  CI (99.9%): [2.069, 7.921] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.967 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.346 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.996 ±(99.9%) 0.010 ms/op
Iteration   1: 5.554 ±(99.9%) 0.014 ms/op
Iteration   2: 5.530 ±(99.9%) 0.012 ms/op
Iteration   3: 5.491 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.525 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (5.491, 5.525, 5.554), stdev = 0.032
  CI (99.9%): [4.942, 6.108] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.940 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.912 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.861 ±(99.9%) 0.008 ms/op
Iteration   1: 5.385 ±(99.9%) 0.020 ms/op
Iteration   2: 5.472 ±(99.9%) 0.015 ms/op
Iteration   3: 5.410 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.422 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (5.385, 5.422, 5.472), stdev = 0.044
  CI (99.9%): [4.612, 6.232] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.007 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.844 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.706 ±(99.9%) 0.008 ms/op
Iteration   1: 5.826 ±(99.9%) 0.010 ms/op
Iteration   2: 5.698 ±(99.9%) 0.011 ms/op
Iteration   3: 5.611 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.712 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (5.611, 5.712, 5.826), stdev = 0.108
  CI (99.9%): [3.744, 7.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.252 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 8.341 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.728 ±(99.9%) 0.011 ms/op
Iteration   1: 6.628 ±(99.9%) 0.011 ms/op
Iteration   2: 6.568 ±(99.9%) 0.016 ms/op
Iteration   3: 6.257 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.484 ±(99.9%) 3.634 ms/op [Average]
  (min, avg, max) = (6.257, 6.484, 6.628), stdev = 0.199
  CI (99.9%): [2.850, 10.118] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.720 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.120 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.210 ±(99.9%) 0.027 ms/op
Iteration   1: 5.580 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.482 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.420 ms/op
                 createUser·p0.999:  26.357 ms/op
                 createUser·p0.9999: 34.573 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   2: 5.656 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.391 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.849 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   10.961 ms/op
                 createUser·p0.999:  26.890 ms/op
                 createUser·p0.9999: 30.793 ms/op
                 createUser·p1.00:   31.818 ms/op

Iteration   3: 5.479 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.490 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.111 ms/op
                 createUser·p0.99:   9.672 ms/op
                 createUser·p0.999:  15.018 ms/op
                 createUser·p0.9999: 33.237 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172229
  mean =      5.571 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 52896 
    [ 5.000,  7.500) = 110483 
    [ 7.500, 10.000) = 6817 
    [10.000, 12.500) = 1365 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.333 ms/op
     p(99.9000) =     23.593 ms/op
     p(99.9900) =     32.531 ms/op
     p(99.9990) =     35.946 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 18.036 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.710 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.619 ±(99.9%) 0.020 ms/op
Iteration   1: 5.511 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.519 ms/op
                 existUser·p0.50:   5.210 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   8.004 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  24.477 ms/op
                 existUser·p0.9999: 27.564 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   2: 5.443 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.593 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.570 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  25.959 ms/op
                 existUser·p0.9999: 32.055 ms/op
                 existUser·p1.00:   32.997 ms/op

Iteration   3: 5.428 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.490 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.737 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   10.454 ms/op
                 existUser·p0.999:  15.714 ms/op
                 existUser·p0.9999: 30.412 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175695
  mean =      5.461 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 70598 
    [ 5.000,  7.500) = 95090 
    [ 7.500, 10.000) = 7642 
    [10.000, 12.500) = 1773 
    [12.500, 15.000) = 338 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.490 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.751 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     20.326 ms/op
     p(99.9900) =     30.788 ms/op
     p(99.9990) =     32.625 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 19.343 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.758 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.562 ±(99.9%) 0.018 ms/op
Iteration   1: 5.695 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.494 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.881 ms/op
                 getUser·p0.95:   8.962 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 28.108 ms/op
                 getUser·p1.00:   28.606 ms/op

Iteration   2: 5.500 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.712 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.545 ms/op
                 getUser·p0.99:   9.974 ms/op
                 getUser·p0.999:  25.035 ms/op
                 getUser·p0.9999: 28.678 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 5.961 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   8.012 ms/op
                 getUser·p0.95:   9.513 ms/op
                 getUser·p0.99:   13.673 ms/op
                 getUser·p0.999:  27.951 ms/op
                 getUser·p0.9999: 31.150 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167901
  mean =      5.713 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 48752 
    [ 5.000,  7.500) = 104775 
    [ 7.500, 10.000) = 10139 
    [10.000, 12.500) = 2715 
    [12.500, 15.000) = 905 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.667 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     23.367 ms/op
     p(99.9900) =     30.743 ms/op
     p(99.9990) =     31.478 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 19.680 ±(99.9%) 0.409 ms/op
# Warmup Iteration   2: 8.091 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.386 ±(99.9%) 0.027 ms/op
Iteration   1: 6.173 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.352 ms/op
                 listUser·p0.99:   12.133 ms/op
                 listUser·p0.999:  26.416 ms/op
                 listUser·p0.9999: 30.403 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 6.292 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   13.287 ms/op
                 listUser·p0.999:  28.189 ms/op
                 listUser·p0.9999: 30.825 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   3: 6.614 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.183 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   13.818 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 29.491 ms/op
                 listUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151007
  mean =      6.354 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 5809 
    [ 5.000,  7.500) = 130479 
    [ 7.500, 10.000) = 9719 
    [10.000, 12.500) = 3154 
    [12.500, 15.000) = 969 
    [15.000, 17.500) = 361 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 101 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.646 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     27.099 ms/op
     p(99.9900) =     30.468 ms/op
     p(99.9990) =     31.354 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.584 ± 2.588  ops/ms
ClientPb.existUser                       thrpt       3   6.048 ± 1.484  ops/ms
ClientPb.getUser                         thrpt       3   5.737 ± 2.670  ops/ms
ClientPb.listUser                        thrpt       3   4.995 ± 2.926  ops/ms
ClientPb.createUser                       avgt       3   5.525 ± 0.583   ms/op
ClientPb.existUser                        avgt       3   5.422 ± 0.810   ms/op
ClientPb.getUser                          avgt       3   5.712 ± 1.967   ms/op
ClientPb.listUser                         avgt       3   6.484 ± 3.634   ms/op
ClientPb.createUser                     sample  172229   5.571 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.391           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.767           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.531           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  175695   5.461 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.751           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.326           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.788           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  167901   5.713 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.809           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.308           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.135           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.667           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.272           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.367           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.743           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  151007   6.354 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.646           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.864           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.099           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.468           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
