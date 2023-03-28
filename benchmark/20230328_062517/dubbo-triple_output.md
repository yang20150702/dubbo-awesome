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
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 6.200 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.748 ops/ms
Iteration   2: 9.360 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.791 ±(99.9%) 8.285 ops/ms [Average]
  (min, avg, max) = (9.360, 9.791, 10.265), stdev = 0.454
  CI (99.9%): [1.506, 18.076] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.592 ops/ms
# Warmup Iteration   2: 9.348 ops/ms
# Warmup Iteration   3: 10.028 ops/ms
Iteration   1: 10.090 ops/ms
Iteration   2: 10.220 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.288 ±(99.9%) 4.370 ops/ms [Average]
  (min, avg, max) = (10.090, 10.288, 10.554), stdev = 0.240
  CI (99.9%): [5.918, 14.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 9.061 ops/ms
# Warmup Iteration   3: 9.472 ops/ms
Iteration   1: 9.667 ops/ms
Iteration   2: 10.350 ops/ms
Iteration   3: 9.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.870 ±(99.9%) 7.613 ops/ms [Average]
  (min, avg, max) = (9.593, 9.870, 10.350), stdev = 0.417
  CI (99.9%): [2.256, 17.483] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.547 ops/ms
Iteration   2: 8.463 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.524 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (8.463, 8.524, 8.561), stdev = 0.053
  CI (99.9%): [7.561, 9.487] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.968 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.007 ms/op
Iteration   1: 3.134 ±(99.9%) 0.003 ms/op
Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
Iteration   3: 3.170 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.134, 3.153, 3.170), stdev = 0.018
  CI (99.9%): [2.822, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 6.855 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.004 ms/op
Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
Iteration   3: 3.164 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.091 ±(99.9%) 1.426 ms/op [Average]
  (min, avg, max) = (3.008, 3.091, 3.164), stdev = 0.078
  CI (99.9%): [1.665, 4.518] (assumes normal distribution)


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
# Warmup Iteration   1: 8.180 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.003 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.386 ±(99.9%) 0.006 ms/op
Iteration   3: 3.267 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.282 ±(99.9%) 1.788 ms/op [Average]
  (min, avg, max) = (3.192, 3.282, 3.386), stdev = 0.098
  CI (99.9%): [1.494, 5.070] (assumes normal distribution)


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
# Warmup Iteration   1: 9.397 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.004 ms/op
Iteration   1: 3.892 ±(99.9%) 0.008 ms/op
Iteration   2: 3.804 ±(99.9%) 0.009 ms/op
Iteration   3: 3.874 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.857 ±(99.9%) 0.851 ms/op [Average]
  (min, avg, max) = (3.804, 3.857, 3.892), stdev = 0.047
  CI (99.9%): [3.006, 4.708] (assumes normal distribution)


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
# Warmup Iteration   1: 8.711 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.473 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 27.293 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   2: 3.300 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.387 ms/op
                 createUser·p0.999:  16.422 ms/op
                 createUser·p0.9999: 24.881 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  15.270 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298879
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22309 
    [ 2.500,  5.000) = 271847 
    [ 5.000,  7.500) = 3970 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     28.673 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 8.230 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.274 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  10.755 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.676 ms/op
                 existUser·p0.9999: 19.904 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.267 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 24.321 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302859
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15834 
    [ 2.500,  5.000) = 280373 
    [ 5.000,  7.500) = 5976 
    [ 7.500, 10.000) = 379 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.267 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.669 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     24.671 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 8.376 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
Iteration   1: 3.181 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 27.554 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  14.296 ms/op
                 getUser·p0.9999: 23.327 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   3: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  17.249 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302943
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9280 
    [ 2.500,  5.000) = 287535 
    [ 5.000,  7.500) = 4935 
    [ 7.500, 10.000) = 760 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.910 ms/op
     p(99.9990) =     28.212 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 9.181 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.011 ms/op
Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.960 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.723 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 20.208 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.723 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253989
  mean =      3.779 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 243911 
    [ 5.000,  7.500) = 7547 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     14.353 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     22.917 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.791 ± 8.285  ops/ms
ClientPb.existUser                       thrpt       3  10.288 ± 4.370  ops/ms
ClientPb.getUser                         thrpt       3   9.870 ± 7.613  ops/ms
ClientPb.listUser                        thrpt       3   8.524 ± 0.963  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 0.331   ms/op
ClientPb.existUser                        avgt       3   3.091 ± 1.426   ms/op
ClientPb.getUser                          avgt       3   3.282 ± 1.788   ms/op
ClientPb.listUser                         avgt       3   3.857 ± 0.851   ms/op
ClientPb.createUser                     sample  298879   3.210 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.543           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.231           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  302859   3.166 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.267           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.644           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.669           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.151           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.740           ms/op
ClientPb.getUser                        sample  302943   3.167 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.817           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.869           ms/op
ClientPb.listUser                       sample  253989   3.779 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.503           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.641           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.955           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.036           ms/op
