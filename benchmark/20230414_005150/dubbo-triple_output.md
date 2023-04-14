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
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 9.079 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.754 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (9.549, 9.754, 9.857), stdev = 0.178
  CI (99.9%): [6.512, 12.996] (assumes normal distribution)


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
# Warmup Iteration   1: 3.492 ops/ms
# Warmup Iteration   2: 9.272 ops/ms
# Warmup Iteration   3: 10.423 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.620 ±(99.9%) 3.919 ops/ms [Average]
  (min, avg, max) = (10.382, 10.620, 10.799), stdev = 0.215
  CI (99.9%): [6.700, 14.539] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ops/ms
# Warmup Iteration   2: 9.481 ops/ms
# Warmup Iteration   3: 9.884 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 10.238 ops/ms
Iteration   3: 10.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.193 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (10.134, 10.193, 10.238), stdev = 0.053
  CI (99.9%): [9.223, 11.163] (assumes normal distribution)


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
# Warmup Iteration   1: 3.650 ops/ms
# Warmup Iteration   2: 8.089 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.622 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.554 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (8.509, 8.554, 8.622), stdev = 0.060
  CI (99.9%): [7.451, 9.656] (assumes normal distribution)


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
# Warmup Iteration   1: 8.384 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.007 ms/op
Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
Iteration   3: 3.291 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (3.150, 3.205, 3.291), stdev = 0.075
  CI (99.9%): [1.828, 4.582] (assumes normal distribution)


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
# Warmup Iteration   1: 7.258 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.107 ±(99.9%) 0.004 ms/op
Iteration   2: 3.083 ±(99.9%) 0.004 ms/op
Iteration   3: 2.960 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.050 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (2.960, 3.050, 3.107), stdev = 0.079
  CI (99.9%): [1.605, 4.495] (assumes normal distribution)


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
# Warmup Iteration   1: 7.663 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.007 ms/op
Iteration   1: 3.252 ±(99.9%) 0.006 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 1.351 ms/op [Average]
  (min, avg, max) = (3.113, 3.168, 3.252), stdev = 0.074
  CI (99.9%): [1.817, 4.519] (assumes normal distribution)


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
# Warmup Iteration   1: 8.392 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.007 ms/op
Iteration   1: 3.743 ±(99.9%) 0.004 ms/op
Iteration   2: 3.736 ±(99.9%) 0.008 ms/op
Iteration   3: 3.744 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.741 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (3.736, 3.741, 3.744), stdev = 0.004
  CI (99.9%): [3.659, 3.823] (assumes normal distribution)


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
# Warmup Iteration   1: 8.014 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  9.995 ms/op
                 createUser·p0.9999: 24.009 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  10.121 ms/op
                 createUser·p0.9999: 22.642 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.454 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  16.096 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301641
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15577 
    [ 2.500,  5.000) = 280140 
    [ 5.000,  7.500) = 5123 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     23.653 ms/op
     p(99.9990) =     24.477 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 7.281 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  10.091 ms/op
                 existUser·p0.9999: 21.561 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 21.137 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.482 ms/op
                 existUser·p0.999:  14.483 ms/op
                 existUser·p0.9999: 20.530 ms/op
                 existUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315199
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11409 
    [ 2.500,  5.000) = 298324 
    [ 5.000,  7.500) = 4671 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     21.282 ms/op
     p(99.9990) =     22.408 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 7.435 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.010 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.254 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  16.390 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  10.631 ms/op
                 getUser·p0.9999: 22.410 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 21.585 ms/op
                 getUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298805
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10524 
    [ 2.500,  5.000) = 278818 
    [ 5.000,  7.500) = 8693 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     22.906 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 8.307 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.013 ms/op
Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.296 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 22.529 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   2: 3.616 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.104 ms/op
                 listUser·p0.99:   6.718 ms/op
                 listUser·p0.999:  12.690 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 3.658 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.291 ms/op
                 listUser·p0.999:  13.199 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260685
  mean =      3.681 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 253062 
    [ 5.000,  7.500) = 5862 
    [ 7.500, 10.000) = 1040 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.574 ms/op
     p(99.9990) =     22.831 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.754 ± 3.242  ops/ms
ClientPb.existUser                       thrpt       3  10.620 ± 3.919  ops/ms
ClientPb.getUser                         thrpt       3  10.193 ± 0.970  ops/ms
ClientPb.listUser                        thrpt       3   8.554 ± 1.102  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.377   ms/op
ClientPb.existUser                        avgt       3   3.050 ± 1.445   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 1.351   ms/op
ClientPb.listUser                         avgt       3   3.741 ± 0.082   ms/op
ClientPb.createUser                     sample  301641   3.182 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.454           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.653           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.543           ms/op
ClientPb.existUser                      sample  315199   3.043 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.364           ms/op
ClientPb.getUser                        sample  298805   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.254           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.889           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  260685   3.681 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.296           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.775           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.069           ms/op
