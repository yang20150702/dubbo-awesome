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
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 3.860 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.629 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.352 ±(99.9%) 5.897 ops/ms [Average]
  (min, avg, max) = (7.997, 8.352, 8.629), stdev = 0.323
  CI (99.9%): [2.455, 14.250] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.374 ops/ms
# Warmup Iteration   2: 6.742 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.352 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.375 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (8.259, 8.375, 8.514), stdev = 0.130
  CI (99.9%): [6.012, 10.738] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.231 ops/ms
# Warmup Iteration   2: 6.974 ops/ms
# Warmup Iteration   3: 8.056 ops/ms
Iteration   1: 7.909 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.235 ±(99.9%) 5.226 ops/ms [Average]
  (min, avg, max) = (7.909, 8.235, 8.448), stdev = 0.286
  CI (99.9%): [3.009, 13.461] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.694 ops/ms
# Warmup Iteration   3: 6.684 ops/ms
Iteration   1: 6.801 ops/ms
Iteration   2: 7.056 ops/ms
Iteration   3: 7.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.982 ±(99.9%) 2.875 ops/ms [Average]
  (min, avg, max) = (6.801, 6.982, 7.089), stdev = 0.158
  CI (99.9%): [4.107, 9.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.589 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.875 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.003 ms/op
Iteration   1: 3.851 ±(99.9%) 0.004 ms/op
Iteration   2: 3.889 ±(99.9%) 0.004 ms/op
Iteration   3: 3.954 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.898 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.851, 3.898, 3.954), stdev = 0.053
  CI (99.9%): [2.939, 4.856] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.015 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.002 ms/op
Iteration   1: 3.840 ±(99.9%) 0.005 ms/op
Iteration   2: 3.656 ±(99.9%) 0.005 ms/op
Iteration   3: 3.681 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.726 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (3.656, 3.726, 3.840), stdev = 0.100
  CI (99.9%): [1.902, 5.549] (assumes normal distribution)


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
# Warmup Iteration   1: 10.660 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.004 ms/op
Iteration   1: 4.155 ±(99.9%) 0.003 ms/op
Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
Iteration   3: 3.908 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.970 ±(99.9%) 2.961 ms/op [Average]
  (min, avg, max) = (3.849, 3.970, 4.155), stdev = 0.162
  CI (99.9%): [1.009, 6.931] (assumes normal distribution)


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
# Warmup Iteration   1: 13.532 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.342 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.793 ±(99.9%) 0.005 ms/op
Iteration   1: 4.589 ±(99.9%) 0.009 ms/op
Iteration   2: 4.686 ±(99.9%) 0.006 ms/op
Iteration   3: 4.936 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.737 ±(99.9%) 3.272 ms/op [Average]
  (min, avg, max) = (4.589, 4.737, 4.936), stdev = 0.179
  CI (99.9%): [1.464, 8.009] (assumes normal distribution)


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
# Warmup Iteration   1: 12.285 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 5.000 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.016 ms/op
Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.998 ms/op
                 createUser·p0.999:  15.336 ms/op
                 createUser·p0.9999: 23.449 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.835 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.895 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.793 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  26.324 ms/op
                 createUser·p0.9999: 29.641 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243485
  mean =      3.940 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1318 
    [ 2.500,  5.000) = 230139 
    [ 5.000,  7.500) = 10442 
    [ 7.500, 10.000) = 1015 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     30.399 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 11.601 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   5.046 ms/op
                 existUser·p0.99:   7.450 ms/op
                 existUser·p0.999:  22.381 ms/op
                 existUser·p0.9999: 27.095 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   3: 3.828 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.665 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.839 ms/op
                 existUser·p0.999:  16.744 ms/op
                 existUser·p0.9999: 27.689 ms/op
                 existUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246243
  mean =      3.895 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 797 
    [ 2.500,  5.000) = 235314 
    [ 5.000,  7.500) = 8122 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 95 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.074 ms/op
     p(99.9000) =     16.196 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     28.649 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 10.703 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.014 ms/op
Iteration   1: 3.847 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   2: 3.964 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  24.157 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 3.837 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   7.463 ms/op
                 getUser·p0.999:  11.660 ms/op
                 getUser·p0.9999: 35.542 ms/op
                 getUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247249
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 586 
    [ 2.500,  5.000) = 237167 
    [ 5.000,  7.500) = 7468 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.205 ms/op
     p(99.9000) =     16.867 ms/op
     p(99.9900) =     31.115 ms/op
     p(99.9990) =     36.411 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 14.824 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.557 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.943 ±(99.9%) 0.017 ms/op
Iteration   1: 4.893 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 30.490 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 4.896 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  20.759 ms/op
                 listUser·p0.9999: 25.536 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   3: 4.572 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  17.369 ms/op
                 listUser·p0.9999: 18.548 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200555
  mean =      4.782 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 154910 
    [ 5.000,  7.500) = 41691 
    [ 7.500, 10.000) = 2784 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 244 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     29.748 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.352 ± 5.897  ops/ms
ClientPb.existUser                       thrpt       3   8.375 ± 2.363  ops/ms
ClientPb.getUser                         thrpt       3   8.235 ± 5.226  ops/ms
ClientPb.listUser                        thrpt       3   6.982 ± 2.875  ops/ms
ClientPb.createUser                       avgt       3   3.898 ± 0.958   ms/op
ClientPb.existUser                        avgt       3   3.726 ± 1.823   ms/op
ClientPb.getUser                          avgt       3   3.970 ± 2.961   ms/op
ClientPb.listUser                         avgt       3   4.737 ± 3.272   ms/op
ClientPb.createUser                     sample  243485   3.940 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.005           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.869           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.802           ms/op
ClientPb.existUser                      sample  246243   3.895 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.074           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.196           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.361           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.164           ms/op
ClientPb.getUser                        sample  247249   3.882 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.260           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.205           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.867           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.115           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569           ms/op
ClientPb.listUser                       sample  200555   4.782 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.056           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.748           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.097           ms/op
