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
# Warmup Iteration   1: 1.092 ops/ms
# Warmup Iteration   2: 2.649 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 6.008 ops/ms
Iteration   2: 6.467 ops/ms
Iteration   3: 6.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.315 ±(99.9%) 4.858 ops/ms [Average]
  (min, avg, max) = (6.008, 6.315, 6.471), stdev = 0.266
  CI (99.9%): [1.458, 11.173] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 5.474 ops/ms
# Warmup Iteration   3: 6.227 ops/ms
Iteration   1: 6.315 ops/ms
Iteration   2: 6.465 ops/ms
Iteration   3: 6.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.484 ±(99.9%) 3.277 ops/ms [Average]
  (min, avg, max) = (6.315, 6.484, 6.673), stdev = 0.180
  CI (99.9%): [3.207, 9.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.727 ops/ms
# Warmup Iteration   2: 5.187 ops/ms
# Warmup Iteration   3: 6.220 ops/ms
Iteration   1: 6.042 ops/ms
Iteration   2: 6.084 ops/ms
Iteration   3: 6.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.132 ±(99.9%) 2.213 ops/ms [Average]
  (min, avg, max) = (6.042, 6.132, 6.270), stdev = 0.121
  CI (99.9%): [3.919, 8.345] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 4.591 ops/ms
# Warmup Iteration   3: 5.493 ops/ms
Iteration   1: 5.563 ops/ms
Iteration   2: 5.568 ops/ms
Iteration   3: 5.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.563 ±(99.9%) 0.082 ops/ms [Average]
  (min, avg, max) = (5.559, 5.563, 5.568), stdev = 0.005
  CI (99.9%): [5.480, 5.645] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.634 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.012 ms/op
Iteration   1: 5.385 ±(99.9%) 0.010 ms/op
Iteration   2: 5.039 ±(99.9%) 0.009 ms/op
Iteration   3: 5.002 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.142 ±(99.9%) 3.861 ms/op [Average]
  (min, avg, max) = (5.002, 5.142, 5.385), stdev = 0.212
  CI (99.9%): [1.281, 9.003] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.081 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.302 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.710 ±(99.9%) 0.011 ms/op
Iteration   1: 4.762 ±(99.9%) 0.010 ms/op
Iteration   2: 4.866 ±(99.9%) 0.009 ms/op
Iteration   3: 4.768 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.799 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (4.762, 4.799, 4.866), stdev = 0.059
  CI (99.9%): [3.726, 5.871] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.093 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 6.412 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.343 ±(99.9%) 0.007 ms/op
Iteration   1: 5.124 ±(99.9%) 0.011 ms/op
Iteration   2: 5.042 ±(99.9%) 0.012 ms/op
Iteration   3: 5.070 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.078 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (5.042, 5.078, 5.124), stdev = 0.042
  CI (99.9%): [4.319, 5.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.435 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.690 ±(99.9%) 0.018 ms/op
Iteration   1: 5.665 ±(99.9%) 0.019 ms/op
Iteration   2: 5.693 ±(99.9%) 0.009 ms/op
Iteration   3: 5.998 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.785 ±(99.9%) 3.376 ms/op [Average]
  (min, avg, max) = (5.665, 5.785, 5.998), stdev = 0.185
  CI (99.9%): [2.409, 9.162] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.414 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.295 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.613 ±(99.9%) 0.028 ms/op
Iteration   1: 5.013 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   4.669 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   7.373 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  26.090 ms/op
                 createUser·p0.9999: 35.003 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 5.185 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.060 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.275 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   10.558 ms/op
                 createUser·p0.999:  29.950 ms/op
                 createUser·p0.9999: 32.801 ms/op
                 createUser·p1.00:   33.194 ms/op

Iteration   3: 5.043 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   5.972 ms/op
                 createUser·p0.95:   7.021 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  25.272 ms/op
                 createUser·p0.9999: 29.611 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188879
  mean =      5.079 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 119978 
    [ 5.000,  7.500) = 60651 
    [ 7.500, 10.000) = 6120 
    [10.000, 12.500) = 1335 
    [12.500, 15.000) = 370 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      6.152 ms/op
     p(95.0000) =      7.299 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     25.833 ms/op
     p(99.9900) =     33.136 ms/op
     p(99.9990) =     35.797 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.199 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.481 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.075 ±(99.9%) 0.018 ms/op
Iteration   1: 4.957 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.955 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  19.729 ms/op
                 existUser·p0.9999: 26.218 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 4.840 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   10.523 ms/op
                 existUser·p0.999:  23.368 ms/op
                 existUser·p0.9999: 27.117 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 4.803 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.062 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   5.620 ms/op
                 existUser·p0.95:   6.338 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  19.510 ms/op
                 existUser·p0.9999: 29.309 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197178
  mean =      4.866 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 150941 
    [ 5.000,  7.500) = 39808 
    [ 7.500, 10.000) = 4576 
    [10.000, 12.500) = 1096 
    [12.500, 15.000) = 380 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     22.309 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     30.281 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.022 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 5.910 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.190 ±(99.9%) 0.017 ms/op
Iteration   1: 5.427 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.971 ms/op
                 getUser·p0.95:   8.126 ms/op
                 getUser·p0.99:   12.698 ms/op
                 getUser·p0.999:  23.210 ms/op
                 getUser·p0.9999: 33.230 ms/op
                 getUser·p1.00:   33.292 ms/op

Iteration   2: 5.334 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.619 ms/op
                 getUser·p0.99:   11.043 ms/op
                 getUser·p0.999:  29.397 ms/op
                 getUser·p0.9999: 35.652 ms/op
                 getUser·p1.00:   39.125 ms/op

Iteration   3: 5.448 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  25.070 ms/op
                 getUser·p0.9999: 30.805 ms/op
                 getUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177518
  mean =      5.402 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 88787 
    [ 5.000,  7.500) = 76366 
    [ 7.500, 10.000) = 8725 
    [10.000, 12.500) = 2434 
    [12.500, 15.000) = 634 
    [15.000, 17.500) = 268 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     24.049 ms/op
     p(99.9900) =     34.259 ms/op
     p(99.9990) =     38.109 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.639 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 6.924 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.786 ±(99.9%) 0.023 ms/op
Iteration   1: 5.747 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.622 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  26.388 ms/op
                 listUser·p0.9999: 40.370 ms/op
                 listUser·p1.00:   40.632 ms/op

Iteration   2: 5.531 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.788 ms/op
                 listUser·p0.50:   5.235 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  25.564 ms/op
                 listUser·p0.9999: 27.867 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   3: 5.787 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.994 ms/op
                 listUser·p0.50:   5.513 ms/op
                 listUser·p0.90:   6.672 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  18.635 ms/op
                 listUser·p0.9999: 21.291 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 168854
  mean =      5.686 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 25710 
    [ 5.000, 10.000) = 140774 
    [10.000, 15.000) = 1868 
    [15.000, 20.000) = 253 
    [20.000, 25.000) = 101 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.520 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     24.454 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     40.542 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.315 ± 4.858  ops/ms
ClientPb.existUser                       thrpt       3   6.484 ± 3.277  ops/ms
ClientPb.getUser                         thrpt       3   6.132 ± 2.213  ops/ms
ClientPb.listUser                        thrpt       3   5.563 ± 0.082  ops/ms
ClientPb.createUser                       avgt       3   5.142 ± 3.861   ms/op
ClientPb.existUser                        avgt       3   4.799 ± 1.072   ms/op
ClientPb.getUser                          avgt       3   5.078 ± 0.760   ms/op
ClientPb.listUser                         avgt       3   5.785 ± 3.376   ms/op
ClientPb.createUser                     sample  188879   5.079 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.224           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.833           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.136           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  197178   4.866 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.062           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.814           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.309           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.591           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  177518   5.402 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.077           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.049           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.125           ms/op
ClientPb.listUser                       sample  168854   5.686 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.788           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.382           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.570           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.715           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.632           ms/op
