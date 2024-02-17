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
# Warmup Iteration   1: 4.759 ops/ms
# Warmup Iteration   2: 12.024 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.532 ops/ms
Iteration   2: 12.661 ops/ms
Iteration   3: 12.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.685 ±(99.9%) 3.025 ops/ms [Average]
  (min, avg, max) = (12.532, 12.685, 12.861), stdev = 0.166
  CI (99.9%): [9.659, 15.710] (assumes normal distribution)


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
# Warmup Iteration   1: 8.419 ops/ms
# Warmup Iteration   2: 13.151 ops/ms
# Warmup Iteration   3: 13.388 ops/ms
Iteration   1: 13.280 ops/ms
Iteration   2: 13.313 ops/ms
Iteration   3: 13.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.318 ±(99.9%) 0.744 ops/ms [Average]
  (min, avg, max) = (13.280, 13.318, 13.361), stdev = 0.041
  CI (99.9%): [12.574, 14.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.512 ops/ms
# Warmup Iteration   2: 12.680 ops/ms
# Warmup Iteration   3: 12.952 ops/ms
Iteration   1: 13.102 ops/ms
Iteration   2: 13.168 ops/ms
Iteration   3: 12.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.070 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (12.939, 13.070, 13.168), stdev = 0.118
  CI (99.9%): [10.923, 15.217] (assumes normal distribution)


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
# Warmup Iteration   1: 6.973 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 10.834 ops/ms
Iteration   1: 10.856 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.815 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (10.776, 10.815, 10.856), stdev = 0.040
  CI (99.9%): [10.082, 11.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (2.473, 2.488, 2.514), stdev = 0.023
  CI (99.9%): [2.075, 2.901] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (2.415, 2.435, 2.448), stdev = 0.018
  CI (99.9%): [2.105, 2.765] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.457 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.446, 2.457, 2.476), stdev = 0.017
  CI (99.9%): [2.153, 2.760] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.005 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
Iteration   2: 2.945 ±(99.9%) 0.006 ms/op
Iteration   3: 2.979 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.945, 2.964, 2.979), stdev = 0.017
  CI (99.9%): [2.648, 3.280] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.866 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.984 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  10.766 ms/op
                 createUser·p0.9999: 14.681 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  6.575 ms/op
                 createUser·p0.9999: 11.207 ms/op
                 createUser·p1.00:   11.977 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.709 ms/op
                 createUser·p0.999:  7.956 ms/op
                 createUser·p0.9999: 10.420 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389805
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 191904 
    [ 2.500,  3.750) = 194265 
    [ 3.750,  5.000) = 2833 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 157 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.834 ms/op
     p(99.9900) =     13.796 ms/op
     p(99.9990) =     14.862 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.235 ms/op
                 existUser·p0.9999: 13.894 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  7.267 ms/op
                 existUser·p0.9999: 13.662 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.527 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 10.595 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395094
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 195845 
    [ 2.500,  3.750) = 196514 
    [ 3.750,  5.000) = 2050 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      7.175 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.955 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.846 ms/op
                 getUser·p0.999:  7.493 ms/op
                 getUser·p0.9999: 12.599 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.126 ms/op
                 getUser·p0.99:   3.981 ms/op
                 getUser·p0.999:  6.076 ms/op
                 getUser·p0.9999: 11.596 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390736
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 197807 
    [ 2.500,  3.750) = 188427 
    [ 3.750,  5.000) = 3541 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     15.550 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.009 ms/op
Iteration   1: 2.934 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 13.717 ms/op
                 listUser·p1.00:   14.778 ms/op

Iteration   3: 2.930 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.419 ms/op
                 listUser·p0.9999: 10.940 ms/op
                 listUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326115
  mean =      2.941 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 107883 
    [ 2.500,  3.750) = 181366 
    [ 3.750,  5.000) = 30185 
    [ 5.000,  6.250) = 5387 
    [ 6.250,  7.500) = 407 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 393 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     12.186 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.685 ± 3.025  ops/ms
ClientPb.existUser                       thrpt       3  13.318 ± 0.744  ops/ms
ClientPb.getUser                         thrpt       3  13.070 ± 2.147  ops/ms
ClientPb.listUser                        thrpt       3  10.815 ± 0.733  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.413   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.330   ms/op
ClientPb.getUser                          avgt       3   2.457 ± 0.304   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.316   ms/op
ClientPb.createUser                     sample  389805   2.459 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.796           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.793           ms/op
ClientPb.existUser                      sample  395094   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.496           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.175           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  390736   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.909           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  326115   2.941 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.186           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.778           ms/op
