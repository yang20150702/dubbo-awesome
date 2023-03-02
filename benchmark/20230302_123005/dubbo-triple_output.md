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
# Warmup Iteration   1: 2.565 ops/ms
# Warmup Iteration   2: 5.621 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 9.633 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.749 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (9.633, 9.749, 9.932), stdev = 0.161
  CI (99.9%): [6.812, 12.685] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ops/ms
# Warmup Iteration   2: 9.259 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.189 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.248 ±(99.9%) 1.041 ops/ms [Average]
  (min, avg, max) = (10.189, 10.248, 10.303), stdev = 0.057
  CI (99.9%): [9.207, 11.289] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.275 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.516 ops/ms
Iteration   1: 9.972 ops/ms
Iteration   2: 9.963 ops/ms
Iteration   3: 9.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.887 ±(99.9%) 2.552 ops/ms [Average]
  (min, avg, max) = (9.725, 9.887, 9.972), stdev = 0.140
  CI (99.9%): [7.334, 12.439] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.551 ops/ms
# Warmup Iteration   2: 8.099 ops/ms
# Warmup Iteration   3: 8.501 ops/ms
Iteration   1: 8.770 ops/ms
Iteration   2: 8.458 ops/ms
Iteration   3: 8.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.574 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (8.458, 8.574, 8.770), stdev = 0.170
  CI (99.9%): [5.471, 11.678] (assumes normal distribution)


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
# Warmup Iteration   1: 8.142 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.004 ms/op
Iteration   1: 3.186 ±(99.9%) 0.004 ms/op
Iteration   2: 3.171 ±(99.9%) 0.004 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.176 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.171, 3.176, 3.186), stdev = 0.008
  CI (99.9%): [3.023, 3.330] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.060 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.008 ms/op
Iteration   1: 3.114 ±(99.9%) 0.003 ms/op
Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.081 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.006, 3.081, 3.124), stdev = 0.065
  CI (99.9%): [1.888, 4.275] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.637 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.007 ms/op
Iteration   1: 3.303 ±(99.9%) 0.003 ms/op
Iteration   2: 3.240 ±(99.9%) 0.005 ms/op
Iteration   3: 3.222 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.222, 3.255, 3.303), stdev = 0.043
  CI (99.9%): [2.477, 4.034] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.244 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.007 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
Iteration   2: 3.687 ±(99.9%) 0.009 ms/op
Iteration   3: 3.671 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.701 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.671, 3.701, 3.745), stdev = 0.039
  CI (99.9%): [2.988, 4.414] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.021 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  19.433 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.100 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.527 ms/op
                 createUser·p0.99:   5.529 ms/op
                 createUser·p0.999:  14.093 ms/op
                 createUser·p0.9999: 21.748 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.428 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 309128
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20881 
    [ 2.500,  5.000) = 283859 
    [ 5.000,  7.500) = 3625 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     21.990 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.588 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.480 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.278 ms/op
                 existUser·p0.999:  9.117 ms/op
                 existUser·p0.9999: 20.316 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 21.815 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  13.930 ms/op
                 existUser·p0.9999: 20.307 ms/op
                 existUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310065
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22977 
    [ 2.500,  5.000) = 282856 
    [ 5.000,  7.500) = 3485 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.712 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     22.308 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.571 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.009 ms/op
Iteration   1: 3.231 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  16.530 ms/op
                 getUser·p0.9999: 20.683 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.317 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  15.938 ms/op
                 getUser·p0.9999: 21.278 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  8.723 ms/op
                 getUser·p0.9999: 19.593 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295976
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18244 
    [ 2.500,  5.000) = 270617 
    [ 5.000,  7.500) = 6108 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     20.919 ms/op
     p(99.9990) =     21.793 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


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
# Warmup Iteration   1: 9.274 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.012 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.713 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.763 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  13.304 ms/op
                 listUser·p0.9999: 15.663 ms/op
                 listUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253488
  mean =      3.784 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 245509 
    [ 5.000,  7.500) = 5963 
    [ 7.500, 10.000) = 1354 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     19.617 ms/op
     p(99.9990) =     21.705 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.749 ± 2.937  ops/ms
ClientPb.existUser                       thrpt       3  10.248 ± 1.041  ops/ms
ClientPb.getUser                         thrpt       3   9.887 ± 2.552  ops/ms
ClientPb.listUser                        thrpt       3   8.574 ± 3.103  ops/ms
ClientPb.createUser                       avgt       3   3.176 ± 0.153   ms/op
ClientPb.existUser                        avgt       3   3.081 ± 1.194   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 0.778   ms/op
ClientPb.listUser                         avgt       3   3.701 ± 0.713   ms/op
ClientPb.createUser                     sample  309128   3.104 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.135           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.576           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.205           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.990           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.691           ms/op
ClientPb.existUser                      sample  310065   3.096 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.722           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.201           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.381           ms/op
ClientPb.getUser                        sample  295976   3.241 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.071           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.958           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.919           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.987           ms/op
ClientPb.listUser                       sample  253488   3.784 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.617           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.856           ms/op
