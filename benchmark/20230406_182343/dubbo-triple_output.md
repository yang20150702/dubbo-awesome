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
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.933 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.049 ±(99.9%) 5.998 ops/ms [Average]
  (min, avg, max) = (9.794, 10.049, 10.421), stdev = 0.329
  CI (99.9%): [4.051, 16.048] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ops/ms
# Warmup Iteration   2: 9.341 ops/ms
# Warmup Iteration   3: 10.453 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.535 ±(99.9%) 2.882 ops/ms [Average]
  (min, avg, max) = (10.411, 10.535, 10.713), stdev = 0.158
  CI (99.9%): [7.654, 13.417] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ops/ms
# Warmup Iteration   2: 9.487 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 9.837 ops/ms
Iteration   2: 10.058 ops/ms
Iteration   3: 9.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.889 ±(99.9%) 2.725 ops/ms [Average]
  (min, avg, max) = (9.773, 9.889, 10.058), stdev = 0.149
  CI (99.9%): [7.164, 12.614] (assumes normal distribution)


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
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 8.047 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.761 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.511 ±(99.9%) 3.950 ops/ms [Average]
  (min, avg, max) = (8.372, 8.511, 8.761), stdev = 0.217
  CI (99.9%): [4.561, 12.461] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.708 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.004 ms/op
Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
Iteration   3: 3.016 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.087 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.016, 3.087, 3.141), stdev = 0.064
  CI (99.9%): [1.922, 4.251] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.648 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.004 ms/op
Iteration   1: 3.238 ±(99.9%) 0.006 ms/op
Iteration   2: 3.124 ±(99.9%) 0.009 ms/op
Iteration   3: 3.052 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.138 ±(99.9%) 1.709 ms/op [Average]
  (min, avg, max) = (3.052, 3.138, 3.238), stdev = 0.094
  CI (99.9%): [1.428, 4.847] (assumes normal distribution)


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
# Warmup Iteration   1: 7.647 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
Iteration   1: 3.141 ±(99.9%) 0.004 ms/op
Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
Iteration   3: 3.320 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.194 ±(99.9%) 1.998 ms/op [Average]
  (min, avg, max) = (3.121, 3.194, 3.320), stdev = 0.110
  CI (99.9%): [1.196, 5.192] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.575 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.005 ms/op
Iteration   1: 3.791 ±(99.9%) 0.006 ms/op
Iteration   2: 3.706 ±(99.9%) 0.008 ms/op
Iteration   3: 3.686 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.728 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.686, 3.728, 3.791), stdev = 0.056
  CI (99.9%): [2.708, 4.747] (assumes normal distribution)


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
# Warmup Iteration   1: 8.137 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.009 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  12.567 ms/op
                 createUser·p0.9999: 20.142 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  10.466 ms/op
                 createUser·p0.9999: 22.377 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 23.857 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306481
  mean =      3.133 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24658 
    [ 2.500,  5.000) = 276957 
    [ 5.000,  7.500) = 3914 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     14.263 ms/op
     p(99.9900) =     23.244 ms/op
     p(99.9990) =     25.393 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 8.312 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  10.323 ms/op
                 existUser·p0.9999: 22.631 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.282 ms/op
                 existUser·p0.999:  13.824 ms/op
                 existUser·p0.9999: 21.256 ms/op
                 existUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315120
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17805 
    [ 2.500,  5.000) = 292371 
    [ 5.000,  7.500) = 4154 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.548 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 7.665 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.329 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  16.696 ms/op
                 getUser·p0.9999: 26.719 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 21.178 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  9.585 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301489
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11258 
    [ 2.500,  5.000) = 281704 
    [ 5.000,  7.500) = 7524 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     15.786 ms/op
     p(99.9900) =     25.862 ms/op
     p(99.9990) =     27.033 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 9.031 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.013 ms/op
Iteration   1: 3.699 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.966 ms/op
                 listUser·p0.9999: 22.850 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 3.665 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   3.748 ms/op
                 listUser·p0.95:   3.895 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  12.042 ms/op
                 listUser·p0.9999: 14.996 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   3: 3.728 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.156 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259527
  mean =      3.697 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 252919 
    [ 5.000,  7.500) = 4780 
    [ 7.500, 10.000) = 1132 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.592 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     22.320 ms/op
     p(99.9990) =     23.384 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.049 ± 5.998  ops/ms
ClientPb.existUser                       thrpt       3  10.535 ± 2.882  ops/ms
ClientPb.getUser                         thrpt       3   9.889 ± 2.725  ops/ms
ClientPb.listUser                        thrpt       3   8.511 ± 3.950  ops/ms
ClientPb.createUser                       avgt       3   3.087 ± 1.165   ms/op
ClientPb.existUser                        avgt       3   3.138 ± 1.709   ms/op
ClientPb.getUser                          avgt       3   3.194 ± 1.998   ms/op
ClientPb.listUser                         avgt       3   3.728 ± 1.020   ms/op
ClientPb.createUser                     sample  306481   3.133 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.027           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.263           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.244           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  315120   3.042 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.077           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.548           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  301489   3.182 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.786           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.862           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.197           ms/op
ClientPb.listUser                       sample  259527   3.697 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.055           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.592           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.320           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.593           ms/op
