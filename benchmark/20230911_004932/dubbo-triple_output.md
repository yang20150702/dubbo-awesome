# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.951 ops/ms
# Warmup Iteration   2: 5.157 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.649 ops/ms
Iteration   2: 8.979 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.900 ±(99.9%) 4.053 ops/ms [Average]
  (min, avg, max) = (8.649, 8.900, 9.072), stdev = 0.222
  CI (99.9%): [4.847, 12.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 7.921 ops/ms
# Warmup Iteration   3: 9.050 ops/ms
Iteration   1: 9.482 ops/ms
Iteration   2: 9.016 ops/ms
Iteration   3: 9.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.328 ±(99.9%) 4.930 ops/ms [Average]
  (min, avg, max) = (9.016, 9.328, 9.487), stdev = 0.270
  CI (99.9%): [4.398, 14.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 8.146 ops/ms
# Warmup Iteration   3: 8.785 ops/ms
Iteration   1: 8.950 ops/ms
Iteration   2: 8.960 ops/ms
Iteration   3: 8.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.936 ±(99.9%) 0.624 ops/ms [Average]
  (min, avg, max) = (8.897, 8.936, 8.960), stdev = 0.034
  CI (99.9%): [8.312, 9.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.734 ops/ms
# Warmup Iteration   2: 6.956 ops/ms
# Warmup Iteration   3: 7.506 ops/ms
Iteration   1: 7.729 ops/ms
Iteration   2: 7.677 ops/ms
Iteration   3: 7.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.720 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (7.677, 7.720, 7.753), stdev = 0.039
  CI (99.9%): [7.006, 8.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.147 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.919 ±(99.9%) 0.007 ms/op
Iteration   1: 3.692 ±(99.9%) 0.006 ms/op
Iteration   2: 3.638 ±(99.9%) 0.003 ms/op
Iteration   3: 3.655 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.662 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.638, 3.662, 3.692), stdev = 0.027
  CI (99.9%): [3.161, 4.163] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.239 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.451 ±(99.9%) 0.012 ms/op
Iteration   2: 3.428 ±(99.9%) 0.005 ms/op
Iteration   3: 3.528 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.469 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.428, 3.469, 3.528), stdev = 0.052
  CI (99.9%): [2.518, 4.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.891 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.005 ms/op
Iteration   1: 3.540 ±(99.9%) 0.003 ms/op
Iteration   2: 3.510 ±(99.9%) 0.005 ms/op
Iteration   3: 3.575 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.542 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.510, 3.542, 3.575), stdev = 0.033
  CI (99.9%): [2.946, 4.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.175 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.009 ms/op
Iteration   1: 4.188 ±(99.9%) 0.007 ms/op
Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
Iteration   3: 3.977 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.078 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (3.977, 4.078, 4.188), stdev = 0.106
  CI (99.9%): [2.151, 6.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.339 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.017 ms/op
Iteration   1: 3.447 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  22.723 ms/op
                 createUser·p0.9999: 28.934 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.537 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  21.350 ms/op
                 createUser·p0.9999: 26.770 ms/op
                 createUser·p1.00:   27.787 ms/op

Iteration   3: 3.480 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  19.795 ms/op
                 createUser·p0.9999: 28.305 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275107
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4612 
    [ 2.500,  5.000) = 262286 
    [ 5.000,  7.500) = 6565 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 108 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     20.149 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.627 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
Iteration   1: 3.501 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  20.687 ms/op
                 existUser·p0.9999: 23.317 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  21.634 ms/op
                 existUser·p0.9999: 29.065 ms/op
                 existUser·p1.00:   29.458 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  10.654 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281076
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12656 
    [ 2.500,  5.000) = 260289 
    [ 5.000,  7.500) = 6686 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     29.319 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.573 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.011 ms/op
Iteration   1: 3.691 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.058 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  14.397 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.668 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  22.697 ms/op
                 getUser·p0.9999: 26.191 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 3.597 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.005 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  25.100 ms/op
                 getUser·p0.9999: 35.462 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262758
  mean =      3.652 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4778 
    [ 2.500,  5.000) = 248028 
    [ 5.000,  7.500) = 7836 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     17.473 ms/op
     p(99.9900) =     33.527 ms/op
     p(99.9990) =     35.652 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.878 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.351 ±(99.9%) 0.015 ms/op
Iteration   1: 4.143 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.373 ms/op
                 listUser·p0.999:  21.823 ms/op
                 listUser·p0.9999: 24.061 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.209 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  17.042 ms/op
                 listUser·p0.9999: 18.953 ms/op
                 listUser·p1.00:   23.069 ms/op

Iteration   3: 4.207 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 16.771 ms/op
                 listUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229083
  mean =      4.186 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 219084 
    [ 5.000,  7.500) = 6287 
    [ 7.500, 10.000) = 2376 
    [10.000, 12.500) = 771 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     17.037 ms/op
     p(99.9900) =     23.367 ms/op
     p(99.9990) =     24.698 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.900 ± 4.053  ops/ms
ClientPb.existUser                       thrpt       3   9.328 ± 4.930  ops/ms
ClientPb.getUser                         thrpt       3   8.936 ± 0.624  ops/ms
ClientPb.listUser                        thrpt       3   7.720 ± 0.714  ops/ms
ClientPb.createUser                       avgt       3   3.662 ± 0.501   ms/op
ClientPb.existUser                        avgt       3   3.469 ± 0.951   ms/op
ClientPb.getUser                          avgt       3   3.542 ± 0.596   ms/op
ClientPb.listUser                         avgt       3   4.078 ± 1.927   ms/op
ClientPb.createUser                     sample  275107   3.488 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.303           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.149           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.410           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.262           ms/op
ClientPb.existUser                      sample  281076   3.413 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.177           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.458           ms/op
ClientPb.getUser                        sample  262758   3.652 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.696           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.473           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.527           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  229083   4.186 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.037           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.367           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
