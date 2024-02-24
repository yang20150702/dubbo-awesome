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
# Warmup Iteration   1: 5.002 ops/ms
# Warmup Iteration   2: 11.983 ops/ms
# Warmup Iteration   3: 12.392 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.716 ops/ms
Iteration   3: 12.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.672 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (12.507, 12.672, 12.792), stdev = 0.148
  CI (99.9%): [9.979, 15.365] (assumes normal distribution)


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
# Warmup Iteration   1: 8.097 ops/ms
# Warmup Iteration   2: 12.801 ops/ms
# Warmup Iteration   3: 12.890 ops/ms
Iteration   1: 13.067 ops/ms
Iteration   2: 13.231 ops/ms
Iteration   3: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.096 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (12.989, 13.096, 13.231), stdev = 0.124
  CI (99.9%): [10.841, 15.350] (assumes normal distribution)


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
# Warmup Iteration   1: 7.905 ops/ms
# Warmup Iteration   2: 12.632 ops/ms
# Warmup Iteration   3: 12.573 ops/ms
Iteration   1: 12.528 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.628 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (12.528, 12.628, 12.695), stdev = 0.088
  CI (99.9%): [11.024, 14.232] (assumes normal distribution)


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
# Warmup Iteration   1: 6.669 ops/ms
# Warmup Iteration   2: 10.480 ops/ms
# Warmup Iteration   3: 10.545 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.638 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (10.605, 10.638, 10.686), stdev = 0.043
  CI (99.9%): [9.860, 11.417] (assumes normal distribution)


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.530, 2.548, 2.557), stdev = 0.015
  CI (99.9%): [2.265, 2.830] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.442, 2.450, 2.460), stdev = 0.009
  CI (99.9%): [2.281, 2.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.502, 2.514, 2.530), stdev = 0.015
  CI (99.9%): [2.247, 2.781] (assumes normal distribution)


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
Iteration   3: 3.057 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.039 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.027, 3.039, 3.057), stdev = 0.016
  CI (99.9%): [2.753, 3.325] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.363 ms/op
                 createUser·p0.9999: 14.409 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 13.822 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  8.750 ms/op
                 createUser·p0.9999: 11.125 ms/op
                 createUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378864
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 182952 
    [ 2.500,  3.750) = 191881 
    [ 3.750,  5.000) = 3102 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.826 ms/op
     p(99.9900) =     13.617 ms/op
     p(99.9990) =     15.175 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  7.243 ms/op
                 existUser·p0.9999: 13.730 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  8.349 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.031 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 11.639 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389762
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 191644 
    [ 2.500,  3.750) = 194590 
    [ 3.750,  5.000) = 2674 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.423 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.174 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.554 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  10.858 ms/op
                 getUser·p0.9999: 13.889 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.326 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  9.224 ms/op
                 getUser·p0.9999: 15.304 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 10.928 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377266
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 182601 
    [ 2.500,  3.750) = 188821 
    [ 3.750,  5.000) = 4310 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     14.402 ms/op
     p(99.9990) =     16.873 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.410 ms/op
                 listUser·p0.9999: 10.676 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   2: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.518 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 12.099 ms/op
                 listUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315098
  mean =      3.043 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 85573 
    [ 2.500,  3.750) = 187947 
    [ 3.750,  5.000) = 34008 
    [ 5.000,  6.250) = 6022 
    [ 6.250,  7.500) = 740 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.846 ms/op
     p(99.9990) =     13.067 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.672 ± 2.693  ops/ms
ClientPb.existUser                       thrpt       3  13.096 ± 2.255  ops/ms
ClientPb.getUser                         thrpt       3  12.628 ± 1.604  ops/ms
ClientPb.listUser                        thrpt       3  10.638 ± 0.779  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.168   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.267   ms/op
ClientPb.listUser                         avgt       3   3.039 ± 0.286   ms/op
ClientPb.createUser                     sample  378864   2.531 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.788           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.826           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.617           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.254           ms/op
ClientPb.existUser                      sample  389762   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.423           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.189           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.221           ms/op
ClientPb.getUser                        sample  377266   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.208           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.072           ms/op
ClientPb.listUser                       sample  315098   3.043 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
