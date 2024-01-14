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
# Warmup Iteration   1: 4.614 ops/ms
# Warmup Iteration   2: 12.180 ops/ms
# Warmup Iteration   3: 12.343 ops/ms
Iteration   1: 12.475 ops/ms
Iteration   2: 12.617 ops/ms
Iteration   3: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.570 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (12.475, 12.570, 12.618), stdev = 0.082
  CI (99.9%): [11.068, 14.072] (assumes normal distribution)


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
# Warmup Iteration   1: 7.806 ops/ms
# Warmup Iteration   2: 12.834 ops/ms
# Warmup Iteration   3: 12.909 ops/ms
Iteration   1: 12.703 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 12.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.849 ±(99.9%) 2.543 ops/ms [Average]
  (min, avg, max) = (12.703, 12.849, 12.981), stdev = 0.139
  CI (99.9%): [10.306, 15.391] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.599 ops/ms
# Warmup Iteration   3: 12.716 ops/ms
Iteration   1: 12.771 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.795 ±(99.9%) 1.063 ops/ms [Average]
  (min, avg, max) = (12.752, 12.795, 12.861), stdev = 0.058
  CI (99.9%): [11.732, 13.858] (assumes normal distribution)


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
# Warmup Iteration   1: 6.806 ops/ms
# Warmup Iteration   2: 10.466 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.677 ±(99.9%) 0.660 ops/ms [Average]
  (min, avg, max) = (10.636, 10.677, 10.704), stdev = 0.036
  CI (99.9%): [10.017, 11.337] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
Iteration   1: 2.561 ±(99.9%) 0.004 ms/op
Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
Iteration   3: 2.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.547 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (2.513, 2.547, 2.566), stdev = 0.029
  CI (99.9%): [2.014, 3.080] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
Iteration   3: 2.451 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.451, 2.455, 2.457), stdev = 0.003
  CI (99.9%): [2.399, 2.511] (assumes normal distribution)


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.486, 2.497, 2.515), stdev = 0.016
  CI (99.9%): [2.200, 2.794] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
Iteration   3: 2.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.954 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.944, 2.954, 2.959), stdev = 0.009
  CI (99.9%): [2.796, 3.112] (assumes normal distribution)


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.719 ms/op
                 createUser·p0.9999: 13.620 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  7.434 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.191 ms/op
                 createUser·p0.9999: 10.913 ms/op
                 createUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387476
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 187849 
    [ 2.500,  3.750) = 195531 
    [ 3.750,  5.000) = 3241 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      7.490 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     14.223 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  9.344 ms/op
                 existUser·p0.9999: 13.470 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.525 ms/op
                 existUser·p0.9999: 13.244 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.818 ms/op
                 existUser·p0.9999: 11.438 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387356
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 191481 
    [ 2.500,  3.750) = 192630 
    [ 3.750,  5.000) = 2505 
    [ 5.000,  6.250) = 271 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      7.308 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     13.785 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.018 ms/op
                 getUser·p0.999:  11.440 ms/op
                 getUser·p0.9999: 13.538 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  5.956 ms/op
                 getUser·p0.9999: 12.536 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  8.377 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380747
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186481 
    [ 2.500,  3.750) = 188972 
    [ 3.750,  5.000) = 4390 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      6.345 ms/op
     p(99.9900) =     12.940 ms/op
     p(99.9990) =     13.759 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 12.487 ms/op
                 listUser·p1.00:   14.041 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.211 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.788 ms/op
                 listUser·p0.9999: 11.365 ms/op
                 listUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319521
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 93831 
    [ 2.500,  3.750) = 188086 
    [ 3.750,  5.000) = 30606 
    [ 5.000,  6.250) = 5559 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     13.796 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.570 ± 1.502  ops/ms
ClientPb.existUser                       thrpt       3  12.849 ± 2.543  ops/ms
ClientPb.getUser                         thrpt       3  12.795 ± 1.063  ops/ms
ClientPb.listUser                        thrpt       3  10.677 ± 0.660  ops/ms
ClientPb.createUser                       avgt       3   2.547 ± 0.533   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.297   ms/op
ClientPb.listUser                         avgt       3   2.954 ± 0.158   ms/op
ClientPb.createUser                     sample  387476   2.475 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.795           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.490           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.140           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.385           ms/op
ClientPb.existUser                      sample  387356   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.308           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  380747   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.345           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.940           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.926           ms/op
ClientPb.listUser                       sample  319521   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.041           ms/op
