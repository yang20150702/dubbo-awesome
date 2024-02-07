# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.041 ops/ms
# Warmup Iteration   2: 12.381 ops/ms
# Warmup Iteration   3: 12.569 ops/ms
Iteration   1: 12.903 ops/ms
Iteration   2: 12.698 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.859 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (12.698, 12.859, 12.976), stdev = 0.144
  CI (99.9%): [10.231, 15.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.536 ops/ms
# Warmup Iteration   2: 13.248 ops/ms
# Warmup Iteration   3: 13.349 ops/ms
Iteration   1: 13.316 ops/ms
Iteration   2: 13.433 ops/ms
Iteration   3: 13.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.393 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (13.316, 13.393, 13.433), stdev = 0.067
  CI (99.9%): [12.179, 14.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.742 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.773 ops/ms
Iteration   1: 12.880 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (12.751, 12.842, 12.896), stdev = 0.080
  CI (99.9%): [11.392, 14.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ops/ms
# Warmup Iteration   2: 10.657 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.782 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.740 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (10.651, 10.740, 10.787), stdev = 0.077
  CI (99.9%): [9.330, 12.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.491, 2.502, 2.518), stdev = 0.014
  CI (99.9%): [2.250, 2.754] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.440, 2.443, 2.447), stdev = 0.004
  CI (99.9%): [2.374, 2.512] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (2.494, 2.495, 2.497), stdev = 0.002
  CI (99.9%): [2.463, 2.527] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.778 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
Iteration   3: 2.946 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.946, 2.958, 2.967), stdev = 0.011
  CI (99.9%): [2.756, 3.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  12.018 ms/op
                 createUser·p0.9999: 13.866 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  9.594 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.161 ms/op
                 createUser·p0.9999: 11.598 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380123
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 181945 
    [ 2.500,  3.750) = 194593 
    [ 3.750,  5.000) = 2822 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      9.206 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.093 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.554 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  8.121 ms/op
                 existUser·p0.9999: 12.500 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.960 ms/op
                 existUser·p0.999:  6.339 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390893
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 192683 
    [ 2.500,  3.750) = 194305 
    [ 3.750,  5.000) = 2884 
    [ 5.000,  6.250) = 524 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      7.910 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     14.259 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  7.306 ms/op
                 getUser·p0.9999: 14.143 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  9.724 ms/op
                 getUser·p0.9999: 12.703 ms/op
                 getUser·p1.00:   12.976 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  7.612 ms/op
                 getUser·p0.9999: 10.718 ms/op
                 getUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383239
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 189783 
    [ 2.500,  3.750) = 189161 
    [ 3.750,  5.000) = 3269 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.715 ms/op
     p(99.9900) =     13.069 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.361 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  10.382 ms/op
                 listUser·p0.9999: 12.837 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.014 ms/op
                 listUser·p0.9999: 12.047 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320580
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 96933 
    [ 2.500,  3.750) = 185347 
    [ 3.750,  5.000) = 31179 
    [ 5.000,  6.250) = 5668 
    [ 6.250,  7.500) = 624 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.189 ms/op
     p(99.9990) =     13.523 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.859 ± 2.627  ops/ms
ClientPb.existUser                       thrpt       3  13.393 ± 1.214  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 1.451  ops/ms
ClientPb.listUser                        thrpt       3  10.740 ± 1.410  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.252   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.069   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.032   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.202   ms/op
ClientPb.createUser                     sample  380123   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.206           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.386           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.172           ms/op
ClientPb.existUser                      sample  390893   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.675           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.910           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.451           ms/op
ClientPb.getUser                        sample  383239   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.715           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.069           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.828           ms/op
ClientPb.listUser                       sample  320580   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.828           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.189           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
