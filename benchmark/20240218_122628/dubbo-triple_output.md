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
# Warmup Iteration   1: 4.989 ops/ms
# Warmup Iteration   2: 12.092 ops/ms
# Warmup Iteration   3: 12.540 ops/ms
Iteration   1: 12.576 ops/ms
Iteration   2: 12.654 ops/ms
Iteration   3: 12.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.663 ±(99.9%) 1.690 ops/ms [Average]
  (min, avg, max) = (12.576, 12.663, 12.760), stdev = 0.093
  CI (99.9%): [10.973, 14.354] (assumes normal distribution)


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
# Warmup Iteration   1: 7.973 ops/ms
# Warmup Iteration   2: 13.231 ops/ms
# Warmup Iteration   3: 13.121 ops/ms
Iteration   1: 13.276 ops/ms
Iteration   2: 13.204 ops/ms
Iteration   3: 13.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.200 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (13.121, 13.200, 13.276), stdev = 0.078
  CI (99.9%): [11.784, 14.617] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.595 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 12.835 ops/ms
Iteration   1: 12.703 ops/ms
Iteration   2: 12.685 ops/ms
Iteration   3: 12.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.749 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (12.685, 12.749, 12.859), stdev = 0.096
  CI (99.9%): [11.001, 14.497] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.550 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 10.441 ops/ms
Iteration   1: 10.445 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.467 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (10.445, 10.467, 10.480), stdev = 0.019
  CI (99.9%): [10.122, 10.812] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.513, 2.529, 2.549), stdev = 0.018
  CI (99.9%): [2.204, 2.855] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.659 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.440 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.363 ms/op [Average]
  (min, avg, max) = (2.409, 2.432, 2.446), stdev = 0.020
  CI (99.9%): [2.069, 2.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.461, 2.476, 2.489), stdev = 0.014
  CI (99.9%): [2.216, 2.736] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.013, 3.021, 3.036), stdev = 0.013
  CI (99.9%): [2.782, 3.261] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.304 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.005 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  11.818 ms/op
                 createUser·p0.9999: 13.640 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  9.203 ms/op
                 createUser·p0.9999: 12.468 ms/op
                 createUser·p1.00:   12.665 ms/op

Iteration   3: 2.586 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 12.773 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372534
  mean =      2.573 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 177313 
    [ 2.500,  3.750) = 190746 
    [ 3.750,  5.000) = 3488 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     16.529 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  7.818 ms/op
                 existUser·p0.9999: 13.453 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  8.091 ms/op
                 existUser·p0.9999: 12.355 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  6.033 ms/op
                 existUser·p0.9999: 12.053 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386128
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 190086 
    [ 2.500,  3.750) = 193314 
    [ 3.750,  5.000) = 1913 
    [ 5.000,  6.250) = 388 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      6.354 ms/op
     p(99.9900) =     13.064 ms/op
     p(99.9990) =     13.673 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 19.973 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.937 ms/op
                 getUser·p0.999:  10.502 ms/op
                 getUser·p0.9999: 15.630 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.607 ms/op
                 getUser·p0.9999: 12.634 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382983
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189020 
    [ 2.500,  5.000) = 193078 
    [ 5.000,  7.500) = 501 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     15.696 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.869 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.764 ms/op
                 listUser·p0.9999: 12.001 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 12.023 ms/op
                 listUser·p1.00:   12.255 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.632 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.395 ms/op
                 listUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316220
  mean =      3.033 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 87961 
    [ 2.500,  3.750) = 187335 
    [ 3.750,  5.000) = 33292 
    [ 5.000,  6.250) = 6090 
    [ 6.250,  7.500) = 781 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.911 ms/op
     p(99.9990) =     12.253 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.663 ± 1.690  ops/ms
ClientPb.existUser                       thrpt       3  13.200 ± 1.416  ops/ms
ClientPb.getUser                         thrpt       3  12.749 ± 1.748  ops/ms
ClientPb.listUser                        thrpt       3  10.467 ± 0.345  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.326   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.363   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.260   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.240   ms/op
ClientPb.createUser                     sample  372534   2.573 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.236           ms/op
ClientPb.existUser                      sample  386128   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.354           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.064           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  382983   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.697           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.832           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.696           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.546           ms/op
ClientPb.listUser                       sample  316220   3.033 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.914           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.911           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
