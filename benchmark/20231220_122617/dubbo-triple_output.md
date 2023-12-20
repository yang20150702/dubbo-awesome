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
# Warmup Iteration   1: 4.796 ops/ms
# Warmup Iteration   2: 12.119 ops/ms
# Warmup Iteration   3: 12.204 ops/ms
Iteration   1: 12.474 ops/ms
Iteration   2: 12.381 ops/ms
Iteration   3: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.435 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (12.381, 12.435, 12.474), stdev = 0.049
  CI (99.9%): [11.545, 13.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ops/ms
# Warmup Iteration   2: 13.101 ops/ms
# Warmup Iteration   3: 12.864 ops/ms
Iteration   1: 13.095 ops/ms
Iteration   2: 13.123 ops/ms
Iteration   3: 13.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.123 ±(99.9%) 0.501 ops/ms [Average]
  (min, avg, max) = (13.095, 13.123, 13.150), stdev = 0.027
  CI (99.9%): [12.622, 13.624] (assumes normal distribution)


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
# Warmup Iteration   1: 7.828 ops/ms
# Warmup Iteration   2: 12.309 ops/ms
# Warmup Iteration   3: 12.799 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.801 ops/ms
Iteration   3: 12.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.694 ±(99.9%) 3.874 ops/ms [Average]
  (min, avg, max) = (12.449, 12.694, 12.831), stdev = 0.212
  CI (99.9%): [8.820, 16.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.754 ops/ms
# Warmup Iteration   2: 10.494 ops/ms
# Warmup Iteration   3: 10.661 ops/ms
Iteration   1: 10.671 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.623 ±(99.9%) 0.986 ops/ms [Average]
  (min, avg, max) = (10.565, 10.623, 10.671), stdev = 0.054
  CI (99.9%): [9.637, 11.609] (assumes normal distribution)


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
# Warmup Iteration   1: 4.106 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.004 ms/op
Iteration   1: 2.569 ±(99.9%) 0.005 ms/op
Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
Iteration   3: 2.562 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.547, 2.559, 2.569), stdev = 0.011
  CI (99.9%): [2.351, 2.768] (assumes normal distribution)


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.377 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.388 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.003 ms/op
Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
Iteration   3: 2.399 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.412 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.399, 2.412, 2.426), stdev = 0.014
  CI (99.9%): [2.163, 2.661] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.463 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.445, 2.463, 2.478), stdev = 0.016
  CI (99.9%): [2.165, 2.760] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.005 ms/op
Iteration   1: 3.084 ±(99.9%) 0.005 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.080 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.078 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (3.070, 3.078, 3.084), stdev = 0.007
  CI (99.9%): [2.947, 3.208] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.746 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  10.994 ms/op
                 createUser·p0.9999: 13.888 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  9.579 ms/op
                 createUser·p0.9999: 12.272 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.394 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.822 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 11.563 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377314
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 180422 
    [ 2.500,  3.750) = 192467 
    [ 3.750,  5.000) = 3478 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.055 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.953 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.827 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  4.858 ms/op
                 existUser·p0.9999: 13.401 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.376 ms/op
                 existUser·p0.9999: 12.203 ms/op
                 existUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392984
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 195913 
    [ 2.500,  3.750) = 194478 
    [ 3.750,  5.000) = 2124 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =      5.153 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.560 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.853 ms/op
                 getUser·p0.999:  12.540 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.561 ms/op
                 getUser·p0.999:  8.768 ms/op
                 getUser·p0.9999: 14.536 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  7.920 ms/op
                 getUser·p0.9999: 11.431 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381074
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 186983 
    [ 2.500,  3.750) = 190003 
    [ 3.750,  5.000) = 3181 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.055 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.937 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   2: 3.075 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.608 ms/op
                 listUser·p0.999:  9.587 ms/op
                 listUser·p0.9999: 15.135 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.199 ms/op
                 listUser·p0.9999: 12.151 ms/op
                 listUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313391
  mean =      3.060 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 126 
    [ 1.250,  2.500) = 81810 
    [ 2.500,  3.750) = 188339 
    [ 3.750,  5.000) = 35619 
    [ 5.000,  6.250) = 6231 
    [ 6.250,  7.500) = 585 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 213 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     12.626 ms/op
     p(99.9990) =     15.937 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.435 ± 0.891  ops/ms
ClientPb.existUser                       thrpt       3  13.123 ± 0.501  ops/ms
ClientPb.getUser                         thrpt       3  12.694 ± 3.874  ops/ms
ClientPb.listUser                        thrpt       3  10.623 ± 0.986  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.208   ms/op
ClientPb.existUser                        avgt       3   2.412 ± 0.249   ms/op
ClientPb.getUser                          avgt       3   2.463 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   3.078 ± 0.131   ms/op
ClientPb.createUser                     sample  377314   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.394           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.287           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  392984   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.153           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.286           ms/op
ClientPb.getUser                        sample  381074   2.517 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.762           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.055           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.450           ms/op
ClientPb.listUser                       sample  313391   3.060 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.863           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.626           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.105           ms/op
