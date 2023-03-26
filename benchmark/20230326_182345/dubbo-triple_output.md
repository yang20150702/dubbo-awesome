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
# Warmup Iteration   1: 2.060 ops/ms
# Warmup Iteration   2: 5.585 ops/ms
# Warmup Iteration   3: 8.600 ops/ms
Iteration   1: 9.411 ops/ms
Iteration   2: 9.610 ops/ms
Iteration   3: 9.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.447 ±(99.9%) 2.705 ops/ms [Average]
  (min, avg, max) = (9.320, 9.447, 9.610), stdev = 0.148
  CI (99.9%): [6.742, 12.152] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ops/ms
# Warmup Iteration   2: 9.153 ops/ms
# Warmup Iteration   3: 9.568 ops/ms
Iteration   1: 9.731 ops/ms
Iteration   2: 9.527 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.617 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (9.527, 9.617, 9.731), stdev = 0.104
  CI (99.9%): [7.713, 11.520] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.535 ops/ms
# Warmup Iteration   2: 8.712 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 9.509 ops/ms
Iteration   3: 9.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.278 ±(99.9%) 3.744 ops/ms [Average]
  (min, avg, max) = (9.117, 9.278, 9.509), stdev = 0.205
  CI (99.9%): [5.534, 13.022] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.278 ops/ms
# Warmup Iteration   2: 7.381 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 8.144 ops/ms
Iteration   2: 7.939 ops/ms
Iteration   3: 7.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.018 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (7.939, 8.018, 8.144), stdev = 0.111
  CI (99.9%): [5.998, 10.037] (assumes normal distribution)


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
# Warmup Iteration   1: 9.465 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
Iteration   1: 3.321 ±(99.9%) 0.009 ms/op
Iteration   2: 3.462 ±(99.9%) 0.006 ms/op
Iteration   3: 3.366 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.383 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (3.321, 3.383, 3.462), stdev = 0.072
  CI (99.9%): [2.065, 4.702] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.683 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.012 ms/op
Iteration   1: 3.246 ±(99.9%) 0.005 ms/op
Iteration   2: 3.217 ±(99.9%) 0.009 ms/op
Iteration   3: 3.216 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (3.216, 3.226, 3.246), stdev = 0.017
  CI (99.9%): [2.908, 3.544] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.120 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.003 ms/op
Iteration   1: 3.384 ±(99.9%) 0.006 ms/op
Iteration   2: 3.384 ±(99.9%) 0.005 ms/op
Iteration   3: 3.330 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.366 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.330, 3.366, 3.384), stdev = 0.031
  CI (99.9%): [2.796, 3.936] (assumes normal distribution)


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
# Warmup Iteration   1: 11.191 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.007 ms/op
Iteration   1: 3.883 ±(99.9%) 0.009 ms/op
Iteration   2: 3.789 ±(99.9%) 0.013 ms/op
Iteration   3: 3.881 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.851 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.789, 3.851, 3.883), stdev = 0.054
  CI (99.9%): [2.874, 4.828] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.263 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.430 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.123 ms/op
                 createUser·p0.9999: 25.157 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.371 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  21.009 ms/op
                 createUser·p0.9999: 27.575 ms/op
                 createUser·p1.00:   29.753 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 25.283 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282132
  mean =      3.399 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9979 
    [ 2.500,  5.000) = 264994 
    [ 5.000,  7.500) = 6258 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     18.575 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     29.673 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 8.459 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
Iteration   1: 3.292 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  10.488 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 27.181 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.446 ms/op
                 existUser·p0.999:  14.755 ms/op
                 existUser·p0.9999: 26.210 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293500
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10785 
    [ 2.500,  5.000) = 279131 
    [ 5.000,  7.500) = 2733 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     14.426 ms/op
     p(99.9900) =     33.106 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 8.463 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.011 ms/op
Iteration   1: 3.483 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  19.602 ms/op
                 getUser·p0.9999: 22.670 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  15.307 ms/op
                 getUser·p0.9999: 28.344 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  21.992 ms/op
                 getUser·p0.9999: 26.851 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284469
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5723 
    [ 2.500,  5.000) = 272822 
    [ 5.000,  7.500) = 4804 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     19.549 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.579 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 9.961 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.502 ms/op
                 listUser·p0.999:  17.616 ms/op
                 listUser·p0.9999: 23.890 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.587 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.455 ms/op
                 listUser·p0.9999: 19.166 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.862 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243107
  mean =      3.949 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 235651 
    [ 5.000,  7.500) = 5373 
    [ 7.500, 10.000) = 1208 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     24.346 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.447 ± 2.705  ops/ms
ClientPb.existUser                       thrpt       3   9.617 ± 1.904  ops/ms
ClientPb.getUser                         thrpt       3   9.278 ± 3.744  ops/ms
ClientPb.listUser                        thrpt       3   8.018 ± 2.019  ops/ms
ClientPb.createUser                       avgt       3   3.383 ± 1.318   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 0.318   ms/op
ClientPb.getUser                          avgt       3   3.366 ± 0.570   ms/op
ClientPb.listUser                         avgt       3   3.851 ± 0.977   ms/op
ClientPb.createUser                     sample  282132   3.399 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.907           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.575           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.753           ms/op
ClientPb.existUser                      sample  293500   3.269 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.426           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.106           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  284469   3.370 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.549           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.066           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  243107   3.949 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.660           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
