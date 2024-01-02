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
# Warmup Iteration   1: 4.936 ops/ms
# Warmup Iteration   2: 12.308 ops/ms
# Warmup Iteration   3: 12.550 ops/ms
Iteration   1: 12.627 ops/ms
Iteration   2: 12.678 ops/ms
Iteration   3: 12.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.645 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (12.627, 12.645, 12.678), stdev = 0.029
  CI (99.9%): [12.117, 13.173] (assumes normal distribution)


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
# Warmup Iteration   1: 8.485 ops/ms
# Warmup Iteration   2: 13.063 ops/ms
# Warmup Iteration   3: 13.163 ops/ms
Iteration   1: 13.128 ops/ms
Iteration   2: 13.137 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.104 ±(99.9%) 0.904 ops/ms [Average]
  (min, avg, max) = (13.047, 13.104, 13.137), stdev = 0.050
  CI (99.9%): [12.200, 14.008] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ops/ms
# Warmup Iteration   2: 12.669 ops/ms
# Warmup Iteration   3: 12.811 ops/ms
Iteration   1: 12.950 ops/ms
Iteration   2: 12.693 ops/ms
Iteration   3: 12.766 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.803 ±(99.9%) 2.416 ops/ms [Average]
  (min, avg, max) = (12.693, 12.803, 12.950), stdev = 0.132
  CI (99.9%): [10.387, 15.219] (assumes normal distribution)


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
# Warmup Iteration   1: 6.708 ops/ms
# Warmup Iteration   2: 10.738 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.772 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.755 ±(99.9%) 0.267 ops/ms [Average]
  (min, avg, max) = (10.745, 10.755, 10.772), stdev = 0.015
  CI (99.9%): [10.488, 11.022] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.003 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.003 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.485, 2.494, 2.505), stdev = 0.010
  CI (99.9%): [2.304, 2.684] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.003 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.411, 2.426, 2.440), stdev = 0.015
  CI (99.9%): [2.157, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.499 ±(99.9%) 0.003 ms/op
Iteration   3: 2.471 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.471, 2.491, 2.504), stdev = 0.018
  CI (99.9%): [2.169, 2.813] (assumes normal distribution)


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
# Warmup Iteration   1: 4.966 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
Iteration   3: 2.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.961, 2.978, 2.995), stdev = 0.017
  CI (99.9%): [2.668, 3.288] (assumes normal distribution)


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
# Warmup Iteration   1: 4.270 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 13.493 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 13.181 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   3: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 9.889 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374088
  mean =      2.564 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 177058 
    [ 2.500,  3.750) = 192095 
    [ 3.750,  5.000) = 3993 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.567 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.906 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.406 ±(99.9%) 0.005 ms/op
Iteration   1: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.920 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.242 ms/op
                 existUser·p0.9999: 13.782 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  6.480 ms/op
                 existUser·p0.9999: 12.530 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  7.149 ms/op
                 existUser·p0.9999: 11.678 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397233
  mean =      2.414 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 198900 
    [ 2.500,  3.750) = 195713 
    [ 3.750,  5.000) = 1883 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 155 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      6.584 ms/op
     p(99.9900) =     12.707 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  6.697 ms/op
                 getUser·p0.9999: 13.325 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  5.843 ms/op
                 getUser·p0.9999: 12.370 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  6.805 ms/op
                 getUser·p0.9999: 12.273 ms/op
                 getUser·p1.00:   13.451 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386340
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 192320 
    [ 2.500,  3.750) = 189327 
    [ 3.750,  5.000) = 3712 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 160 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.865 ms/op
     p(99.9000) =      6.423 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.008 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.827 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.177 ms/op
                 listUser·p0.9999: 10.863 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.795 ms/op
                 listUser·p0.9999: 11.820 ms/op
                 listUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316457
  mean =      3.031 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 86929 
    [ 2.500,  3.750) = 189668 
    [ 3.750,  5.000) = 32359 
    [ 5.000,  6.250) = 5918 
    [ 6.250,  7.500) = 755 
    [ 7.500,  8.750) = 230 
    [ 8.750, 10.000) = 300 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.638 ms/op
     p(99.9990) =     14.424 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.645 ± 0.528  ops/ms
ClientPb.existUser                       thrpt       3  13.104 ± 0.904  ops/ms
ClientPb.getUser                         thrpt       3  12.803 ± 2.416  ops/ms
ClientPb.listUser                        thrpt       3  10.755 ± 0.267  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.190   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.310   ms/op
ClientPb.createUser                     sample  374088   2.564 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.969           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.567           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.074           ms/op
ClientPb.existUser                      sample  397233   2.414 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.779           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.584           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.707           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  386340   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.865           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.423           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.927           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.681           ms/op
ClientPb.listUser                       sample  316457   3.031 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.638           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.795           ms/op
