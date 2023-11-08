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
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 11.439 ops/ms
# Warmup Iteration   3: 12.067 ops/ms
Iteration   1: 12.135 ops/ms
Iteration   2: 12.389 ops/ms
Iteration   3: 12.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.312 ±(99.9%) 2.803 ops/ms [Average]
  (min, avg, max) = (12.135, 12.312, 12.411), stdev = 0.154
  CI (99.9%): [9.509, 15.115] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ops/ms
# Warmup Iteration   2: 12.719 ops/ms
# Warmup Iteration   3: 12.800 ops/ms
Iteration   1: 12.683 ops/ms
Iteration   2: 12.786 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.749 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (12.683, 12.749, 12.786), stdev = 0.058
  CI (99.9%): [11.699, 13.799] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.825 ops/ms
# Warmup Iteration   2: 12.350 ops/ms
# Warmup Iteration   3: 12.372 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.533 ops/ms
Iteration   3: 12.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.516 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (12.384, 12.516, 12.631), stdev = 0.124
  CI (99.9%): [10.247, 14.786] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.323 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.477 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (10.441, 10.477, 10.497), stdev = 0.031
  CI (99.9%): [9.912, 11.042] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.501, 2.530, 2.556), stdev = 0.028
  CI (99.9%): [2.023, 3.037] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.500 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.477, 2.500, 2.512), stdev = 0.020
  CI (99.9%): [2.132, 2.867] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
Iteration   3: 2.545 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (2.506, 2.529, 2.545), stdev = 0.020
  CI (99.9%): [2.160, 2.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
Iteration   2: 3.090 ±(99.9%) 0.004 ms/op
Iteration   3: 3.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.088 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.071, 3.088, 3.103), stdev = 0.016
  CI (99.9%): [2.795, 3.382] (assumes normal distribution)


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  12.008 ms/op
                 createUser·p0.9999: 14.639 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 2.620 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  10.323 ms/op
                 createUser·p0.9999: 12.957 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  9.110 ms/op
                 createUser·p0.9999: 10.990 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369358
  mean =      2.596 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 172878 
    [ 2.500,  3.750) = 189923 
    [ 3.750,  5.000) = 5196 
    [ 5.000,  6.250) = 842 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      9.235 ms/op
     p(99.9900) =     13.519 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  6.867 ms/op
                 existUser·p0.9999: 14.410 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.542 ms/op
                 existUser·p0.999:  5.472 ms/op
                 existUser·p0.9999: 15.599 ms/op
                 existUser·p1.00:   16.269 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  9.205 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388028
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 192187 
    [ 2.500,  3.750) = 191511 
    [ 3.750,  5.000) = 3106 
    [ 5.000,  6.250) = 711 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      8.141 ms/op
     p(99.9900) =     14.651 ms/op
     p(99.9990) =     16.115 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  12.636 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  10.765 ms/op
                 getUser·p0.9999: 13.116 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.251 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.871 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375063
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 181365 
    [ 2.500,  3.750) = 186695 
    [ 3.750,  5.000) = 5299 
    [ 5.000,  6.250) = 1076 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     15.151 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.091 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.461 ms/op
                 listUser·p0.99:   5.642 ms/op
                 listUser·p0.999:  9.751 ms/op
                 listUser·p0.9999: 11.845 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.750 ms/op
                 listUser·p0.9999: 11.714 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.826 ms/op
                 listUser·p0.9999: 11.868 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310012
  mean =      3.094 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 77095 
    [ 2.500,  3.750) = 187626 
    [ 3.750,  5.000) = 36986 
    [ 5.000,  6.250) = 6693 
    [ 6.250,  7.500) = 815 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 188 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     11.780 ms/op
     p(99.9990) =     12.745 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.312 ± 2.803  ops/ms
ClientPb.existUser                       thrpt       3  12.749 ± 1.050  ops/ms
ClientPb.getUser                         thrpt       3  12.516 ± 2.269  ops/ms
ClientPb.listUser                        thrpt       3  10.477 ± 0.565  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.507   ms/op
ClientPb.existUser                        avgt       3   2.500 ± 0.367   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.369   ms/op
ClientPb.listUser                         avgt       3   3.088 ± 0.293   ms/op
ClientPb.createUser                     sample  369358   2.596 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.777           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.235           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.519           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.204           ms/op
ClientPb.existUser                      sample  388028   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.141           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.651           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.269           ms/op
ClientPb.getUser                        sample  375063   2.557 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.962           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.385           ms/op
ClientPb.listUser                       sample  310012   3.094 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.780           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
