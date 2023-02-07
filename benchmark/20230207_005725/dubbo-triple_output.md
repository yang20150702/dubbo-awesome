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
# Warmup Iteration   1: 2.108 ops/ms
# Warmup Iteration   2: 4.824 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.280 ops/ms
Iteration   3: 9.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.359 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (9.280, 9.359, 9.454), stdev = 0.088
  CI (99.9%): [7.751, 10.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 8.918 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.734 ops/ms
Iteration   2: 9.938 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.875 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (9.734, 9.875, 9.953), stdev = 0.122
  CI (99.9%): [7.646, 12.104] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.675 ops/ms
# Warmup Iteration   2: 8.634 ops/ms
# Warmup Iteration   3: 9.215 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.216 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.438 ±(99.9%) 4.547 ops/ms [Average]
  (min, avg, max) = (9.216, 9.438, 9.707), stdev = 0.249
  CI (99.9%): [4.891, 13.984] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ops/ms
# Warmup Iteration   2: 7.229 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 7.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.007 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (7.932, 8.007, 8.130), stdev = 0.108
  CI (99.9%): [6.043, 9.972] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.227 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.005 ms/op
Iteration   1: 3.427 ±(99.9%) 0.008 ms/op
Iteration   2: 3.386 ±(99.9%) 0.013 ms/op
Iteration   3: 3.437 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.416 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.386, 3.416, 3.437), stdev = 0.027
  CI (99.9%): [2.921, 3.911] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.673 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.010 ms/op
Iteration   1: 3.256 ±(99.9%) 0.003 ms/op
Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
Iteration   3: 3.251 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.235 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.198, 3.235, 3.256), stdev = 0.032
  CI (99.9%): [2.645, 3.826] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.806 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.006 ms/op
Iteration   1: 3.570 ±(99.9%) 0.008 ms/op
Iteration   2: 3.409 ±(99.9%) 0.006 ms/op
Iteration   3: 3.537 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 1.548 ms/op [Average]
  (min, avg, max) = (3.409, 3.505, 3.570), stdev = 0.085
  CI (99.9%): [1.958, 5.053] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.150 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.551 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.012 ms/op
Iteration   1: 4.120 ±(99.9%) 0.009 ms/op
Iteration   2: 4.129 ±(99.9%) 0.007 ms/op
Iteration   3: 3.926 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 2.086 ms/op [Average]
  (min, avg, max) = (3.926, 4.058, 4.129), stdev = 0.114
  CI (99.9%): [1.972, 6.145] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.698 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.314 ms/op
                 createUser·p0.9999: 21.253 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  21.610 ms/op
                 createUser·p0.9999: 31.544 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 25.690 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282466
  mean =      3.394 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8195 
    [ 2.500,  5.000) = 268762 
    [ 5.000,  7.500) = 4374 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     19.777 ms/op
     p(99.9900) =     25.871 ms/op
     p(99.9990) =     32.386 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 8.745 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.009 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  9.820 ms/op
                 existUser·p0.9999: 27.367 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.475 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 25.396 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  10.059 ms/op
                 existUser·p0.9999: 23.632 ms/op
                 existUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296600
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11702 
    [ 2.500,  5.000) = 281536 
    [ 5.000,  7.500) = 2639 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.470 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.486 ms/op
     p(99.9900) =     25.865 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 9.659 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.013 ms/op
Iteration   1: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.165 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  21.510 ms/op
                 getUser·p0.9999: 24.169 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.820 ms/op
                 getUser·p0.999:  22.580 ms/op
                 getUser·p0.9999: 26.143 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.031 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  18.444 ms/op
                 getUser·p0.9999: 27.970 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284229
  mean =      3.375 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14749 
    [ 2.500,  5.000) = 262609 
    [ 5.000,  7.500) = 5881 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     19.653 ms/op
     p(99.9900) =     27.380 ms/op
     p(99.9990) =     28.458 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 10.842 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.013 ms/op
Iteration   1: 4.166 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.426 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  21.463 ms/op
                 listUser·p0.9999: 28.847 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 3.969 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.010 ms/op
                 listUser·p0.999:  17.295 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.444 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 19.595 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238094
  mean =      4.029 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 229420 
    [ 5.000,  7.500) = 6515 
    [ 7.500, 10.000) = 1359 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.275 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     27.171 ms/op
     p(99.9990) =     29.639 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.359 ± 1.608  ops/ms
ClientPb.existUser                       thrpt       3   9.875 ± 2.229  ops/ms
ClientPb.getUser                         thrpt       3   9.438 ± 4.547  ops/ms
ClientPb.listUser                        thrpt       3   8.007 ± 1.964  ops/ms
ClientPb.createUser                       avgt       3   3.416 ± 0.495   ms/op
ClientPb.existUser                        avgt       3   3.235 ± 0.590   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 1.548   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 2.086   ms/op
ClientPb.createUser                     sample  282466   3.394 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.777           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.871           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  296600   3.236 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.470           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.486           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.865           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.853           ms/op
ClientPb.getUser                        sample  284229   3.375 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.067           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.380           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  238094   4.029 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.426           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.275           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.171           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
