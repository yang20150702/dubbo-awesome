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
# Warmup Iteration   1: 4.700 ops/ms
# Warmup Iteration   2: 12.024 ops/ms
# Warmup Iteration   3: 12.334 ops/ms
Iteration   1: 12.612 ops/ms
Iteration   2: 12.789 ops/ms
Iteration   3: 12.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.763 ±(99.9%) 2.557 ops/ms [Average]
  (min, avg, max) = (12.612, 12.763, 12.889), stdev = 0.140
  CI (99.9%): [10.206, 15.320] (assumes normal distribution)


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
# Warmup Iteration   1: 8.225 ops/ms
# Warmup Iteration   2: 12.960 ops/ms
# Warmup Iteration   3: 13.080 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.047 ops/ms
Iteration   3: 13.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.065 ±(99.9%) 0.481 ops/ms [Average]
  (min, avg, max) = (13.047, 13.065, 13.095), stdev = 0.026
  CI (99.9%): [12.583, 13.546] (assumes normal distribution)


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
# Warmup Iteration   1: 7.541 ops/ms
# Warmup Iteration   2: 12.659 ops/ms
# Warmup Iteration   3: 12.660 ops/ms
Iteration   1: 12.877 ops/ms
Iteration   2: 12.782 ops/ms
Iteration   3: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.804 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (12.755, 12.804, 12.877), stdev = 0.064
  CI (99.9%): [11.638, 13.970] (assumes normal distribution)


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
# Warmup Iteration   1: 6.673 ops/ms
# Warmup Iteration   2: 10.433 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.787 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.712 ±(99.9%) 1.663 ops/ms [Average]
  (min, avg, max) = (10.611, 10.712, 10.787), stdev = 0.091
  CI (99.9%): [9.049, 12.376] (assumes normal distribution)


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
Iteration   1: 2.554 ±(99.9%) 0.003 ms/op
Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.546, 2.560, 2.581), stdev = 0.018
  CI (99.9%): [2.226, 2.894] (assumes normal distribution)


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (2.487, 2.494, 2.506), stdev = 0.010
  CI (99.9%): [2.307, 2.681] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.502, 2.509, 2.521), stdev = 0.011
  CI (99.9%): [2.310, 2.708] (assumes normal distribution)


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
# Warmup Iteration   1: 4.959 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.014 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (3.006, 3.014, 3.021), stdev = 0.007
  CI (99.9%): [2.880, 3.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.709 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.770 ms/op
                 createUser·p0.999:  12.318 ms/op
                 createUser·p0.9999: 14.402 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 12.395 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.230 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.323 ms/op
                 createUser·p0.9999: 10.879 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373851
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 180023 
    [ 2.500,  3.750) = 190179 
    [ 3.750,  5.000) = 2821 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.599 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.430 ms/op
                 existUser·p0.9999: 13.781 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.278 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 12.157 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386322
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 191452 
    [ 2.500,  3.750) = 191977 
    [ 3.750,  5.000) = 2059 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      7.780 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.048 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  10.210 ms/op
                 getUser·p0.9999: 13.724 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.052 ms/op
                 getUser·p0.999:  6.651 ms/op
                 getUser·p0.9999: 13.054 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.952 ms/op
                 getUser·p0.9999: 17.695 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382576
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 189407 
    [ 2.500,  3.750) = 187388 
    [ 3.750,  5.000) = 4230 
    [ 5.000,  6.250) = 1029 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.991 ms/op
     p(99.9900) =     13.967 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.785 ms/op
                 listUser·p0.9999: 10.616 ms/op
                 listUser·p1.00:   10.961 ms/op

Iteration   2: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.597 ms/op
                 listUser·p1.00:   10.846 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.672 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.722 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321139
  mean =      2.986 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 96033 
    [ 2.500,  3.750) = 187717 
    [ 3.750,  5.000) = 30530 
    [ 5.000,  6.250) = 5541 
    [ 6.250,  7.500) = 556 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 275 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     10.599 ms/op
     p(99.9990) =     11.334 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.763 ± 2.557  ops/ms
ClientPb.existUser                       thrpt       3  13.065 ± 0.481  ops/ms
ClientPb.getUser                         thrpt       3  12.804 ± 1.166  ops/ms
ClientPb.listUser                        thrpt       3  10.712 ± 1.663  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.187   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   3.014 ± 0.133   ms/op
ClientPb.createUser                     sample  373851   2.566 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  386322   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.878           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  382576   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.750           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.991           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.967           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.416           ms/op
ClientPb.listUser                       sample  321139   2.986 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.672           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.028           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.599           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.518           ms/op
