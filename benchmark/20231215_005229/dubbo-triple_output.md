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
# Warmup Iteration   1: 4.740 ops/ms
# Warmup Iteration   2: 11.724 ops/ms
# Warmup Iteration   3: 12.124 ops/ms
Iteration   1: 12.296 ops/ms
Iteration   2: 12.483 ops/ms
Iteration   3: 12.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.414 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (12.296, 12.414, 12.483), stdev = 0.103
  CI (99.9%): [10.542, 14.286] (assumes normal distribution)


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
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 12.952 ops/ms
# Warmup Iteration   3: 13.042 ops/ms
Iteration   1: 12.892 ops/ms
Iteration   2: 12.659 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.831 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (12.659, 12.831, 12.942), stdev = 0.151
  CI (99.9%): [10.075, 15.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.710 ops/ms
# Warmup Iteration   2: 12.425 ops/ms
# Warmup Iteration   3: 12.603 ops/ms
Iteration   1: 12.618 ops/ms
Iteration   2: 12.676 ops/ms
Iteration   3: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.680 ±(99.9%) 1.178 ops/ms [Average]
  (min, avg, max) = (12.618, 12.680, 12.747), stdev = 0.065
  CI (99.9%): [11.503, 13.858] (assumes normal distribution)


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
# Warmup Iteration   1: 6.623 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.501 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (10.460, 10.501, 10.555), stdev = 0.049
  CI (99.9%): [9.609, 11.393] (assumes normal distribution)


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
# Warmup Iteration   1: 4.149 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.004 ms/op
Iteration   1: 2.611 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.600 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.591 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.562, 2.591, 2.611), stdev = 0.026
  CI (99.9%): [2.118, 3.064] (assumes normal distribution)


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.495 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.483, 2.495, 2.504), stdev = 0.011
  CI (99.9%): [2.303, 2.687] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.003 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.543 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.539, 2.543, 2.550), stdev = 0.006
  CI (99.9%): [2.434, 2.652] (assumes normal distribution)


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
Iteration   3: 3.032 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (2.985, 3.016, 3.033), stdev = 0.027
  CI (99.9%): [2.519, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.689 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.005 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  11.372 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  10.096 ms/op
                 createUser·p0.9999: 12.575 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.787 ms/op
                 createUser·p0.9999: 10.003 ms/op
                 createUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375373
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 180552 
    [ 2.500,  3.750) = 190600 
    [ 3.750,  5.000) = 3397 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     13.352 ms/op
     p(99.9990) =     14.438 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  12.016 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   2.630 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  9.133 ms/op
                 existUser·p0.9999: 12.141 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  7.789 ms/op
                 existUser·p0.9999: 12.293 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382003
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 186100 
    [ 2.500,  3.750) = 192322 
    [ 3.750,  5.000) = 2599 
    [ 5.000,  6.250) = 424 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 131 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     13.179 ms/op
     p(99.9990) =     14.041 ms/op
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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.853 ms/op
                 getUser·p0.999:  10.705 ms/op
                 getUser·p0.9999: 14.066 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  9.163 ms/op
                 getUser·p0.9999: 16.761 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  7.939 ms/op
                 getUser·p0.9999: 11.623 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380065
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 186069 
    [ 2.500,  3.750) = 188746 
    [ 3.750,  5.000) = 4182 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     17.282 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
Iteration   1: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 10.992 ms/op
                 listUser·p1.00:   12.321 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.861 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 10.855 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   3: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.641 ms/op
                 listUser·p0.999:  9.608 ms/op
                 listUser·p0.9999: 11.818 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311744
  mean =      3.076 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 77697 
    [ 2.500,  3.750) = 190680 
    [ 3.750,  5.000) = 36020 
    [ 5.000,  6.250) = 6001 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     10.994 ms/op
     p(99.9990) =     12.221 ms/op
     p(99.9999) =     12.321 ms/op
    p(100.0000) =     12.321 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.414 ± 1.872  ops/ms
ClientPb.existUser                       thrpt       3  12.831 ± 2.756  ops/ms
ClientPb.getUser                         thrpt       3  12.680 ± 1.178  ops/ms
ClientPb.listUser                        thrpt       3  10.501 ± 0.892  ops/ms
ClientPb.createUser                       avgt       3   2.591 ± 0.473   ms/op
ClientPb.existUser                        avgt       3   2.495 ± 0.192   ms/op
ClientPb.getUser                          avgt       3   2.543 ± 0.109   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.498   ms/op
ClientPb.createUser                     sample  375373   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.831           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.352           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  382003   2.511 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.505           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.889           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  380065   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.751           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.514           ms/op
ClientPb.listUser                       sample  311744   3.076 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.861           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.321           ms/op
