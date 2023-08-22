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
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 5.242 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.535 ops/ms
Iteration   2: 8.893 ops/ms
Iteration   3: 8.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.794 ±(99.9%) 4.117 ops/ms [Average]
  (min, avg, max) = (8.535, 8.794, 8.953), stdev = 0.226
  CI (99.9%): [4.677, 12.911] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.346 ops/ms
# Warmup Iteration   3: 9.445 ops/ms
Iteration   1: 9.155 ops/ms
Iteration   2: 9.796 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.452 ±(99.9%) 5.892 ops/ms [Average]
  (min, avg, max) = (9.155, 9.452, 9.796), stdev = 0.323
  CI (99.9%): [3.560, 15.344] (assumes normal distribution)


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
# Warmup Iteration   1: 2.984 ops/ms
# Warmup Iteration   2: 8.285 ops/ms
# Warmup Iteration   3: 8.775 ops/ms
Iteration   1: 9.311 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.170 ±(99.9%) 3.929 ops/ms [Average]
  (min, avg, max) = (8.922, 9.170, 9.311), stdev = 0.215
  CI (99.9%): [5.241, 13.100] (assumes normal distribution)


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
# Warmup Iteration   1: 2.750 ops/ms
# Warmup Iteration   2: 7.177 ops/ms
# Warmup Iteration   3: 7.520 ops/ms
Iteration   1: 7.746 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 7.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.841 ±(99.9%) 2.477 ops/ms [Average]
  (min, avg, max) = (7.746, 7.841, 7.996), stdev = 0.136
  CI (99.9%): [5.363, 10.318] (assumes normal distribution)


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
# Warmup Iteration   1: 9.912 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.005 ms/op
Iteration   1: 3.578 ±(99.9%) 0.004 ms/op
Iteration   2: 3.522 ±(99.9%) 0.007 ms/op
Iteration   3: 3.395 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.498 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.395, 3.498, 3.578), stdev = 0.094
  CI (99.9%): [1.779, 5.218] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.312 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.006 ms/op
Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
Iteration   3: 3.364 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.353 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.313, 3.353, 3.380), stdev = 0.035
  CI (99.9%): [2.716, 3.990] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.025 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.006 ms/op
Iteration   1: 3.498 ±(99.9%) 0.006 ms/op
Iteration   2: 3.430 ±(99.9%) 0.010 ms/op
Iteration   3: 3.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.480 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.430, 3.480, 3.510), stdev = 0.043
  CI (99.9%): [2.693, 4.266] (assumes normal distribution)


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
# Warmup Iteration   1: 10.877 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.008 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
Iteration   2: 4.077 ±(99.9%) 0.009 ms/op
Iteration   3: 4.103 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.061 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (4.002, 4.061, 4.103), stdev = 0.052
  CI (99.9%): [3.106, 5.015] (assumes normal distribution)


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
# Warmup Iteration   1: 11.071 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.015 ms/op
Iteration   1: 3.543 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  9.894 ms/op
                 createUser·p0.9999: 29.785 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   2: 3.514 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.024 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.327 ms/op
                 createUser·p0.999:  22.417 ms/op
                 createUser·p0.9999: 43.426 ms/op
                 createUser·p1.00:   49.873 ms/op

Iteration   3: 3.531 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.486 ms/op
                 createUser·p0.999:  23.855 ms/op
                 createUser·p0.9999: 27.813 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271947
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263414 
    [ 5.000, 10.000) = 8113 
    [10.000, 15.000) = 92 
    [15.000, 20.000) = 47 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     20.614 ms/op
     p(99.9900) =     36.518 ms/op
     p(99.9990) =     49.582 ms/op
     p(99.9999) =     49.873 ms/op
    p(100.0000) =     49.873 ms/op


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
# Warmup Iteration   1: 8.688 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
Iteration   1: 3.338 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.522 ms/op
                 existUser·p0.9999: 22.605 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  19.198 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  17.513 ms/op
                 existUser·p0.9999: 24.904 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285875
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16096 
    [ 2.500,  5.000) = 262060 
    [ 5.000,  7.500) = 6353 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     13.240 ms/op
     p(99.9900) =     24.327 ms/op
     p(99.9990) =     25.315 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 10.320 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.011 ms/op
Iteration   1: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  21.357 ms/op
                 getUser·p0.9999: 24.737 ms/op
                 getUser·p1.00:   27.886 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  22.446 ms/op
                 getUser·p0.9999: 24.503 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.452 ms/op
                 getUser·p0.999:  20.578 ms/op
                 getUser·p0.9999: 27.656 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274385
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16707 
    [ 2.500,  5.000) = 249216 
    [ 5.000,  7.500) = 6828 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     21.170 ms/op
     p(99.9900) =     26.794 ms/op
     p(99.9990) =     28.164 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.160 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.015 ms/op
Iteration   1: 4.153 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  21.463 ms/op
                 listUser·p0.9999: 26.506 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   2: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.661 ms/op
                 listUser·p0.9999: 17.730 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.345 ms/op
                 listUser·p0.999:  16.231 ms/op
                 listUser·p0.9999: 17.723 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233424
  mean =      4.111 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 221258 
    [ 5.000,  7.500) = 8860 
    [ 7.500, 10.000) = 2059 
    [10.000, 12.500) = 666 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     25.297 ms/op
     p(99.9990) =     27.557 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.794 ± 4.117  ops/ms
ClientPb.existUser                       thrpt       3   9.452 ± 5.892  ops/ms
ClientPb.getUser                         thrpt       3   9.170 ± 3.929  ops/ms
ClientPb.listUser                        thrpt       3   7.841 ± 2.477  ops/ms
ClientPb.createUser                       avgt       3   3.498 ± 1.719   ms/op
ClientPb.existUser                        avgt       3   3.353 ± 0.637   ms/op
ClientPb.getUser                          avgt       3   3.480 ± 0.786   ms/op
ClientPb.listUser                         avgt       3   4.061 ± 0.954   ms/op
ClientPb.createUser                     sample  271947   3.529 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.614           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.518           ms/op
ClientPb.createUser:createUser·p1.00    sample          49.873           ms/op
ClientPb.existUser                      sample  285875   3.356 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.327           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.240           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.327           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.018           ms/op
ClientPb.getUser                        sample  274385   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.620           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.794           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.377           ms/op
ClientPb.listUser                       sample  233424   4.111 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.460           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.297           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.049           ms/op
