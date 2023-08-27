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
# Warmup Iteration   1: 1.918 ops/ms
# Warmup Iteration   2: 5.631 ops/ms
# Warmup Iteration   3: 8.754 ops/ms
Iteration   1: 9.165 ops/ms
Iteration   2: 9.073 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.232 ±(99.9%) 3.676 ops/ms [Average]
  (min, avg, max) = (9.073, 9.232, 9.459), stdev = 0.202
  CI (99.9%): [5.556, 12.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.794 ops/ms
# Warmup Iteration   2: 8.379 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 8.808 ops/ms
Iteration   3: 9.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.073 ±(99.9%) 4.255 ops/ms [Average]
  (min, avg, max) = (8.808, 9.073, 9.248), stdev = 0.233
  CI (99.9%): [4.818, 13.328] (assumes normal distribution)


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
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 7.788 ops/ms
# Warmup Iteration   3: 8.596 ops/ms
Iteration   1: 8.569 ops/ms
Iteration   2: 8.984 ops/ms
Iteration   3: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.849 ±(99.9%) 4.427 ops/ms [Average]
  (min, avg, max) = (8.569, 8.849, 8.995), stdev = 0.243
  CI (99.9%): [4.422, 13.276] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.586 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.247 ops/ms
Iteration   1: 7.418 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 7.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.721 ±(99.9%) 5.250 ops/ms [Average]
  (min, avg, max) = (7.418, 7.721, 7.990), stdev = 0.288
  CI (99.9%): [2.471, 12.970] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.090 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.654 ±(99.9%) 0.003 ms/op
Iteration   1: 3.614 ±(99.9%) 0.003 ms/op
Iteration   2: 3.457 ±(99.9%) 0.005 ms/op
Iteration   3: 3.623 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.565 ±(99.9%) 1.709 ms/op [Average]
  (min, avg, max) = (3.457, 3.565, 3.623), stdev = 0.094
  CI (99.9%): [1.855, 5.274] (assumes normal distribution)


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
# Warmup Iteration   1: 9.636 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.003 ms/op
Iteration   1: 3.294 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.003 ms/op
Iteration   3: 3.269 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.203, 3.256, 3.294), stdev = 0.047
  CI (99.9%): [2.398, 4.113] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.599 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.006 ms/op
Iteration   1: 3.523 ±(99.9%) 0.008 ms/op
Iteration   2: 3.523 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.404, 3.483, 3.523), stdev = 0.069
  CI (99.9%): [2.233, 4.734] (assumes normal distribution)


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
# Warmup Iteration   1: 11.304 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.718 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.007 ms/op
Iteration   1: 4.199 ±(99.9%) 0.007 ms/op
Iteration   2: 4.010 ±(99.9%) 0.009 ms/op
Iteration   3: 3.876 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.028 ±(99.9%) 2.961 ms/op [Average]
  (min, avg, max) = (3.876, 4.028, 4.199), stdev = 0.162
  CI (99.9%): [1.067, 6.989] (assumes normal distribution)


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
# Warmup Iteration   1: 10.071 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.743 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.946 ms/op
                 createUser·p0.999:  21.374 ms/op
                 createUser·p0.9999: 25.050 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.537 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  23.691 ms/op
                 createUser·p0.9999: 33.814 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   3: 3.644 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  25.076 ms/op
                 createUser·p0.9999: 31.021 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263711
  mean =      3.639 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7900 
    [ 2.500,  5.000) = 240062 
    [ 5.000,  7.500) = 13328 
    [ 7.500, 10.000) = 1616 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     22.619 ms/op
     p(99.9900) =     32.580 ms/op
     p(99.9990) =     36.331 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 9.606 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.012 ms/op
Iteration   1: 3.593 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  20.089 ms/op
                 existUser·p0.9999: 23.891 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.290 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  14.552 ms/op
                 existUser·p0.9999: 25.926 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.318 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.213 ms/op
                 existUser·p0.999:  19.098 ms/op
                 existUser·p0.9999: 27.996 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279314
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10184 
    [ 2.500,  5.000) = 261008 
    [ 5.000,  7.500) = 6722 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     27.202 ms/op
     p(99.9990) =     28.260 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 10.997 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.016 ms/op
Iteration   1: 3.647 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  20.884 ms/op
                 getUser·p0.9999: 24.420 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  11.780 ms/op
                 getUser·p0.9999: 26.261 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.589 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  27.983 ms/op
                 getUser·p0.9999: 31.067 ms/op
                 getUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264569
  mean =      3.626 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3304 
    [ 2.500,  5.000) = 251294 
    [ 5.000,  7.500) = 7909 
    [ 7.500, 10.000) = 1459 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     30.001 ms/op
     p(99.9990) =     31.326 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 11.619 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.803 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.428 ±(99.9%) 0.017 ms/op
Iteration   1: 4.311 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   4.166 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  21.840 ms/op
                 listUser·p0.9999: 32.609 ms/op
                 listUser·p1.00:   35.586 ms/op

Iteration   2: 4.215 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   4.108 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.723 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  16.732 ms/op
                 listUser·p0.9999: 19.609 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 4.183 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  21.155 ms/op
                 listUser·p0.9999: 24.218 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226532
  mean =      4.236 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 141 
    [ 2.500,  5.000) = 209307 
    [ 5.000,  7.500) = 13627 
    [ 7.500, 10.000) = 2376 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.804 ms/op
     p(50.0000) =      4.108 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     18.890 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     33.341 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.232 ± 3.676  ops/ms
ClientPb.existUser                       thrpt       3   9.073 ± 4.255  ops/ms
ClientPb.getUser                         thrpt       3   8.849 ± 4.427  ops/ms
ClientPb.listUser                        thrpt       3   7.721 ± 5.250  ops/ms
ClientPb.createUser                       avgt       3   3.565 ± 1.709   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 0.858   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 1.251   ms/op
ClientPb.listUser                         avgt       3   4.028 ± 2.961   ms/op
ClientPb.createUser                     sample  263711   3.639 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.227           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.619           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.580           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  279314   3.434 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.268           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.481           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.795           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.202           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  264569   3.626 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.511           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.189           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.001           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.425           ms/op
ClientPb.listUser                       sample  226532   4.236 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.159           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.890           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.586           ms/op
