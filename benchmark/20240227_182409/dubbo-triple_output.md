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
# Warmup Iteration   1: 4.675 ops/ms
# Warmup Iteration   2: 12.042 ops/ms
# Warmup Iteration   3: 12.622 ops/ms
Iteration   1: 12.868 ops/ms
Iteration   2: 13.124 ops/ms
Iteration   3: 13.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.038 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (12.868, 13.038, 13.124), stdev = 0.147
  CI (99.9%): [10.353, 15.724] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.971 ops/ms
# Warmup Iteration   2: 13.535 ops/ms
# Warmup Iteration   3: 13.623 ops/ms
Iteration   1: 13.466 ops/ms
Iteration   2: 13.484 ops/ms
Iteration   3: 13.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.441 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (13.372, 13.441, 13.484), stdev = 0.061
  CI (99.9%): [12.336, 14.545] (assumes normal distribution)


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
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 12.493 ops/ms
# Warmup Iteration   3: 12.840 ops/ms
Iteration   1: 13.021 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 13.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.076 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (13.021, 13.076, 13.179), stdev = 0.089
  CI (99.9%): [11.452, 14.700] (assumes normal distribution)


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
# Warmup Iteration   1: 6.768 ops/ms
# Warmup Iteration   2: 10.645 ops/ms
# Warmup Iteration   3: 10.813 ops/ms
Iteration   1: 10.873 ops/ms
Iteration   2: 10.809 ops/ms
Iteration   3: 10.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.856 ±(99.9%) 0.746 ops/ms [Average]
  (min, avg, max) = (10.809, 10.856, 10.886), stdev = 0.041
  CI (99.9%): [10.110, 11.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.122 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (2.457, 2.488, 2.518), stdev = 0.031
  CI (99.9%): [1.929, 3.048] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.003 ms/op
Iteration   1: 2.386 ±(99.9%) 0.004 ms/op
Iteration   2: 2.391 ±(99.9%) 0.004 ms/op
Iteration   3: 2.406 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.386, 2.395, 2.406), stdev = 0.011
  CI (99.9%): [2.203, 2.586] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.451 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.443, 2.451, 2.457), stdev = 0.007
  CI (99.9%): [2.325, 2.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (2.951, 2.977, 2.994), stdev = 0.023
  CI (99.9%): [2.553, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.462 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  6.375 ms/op
                 createUser·p0.9999: 13.813 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  9.200 ms/op
                 createUser·p0.9999: 12.195 ms/op
                 createUser·p1.00:   12.714 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 10.751 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388371
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 194757 
    [ 2.500,  3.750) = 189356 
    [ 3.750,  5.000) = 3255 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.491 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.365 ±(99.9%) 0.005 ms/op
Iteration   1: 2.355 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.384 ms/op
                 existUser·p0.90:   2.859 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  6.034 ms/op
                 existUser·p0.9999: 14.127 ms/op
                 existUser·p1.00:   15.270 ms/op

Iteration   2: 2.368 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 13.050 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.900 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.487 ms/op
                 existUser·p0.9999: 11.387 ms/op
                 existUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404598
  mean =      2.370 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 215875 
    [ 2.500,  3.750) = 184954 
    [ 3.750,  5.000) = 2673 
    [ 5.000,  6.250) = 459 
    [ 6.250,  7.500) = 126 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.408 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      8.297 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     15.216 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  7.174 ms/op
                 getUser·p0.9999: 13.437 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.504 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  9.762 ms/op
                 getUser·p0.9999: 15.410 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  7.914 ms/op
                 getUser·p0.9999: 11.130 ms/op
                 getUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385771
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 192191 
    [ 2.500,  3.750) = 188279 
    [ 3.750,  5.000) = 4347 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.507 ms/op
     p(99.9900) =     13.753 ms/op
     p(99.9990) =     15.691 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.008 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 12.239 ms/op
                 listUser·p1.00:   13.648 ms/op

Iteration   2: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.580 ms/op
                 listUser·p0.999:  9.639 ms/op
                 listUser·p0.9999: 12.616 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.518 ms/op
                 listUser·p0.9999: 11.314 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323756
  mean =      2.962 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 102782 
    [ 2.500,  3.750) = 183857 
    [ 3.750,  5.000) = 29970 
    [ 5.000,  6.250) = 5622 
    [ 6.250,  7.500) = 594 
    [ 7.500,  8.750) = 251 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.108 ms/op
     p(99.9990) =     13.370 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.038 ± 2.686  ops/ms
ClientPb.existUser                       thrpt       3  13.441 ± 1.104  ops/ms
ClientPb.getUser                         thrpt       3  13.076 ± 1.624  ops/ms
ClientPb.listUser                        thrpt       3  10.856 ± 0.746  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.559   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.192   ms/op
ClientPb.getUser                          avgt       3   2.451 ± 0.126   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.424   ms/op
ClientPb.createUser                     sample  388371   2.469 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.617           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.494           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.491           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  404598   2.370 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.705           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.408           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.297           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.581           ms/op
ClientPb.getUser                        sample  385771   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.504           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.507           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.991           ms/op
ClientPb.listUser                       sample  323756   2.962 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.928           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.648           ms/op
