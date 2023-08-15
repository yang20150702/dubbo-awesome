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
# Warmup Iteration   1: 1.965 ops/ms
# Warmup Iteration   2: 4.937 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.731 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.087 ±(99.9%) 5.791 ops/ms [Average]
  (min, avg, max) = (8.731, 9.087, 9.340), stdev = 0.317
  CI (99.9%): [3.296, 14.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 8.168 ops/ms
# Warmup Iteration   3: 9.310 ops/ms
Iteration   1: 9.433 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.493 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (9.433, 9.493, 9.549), stdev = 0.058
  CI (99.9%): [8.427, 10.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 8.421 ops/ms
# Warmup Iteration   3: 8.844 ops/ms
Iteration   1: 9.393 ops/ms
Iteration   2: 9.350 ops/ms
Iteration   3: 8.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 3.999 ops/ms [Average]
  (min, avg, max) = (8.994, 9.245, 9.393), stdev = 0.219
  CI (99.9%): [5.247, 13.244] (assumes normal distribution)


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
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 7.191 ops/ms
# Warmup Iteration   3: 7.752 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 7.984 ops/ms
Iteration   3: 8.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.990 ±(99.9%) 0.161 ops/ms [Average]
  (min, avg, max) = (7.984, 7.990, 8.000), stdev = 0.009
  CI (99.9%): [7.829, 8.151] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.186 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.004 ms/op
Iteration   1: 3.409 ±(99.9%) 0.010 ms/op
Iteration   2: 3.689 ±(99.9%) 0.004 ms/op
Iteration   3: 3.575 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.558 ±(99.9%) 2.563 ms/op [Average]
  (min, avg, max) = (3.409, 3.558, 3.689), stdev = 0.140
  CI (99.9%): [0.994, 6.121] (assumes normal distribution)


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
# Warmup Iteration   1: 9.850 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.005 ms/op
Iteration   1: 3.334 ±(99.9%) 0.004 ms/op
Iteration   2: 3.305 ±(99.9%) 0.002 ms/op
Iteration   3: 3.360 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (3.305, 3.333, 3.360), stdev = 0.027
  CI (99.9%): [2.835, 3.832] (assumes normal distribution)


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
# Warmup Iteration   1: 8.887 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.420 ±(99.9%) 0.004 ms/op
Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
Iteration   3: 3.339 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.397 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.339, 3.397, 3.433), stdev = 0.051
  CI (99.9%): [2.472, 4.323] (assumes normal distribution)


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
# Warmup Iteration   1: 11.395 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.008 ms/op
Iteration   1: 4.155 ±(99.9%) 0.004 ms/op
Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
Iteration   3: 4.019 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.060 ±(99.9%) 1.510 ms/op [Average]
  (min, avg, max) = (4.005, 4.060, 4.155), stdev = 0.083
  CI (99.9%): [2.549, 5.570] (assumes normal distribution)


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
# Warmup Iteration   1: 9.608 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.652 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 25.110 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 3.448 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  20.249 ms/op
                 createUser·p0.9999: 26.187 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  20.044 ms/op
                 createUser·p0.9999: 26.067 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280569
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10387 
    [ 2.500,  5.000) = 263224 
    [ 5.000,  7.500) = 5204 
    [ 7.500, 10.000) = 1200 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.474 ms/op
     p(99.9000) =     18.888 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     26.778 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 9.803 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.607 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  13.368 ms/op
                 existUser·p0.9999: 24.259 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   3: 3.305 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  13.251 ms/op
                 existUser·p0.9999: 39.779 ms/op
                 existUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289054
  mean =      3.319 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 282521 
    [ 5.000, 10.000) = 6074 
    [10.000, 15.000) = 203 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 169 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     37.667 ms/op
     p(99.9990) =     40.967 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


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
# Warmup Iteration   1: 9.042 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.013 ms/op
Iteration   1: 3.573 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   5.423 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  14.254 ms/op
                 getUser·p0.9999: 22.236 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.512 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  21.494 ms/op
                 getUser·p0.9999: 25.130 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  18.242 ms/op
                 getUser·p0.9999: 26.673 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271927
  mean =      3.528 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5224 
    [ 2.500,  5.000) = 255650 
    [ 5.000,  7.500) = 8895 
    [ 7.500, 10.000) = 1559 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.076 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 12.162 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.016 ms/op
Iteration   1: 4.170 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.040 ms/op
                 listUser·p0.999:  20.372 ms/op
                 listUser·p0.9999: 31.021 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  14.040 ms/op
                 listUser·p0.9999: 16.351 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   3: 4.045 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  14.353 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236699
  mean =      4.051 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 226251 
    [ 5.000,  7.500) = 7531 
    [ 7.500, 10.000) = 1976 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     29.546 ms/op
     p(99.9990) =     31.804 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.087 ± 5.791  ops/ms
ClientPb.existUser                       thrpt       3   9.493 ± 1.066  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 3.999  ops/ms
ClientPb.listUser                        thrpt       3   7.990 ± 0.161  ops/ms
ClientPb.createUser                       avgt       3   3.558 ± 2.563   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 0.499   ms/op
ClientPb.getUser                          avgt       3   3.397 ± 0.925   ms/op
ClientPb.listUser                         avgt       3   4.060 ± 1.510   ms/op
ClientPb.createUser                     sample  280569   3.419 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.474           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.888           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.919           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  289054   3.319 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.144           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.667           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.091           ms/op
ClientPb.getUser                        sample  271927   3.528 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.165           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.102           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.329           ms/op
ClientPb.listUser                       sample  236699   4.051 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.589           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.546           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
