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
# Warmup Iteration   1: 1.074 ops/ms
# Warmup Iteration   2: 2.409 ops/ms
# Warmup Iteration   3: 5.352 ops/ms
Iteration   1: 5.712 ops/ms
Iteration   2: 5.992 ops/ms
Iteration   3: 6.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.935 ±(99.9%) 3.666 ops/ms [Average]
  (min, avg, max) = (5.712, 5.935, 6.102), stdev = 0.201
  CI (99.9%): [2.270, 9.601] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.652 ops/ms
# Warmup Iteration   2: 4.677 ops/ms
# Warmup Iteration   3: 5.972 ops/ms
Iteration   1: 6.459 ops/ms
Iteration   2: 6.215 ops/ms
Iteration   3: 6.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.270 ±(99.9%) 3.057 ops/ms [Average]
  (min, avg, max) = (6.138, 6.270, 6.459), stdev = 0.168
  CI (99.9%): [3.213, 9.328] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.711 ops/ms
# Warmup Iteration   2: 5.006 ops/ms
# Warmup Iteration   3: 5.630 ops/ms
Iteration   1: 5.649 ops/ms
Iteration   2: 5.969 ops/ms
Iteration   3: 5.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.850 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (5.649, 5.850, 5.969), stdev = 0.175
  CI (99.9%): [2.662, 9.039] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.642 ops/ms
# Warmup Iteration   2: 4.224 ops/ms
# Warmup Iteration   3: 5.029 ops/ms
Iteration   1: 5.064 ops/ms
Iteration   2: 5.179 ops/ms
Iteration   3: 5.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.096 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (5.045, 5.096, 5.179), stdev = 0.072
  CI (99.9%): [3.779, 6.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.669 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.868 ±(99.9%) 0.009 ms/op
Iteration   1: 5.383 ±(99.9%) 0.012 ms/op
Iteration   2: 5.442 ±(99.9%) 0.010 ms/op
Iteration   3: 5.322 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.383 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (5.322, 5.383, 5.442), stdev = 0.060
  CI (99.9%): [4.287, 6.478] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.132 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.987 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.219 ±(99.9%) 0.008 ms/op
Iteration   1: 5.170 ±(99.9%) 0.007 ms/op
Iteration   2: 4.997 ±(99.9%) 0.021 ms/op
Iteration   3: 5.386 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.185 ±(99.9%) 3.557 ms/op [Average]
  (min, avg, max) = (4.997, 5.185, 5.386), stdev = 0.195
  CI (99.9%): [1.628, 8.741] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.105 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.909 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.006 ms/op
Iteration   1: 5.381 ±(99.9%) 0.013 ms/op
Iteration   2: 5.210 ±(99.9%) 0.011 ms/op
Iteration   3: 5.187 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.260 ±(99.9%) 1.930 ms/op [Average]
  (min, avg, max) = (5.187, 5.260, 5.381), stdev = 0.106
  CI (99.9%): [3.329, 7.190] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.482 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.992 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.371 ±(99.9%) 0.010 ms/op
Iteration   1: 6.353 ±(99.9%) 0.010 ms/op
Iteration   2: 6.186 ±(99.9%) 0.016 ms/op
Iteration   3: 6.424 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.321 ±(99.9%) 2.230 ms/op [Average]
  (min, avg, max) = (6.186, 6.321, 6.424), stdev = 0.122
  CI (99.9%): [4.092, 8.551] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.932 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.740 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.024 ms/op
Iteration   1: 5.221 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  20.100 ms/op
                 createUser·p0.9999: 22.734 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 5.155 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.540 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  20.611 ms/op
                 createUser·p0.9999: 24.294 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 5.192 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   7.045 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  24.321 ms/op
                 createUser·p0.9999: 28.334 ms/op
                 createUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184922
  mean =      5.189 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 101480 
    [ 5.000,  7.500) = 76175 
    [ 7.500, 10.000) = 5529 
    [10.000, 12.500) = 1161 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.160 ms/op
     p(99.0000) =      9.827 ms/op
     p(99.9000) =     20.253 ms/op
     p(99.9900) =     28.001 ms/op
     p(99.9990) =     28.780 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 16.666 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.017 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.020 ms/op
Iteration   1: 5.219 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.545 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  23.486 ms/op
                 existUser·p0.9999: 27.095 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 5.198 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.447 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  13.982 ms/op
                 existUser·p0.9999: 29.973 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 5.091 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.269 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.857 ms/op
                 existUser·p0.99:   9.486 ms/op
                 existUser·p0.999:  27.168 ms/op
                 existUser·p0.9999: 34.125 ms/op
                 existUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185592
  mean =      5.169 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 103436 
    [ 5.000,  7.500) = 73858 
    [ 7.500, 10.000) = 6349 
    [10.000, 12.500) = 1387 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     32.596 ms/op
     p(99.9990) =     34.585 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.298 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 5.973 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.435 ±(99.9%) 0.018 ms/op
Iteration   1: 5.385 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 28.878 ms/op
                 getUser·p1.00:   30.867 ms/op

Iteration   2: 5.240 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.570 ms/op
                 getUser·p0.95:   7.535 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  23.954 ms/op
                 getUser·p0.9999: 27.787 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 5.406 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.585 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   7.903 ms/op
                 getUser·p0.99:   10.715 ms/op
                 getUser·p0.999:  26.561 ms/op
                 getUser·p0.9999: 30.709 ms/op
                 getUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179558
  mean =      5.343 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 89205 
    [ 5.000,  7.500) = 78937 
    [ 7.500, 10.000) = 8784 
    [10.000, 12.500) = 1967 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.585 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     29.983 ms/op
     p(99.9990) =     31.576 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 19.202 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.344 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.389 ±(99.9%) 0.027 ms/op
Iteration   1: 6.354 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  28.770 ms/op
                 listUser·p0.9999: 33.126 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   2: 6.145 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  29.164 ms/op
                 listUser·p0.9999: 41.393 ms/op
                 listUser·p1.00:   41.878 ms/op

Iteration   3: 6.344 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   9.028 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  22.955 ms/op
                 listUser·p0.9999: 24.439 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152759
  mean =      6.280 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7975 
    [ 5.000, 10.000) = 140647 
    [10.000, 15.000) = 3566 
    [15.000, 20.000) = 254 
    [20.000, 25.000) = 139 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 44 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     27.336 ms/op
     p(99.9900) =     39.505 ms/op
     p(99.9990) =     41.843 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.935 ± 3.666  ops/ms
ClientPb.existUser                       thrpt       3   6.270 ± 3.057  ops/ms
ClientPb.getUser                         thrpt       3   5.850 ± 3.189  ops/ms
ClientPb.listUser                        thrpt       3   5.096 ± 1.317  ops/ms
ClientPb.createUser                       avgt       3   5.383 ± 1.095   ms/op
ClientPb.existUser                        avgt       3   5.185 ± 3.557   ms/op
ClientPb.getUser                          avgt       3   5.260 ± 1.930   ms/op
ClientPb.listUser                         avgt       3   6.321 ± 2.230   ms/op
ClientPb.createUser                     sample  184922   5.189 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.357           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.827           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.253           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.001           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.836           ms/op
ClientPb.existUser                      sample  185592   5.169 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.556           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.907           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.093           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.171           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.596           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.865           ms/op
ClientPb.getUser                        sample  179558   5.343 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.889           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.983           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.785           ms/op
ClientPb.listUser                       sample  152759   6.280 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.146           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.796           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.505           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.878           ms/op
