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
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 11.847 ops/ms
# Warmup Iteration   3: 12.112 ops/ms
Iteration   1: 12.274 ops/ms
Iteration   2: 12.322 ops/ms
Iteration   3: 12.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.447 ±(99.9%) 4.732 ops/ms [Average]
  (min, avg, max) = (12.274, 12.447, 12.745), stdev = 0.259
  CI (99.9%): [7.715, 17.179] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.958 ops/ms
# Warmup Iteration   2: 13.108 ops/ms
# Warmup Iteration   3: 13.062 ops/ms
Iteration   1: 12.851 ops/ms
Iteration   2: 12.830 ops/ms
Iteration   3: 12.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.822 ±(99.9%) 0.610 ops/ms [Average]
  (min, avg, max) = (12.786, 12.822, 12.851), stdev = 0.033
  CI (99.9%): [12.212, 13.432] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ops/ms
# Warmup Iteration   2: 12.279 ops/ms
# Warmup Iteration   3: 12.525 ops/ms
Iteration   1: 12.569 ops/ms
Iteration   2: 12.539 ops/ms
Iteration   3: 12.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.536 ±(99.9%) 0.642 ops/ms [Average]
  (min, avg, max) = (12.499, 12.536, 12.569), stdev = 0.035
  CI (99.9%): [11.894, 13.178] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.513 ops/ms
# Warmup Iteration   2: 10.305 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.573 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.503 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (10.416, 10.503, 10.573), stdev = 0.080
  CI (99.9%): [9.042, 11.964] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.003 ms/op
Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
Iteration   3: 2.609 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.580 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (2.528, 2.580, 2.609), stdev = 0.045
  CI (99.9%): [1.762, 3.397] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.003 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.474, 2.482, 2.489), stdev = 0.007
  CI (99.9%): [2.347, 2.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.541 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.530 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.523, 2.530, 2.541), stdev = 0.009
  CI (99.9%): [2.362, 2.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
Iteration   3: 3.057 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.042, 3.055, 3.066), stdev = 0.012
  CI (99.9%): [2.838, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
Iteration   1: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  11.314 ms/op
                 createUser·p0.9999: 13.900 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  9.757 ms/op
                 createUser·p0.9999: 12.222 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.071 ms/op
                 createUser·p0.999:  8.883 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372053
  mean =      2.578 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 174295 
    [ 2.500,  3.750) = 192296 
    [ 3.750,  5.000) = 4278 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.961 ms/op
     p(99.9900) =     13.006 ms/op
     p(99.9990) =     14.261 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.050 ms/op
                 existUser·p0.9999: 14.303 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  9.325 ms/op
                 existUser·p0.9999: 14.762 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  6.298 ms/op
                 existUser·p0.9999: 11.680 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389169
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 191609 
    [ 2.500,  3.750) = 193180 
    [ 3.750,  5.000) = 3412 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      6.666 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     14.911 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  11.294 ms/op
                 getUser·p0.9999: 14.066 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  9.306 ms/op
                 getUser·p0.9999: 14.130 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.956 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377026
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 184154 
    [ 2.500,  3.750) = 187675 
    [ 3.750,  5.000) = 3909 
    [ 5.000,  6.250) = 799 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.863 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.761 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.811 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.823 ms/op
                 listUser·p1.00:   12.517 ms/op

Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.637 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   3: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.010 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.871 ms/op
                 listUser·p0.9999: 13.133 ms/op
                 listUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312084
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 81281 
    [ 2.500,  3.750) = 188366 
    [ 3.750,  5.000) = 34709 
    [ 5.000,  6.250) = 6132 
    [ 6.250,  7.500) = 849 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     12.255 ms/op
     p(99.9990) =     15.211 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.447 ± 4.732  ops/ms
ClientPb.existUser                       thrpt       3  12.822 ± 0.610  ops/ms
ClientPb.getUser                         thrpt       3  12.536 ± 0.642  ops/ms
ClientPb.listUser                        thrpt       3  10.503 ± 1.461  ops/ms
ClientPb.createUser                       avgt       3   2.580 ± 0.817   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.136   ms/op
ClientPb.getUser                          avgt       3   2.530 ± 0.168   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.217   ms/op
ClientPb.createUser                     sample  372053   2.578 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.676           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.961           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.006           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.811           ms/op
ClientPb.existUser                      sample  389169   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.666           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.254           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.139           ms/op
ClientPb.getUser                        sample  377026   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.672           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.863           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  312084   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.585           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.255           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.499           ms/op
