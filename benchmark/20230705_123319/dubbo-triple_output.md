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
# Warmup Iteration   1: 1.801 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 8.610 ops/ms
Iteration   1: 8.869 ops/ms
Iteration   2: 9.018 ops/ms
Iteration   3: 9.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.014 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (8.869, 9.014, 9.155), stdev = 0.143
  CI (99.9%): [6.406, 11.622] (assumes normal distribution)


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
# Warmup Iteration   1: 3.049 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 9.702 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.747 ops/ms
Iteration   3: 9.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.637 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (9.432, 9.637, 9.747), stdev = 0.178
  CI (99.9%): [6.396, 12.879] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 7.432 ops/ms
# Warmup Iteration   3: 8.911 ops/ms
Iteration   1: 9.180 ops/ms
Iteration   2: 9.323 ops/ms
Iteration   3: 8.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.155 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (8.963, 9.155, 9.323), stdev = 0.181
  CI (99.9%): [5.845, 12.466] (assumes normal distribution)


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
# Warmup Iteration   1: 2.747 ops/ms
# Warmup Iteration   2: 6.891 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 7.706 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 7.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.794 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (7.706, 7.794, 7.901), stdev = 0.099
  CI (99.9%): [5.984, 9.604] (assumes normal distribution)


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.004 ms/op
Iteration   1: 3.390 ±(99.9%) 0.008 ms/op
Iteration   2: 3.553 ±(99.9%) 0.010 ms/op
Iteration   3: 3.675 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.539 ±(99.9%) 2.602 ms/op [Average]
  (min, avg, max) = (3.390, 3.539, 3.675), stdev = 0.143
  CI (99.9%): [0.937, 6.141] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.017 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.006 ms/op
Iteration   1: 3.312 ±(99.9%) 0.010 ms/op
Iteration   2: 3.318 ±(99.9%) 0.003 ms/op
Iteration   3: 3.257 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.296 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.257, 3.296, 3.318), stdev = 0.034
  CI (99.9%): [2.676, 3.915] (assumes normal distribution)


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
# Warmup Iteration   1: 9.171 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.003 ms/op
Iteration   1: 3.477 ±(99.9%) 0.007 ms/op
Iteration   2: 3.430 ±(99.9%) 0.005 ms/op
Iteration   3: 3.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.468 ±(99.9%) 0.632 ms/op [Average]
  (min, avg, max) = (3.430, 3.468, 3.498), stdev = 0.035
  CI (99.9%): [2.836, 4.101] (assumes normal distribution)


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
# Warmup Iteration   1: 10.231 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.961 ±(99.9%) 0.013 ms/op
Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
Iteration   3: 3.890 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.946 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (3.890, 3.946, 3.987), stdev = 0.051
  CI (99.9%): [3.023, 4.869] (assumes normal distribution)


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
# Warmup Iteration   1: 9.067 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.012 ms/op
Iteration   1: 3.402 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  19.292 ms/op
                 createUser·p0.9999: 22.222 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.504 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  21.520 ms/op
                 createUser·p0.9999: 26.137 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  18.155 ms/op
                 createUser·p0.9999: 27.116 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277843
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4257 
    [ 2.500,  5.000) = 267800 
    [ 5.000,  7.500) = 4622 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     18.748 ms/op
     p(99.9900) =     26.327 ms/op
     p(99.9990) =     27.732 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 9.800 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.306 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  17.457 ms/op
                 existUser·p0.9999: 23.747 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  20.891 ms/op
                 existUser·p0.9999: 30.159 ms/op
                 existUser·p1.00:   31.490 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 27.136 ms/op
                 existUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284151
  mean =      3.375 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8488 
    [ 2.500,  5.000) = 269901 
    [ 5.000,  7.500) = 4584 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 152 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     28.735 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 10.297 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.266 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.010 ms/op
Iteration   1: 3.513 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.714 ms/op
                 getUser·p0.999:  21.656 ms/op
                 getUser·p0.9999: 27.456 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 3.511 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.593 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 25.096 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  22.103 ms/op
                 getUser·p0.9999: 34.358 ms/op
                 getUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274738
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6960 
    [ 2.500,  5.000) = 259499 
    [ 5.000,  7.500) = 6724 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.886 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     37.175 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 11.111 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
Iteration   1: 4.092 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  23.167 ms/op
                 listUser·p0.9999: 28.762 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 4.182 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  15.787 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.103 ms/op

Iteration   3: 4.023 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.606 ms/op
                 listUser·p0.9999: 18.679 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234116
  mean =      4.098 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 222223 
    [ 5.000,  7.500) = 9168 
    [ 7.500, 10.000) = 1966 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     17.068 ms/op
     p(99.9900) =     27.367 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.014 ± 2.608  ops/ms
ClientPb.existUser                       thrpt       3   9.637 ± 3.242  ops/ms
ClientPb.getUser                         thrpt       3   9.155 ± 3.311  ops/ms
ClientPb.listUser                        thrpt       3   7.794 ± 1.810  ops/ms
ClientPb.createUser                       avgt       3   3.539 ± 2.602   ms/op
ClientPb.existUser                        avgt       3   3.296 ± 0.620   ms/op
ClientPb.getUser                          avgt       3   3.468 ± 0.632   ms/op
ClientPb.listUser                         avgt       3   3.946 ± 0.923   ms/op
ClientPb.createUser                     sample  277843   3.455 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.432           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.748           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.327           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  284151   3.375 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.893           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.735           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.490           ms/op
ClientPb.getUser                        sample  274738   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.994           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.886           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.523           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  234116   4.098 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.068           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.367           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
