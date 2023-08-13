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
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 5.923 ops/ms
# Warmup Iteration   3: 8.947 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.722 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.611 ±(99.9%) 2.928 ops/ms [Average]
  (min, avg, max) = (9.427, 9.611, 9.722), stdev = 0.161
  CI (99.9%): [6.683, 12.539] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
# Warmup Iteration   2: 9.251 ops/ms
# Warmup Iteration   3: 9.682 ops/ms
Iteration   1: 10.126 ops/ms
Iteration   2: 10.268 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.143 ±(99.9%) 2.136 ops/ms [Average]
  (min, avg, max) = (10.036, 10.143, 10.268), stdev = 0.117
  CI (99.9%): [8.008, 12.279] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.226 ops/ms
# Warmup Iteration   2: 9.058 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 9.940 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 9.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.750 ±(99.9%) 4.615 ops/ms [Average]
  (min, avg, max) = (9.463, 9.750, 9.940), stdev = 0.253
  CI (99.9%): [5.136, 14.365] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.123 ops/ms
# Warmup Iteration   2: 7.748 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 8.444 ops/ms
Iteration   2: 8.603 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.514 ±(99.9%) 1.482 ops/ms [Average]
  (min, avg, max) = (8.444, 8.514, 8.603), stdev = 0.081
  CI (99.9%): [7.032, 9.996] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.615 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.002 ms/op
Iteration   1: 3.286 ±(99.9%) 0.006 ms/op
Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
Iteration   3: 3.274 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.261 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.224, 3.261, 3.286), stdev = 0.033
  CI (99.9%): [2.662, 3.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.458 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.027, 3.035, 3.045), stdev = 0.009
  CI (99.9%): [2.862, 3.208] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.663 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.005 ms/op
Iteration   1: 3.333 ±(99.9%) 0.006 ms/op
Iteration   2: 3.236 ±(99.9%) 0.004 ms/op
Iteration   3: 3.225 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.225, 3.265, 3.333), stdev = 0.060
  CI (99.9%): [2.173, 4.356] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.571 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.007 ms/op
Iteration   1: 3.767 ±(99.9%) 0.005 ms/op
Iteration   2: 3.739 ±(99.9%) 0.011 ms/op
Iteration   3: 3.744 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.750 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.739, 3.750, 3.767), stdev = 0.015
  CI (99.9%): [3.482, 4.018] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.926 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  10.686 ms/op
                 createUser·p0.9999: 21.490 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  11.747 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  15.543 ms/op
                 createUser·p0.9999: 18.842 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300400
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13408 
    [ 2.500,  5.000) = 279925 
    [ 5.000,  7.500) = 5248 
    [ 7.500, 10.000) = 1321 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     22.215 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 8.753 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.749 ms/op
                 existUser·p0.999:  11.249 ms/op
                 existUser·p0.9999: 20.649 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.237 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  15.237 ms/op
                 existUser·p0.9999: 22.188 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  9.628 ms/op
                 existUser·p0.9999: 21.922 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298420
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27954 
    [ 2.500,  5.000) = 263419 
    [ 5.000,  7.500) = 5762 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 7.857 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.012 ms/op
Iteration   1: 3.213 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  17.808 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.185 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 21.855 ms/op
                 getUser·p1.00:   22.282 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.553 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  14.932 ms/op
                 getUser·p0.9999: 20.921 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295484
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12065 
    [ 2.500,  5.000) = 272893 
    [ 5.000,  7.500) = 8821 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     22.296 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 8.889 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.013 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  17.459 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  12.709 ms/op
                 listUser·p0.9999: 15.679 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  13.509 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248752
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 238583 
    [ 5.000,  7.500) = 7746 
    [ 7.500, 10.000) = 1521 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     21.012 ms/op
     p(99.9990) =     22.692 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.611 ± 2.928  ops/ms
ClientPb.existUser                       thrpt       3  10.143 ± 2.136  ops/ms
ClientPb.getUser                         thrpt       3   9.750 ± 4.615  ops/ms
ClientPb.listUser                        thrpt       3   8.514 ± 1.482  ops/ms
ClientPb.createUser                       avgt       3   3.261 ± 0.599   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 0.173   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 1.091   ms/op
ClientPb.listUser                         avgt       3   3.750 ± 0.268   ms/op
ClientPb.createUser                     sample  300400   3.195 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.059           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.320           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.215           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.248           ms/op
ClientPb.existUser                      sample  298420   3.215 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.958           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  295484   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.553           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.103           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.905           ms/op
ClientPb.listUser                       sample  248752   3.857 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.307           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.746           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.012           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
