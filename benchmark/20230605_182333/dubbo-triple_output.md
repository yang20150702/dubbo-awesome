# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.158 ops/ms
# Warmup Iteration   2: 2.777 ops/ms
# Warmup Iteration   3: 5.454 ops/ms
Iteration   1: 5.598 ops/ms
Iteration   2: 6.007 ops/ms
Iteration   3: 6.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.871 ±(99.9%) 4.307 ops/ms [Average]
  (min, avg, max) = (5.598, 5.871, 6.007), stdev = 0.236
  CI (99.9%): [1.563, 10.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.795 ops/ms
# Warmup Iteration   2: 4.658 ops/ms
# Warmup Iteration   3: 6.118 ops/ms
Iteration   1: 6.202 ops/ms
Iteration   2: 6.228 ops/ms
Iteration   3: 6.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.243 ±(99.9%) 0.911 ops/ms [Average]
  (min, avg, max) = (6.202, 6.243, 6.299), stdev = 0.050
  CI (99.9%): [5.332, 7.154] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.563 ops/ms
# Warmup Iteration   2: 4.695 ops/ms
# Warmup Iteration   3: 5.892 ops/ms
Iteration   1: 6.090 ops/ms
Iteration   2: 6.040 ops/ms
Iteration   3: 5.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.019 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (5.927, 6.019, 6.090), stdev = 0.083
  CI (99.9%): [4.501, 7.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.525 ops/ms
# Warmup Iteration   2: 4.306 ops/ms
# Warmup Iteration   3: 5.096 ops/ms
Iteration   1: 4.950 ops/ms
Iteration   2: 5.159 ops/ms
Iteration   3: 5.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.092 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (4.950, 5.092, 5.168), stdev = 0.124
  CI (99.9%): [2.838, 7.347] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.366 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 7.022 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.739 ±(99.9%) 0.010 ms/op
Iteration   1: 5.314 ±(99.9%) 0.013 ms/op
Iteration   2: 5.411 ±(99.9%) 0.019 ms/op
Iteration   3: 5.346 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.357 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (5.314, 5.357, 5.411), stdev = 0.049
  CI (99.9%): [4.461, 6.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.480 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.984 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.305 ±(99.9%) 0.010 ms/op
Iteration   1: 4.992 ±(99.9%) 0.012 ms/op
Iteration   2: 5.109 ±(99.9%) 0.010 ms/op
Iteration   3: 5.138 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.080 ±(99.9%) 1.409 ms/op [Average]
  (min, avg, max) = (4.992, 5.080, 5.138), stdev = 0.077
  CI (99.9%): [3.671, 6.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.502 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.389 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.013 ms/op
Iteration   1: 5.865 ±(99.9%) 0.011 ms/op
Iteration   2: 5.455 ±(99.9%) 0.011 ms/op
Iteration   3: 5.568 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.629 ±(99.9%) 3.871 ms/op [Average]
  (min, avg, max) = (5.455, 5.629, 5.865), stdev = 0.212
  CI (99.9%): [1.758, 9.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.158 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.451 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.206 ±(99.9%) 0.015 ms/op
Iteration   1: 6.373 ±(99.9%) 0.012 ms/op
Iteration   2: 6.195 ±(99.9%) 0.018 ms/op
Iteration   3: 6.078 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.215 ±(99.9%) 2.705 ms/op [Average]
  (min, avg, max) = (6.078, 6.215, 6.373), stdev = 0.148
  CI (99.9%): [3.511, 8.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.365 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.749 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.651 ±(99.9%) 0.027 ms/op
Iteration   1: 5.500 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   7.160 ms/op
                 createUser·p0.95:   8.167 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  24.276 ms/op
                 createUser·p0.9999: 29.968 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   2: 5.268 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.217 ms/op
                 createUser·p0.99:   9.748 ms/op
                 createUser·p0.999:  23.404 ms/op
                 createUser·p0.9999: 28.203 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 5.351 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.545 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  31.268 ms/op
                 createUser·p0.9999: 39.518 ms/op
                 createUser·p1.00:   46.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178677
  mean =      5.371 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 83972 
    [ 5.000, 10.000) = 92441 
    [10.000, 15.000) = 1916 
    [15.000, 20.000) = 122 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 100 
    [30.000, 35.000) = 53 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     25.153 ms/op
     p(99.9900) =     37.037 ms/op
     p(99.9990) =     46.282 ms/op
     p(99.9999) =     46.334 ms/op
    p(100.0000) =     46.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.791 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.083 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.131 ±(99.9%) 0.018 ms/op
Iteration   1: 5.198 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.521 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  23.298 ms/op
                 existUser·p0.9999: 25.703 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 5.142 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.274 ms/op
                 existUser·p0.99:   9.634 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 31.712 ms/op
                 existUser·p1.00:   33.882 ms/op

Iteration   3: 5.062 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   9.519 ms/op
                 existUser·p0.999:  14.560 ms/op
                 existUser·p0.9999: 32.320 ms/op
                 existUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186907
  mean =      5.133 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 105856 
    [ 5.000,  7.500) = 72991 
    [ 7.500, 10.000) = 6302 
    [10.000, 12.500) = 1131 
    [12.500, 15.000) = 326 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =      9.798 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     31.140 ms/op
     p(99.9990) =     34.963 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.622 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.419 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.022 ms/op
Iteration   1: 5.385 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  24.609 ms/op
                 getUser·p0.9999: 31.953 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   2: 5.407 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.056 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   7.668 ms/op
                 getUser·p0.99:   10.846 ms/op
                 getUser·p0.999:  23.233 ms/op
                 getUser·p0.9999: 28.154 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 5.588 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.499 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   7.946 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  26.008 ms/op
                 getUser·p0.9999: 28.945 ms/op
                 getUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175811
  mean =      5.459 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 76240 
    [ 5.000,  7.500) = 88982 
    [ 7.500, 10.000) = 7792 
    [10.000, 12.500) = 1820 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.877 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     30.160 ms/op
     p(99.9990) =     32.088 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.542 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 8.125 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.267 ±(99.9%) 0.028 ms/op
Iteration   1: 5.908 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   5.530 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.875 ms/op
                 listUser·p0.999:  27.816 ms/op
                 listUser·p0.9999: 30.644 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   2: 6.185 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.759 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.861 ms/op
                 listUser·p0.999:  29.608 ms/op
                 listUser·p0.9999: 32.068 ms/op
                 listUser·p1.00:   35.258 ms/op

Iteration   3: 6.023 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   5.734 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  22.867 ms/op
                 listUser·p0.9999: 29.332 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158911
  mean =      6.036 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 24213 
    [ 5.000,  7.500) = 120246 
    [ 7.500, 10.000) = 10904 
    [10.000, 12.500) = 2323 
    [12.500, 15.000) = 603 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.876 ms/op
     p(99.9000) =     27.397 ms/op
     p(99.9900) =     31.625 ms/op
     p(99.9990) =     35.285 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.871 ± 4.307  ops/ms
ClientPb.existUser                       thrpt       3   6.243 ± 0.911  ops/ms
ClientPb.getUser                         thrpt       3   6.019 ± 1.518  ops/ms
ClientPb.listUser                        thrpt       3   5.092 ± 2.254  ops/ms
ClientPb.createUser                       avgt       3   5.357 ± 0.896   ms/op
ClientPb.existUser                        avgt       3   5.080 ± 1.409   ms/op
ClientPb.getUser                          avgt       3   5.629 ± 3.871   ms/op
ClientPb.listUser                         avgt       3   6.215 ± 2.705   ms/op
ClientPb.createUser                     sample  178677   5.371 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.676           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.037           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.334           ms/op
ClientPb.existUser                      sample  186907   5.133 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.407           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.798           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.186           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  175811   5.459 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.056           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.877           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.160           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.113           ms/op
ClientPb.listUser                       sample  158911   6.036 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.064           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.876           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.397           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.625           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.324           ms/op
