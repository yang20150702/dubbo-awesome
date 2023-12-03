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
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 12.050 ops/ms
# Warmup Iteration   3: 12.426 ops/ms
Iteration   1: 12.752 ops/ms
Iteration   2: 12.649 ops/ms
Iteration   3: 12.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.668 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (12.604, 12.668, 12.752), stdev = 0.076
  CI (99.9%): [11.285, 14.052] (assumes normal distribution)


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
# Warmup Iteration   1: 7.682 ops/ms
# Warmup Iteration   2: 12.758 ops/ms
# Warmup Iteration   3: 12.888 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 13.015 ops/ms
Iteration   3: 12.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.916 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (12.847, 12.916, 13.015), stdev = 0.088
  CI (99.9%): [11.311, 14.521] (assumes normal distribution)


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
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 12.586 ops/ms
# Warmup Iteration   3: 12.618 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.650 ops/ms
Iteration   3: 12.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.699 ±(99.9%) 1.037 ops/ms [Average]
  (min, avg, max) = (12.650, 12.699, 12.761), stdev = 0.057
  CI (99.9%): [11.661, 13.736] (assumes normal distribution)


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
# Warmup Iteration   1: 6.667 ops/ms
# Warmup Iteration   2: 10.150 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.519 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.428 ±(99.9%) 2.592 ops/ms [Average]
  (min, avg, max) = (10.264, 10.428, 10.519), stdev = 0.142
  CI (99.9%): [7.836, 13.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.606 ±(99.9%) 0.005 ms/op
Iteration   3: 2.559 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.584 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (2.559, 2.584, 2.606), stdev = 0.024
  CI (99.9%): [2.149, 3.020] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.497 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.482, 2.497, 2.508), stdev = 0.013
  CI (99.9%): [2.252, 2.741] (assumes normal distribution)


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
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
Iteration   2: 2.513 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.505, 2.509, 2.513), stdev = 0.004
  CI (99.9%): [2.432, 2.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.993 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
Iteration   2: 3.076 ±(99.9%) 0.005 ms/op
Iteration   3: 3.077 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.077 ±(99.9%) 0.012 ms/op [Average]
  (min, avg, max) = (3.076, 3.077, 3.078), stdev = 0.001
  CI (99.9%): [3.065, 3.089] (assumes normal distribution)


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 14.335 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.036 ms/op
                 createUser·p0.9999: 15.385 ms/op
                 createUser·p1.00:   16.253 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 12.704 ms/op
                 createUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376576
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 179929 
    [ 2.500,  3.750) = 191801 
    [ 3.750,  5.000) = 3837 
    [ 5.000,  6.250) = 422 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      8.550 ms/op
     p(99.9900) =     14.424 ms/op
     p(99.9990) =     16.109 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 14.888 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  8.146 ms/op
                 existUser·p0.9999: 15.251 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 13.332 ms/op
                 existUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379297
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 183996 
    [ 2.500,  3.750) = 191041 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 77 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.398 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     15.593 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  6.974 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  10.940 ms/op
                 getUser·p0.9999: 16.028 ms/op
                 getUser·p1.00:   16.974 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  9.375 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380922
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 185908 
    [ 2.500,  3.750) = 190085 
    [ 3.750,  5.000) = 3687 
    [ 5.000,  6.250) = 639 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      7.628 ms/op
     p(99.9900) =     14.973 ms/op
     p(99.9990) =     16.490 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.215 ms/op
                 listUser·p0.9999: 11.465 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.664 ms/op
                 listUser·p0.9999: 12.121 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  10.027 ms/op
                 listUser·p0.9999: 14.073 ms/op
                 listUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313853
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 81782 
    [ 2.500,  3.750) = 190011 
    [ 3.750,  5.000) = 34201 
    [ 5.000,  6.250) = 6302 
    [ 6.250,  7.500) = 761 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 219 
    [10.000, 11.250) = 244 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.308 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.668 ± 1.384  ops/ms
ClientPb.existUser                       thrpt       3  12.916 ± 1.605  ops/ms
ClientPb.getUser                         thrpt       3  12.699 ± 1.037  ops/ms
ClientPb.listUser                        thrpt       3  10.428 ± 2.592  ops/ms
ClientPb.createUser                       avgt       3   2.584 ± 0.435   ms/op
ClientPb.existUser                        avgt       3   2.497 ± 0.245   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.076   ms/op
ClientPb.listUser                         avgt       3   3.077 ± 0.012   ms/op
ClientPb.createUser                     sample  376576   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.550           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.424           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.253           ms/op
ClientPb.existUser                      sample  379297   2.528 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.402           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.565           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.089           ms/op
ClientPb.getUser                        sample  380922   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.670           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.628           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.973           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.974           ms/op
ClientPb.listUser                       sample  313853   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.808           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.042           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.352           ms/op
