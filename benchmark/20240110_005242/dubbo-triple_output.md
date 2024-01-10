# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.072 ops/ms
# Warmup Iteration   2: 12.291 ops/ms
# Warmup Iteration   3: 12.666 ops/ms
Iteration   1: 12.792 ops/ms
Iteration   2: 12.897 ops/ms
Iteration   3: 12.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.839 ±(99.9%) 0.971 ops/ms [Average]
  (min, avg, max) = (12.792, 12.839, 12.897), stdev = 0.053
  CI (99.9%): [11.867, 13.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.146 ops/ms
# Warmup Iteration   2: 12.805 ops/ms
# Warmup Iteration   3: 13.008 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.952 ops/ms
Iteration   3: 13.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.990 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (12.919, 12.990, 13.098), stdev = 0.095
  CI (99.9%): [11.253, 14.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.010 ops/ms
# Warmup Iteration   2: 12.795 ops/ms
# Warmup Iteration   3: 12.829 ops/ms
Iteration   1: 13.058 ops/ms
Iteration   2: 13.036 ops/ms
Iteration   3: 13.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.050 ±(99.9%) 0.218 ops/ms [Average]
  (min, avg, max) = (13.036, 13.050, 13.058), stdev = 0.012
  CI (99.9%): [12.832, 13.268] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ops/ms
# Warmup Iteration   2: 10.561 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.794 ±(99.9%) 1.006 ops/ms [Average]
  (min, avg, max) = (10.734, 10.794, 10.841), stdev = 0.055
  CI (99.9%): [9.788, 11.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.518, 2.528, 2.546), stdev = 0.015
  CI (99.9%): [2.250, 2.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.445, 2.454, 2.469), stdev = 0.013
  CI (99.9%): [2.218, 2.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.062 ms/op [Average]
  (min, avg, max) = (2.478, 2.481, 2.485), stdev = 0.003
  CI (99.9%): [2.419, 2.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
Iteration   3: 2.971 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.971, 2.976, 2.982), stdev = 0.006
  CI (99.9%): [2.874, 3.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  6.245 ms/op
                 createUser·p0.9999: 13.616 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  6.412 ms/op
                 createUser·p0.9999: 12.451 ms/op
                 createUser·p1.00:   12.632 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.004 ms/op
                 createUser·p0.9999: 11.190 ms/op
                 createUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389666
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 193547 
    [ 2.500,  3.750) = 192632 
    [ 3.750,  5.000) = 2580 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 138 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      8.918 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.310 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.130 ms/op
                 existUser·p0.9999: 13.807 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.511 ms/op
                 existUser·p0.9999: 15.374 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  6.835 ms/op
                 existUser·p0.9999: 11.747 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397504
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 200077 
    [ 2.500,  3.750) = 195161 
    [ 3.750,  5.000) = 1608 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.416 ms/op
     p(99.9000) =      6.152 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     15.795 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.469 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 14.259 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  9.833 ms/op
                 getUser·p0.9999: 11.673 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.892 ms/op
                 getUser·p0.9999: 10.487 ms/op
                 getUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379035
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 186526 
    [ 2.500,  3.750) = 188117 
    [ 3.750,  5.000) = 3351 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      6.913 ms/op
     p(99.9900) =     13.453 ms/op
     p(99.9990) =     14.421 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.710 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.985 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.937 ms/op
                 listUser·p0.9999: 12.064 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.843 ms/op
                 listUser·p1.00:   12.321 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.673 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  9.013 ms/op
                 listUser·p0.9999: 10.833 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321567
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 154 
    [ 1.250,  2.500) = 98417 
    [ 2.500,  3.750) = 185383 
    [ 3.750,  5.000) = 31193 
    [ 5.000,  6.250) = 5354 
    [ 6.250,  7.500) = 467 
    [ 7.500,  8.750) = 241 
    [ 8.750, 10.000) = 200 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      8.986 ms/op
     p(99.9900) =     11.734 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.839 ± 0.971  ops/ms
ClientPb.existUser                       thrpt       3  12.990 ± 1.736  ops/ms
ClientPb.getUser                         thrpt       3  13.050 ± 0.218  ops/ms
ClientPb.listUser                        thrpt       3  10.794 ± 1.006  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.278   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.236   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.062   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.101   ms/op
ClientPb.createUser                     sample  389666   2.460 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.739           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.918           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.498           ms/op
ClientPb.existUser                      sample  397504   2.413 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.860           ms/op
ClientPb.getUser                        sample  379035   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.913           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.453           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  321567   2.983 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.673           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.986           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.734           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.321           ms/op
