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
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 6.123 ops/ms
# Warmup Iteration   3: 8.667 ops/ms
Iteration   1: 9.476 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.420 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (9.345, 9.420, 9.476), stdev = 0.068
  CI (99.9%): [8.179, 10.662] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.324 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 9.547 ops/ms
Iteration   1: 9.682 ops/ms
Iteration   2: 9.795 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.784 ±(99.9%) 1.778 ops/ms [Average]
  (min, avg, max) = (9.682, 9.784, 9.876), stdev = 0.097
  CI (99.9%): [8.006, 11.562] (assumes normal distribution)


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
# Warmup Iteration   1: 3.041 ops/ms
# Warmup Iteration   2: 8.399 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.574 ops/ms
Iteration   2: 9.633 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.599 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (9.574, 9.599, 9.633), stdev = 0.030
  CI (99.9%): [9.043, 10.155] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 7.306 ops/ms
# Warmup Iteration   3: 8.057 ops/ms
Iteration   1: 7.651 ops/ms
Iteration   2: 7.883 ops/ms
Iteration   3: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.907 ±(99.9%) 4.897 ops/ms [Average]
  (min, avg, max) = (7.651, 7.907, 8.186), stdev = 0.268
  CI (99.9%): [3.010, 12.803] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.134 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.005 ms/op
Iteration   1: 3.438 ±(99.9%) 0.004 ms/op
Iteration   2: 3.537 ±(99.9%) 0.007 ms/op
Iteration   3: 3.370 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.448 ±(99.9%) 1.532 ms/op [Average]
  (min, avg, max) = (3.370, 3.448, 3.537), stdev = 0.084
  CI (99.9%): [1.916, 4.980] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.371 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.006 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
Iteration   2: 3.201 ±(99.9%) 0.004 ms/op
Iteration   3: 3.311 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.251 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.201, 3.251, 3.311), stdev = 0.055
  CI (99.9%): [2.242, 4.260] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.992 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.007 ms/op
Iteration   1: 3.487 ±(99.9%) 0.008 ms/op
Iteration   2: 3.426 ±(99.9%) 0.008 ms/op
Iteration   3: 3.389 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.434 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.389, 3.434, 3.487), stdev = 0.050
  CI (99.9%): [2.530, 4.338] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.692 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.005 ms/op
Iteration   1: 4.035 ±(99.9%) 0.007 ms/op
Iteration   2: 3.934 ±(99.9%) 0.013 ms/op
Iteration   3: 3.880 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.950 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.880, 3.950, 4.035), stdev = 0.079
  CI (99.9%): [2.513, 5.386] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.647 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
Iteration   1: 3.365 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.951 ms/op
                 createUser·p0.999:  20.540 ms/op
                 createUser·p0.9999: 24.718 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   2: 3.460 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  23.745 ms/op
                 createUser·p0.9999: 26.739 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  17.958 ms/op
                 createUser·p0.9999: 34.308 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282461
  mean =      3.400 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11333 
    [ 2.500,  5.000) = 263969 
    [ 5.000,  7.500) = 6115 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     18.242 ms/op
     p(99.9900) =     32.932 ms/op
     p(99.9990) =     34.888 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.239 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 26.480 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  9.008 ms/op
                 existUser·p0.9999: 27.886 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 3.302 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  16.378 ms/op
                 existUser·p0.9999: 29.797 ms/op
                 existUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291716
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13771 
    [ 2.500,  5.000) = 271526 
    [ 5.000,  7.500) = 5762 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.081 ms/op
     p(99.9900) =     28.961 ms/op
     p(99.9990) =     30.218 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.849 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.011 ms/op
Iteration   1: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  21.529 ms/op
                 getUser·p0.9999: 31.813 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   2: 3.480 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 31.523 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  21.096 ms/op
                 getUser·p0.9999: 28.665 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275547
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9600 
    [ 2.500,  5.000) = 259770 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     12.106 ms/op
     p(99.9900) =     31.406 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 11.625 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.014 ms/op
Iteration   1: 3.992 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  21.858 ms/op
                 listUser·p0.9999: 29.658 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.556 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 21.726 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 3.942 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  16.121 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240778
  mean =      3.981 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 231455 
    [ 5.000,  7.500) = 6742 
    [ 7.500, 10.000) = 1666 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.017 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     18.325 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     30.532 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.420 ± 1.241  ops/ms
ClientPb.existUser                       thrpt       3   9.784 ± 1.778  ops/ms
ClientPb.getUser                         thrpt       3   9.599 ± 0.556  ops/ms
ClientPb.listUser                        thrpt       3   7.907 ± 4.897  ops/ms
ClientPb.createUser                       avgt       3   3.448 ± 1.532   ms/op
ClientPb.existUser                        avgt       3   3.251 ± 1.009   ms/op
ClientPb.getUser                          avgt       3   3.434 ± 0.904   ms/op
ClientPb.listUser                         avgt       3   3.950 ± 1.436   ms/op
ClientPb.createUser                     sample  282461   3.400 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.163           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.932           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  291716   3.290 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.376           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.961           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.605           ms/op
ClientPb.getUser                        sample  275547   3.482 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.757           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.106           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.406           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  240778   3.981 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.017           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.325           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.410           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.654           ms/op
