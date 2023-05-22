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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 5.772 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 9.474 ops/ms
Iteration   2: 9.670 ops/ms
Iteration   3: 9.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.518 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (9.412, 9.518, 9.670), stdev = 0.135
  CI (99.9%): [7.057, 11.980] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 9.025 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 9.903 ops/ms
Iteration   3: 10.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.914 ±(99.9%) 2.566 ops/ms [Average]
  (min, avg, max) = (9.779, 9.914, 10.059), stdev = 0.141
  CI (99.9%): [7.348, 12.480] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 9.626 ops/ms
Iteration   1: 9.302 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 9.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.269 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (9.220, 9.269, 9.302), stdev = 0.043
  CI (99.9%): [8.478, 10.059] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.999 ops/ms
# Warmup Iteration   2: 7.445 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 8.108 ops/ms
Iteration   2: 8.178 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.099 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (8.010, 8.099, 8.178), stdev = 0.085
  CI (99.9%): [6.555, 9.642] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.837 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.007 ms/op
Iteration   1: 3.425 ±(99.9%) 0.008 ms/op
Iteration   2: 3.500 ±(99.9%) 0.006 ms/op
Iteration   3: 3.333 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.333, 3.419, 3.500), stdev = 0.083
  CI (99.9%): [1.900, 4.939] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.679 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.004 ms/op
Iteration   1: 3.210 ±(99.9%) 0.010 ms/op
Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
Iteration   3: 3.261 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.210, 3.253, 3.289), stdev = 0.040
  CI (99.9%): [2.528, 3.979] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.573 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.005 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
Iteration   2: 3.333 ±(99.9%) 0.008 ms/op
Iteration   3: 3.264 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.320 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.264, 3.320, 3.361), stdev = 0.050
  CI (99.9%): [2.406, 4.233] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.511 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.012 ms/op
Iteration   1: 4.006 ±(99.9%) 0.010 ms/op
Iteration   2: 3.878 ±(99.9%) 0.014 ms/op
Iteration   3: 3.815 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.899 ±(99.9%) 1.778 ms/op [Average]
  (min, avg, max) = (3.815, 3.899, 4.006), stdev = 0.097
  CI (99.9%): [2.121, 5.678] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.178 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  14.786 ms/op
                 createUser·p0.9999: 28.167 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 3.298 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  13.139 ms/op
                 createUser·p0.9999: 22.812 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 24.262 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289885
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10398 
    [ 2.500,  5.000) = 274304 
    [ 5.000,  7.500) = 4135 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     26.282 ms/op
     p(99.9990) =     28.509 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 7.763 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  9.776 ms/op
                 existUser·p0.9999: 25.860 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  17.236 ms/op
                 existUser·p0.9999: 26.323 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295007
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10155 
    [ 2.500,  5.000) = 280280 
    [ 5.000,  7.500) = 3730 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.578 ms/op
     p(99.9900) =     25.788 ms/op
     p(99.9990) =     26.961 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 9.364 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
Iteration   1: 3.466 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  9.661 ms/op
                 getUser·p0.9999: 21.750 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   6.491 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 30.716 ms/op
                 getUser·p1.00:   32.997 ms/op

Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.063 ms/op
                 getUser·p0.999:  11.613 ms/op
                 getUser·p0.9999: 26.323 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286553
  mean =      3.350 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8013 
    [ 2.500,  5.000) = 272790 
    [ 5.000,  7.500) = 4822 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.002 ms/op
     p(99.9900) =     29.385 ms/op
     p(99.9990) =     32.159 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.447 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.434 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.013 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  19.779 ms/op
                 listUser·p0.9999: 22.270 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 3.976 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.339 ms/op
                 listUser·p0.999:  14.460 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.862 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.093 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244502
  mean =      3.924 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 236899 
    [ 5.000,  7.500) = 5635 
    [ 7.500, 10.000) = 1197 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.061 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     21.383 ms/op
     p(99.9990) =     22.908 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.518 ± 2.462  ops/ms
ClientPb.existUser                       thrpt       3   9.914 ± 2.566  ops/ms
ClientPb.getUser                         thrpt       3   9.269 ± 0.791  ops/ms
ClientPb.listUser                        thrpt       3   8.099 ± 1.543  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 1.519   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 0.726   ms/op
ClientPb.getUser                          avgt       3   3.320 ± 0.914   ms/op
ClientPb.listUser                         avgt       3   3.899 ± 1.778   ms/op
ClientPb.createUser                     sample  289885   3.312 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.547           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.282           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  295007   3.249 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.202           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.788           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  286553   3.350 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.771           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.890           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.002           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  244502   3.924 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.061           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.383           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.003           ms/op
