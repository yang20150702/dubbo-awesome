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
# Warmup Iteration   1: 2.632 ops/ms
# Warmup Iteration   2: 6.307 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.464 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.714 ±(99.9%) 3.951 ops/ms [Average]
  (min, avg, max) = (9.464, 9.714, 9.841), stdev = 0.217
  CI (99.9%): [5.764, 13.665] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 9.369 ops/ms
# Warmup Iteration   3: 10.300 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.495 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.345 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (10.226, 10.345, 10.495), stdev = 0.137
  CI (99.9%): [7.839, 12.851] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ops/ms
# Warmup Iteration   2: 9.274 ops/ms
# Warmup Iteration   3: 9.657 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 10.000 ops/ms
Iteration   3: 9.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.988 ±(99.9%) 0.359 ops/ms [Average]
  (min, avg, max) = (9.965, 9.988, 10.000), stdev = 0.020
  CI (99.9%): [9.628, 10.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 8.313 ops/ms
Iteration   2: 8.497 ops/ms
Iteration   3: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.430 ±(99.9%) 1.860 ops/ms [Average]
  (min, avg, max) = (8.313, 8.430, 8.497), stdev = 0.102
  CI (99.9%): [6.570, 10.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.514 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.004 ms/op
Iteration   1: 3.332 ±(99.9%) 0.006 ms/op
Iteration   2: 3.198 ±(99.9%) 0.004 ms/op
Iteration   3: 3.198 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.243 ±(99.9%) 1.405 ms/op [Average]
  (min, avg, max) = (3.198, 3.243, 3.332), stdev = 0.077
  CI (99.9%): [1.838, 4.648] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.236 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.005 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
Iteration   2: 3.062 ±(99.9%) 0.010 ms/op
Iteration   3: 3.134 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.086 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.062, 3.086, 3.134), stdev = 0.042
  CI (99.9%): [2.322, 3.850] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 6.873 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.002 ms/op
Iteration   1: 3.113 ±(99.9%) 0.006 ms/op
Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
Iteration   3: 3.265 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.187 ±(99.9%) 1.387 ms/op [Average]
  (min, avg, max) = (3.113, 3.187, 3.265), stdev = 0.076
  CI (99.9%): [1.800, 4.574] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.659 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.005 ms/op
Iteration   1: 3.748 ±(99.9%) 0.008 ms/op
Iteration   2: 3.769 ±(99.9%) 0.007 ms/op
Iteration   3: 3.717 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.717, 3.745, 3.769), stdev = 0.026
  CI (99.9%): [3.269, 4.220] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.630 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.321 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  18.794 ms/op
                 createUser·p0.9999: 22.207 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.966 ms/op
                 createUser·p0.9999: 22.261 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  15.934 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292396
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16661 
    [ 2.500,  5.000) = 269780 
    [ 5.000,  7.500) = 5131 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     17.112 ms/op
     p(99.9900) =     22.373 ms/op
     p(99.9990) =     23.247 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.634 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.164 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.829 ms/op
                 existUser·p0.9999: 20.972 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.205 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  16.060 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.140 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 22.697 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302620
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21817 
    [ 2.500,  5.000) = 274067 
    [ 5.000,  7.500) = 5775 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     14.752 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.753 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.707 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.008 ms/op
Iteration   1: 3.325 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 3.248 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.255 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.761 ms/op
                 getUser·p0.9999: 26.252 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 23.042 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293655
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12087 
    [ 2.500,  5.000) = 273266 
    [ 5.000,  7.500) = 7238 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     16.685 ms/op
     p(99.9900) =     26.301 ms/op
     p(99.9990) =     28.674 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.599 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 3.752 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.820 ms/op
                 listUser·p0.999:  13.152 ms/op
                 listUser·p0.9999: 16.138 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.759 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.316 ms/op
                 listUser·p0.9999: 13.763 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254331
  mean =      3.772 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 246853 
    [ 5.000,  7.500) = 5523 
    [ 7.500, 10.000) = 1110 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     20.630 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.714 ± 3.951  ops/ms
ClientPb.existUser                       thrpt       3  10.345 ± 2.506  ops/ms
ClientPb.getUser                         thrpt       3   9.988 ± 0.359  ops/ms
ClientPb.listUser                        thrpt       3   8.430 ± 1.860  ops/ms
ClientPb.createUser                       avgt       3   3.243 ± 1.405   ms/op
ClientPb.existUser                        avgt       3   3.086 ± 0.764   ms/op
ClientPb.getUser                          avgt       3   3.187 ± 1.387   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 0.475   ms/op
ClientPb.createUser                     sample  292396   3.284 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.151           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.112           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.373           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.691           ms/op
ClientPb.existUser                      sample  302620   3.169 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.752           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.348           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.084           ms/op
ClientPb.getUser                        sample  293655   3.268 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.685           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.301           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.393           ms/op
ClientPb.listUser                       sample  254331   3.772 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.630           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.840           ms/op
