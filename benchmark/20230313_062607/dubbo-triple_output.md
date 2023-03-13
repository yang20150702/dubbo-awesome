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
# Warmup Iteration   1: 2.501 ops/ms
# Warmup Iteration   2: 6.777 ops/ms
# Warmup Iteration   3: 9.225 ops/ms
Iteration   1: 9.918 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 9.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.799 ±(99.9%) 9.646 ops/ms [Average]
  (min, avg, max) = (9.221, 9.799, 10.258), stdev = 0.529
  CI (99.9%): [0.154, 19.445] (assumes normal distribution)


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
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 9.515 ops/ms
# Warmup Iteration   3: 10.379 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.427 ops/ms
Iteration   3: 10.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.500 ±(99.9%) 2.185 ops/ms [Average]
  (min, avg, max) = (10.427, 10.500, 10.638), stdev = 0.120
  CI (99.9%): [8.315, 12.685] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ops/ms
# Warmup Iteration   2: 9.526 ops/ms
# Warmup Iteration   3: 9.816 ops/ms
Iteration   1: 10.222 ops/ms
Iteration   2: 10.141 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.212 ±(99.9%) 1.220 ops/ms [Average]
  (min, avg, max) = (10.141, 10.212, 10.273), stdev = 0.067
  CI (99.9%): [8.992, 11.432] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ops/ms
# Warmup Iteration   2: 7.755 ops/ms
# Warmup Iteration   3: 8.622 ops/ms
Iteration   1: 8.666 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.668 ±(99.9%) 4.665 ops/ms [Average]
  (min, avg, max) = (8.413, 8.668, 8.924), stdev = 0.256
  CI (99.9%): [4.003, 13.332] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.499 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.005 ms/op
Iteration   1: 3.137 ±(99.9%) 0.006 ms/op
Iteration   2: 3.224 ±(99.9%) 0.005 ms/op
Iteration   3: 3.321 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.227 ±(99.9%) 1.677 ms/op [Average]
  (min, avg, max) = (3.137, 3.227, 3.321), stdev = 0.092
  CI (99.9%): [1.551, 4.904] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.308 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.005 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.978 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (2.918, 2.978, 3.061), stdev = 0.075
  CI (99.9%): [1.617, 4.338] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.003 ms/op
Iteration   1: 3.163 ±(99.9%) 0.002 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.172 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.136 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.074, 3.136, 3.172), stdev = 0.054
  CI (99.9%): [2.144, 4.128] (assumes normal distribution)


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
# Warmup Iteration   1: 8.388 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.009 ms/op
Iteration   1: 3.673 ±(99.9%) 0.006 ms/op
Iteration   2: 3.691 ±(99.9%) 0.008 ms/op
Iteration   3: 3.710 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.692 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.673, 3.692, 3.710), stdev = 0.018
  CI (99.9%): [3.359, 4.024] (assumes normal distribution)


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
# Warmup Iteration   1: 8.047 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
Iteration   1: 3.103 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.158 ms/op
                 createUser·p0.9999: 23.300 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.750 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  17.895 ms/op
                 createUser·p0.9999: 22.307 ms/op
                 createUser·p1.00:   24.216 ms/op

Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.289 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   5.184 ms/op
                 createUser·p0.999:  15.687 ms/op
                 createUser·p0.9999: 19.595 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 308310
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15775 
    [ 2.500,  5.000) = 287483 
    [ 5.000,  7.500) = 4100 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.943 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.983 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 7.530 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  11.715 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   19.038 ms/op

Iteration   2: 3.069 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  19.097 ms/op
                 existUser·p0.9999: 42.636 ms/op
                 existUser·p1.00:   44.368 ms/op

Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  11.858 ms/op
                 existUser·p0.9999: 19.650 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308178
  mean =      3.112 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 302242 
    [ 5.000, 10.000) = 5457 
    [10.000, 15.000) = 187 
    [15.000, 20.000) = 220 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.151 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     43.434 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


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
# Warmup Iteration   1: 8.025 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.011 ms/op
Iteration   1: 3.239 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 25.895 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  11.080 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  11.276 ms/op
                 getUser·p0.9999: 21.366 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299891
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19200 
    [ 2.500,  5.000) = 273961 
    [ 5.000,  7.500) = 5734 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 165 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     15.780 ms/op
     p(99.9900) =     24.250 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 8.698 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 19.152 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.477 ms/op
                 listUser·p0.999:  13.530 ms/op
                 listUser·p0.9999: 18.395 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.677 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.747 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258495
  mean =      3.714 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 122 
    [ 2.500,  3.750) = 203936 
    [ 3.750,  5.000) = 45074 
    [ 5.000,  6.250) = 4510 
    [ 6.250,  7.500) = 3065 
    [ 7.500,  8.750) = 766 
    [ 8.750, 10.000) = 298 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 228 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 89 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     19.379 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.799 ± 9.646  ops/ms
ClientPb.existUser                       thrpt       3  10.500 ± 2.185  ops/ms
ClientPb.getUser                         thrpt       3  10.212 ± 1.220  ops/ms
ClientPb.listUser                        thrpt       3   8.668 ± 4.665  ops/ms
ClientPb.createUser                       avgt       3   3.227 ± 1.677   ms/op
ClientPb.existUser                        avgt       3   2.978 ± 1.360   ms/op
ClientPb.getUser                          avgt       3   3.136 ± 0.992   ms/op
ClientPb.listUser                         avgt       3   3.692 ± 0.333   ms/op
ClientPb.createUser                     sample  308310   3.113 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.802           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.943           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.512           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.314           ms/op
ClientPb.existUser                      sample  308178   3.112 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.081           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.586           ms/op
ClientPb.existUser:existUser·p1.00      sample          44.368           ms/op
ClientPb.getUser                        sample  299891   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.780           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.250           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  258495   3.714 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.091           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.350           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.530           ms/op
