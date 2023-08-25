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
# Warmup Iteration   1: 1.431 ops/ms
# Warmup Iteration   2: 2.854 ops/ms
# Warmup Iteration   3: 6.113 ops/ms
Iteration   1: 6.759 ops/ms
Iteration   2: 6.634 ops/ms
Iteration   3: 7.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.928 ±(99.9%) 7.417 ops/ms [Average]
  (min, avg, max) = (6.634, 6.928, 7.392), stdev = 0.407
  CI (99.9%): [≈ 0, 14.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.864 ops/ms
# Warmup Iteration   2: 5.734 ops/ms
# Warmup Iteration   3: 7.106 ops/ms
Iteration   1: 7.223 ops/ms
Iteration   2: 7.414 ops/ms
Iteration   3: 7.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.408 ±(99.9%) 3.326 ops/ms [Average]
  (min, avg, max) = (7.223, 7.408, 7.588), stdev = 0.182
  CI (99.9%): [4.082, 10.735] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 7.055 ops/ms
Iteration   1: 7.318 ops/ms
Iteration   2: 7.341 ops/ms
Iteration   3: 7.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.398 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (7.318, 7.398, 7.535), stdev = 0.119
  CI (99.9%): [5.221, 9.575] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.051 ops/ms
# Warmup Iteration   2: 5.013 ops/ms
# Warmup Iteration   3: 5.903 ops/ms
Iteration   1: 6.016 ops/ms
Iteration   2: 6.113 ops/ms
Iteration   3: 6.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.087 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (6.016, 6.087, 6.133), stdev = 0.062
  CI (99.9%): [4.949, 7.226] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.583 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.318 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.006 ms/op
Iteration   1: 4.453 ±(99.9%) 0.005 ms/op
Iteration   2: 4.189 ±(99.9%) 0.008 ms/op
Iteration   3: 4.183 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.275 ±(99.9%) 2.814 ms/op [Average]
  (min, avg, max) = (4.183, 4.275, 4.453), stdev = 0.154
  CI (99.9%): [1.461, 7.089] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.067 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.003 ms/op
Iteration   1: 4.146 ±(99.9%) 0.007 ms/op
Iteration   2: 4.318 ±(99.9%) 0.009 ms/op
Iteration   3: 4.204 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.223 ±(99.9%) 1.597 ms/op [Average]
  (min, avg, max) = (4.146, 4.223, 4.318), stdev = 0.088
  CI (99.9%): [2.626, 5.820] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.162 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.438 ±(99.9%) 0.006 ms/op
Iteration   1: 4.576 ±(99.9%) 0.006 ms/op
Iteration   2: 4.201 ±(99.9%) 0.004 ms/op
Iteration   3: 4.231 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.336 ±(99.9%) 3.803 ms/op [Average]
  (min, avg, max) = (4.201, 4.336, 4.576), stdev = 0.208
  CI (99.9%): [0.534, 8.139] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.164 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.044 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.015 ms/op
Iteration   1: 5.571 ±(99.9%) 0.010 ms/op
Iteration   2: 4.779 ±(99.9%) 0.012 ms/op
Iteration   3: 4.704 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.018 ±(99.9%) 8.769 ms/op [Average]
  (min, avg, max) = (4.704, 5.018, 5.571), stdev = 0.481
  CI (99.9%): [≈ 0, 13.787] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.955 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.445 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.021 ms/op
Iteration   1: 4.448 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.274 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 26.011 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 4.529 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.849 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  26.355 ms/op
                 createUser·p0.9999: 29.358 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   3: 4.468 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.399 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  22.105 ms/op
                 createUser·p0.9999: 38.470 ms/op
                 createUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 214399
  mean =      4.481 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 178942 
    [ 5.000, 10.000) = 34283 
    [10.000, 15.000) = 844 
    [15.000, 20.000) = 72 
    [20.000, 25.000) = 72 
    [25.000, 30.000) = 141 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     23.678 ms/op
     p(99.9900) =     37.945 ms/op
     p(99.9990) =     39.340 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.968 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.379 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.383 ±(99.9%) 0.016 ms/op
Iteration   1: 4.182 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   4.112 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   7.299 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 25.374 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 4.601 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   10.705 ms/op
                 existUser·p0.999:  23.407 ms/op
                 existUser·p0.9999: 26.913 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   3: 4.210 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  20.177 ms/op
                 existUser·p0.9999: 28.488 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 222172
  mean =      4.323 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 173 
    [ 2.500,  5.000) = 199222 
    [ 5.000,  7.500) = 17594 
    [ 7.500, 10.000) = 3522 
    [10.000, 12.500) = 1028 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     27.420 ms/op
     p(99.9990) =     29.200 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.432 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.015 ms/op
Iteration   1: 4.425 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   4.162 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.980 ms/op
                 getUser·p0.99:   8.983 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.454 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   9.503 ms/op
                 getUser·p0.999:  17.793 ms/op
                 getUser·p0.9999: 33.456 ms/op
                 getUser·p1.00:   34.669 ms/op

Iteration   3: 4.405 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   6.226 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  15.455 ms/op
                 getUser·p0.9999: 33.251 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 214643
  mean =      4.471 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 180722 
    [ 5.000,  7.500) = 28660 
    [ 7.500, 10.000) = 3868 
    [10.000, 12.500) = 857 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      6.406 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     18.073 ms/op
     p(99.9900) =     33.244 ms/op
     p(99.9990) =     33.938 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 17.740 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 6.638 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.399 ±(99.9%) 0.022 ms/op
Iteration   1: 5.418 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   6.578 ms/op
                 listUser·p0.95:   7.773 ms/op
                 listUser·p0.99:   10.911 ms/op
                 listUser·p0.999:  27.722 ms/op
                 listUser·p0.9999: 31.474 ms/op
                 listUser·p1.00:   32.113 ms/op

Iteration   2: 5.069 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.780 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  23.026 ms/op
                 listUser·p0.9999: 28.304 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   3: 5.169 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 25.574 ms/op
                 listUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 183952
  mean =      5.215 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 113322 
    [ 5.000,  7.500) = 61740 
    [ 7.500, 10.000) = 6411 
    [10.000, 12.500) = 1537 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.408 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     30.907 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.928 ± 7.417  ops/ms
ClientPb.existUser                       thrpt       3   7.408 ± 3.326  ops/ms
ClientPb.getUser                         thrpt       3   7.398 ± 2.177  ops/ms
ClientPb.listUser                        thrpt       3   6.087 ± 1.139  ops/ms
ClientPb.createUser                       avgt       3   4.275 ± 2.814   ms/op
ClientPb.existUser                        avgt       3   4.223 ± 1.597   ms/op
ClientPb.getUser                          avgt       3   4.336 ± 3.803   ms/op
ClientPb.listUser                         avgt       3   5.018 ± 8.769   ms/op
ClientPb.createUser                     sample  214399   4.481 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.827           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.357           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.782           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.678           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.945           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.042           ms/op
ClientPb.existUser                      sample  222172   4.323 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.477           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.503           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.021           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.420           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  214643   4.471 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.126           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  183952   5.215 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.408           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.682           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.510           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.907           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.113           ms/op
