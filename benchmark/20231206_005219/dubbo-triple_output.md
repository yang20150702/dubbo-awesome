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
# Warmup Iteration   1: 4.938 ops/ms
# Warmup Iteration   2: 11.880 ops/ms
# Warmup Iteration   3: 12.283 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.603 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.543 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (12.504, 12.543, 12.603), stdev = 0.053
  CI (99.9%): [11.576, 13.510] (assumes normal distribution)


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
# Warmup Iteration   1: 8.336 ops/ms
# Warmup Iteration   2: 13.074 ops/ms
# Warmup Iteration   3: 12.862 ops/ms
Iteration   1: 13.137 ops/ms
Iteration   2: 13.166 ops/ms
Iteration   3: 13.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.118 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (13.051, 13.118, 13.166), stdev = 0.060
  CI (99.9%): [12.024, 14.213] (assumes normal distribution)


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
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 12.346 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.742 ops/ms
Iteration   2: 12.679 ops/ms
Iteration   3: 12.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.722 ±(99.9%) 0.671 ops/ms [Average]
  (min, avg, max) = (12.679, 12.722, 12.744), stdev = 0.037
  CI (99.9%): [12.051, 13.393] (assumes normal distribution)


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
# Warmup Iteration   1: 6.798 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.773 ops/ms
Iteration   2: 10.741 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.718 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (10.641, 10.718, 10.773), stdev = 0.069
  CI (99.9%): [9.462, 11.975] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.552 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.003 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.505, 2.530, 2.552), stdev = 0.024
  CI (99.9%): [2.098, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.444, 2.451, 2.462), stdev = 0.009
  CI (99.9%): [2.281, 2.622] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.427 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (2.427, 2.461, 2.485), stdev = 0.030
  CI (99.9%): [1.910, 3.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 2.899 ±(99.9%) 0.006 ms/op
Iteration   2: 2.911 ±(99.9%) 0.008 ms/op
Iteration   3: 2.906 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.905 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.899, 2.905, 2.911), stdev = 0.006
  CI (99.9%): [2.795, 3.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  11.155 ms/op
                 createUser·p0.9999: 14.434 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  7.789 ms/op
                 createUser·p0.9999: 11.762 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 11.611 ms/op
                 createUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382970
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 186147 
    [ 2.500,  3.750) = 191407 
    [ 3.750,  5.000) = 4306 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     15.341 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 14.296 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.671 ms/op
                 existUser·p0.9999: 12.551 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  6.874 ms/op
                 existUser·p0.9999: 12.879 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391444
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 196240 
    [ 2.500,  3.750) = 192073 
    [ 3.750,  5.000) = 2282 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.484 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.607 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.794 ms/op
                 getUser·p0.999:  5.672 ms/op
                 getUser·p0.9999: 13.592 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 13.474 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.375 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 11.380 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377129
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 184058 
    [ 2.500,  3.750) = 186457 
    [ 3.750,  5.000) = 5222 
    [ 5.000,  6.250) = 920 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.458 ms/op
     p(99.9900) =     13.325 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.009 ms/op
Iteration   1: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.035 ms/op
                 listUser·p0.9999: 12.638 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   2: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.884 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 10.786 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.539 ms/op
                 listUser·p0.9999: 10.944 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321635
  mean =      2.982 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 97751 
    [ 2.500,  3.750) = 185286 
    [ 3.750,  5.000) = 30875 
    [ 5.000,  6.250) = 6020 
    [ 6.250,  7.500) = 811 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.589 ms/op
     p(99.9990) =     13.015 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.543 ± 0.967  ops/ms
ClientPb.existUser                       thrpt       3  13.118 ± 1.094  ops/ms
ClientPb.getUser                         thrpt       3  12.722 ± 0.671  ops/ms
ClientPb.listUser                        thrpt       3  10.718 ± 1.257  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.170   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.551   ms/op
ClientPb.listUser                         avgt       3   2.905 ± 0.110   ms/op
ClientPb.createUser                     sample  382970   2.504 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.926           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.466           ms/op
ClientPb.existUser                      sample  391444   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.744           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.484           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.172           ms/op
ClientPb.getUser                        sample  377129   2.544 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.658           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.458           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.325           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  321635   2.982 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.589           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
