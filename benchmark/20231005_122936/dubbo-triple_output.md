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
# Warmup Iteration   1: 2.513 ops/ms
# Warmup Iteration   2: 6.005 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 9.973 ops/ms
Iteration   2: 9.931 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.878 ±(99.9%) 2.380 ops/ms [Average]
  (min, avg, max) = (9.729, 9.878, 9.973), stdev = 0.130
  CI (99.9%): [7.497, 12.258] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ops/ms
# Warmup Iteration   2: 9.107 ops/ms
# Warmup Iteration   3: 10.192 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.487 ops/ms
Iteration   3: 10.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.353 ±(99.9%) 2.208 ops/ms [Average]
  (min, avg, max) = (10.252, 10.353, 10.487), stdev = 0.121
  CI (99.9%): [8.144, 12.561] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 9.154 ops/ms
# Warmup Iteration   3: 9.630 ops/ms
Iteration   1: 9.958 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 9.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.933 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (9.883, 9.933, 9.958), stdev = 0.043
  CI (99.9%): [9.144, 10.722] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.369 ops/ms
# Warmup Iteration   2: 8.058 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.468 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.357 ±(99.9%) 2.259 ops/ms [Average]
  (min, avg, max) = (8.223, 8.357, 8.468), stdev = 0.124
  CI (99.9%): [6.098, 10.615] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.212 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.002 ms/op
Iteration   1: 3.289 ±(99.9%) 0.002 ms/op
Iteration   2: 3.207 ±(99.9%) 0.003 ms/op
Iteration   3: 3.198 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.231 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.198, 3.231, 3.289), stdev = 0.050
  CI (99.9%): [2.314, 4.149] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.108 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (3.054, 3.108, 3.210), stdev = 0.088
  CI (99.9%): [1.501, 4.715] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.002 ms/op
Iteration   1: 3.253 ±(99.9%) 0.003 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.298 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.194, 3.248, 3.298), stdev = 0.052
  CI (99.9%): [2.305, 4.191] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.432 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.006 ms/op
Iteration   1: 3.744 ±(99.9%) 0.004 ms/op
Iteration   2: 3.770 ±(99.9%) 0.006 ms/op
Iteration   3: 3.780 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.765 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (3.744, 3.765, 3.780), stdev = 0.019
  CI (99.9%): [3.424, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 7.823 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.008 ms/op
Iteration   1: 3.228 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  17.254 ms/op
                 createUser·p0.9999: 20.810 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  14.509 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296917
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21284 
    [ 2.500,  5.000) = 270660 
    [ 5.000,  7.500) = 3998 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 179 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     21.072 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.291 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
Iteration   1: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  13.287 ms/op
                 existUser·p0.9999: 18.677 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  14.408 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  10.580 ms/op
                 existUser·p0.9999: 21.389 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301045
  mean =      3.185 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15956 
    [ 2.500,  5.000) = 280777 
    [ 5.000,  7.500) = 3357 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     20.280 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 7.298 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
Iteration   1: 3.355 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  18.111 ms/op
                 getUser·p0.9999: 20.773 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  13.545 ms/op
                 getUser·p0.9999: 22.383 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  14.916 ms/op
                 getUser·p0.9999: 21.571 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292282
  mean =      3.283 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3981 
    [ 2.500,  5.000) = 281032 
    [ 5.000,  7.500) = 5883 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     16.436 ms/op
     p(99.9900) =     21.750 ms/op
     p(99.9990) =     23.631 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 8.794 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.010 ms/op
Iteration   1: 3.883 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 24.650 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 3.759 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 15.925 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   3: 3.778 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.097 ms/op
                 listUser·p0.999:  12.774 ms/op
                 listUser·p0.9999: 15.778 ms/op
                 listUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252314
  mean =      3.806 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 246047 
    [ 5.000,  7.500) = 5102 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     21.551 ms/op
     p(99.9990) =     25.875 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.878 ± 2.380  ops/ms
ClientPb.existUser                       thrpt       3  10.353 ± 2.208  ops/ms
ClientPb.getUser                         thrpt       3   9.933 ± 0.789  ops/ms
ClientPb.listUser                        thrpt       3   8.357 ± 2.259  ops/ms
ClientPb.createUser                       avgt       3   3.231 ± 0.917   ms/op
ClientPb.existUser                        avgt       3   3.108 ± 1.607   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.943   ms/op
ClientPb.listUser                         avgt       3   3.765 ± 0.341   ms/op
ClientPb.createUser                     sample  296917   3.231 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.861           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.551           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.220           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.447           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.168           ms/op
ClientPb.existUser                      sample  301045   3.185 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.995           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.280           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.839           ms/op
ClientPb.getUser                        sample  292282   3.283 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.829           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.584           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.750           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  252314   3.806 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.480           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.551           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.801           ms/op
