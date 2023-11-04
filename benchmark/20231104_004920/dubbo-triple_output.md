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
# Warmup Iteration   1: 4.993 ops/ms
# Warmup Iteration   2: 11.921 ops/ms
# Warmup Iteration   3: 12.250 ops/ms
Iteration   1: 12.500 ops/ms
Iteration   2: 12.363 ops/ms
Iteration   3: 12.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.479 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (12.363, 12.479, 12.575), stdev = 0.107
  CI (99.9%): [10.524, 14.435] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ops/ms
# Warmup Iteration   2: 12.906 ops/ms
# Warmup Iteration   3: 12.774 ops/ms
Iteration   1: 12.681 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.818 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (12.681, 12.818, 12.927), stdev = 0.125
  CI (99.9%): [10.532, 15.104] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.336 ops/ms
# Warmup Iteration   2: 12.363 ops/ms
# Warmup Iteration   3: 12.628 ops/ms
Iteration   1: 12.706 ops/ms
Iteration   2: 12.831 ops/ms
Iteration   3: 12.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.720 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (12.623, 12.720, 12.831), stdev = 0.105
  CI (99.9%): [10.809, 14.631] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.554 ops/ms
# Warmup Iteration   2: 10.261 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.505 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.515 ±(99.9%) 0.914 ops/ms [Average]
  (min, avg, max) = (10.471, 10.515, 10.570), stdev = 0.050
  CI (99.9%): [9.601, 11.430] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.594 ±(99.9%) 0.005 ms/op
Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (2.547, 2.566, 2.594), stdev = 0.024
  CI (99.9%): [2.126, 3.006] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.531 ±(99.9%) 0.393 ms/op [Average]
  (min, avg, max) = (2.506, 2.531, 2.545), stdev = 0.022
  CI (99.9%): [2.138, 2.923] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.586 ±(99.9%) 0.005 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.558 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.539, 2.558, 2.586), stdev = 0.025
  CI (99.9%): [2.104, 3.012] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.059 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.035, 3.059, 3.084), stdev = 0.025
  CI (99.9%): [2.610, 3.507] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.707 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.608 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  12.529 ms/op
                 createUser·p0.9999: 14.527 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  10.860 ms/op
                 createUser·p0.9999: 12.963 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.331 ms/op
                 createUser·p0.9999: 10.767 ms/op
                 createUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370803
  mean =      2.587 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 175640 
    [ 2.500,  3.750) = 189769 
    [ 3.750,  5.000) = 4144 
    [ 5.000,  6.250) = 671 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      8.474 ms/op
     p(99.9900) =     13.778 ms/op
     p(99.9990) =     14.849 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.830 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.814 ms/op
                 existUser·p0.999:  5.366 ms/op
                 existUser·p0.9999: 15.221 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  9.257 ms/op
                 existUser·p0.9999: 13.487 ms/op
                 existUser·p1.00:   16.187 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.922 ms/op
                 existUser·p0.999:  8.402 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384645
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 189121 
    [ 2.500,  3.750) = 190803 
    [ 3.750,  5.000) = 3721 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      7.881 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.310 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  7.565 ms/op
                 getUser·p0.9999: 16.822 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.601 ms/op
                 getUser·p0.9999: 14.483 ms/op
                 getUser·p1.00:   15.303 ms/op

Iteration   3: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  8.050 ms/op
                 getUser·p0.9999: 12.227 ms/op
                 getUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380428
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 186881 
    [ 2.500,  3.750) = 188466 
    [ 3.750,  5.000) = 3730 
    [ 5.000,  6.250) = 837 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.150 ms/op
     p(99.9900) =     15.181 ms/op
     p(99.9990) =     17.581 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.009 ms/op
Iteration   1: 3.072 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.013 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.839 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.408 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.034 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314086
  mean =      3.054 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 87008 
    [ 2.500,  3.750) = 184252 
    [ 3.750,  5.000) = 33880 
    [ 5.000,  6.250) = 7078 
    [ 6.250,  7.500) = 1007 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 227 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.813 ms/op
     p(99.9900) =     11.485 ms/op
     p(99.9990) =     12.333 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.479 ± 1.956  ops/ms
ClientPb.existUser                       thrpt       3  12.818 ± 2.286  ops/ms
ClientPb.getUser                         thrpt       3  12.720 ± 1.911  ops/ms
ClientPb.listUser                        thrpt       3  10.515 ± 0.914  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.440   ms/op
ClientPb.existUser                        avgt       3   2.531 ± 0.393   ms/op
ClientPb.getUser                          avgt       3   2.558 ± 0.454   ms/op
ClientPb.listUser                         avgt       3   3.059 ± 0.448   ms/op
ClientPb.createUser                     sample  370803   2.587 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.786           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.474           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.778           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.090           ms/op
ClientPb.existUser                      sample  384645   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.691           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.187           ms/op
ClientPb.getUser                        sample  380428   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.925           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.181           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.481           ms/op
ClientPb.listUser                       sample  314086   3.054 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.813           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.485           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.681           ms/op
