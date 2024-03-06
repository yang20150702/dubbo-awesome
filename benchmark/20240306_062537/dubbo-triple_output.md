# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.003 ops/ms
# Warmup Iteration   2: 12.363 ops/ms
# Warmup Iteration   3: 12.643 ops/ms
Iteration   1: 12.780 ops/ms
Iteration   2: 13.005 ops/ms
Iteration   3: 13.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.930 ±(99.9%) 2.368 ops/ms [Average]
  (min, avg, max) = (12.780, 12.930, 13.005), stdev = 0.130
  CI (99.9%): [10.563, 15.298] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.601 ops/ms
# Warmup Iteration   2: 13.526 ops/ms
# Warmup Iteration   3: 13.474 ops/ms
Iteration   1: 13.522 ops/ms
Iteration   2: 13.532 ops/ms
Iteration   3: 13.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.502 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (13.451, 13.502, 13.532), stdev = 0.044
  CI (99.9%): [12.700, 14.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.579 ops/ms
# Warmup Iteration   2: 12.751 ops/ms
# Warmup Iteration   3: 13.011 ops/ms
Iteration   1: 12.838 ops/ms
Iteration   2: 12.904 ops/ms
Iteration   3: 12.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.902 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (12.838, 12.902, 12.963), stdev = 0.062
  CI (99.9%): [11.764, 14.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.814 ops/ms
# Warmup Iteration   2: 10.733 ops/ms
# Warmup Iteration   3: 10.837 ops/ms
Iteration   1: 10.870 ops/ms
Iteration   2: 10.907 ops/ms
Iteration   3: 10.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.895 ±(99.9%) 0.393 ops/ms [Average]
  (min, avg, max) = (10.870, 10.895, 10.908), stdev = 0.022
  CI (99.9%): [10.502, 11.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.438 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.427, 2.438, 2.451), stdev = 0.012
  CI (99.9%): [2.216, 2.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.482 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.386 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.004 ms/op
Iteration   1: 2.355 ±(99.9%) 0.004 ms/op
Iteration   2: 2.375 ±(99.9%) 0.003 ms/op
Iteration   3: 2.366 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.365 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.355, 2.365, 2.375), stdev = 0.010
  CI (99.9%): [2.185, 2.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.004 ms/op
Iteration   1: 2.439 ±(99.9%) 0.004 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.435 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.421, 2.435, 2.445), stdev = 0.012
  CI (99.9%): [2.207, 2.663] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.477 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.005 ms/op
Iteration   1: 2.917 ±(99.9%) 0.006 ms/op
Iteration   2: 2.897 ±(99.9%) 0.004 ms/op
Iteration   3: 2.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.914 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.897, 2.914, 2.927), stdev = 0.015
  CI (99.9%): [2.633, 3.194] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  6.430 ms/op
                 createUser·p0.9999: 13.583 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 12.848 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  8.353 ms/op
                 createUser·p0.9999: 13.451 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386263
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 188712 
    [ 2.500,  3.750) = 192996 
    [ 3.750,  5.000) = 3502 
    [ 5.000,  6.250) = 444 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.277 ms/op
     p(99.9990) =     14.264 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.535 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
Iteration   1: 2.388 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  6.900 ms/op
                 existUser·p0.9999: 13.333 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.553 ms/op
                 existUser·p0.999:  5.499 ms/op
                 existUser·p0.9999: 10.486 ms/op
                 existUser·p1.00:   11.223 ms/op

Iteration   3: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   2.990 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.507 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 400961
  mean =      2.391 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 203044 
    [ 2.500,  3.750) = 195032 
    [ 3.750,  5.000) = 2013 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      6.185 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.937 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.469 ms/op
                 getUser·p0.999:  8.043 ms/op
                 getUser·p0.9999: 13.280 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  8.959 ms/op
                 getUser·p0.9999: 12.076 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  7.052 ms/op
                 getUser·p0.9999: 10.486 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 393962
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 199465 
    [ 2.500,  3.750) = 190007 
    [ 3.750,  5.000) = 2753 
    [ 5.000,  6.250) = 1015 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      7.891 ms/op
     p(99.9900) =     12.626 ms/op
     p(99.9990) =     13.962 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.486 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
Iteration   1: 2.941 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.754 ms/op
                 listUser·p0.9999: 12.257 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   2: 2.924 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.290 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.968 ms/op
                 listUser·p0.9999: 12.856 ms/op
                 listUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326334
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 167 
    [ 1.250,  2.500) = 105373 
    [ 2.500,  3.750) = 185743 
    [ 3.750,  5.000) = 28480 
    [ 5.000,  6.250) = 5396 
    [ 6.250,  7.500) = 577 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 220 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     12.095 ms/op
     p(99.9990) =     13.234 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.930 ± 2.368  ops/ms
ClientPb.existUser                       thrpt       3  13.502 ± 0.802  ops/ms
ClientPb.getUser                         thrpt       3  12.902 ± 1.138  ops/ms
ClientPb.listUser                        thrpt       3  10.895 ± 0.393  ops/ms
ClientPb.createUser                       avgt       3   2.438 ± 0.222   ms/op
ClientPb.existUser                        avgt       3   2.365 ± 0.180   ms/op
ClientPb.getUser                          avgt       3   2.435 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   2.914 ± 0.280   ms/op
ClientPb.createUser                     sample  386263   2.482 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.816           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.437           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.277           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  400961   2.391 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.892           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.185           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  393962   2.435 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.732           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.090           ms/op
ClientPb.listUser                       sample  326334   2.939 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.962           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.095           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.435           ms/op
