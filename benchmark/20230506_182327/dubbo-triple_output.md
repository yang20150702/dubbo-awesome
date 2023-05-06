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
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 6.579 ops/ms
# Warmup Iteration   3: 9.256 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 9.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.127 ±(99.9%) 5.794 ops/ms [Average]
  (min, avg, max) = (9.849, 10.127, 10.473), stdev = 0.318
  CI (99.9%): [4.333, 15.922] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.462 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.645 ops/ms
Iteration   2: 10.684 ops/ms
Iteration   3: 10.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.605 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (10.486, 10.605, 10.684), stdev = 0.105
  CI (99.9%): [8.690, 12.520] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 9.251 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 9.755 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.882 ±(99.9%) 3.541 ops/ms [Average]
  (min, avg, max) = (9.755, 9.882, 10.106), stdev = 0.194
  CI (99.9%): [6.341, 13.423] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.326 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.453 ops/ms
Iteration   2: 8.764 ops/ms
Iteration   3: 8.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.589 ±(99.9%) 2.912 ops/ms [Average]
  (min, avg, max) = (8.453, 8.589, 8.764), stdev = 0.160
  CI (99.9%): [5.676, 11.501] (assumes normal distribution)


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
# Warmup Iteration   1: 8.152 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.004 ms/op
Iteration   2: 3.221 ±(99.9%) 0.006 ms/op
Iteration   3: 3.065 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.142 ±(99.9%) 1.424 ms/op [Average]
  (min, avg, max) = (3.065, 3.142, 3.221), stdev = 0.078
  CI (99.9%): [1.718, 4.566] (assumes normal distribution)


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
# Warmup Iteration   1: 6.669 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.070 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.040, 3.070, 3.126), stdev = 0.048
  CI (99.9%): [2.189, 3.952] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.295 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.002 ms/op
Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
Iteration   3: 3.090 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.117 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.081, 3.117, 3.179), stdev = 0.054
  CI (99.9%): [2.126, 4.108] (assumes normal distribution)


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
# Warmup Iteration   1: 9.501 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.007 ms/op
Iteration   1: 3.648 ±(99.9%) 0.012 ms/op
Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
Iteration   3: 3.814 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (3.648, 3.771, 3.851), stdev = 0.108
  CI (99.9%): [1.796, 5.745] (assumes normal distribution)


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
# Warmup Iteration   1: 7.451 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.010 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  11.336 ms/op
                 createUser·p0.9999: 19.755 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  14.902 ms/op
                 createUser·p0.9999: 30.183 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304524
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18219 
    [ 2.500,  5.000) = 279852 
    [ 5.000,  7.500) = 5744 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.671 ms/op
     p(99.9900) =     28.002 ms/op
     p(99.9990) =     30.735 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 6.853 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 24.404 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 21.700 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309948
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19698 
    [ 2.500,  5.000) = 284323 
    [ 5.000,  7.500) = 5292 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     23.265 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.934 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
Iteration   1: 3.110 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  18.617 ms/op
                 getUser·p0.9999: 23.710 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  12.663 ms/op
                 getUser·p0.9999: 24.533 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 307496
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10140 
    [ 2.500,  5.000) = 291375 
    [ 5.000,  7.500) = 5073 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     14.754 ms/op
     p(99.9900) =     23.405 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 9.535 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.010 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  18.104 ms/op
                 listUser·p0.9999: 21.496 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 20.562 ms/op
                 listUser·p1.00:   23.429 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.205 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247141
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 236831 
    [ 5.000,  7.500) = 8436 
    [ 7.500, 10.000) = 1098 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     21.262 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.127 ± 5.794  ops/ms
ClientPb.existUser                       thrpt       3  10.605 ± 1.915  ops/ms
ClientPb.getUser                         thrpt       3   9.882 ± 3.541  ops/ms
ClientPb.listUser                        thrpt       3   8.589 ± 2.912  ops/ms
ClientPb.createUser                       avgt       3   3.142 ± 1.424   ms/op
ClientPb.existUser                        avgt       3   3.070 ± 0.882   ms/op
ClientPb.getUser                          avgt       3   3.117 ± 0.991   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 1.974   ms/op
ClientPb.createUser                     sample  304524   3.150 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.011           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.671           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.002           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  309948   3.095 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.265           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  307496   3.121 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.856           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.754           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.405           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.133           ms/op
ClientPb.listUser                       sample  247141   3.882 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.262           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.429           ms/op
