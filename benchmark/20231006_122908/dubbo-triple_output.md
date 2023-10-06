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
# Warmup Iteration   1: 1.865 ops/ms
# Warmup Iteration   2: 4.521 ops/ms
# Warmup Iteration   3: 7.868 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 8.088 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.015 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (7.970, 8.015, 8.088), stdev = 0.064
  CI (99.9%): [6.845, 9.185] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 6.943 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.354 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.283 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (8.207, 8.283, 8.354), stdev = 0.074
  CI (99.9%): [6.934, 9.631] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.167 ops/ms
# Warmup Iteration   2: 6.387 ops/ms
# Warmup Iteration   3: 7.548 ops/ms
Iteration   1: 7.732 ops/ms
Iteration   2: 8.012 ops/ms
Iteration   3: 7.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.886 ±(99.9%) 2.587 ops/ms [Average]
  (min, avg, max) = (7.732, 7.886, 8.012), stdev = 0.142
  CI (99.9%): [5.299, 10.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.001 ops/ms
# Warmup Iteration   2: 5.632 ops/ms
# Warmup Iteration   3: 6.445 ops/ms
Iteration   1: 6.673 ops/ms
Iteration   2: 6.751 ops/ms
Iteration   3: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.639 ±(99.9%) 2.413 ops/ms [Average]
  (min, avg, max) = (6.493, 6.639, 6.751), stdev = 0.132
  CI (99.9%): [4.225, 9.052] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.921 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.004 ms/op
Iteration   1: 4.053 ±(99.9%) 0.005 ms/op
Iteration   2: 4.130 ±(99.9%) 0.004 ms/op
Iteration   3: 4.018 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.067 ±(99.9%) 1.047 ms/op [Average]
  (min, avg, max) = (4.018, 4.067, 4.130), stdev = 0.057
  CI (99.9%): [3.020, 5.114] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.362 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.003 ms/op
Iteration   1: 3.794 ±(99.9%) 0.005 ms/op
Iteration   2: 3.830 ±(99.9%) 0.006 ms/op
Iteration   3: 3.950 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.858 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.794, 3.858, 3.950), stdev = 0.082
  CI (99.9%): [2.371, 5.345] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.249 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.002 ms/op
Iteration   1: 3.992 ±(99.9%) 0.004 ms/op
Iteration   2: 3.976 ±(99.9%) 0.004 ms/op
Iteration   3: 3.980 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.983 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (3.976, 3.983, 3.992), stdev = 0.008
  CI (99.9%): [3.835, 4.130] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.992 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.321 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.801 ±(99.9%) 0.008 ms/op
Iteration   1: 4.701 ±(99.9%) 0.011 ms/op
Iteration   2: 4.696 ±(99.9%) 0.005 ms/op
Iteration   3: 4.732 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.709 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (4.696, 4.709, 4.732), stdev = 0.019
  CI (99.9%): [4.355, 5.063] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.821 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.978 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.018 ms/op
Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  22.267 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  24.681 ms/op
                 createUser·p0.9999: 27.408 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 4.168 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.006 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  15.761 ms/op
                 createUser·p0.9999: 30.944 ms/op
                 createUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235280
  mean =      4.077 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 501 
    [ 2.500,  5.000) = 219908 
    [ 5.000,  7.500) = 12128 
    [ 7.500, 10.000) = 1750 
    [10.000, 12.500) = 478 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     22.793 ms/op
     p(99.9900) =     30.490 ms/op
     p(99.9990) =     31.290 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.384 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.012 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 24.337 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   2: 3.932 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.808 ms/op
                 existUser·p0.999:  23.691 ms/op
                 existUser·p0.9999: 29.211 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   3: 3.713 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  13.171 ms/op
                 existUser·p0.9999: 29.123 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250462
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1449 
    [ 2.500,  5.000) = 238773 
    [ 5.000,  7.500) = 8539 
    [ 7.500, 10.000) = 1053 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     28.998 ms/op
     p(99.9990) =     29.720 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.737 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
Iteration   1: 4.104 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   6.308 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  20.217 ms/op
                 getUser·p0.9999: 29.733 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   2: 3.884 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  24.578 ms/op
                 getUser·p0.9999: 27.931 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  11.626 ms/op
                 getUser·p0.9999: 31.293 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239822
  mean =      4.002 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 142 
    [ 2.500,  5.000) = 228018 
    [ 5.000,  7.500) = 7884 
    [ 7.500, 10.000) = 2762 
    [10.000, 12.500) = 573 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     20.158 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     32.218 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.896 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.378 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.016 ms/op
Iteration   1: 4.633 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  23.888 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 4.421 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.012 ms/op
                 listUser·p0.999:  17.246 ms/op
                 listUser·p0.9999: 19.522 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.799 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  18.252 ms/op
                 listUser·p0.9999: 20.043 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208103
  mean =      4.613 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 178733 
    [ 5.000,  7.500) = 24919 
    [ 7.500, 10.000) = 3315 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     25.440 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.015 ± 1.170  ops/ms
ClientPb.existUser                       thrpt       3   8.283 ± 1.348  ops/ms
ClientPb.getUser                         thrpt       3   7.886 ± 2.587  ops/ms
ClientPb.listUser                        thrpt       3   6.639 ± 2.413  ops/ms
ClientPb.createUser                       avgt       3   4.067 ± 1.047   ms/op
ClientPb.existUser                        avgt       3   3.858 ± 1.487   ms/op
ClientPb.getUser                          avgt       3   3.983 ± 0.148   ms/op
ClientPb.listUser                         avgt       3   4.709 ± 0.354   ms/op
ClientPb.createUser                     sample  235280   4.077 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.799           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.793           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  250462   3.831 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.998           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  239822   4.002 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.694           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.956           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.126           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.158           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.507           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  208103   4.613 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.005           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.440           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.492           ms/op
