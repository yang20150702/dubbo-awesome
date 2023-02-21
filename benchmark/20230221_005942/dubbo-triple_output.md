# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.607 ops/ms
# Warmup Iteration   2: 5.895 ops/ms
# Warmup Iteration   3: 9.511 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.901 ±(99.9%) 0.697 ops/ms [Average]
  (min, avg, max) = (9.857, 9.901, 9.923), stdev = 0.038
  CI (99.9%): [9.204, 10.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.004 ops/ms
# Warmup Iteration   2: 9.471 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 10.814 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.746 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (10.678, 10.746, 10.814), stdev = 0.068
  CI (99.9%): [9.503, 11.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ops/ms
# Warmup Iteration   2: 9.581 ops/ms
# Warmup Iteration   3: 10.238 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 9.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.029 ±(99.9%) 4.494 ops/ms [Average]
  (min, avg, max) = (9.847, 10.029, 10.309), stdev = 0.246
  CI (99.9%): [5.535, 14.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ops/ms
# Warmup Iteration   2: 8.165 ops/ms
# Warmup Iteration   3: 8.594 ops/ms
Iteration   1: 8.632 ops/ms
Iteration   2: 8.469 ops/ms
Iteration   3: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.602 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (8.469, 8.602, 8.704), stdev = 0.120
  CI (99.9%): [6.411, 10.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.531 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.091 ±(99.9%) 0.890 ms/op [Average]
  (min, avg, max) = (3.059, 3.091, 3.147), stdev = 0.049
  CI (99.9%): [2.201, 3.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.723 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 2.970 ±(99.9%) 0.005 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.032 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (2.970, 3.032, 3.066), stdev = 0.054
  CI (99.9%): [2.052, 4.012] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.643 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.007 ms/op
Iteration   2: 3.100 ±(99.9%) 0.002 ms/op
Iteration   3: 3.067 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.090 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.067, 3.090, 3.103), stdev = 0.020
  CI (99.9%): [2.725, 3.455] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.459 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.003 ms/op
Iteration   1: 3.660 ±(99.9%) 0.006 ms/op
Iteration   2: 3.659 ±(99.9%) 0.012 ms/op
Iteration   3: 3.651 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.656 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (3.651, 3.656, 3.660), stdev = 0.005
  CI (99.9%): [3.564, 3.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.349 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  18.351 ms/op
                 createUser·p0.9999: 22.224 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  11.092 ms/op
                 createUser·p0.9999: 25.442 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  12.665 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306156
  mean =      3.134 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34148 
    [ 2.500,  5.000) = 266438 
    [ 5.000,  7.500) = 4645 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.552 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     26.534 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.293 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.008 ms/op
Iteration   1: 3.005 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  9.308 ms/op
                 existUser·p0.9999: 21.453 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  10.420 ms/op
                 existUser·p0.9999: 21.963 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.376 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  13.146 ms/op
                 existUser·p0.9999: 20.349 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313120
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24803 
    [ 2.500,  5.000) = 283714 
    [ 5.000,  7.500) = 3922 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.822 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.227 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.010 ms/op
Iteration   1: 3.126 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  9.454 ms/op
                 getUser·p0.9999: 24.110 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.637 ms/op
                 getUser·p0.999:  9.878 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305348
  mean =      3.143 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8564 
    [ 2.500,  5.000) = 289791 
    [ 5.000,  7.500) = 6171 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.330 ms/op
     p(99.9900) =     23.180 ms/op
     p(99.9990) =     24.804 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.893 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.011 ms/op
Iteration   1: 3.730 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.074 ms/op
                 listUser·p0.999:  17.646 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 3.779 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.745 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.543 ms/op
                 listUser·p0.9999: 16.120 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255797
  mean =      3.751 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 247757 
    [ 5.000,  7.500) = 6044 
    [ 7.500, 10.000) = 1203 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     14.765 ms/op
     p(99.9900) =     21.930 ms/op
     p(99.9990) =     24.107 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.901 ± 0.697  ops/ms
ClientPb.existUser                       thrpt       3  10.746 ± 1.243  ops/ms
ClientPb.getUser                         thrpt       3  10.029 ± 4.494  ops/ms
ClientPb.listUser                        thrpt       3   8.602 ± 2.191  ops/ms
ClientPb.createUser                       avgt       3   3.091 ± 0.890   ms/op
ClientPb.existUser                        avgt       3   3.032 ± 0.980   ms/op
ClientPb.getUser                          avgt       3   3.090 ± 0.365   ms/op
ClientPb.listUser                         avgt       3   3.656 ± 0.092   ms/op
ClientPb.createUser                     sample  306156   3.134 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.634           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  313120   3.063 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.014           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.970           ms/op
ClientPb.getUser                        sample  305348   3.143 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.047           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.330           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.180           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  255797   3.751 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.559           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.765           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.930           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
