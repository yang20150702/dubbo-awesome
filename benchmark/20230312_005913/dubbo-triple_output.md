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
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 6.317 ops/ms
# Warmup Iteration   3: 9.521 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 9.678 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.709 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (9.675, 9.709, 9.775), stdev = 0.056
  CI (99.9%): [8.679, 10.740] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.447 ops/ms
# Warmup Iteration   2: 9.373 ops/ms
# Warmup Iteration   3: 10.175 ops/ms
Iteration   1: 10.593 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.531 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (10.472, 10.531, 10.593), stdev = 0.060
  CI (99.9%): [9.428, 11.633] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 9.034 ops/ms
# Warmup Iteration   3: 9.410 ops/ms
Iteration   1: 10.197 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 9.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.186 ±(99.9%) 3.543 ops/ms [Average]
  (min, avg, max) = (9.987, 10.186, 10.375), stdev = 0.194
  CI (99.9%): [6.643, 13.730] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.381 ops/ms
# Warmup Iteration   2: 7.731 ops/ms
# Warmup Iteration   3: 8.518 ops/ms
Iteration   1: 8.727 ops/ms
Iteration   2: 8.459 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.580 ±(99.9%) 2.478 ops/ms [Average]
  (min, avg, max) = (8.459, 8.580, 8.727), stdev = 0.136
  CI (99.9%): [6.102, 11.057] (assumes normal distribution)


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
# Warmup Iteration   1: 7.417 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.005 ms/op
Iteration   1: 3.229 ±(99.9%) 0.004 ms/op
Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
Iteration   3: 3.189 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.190 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.153, 3.190, 3.229), stdev = 0.038
  CI (99.9%): [2.495, 3.885] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.573 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.001 ms/op
Iteration   1: 3.020 ±(99.9%) 0.005 ms/op
Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
Iteration   3: 3.032 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (3.020, 3.066, 3.147), stdev = 0.070
  CI (99.9%): [1.789, 4.343] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.149 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.002 ms/op
Iteration   1: 3.300 ±(99.9%) 0.005 ms/op
Iteration   2: 3.114 ±(99.9%) 0.002 ms/op
Iteration   3: 3.223 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.212 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (3.114, 3.212, 3.300), stdev = 0.093
  CI (99.9%): [1.516, 4.909] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.729 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.009 ms/op
Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
Iteration   2: 3.685 ±(99.9%) 0.007 ms/op
Iteration   3: 3.653 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.681 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (3.653, 3.681, 3.706), stdev = 0.027
  CI (99.9%): [3.193, 4.169] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.935 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.010 ms/op
Iteration   1: 3.352 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  19.194 ms/op
                 createUser·p0.9999: 30.784 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 22.569 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.353 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  14.795 ms/op
                 createUser·p0.9999: 20.659 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291993
  mean =      3.285 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24375 
    [ 2.500,  5.000) = 260553 
    [ 5.000,  7.500) = 6238 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     27.348 ms/op
     p(99.9990) =     36.378 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.479 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.008 ms/op
Iteration   1: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  9.285 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 23.069 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306874
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21747 
    [ 2.500,  5.000) = 279105 
    [ 5.000,  7.500) = 5401 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.689 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 7.656 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
Iteration   1: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.786 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  11.067 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   3: 3.181 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.966 ms/op
                 getUser·p0.999:  15.548 ms/op
                 getUser·p0.9999: 23.224 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303846
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10720 
    [ 2.500,  5.000) = 286455 
    [ 5.000,  7.500) = 5793 
    [ 7.500, 10.000) = 494 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     14.781 ms/op
     p(99.9900) =     25.392 ms/op
     p(99.9990) =     28.769 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 9.026 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.010 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.763 ms/op
                 listUser·p0.9999: 20.611 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   2: 3.650 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   15.712 ms/op

Iteration   3: 3.690 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.304 ms/op
                 listUser·p0.9999: 13.697 ms/op
                 listUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259916
  mean =      3.691 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 253771 
    [ 5.000,  7.500) = 4365 
    [ 7.500, 10.000) = 1161 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.709 ± 1.031  ops/ms
ClientPb.existUser                       thrpt       3  10.531 ± 1.103  ops/ms
ClientPb.getUser                         thrpt       3  10.186 ± 3.543  ops/ms
ClientPb.listUser                        thrpt       3   8.580 ± 2.478  ops/ms
ClientPb.createUser                       avgt       3   3.190 ± 0.695   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.277   ms/op
ClientPb.getUser                          avgt       3   3.212 ± 1.696   ms/op
ClientPb.listUser                         avgt       3   3.681 ± 0.488   ms/op
ClientPb.createUser                     sample  291993   3.285 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.582           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.348           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  306874   3.128 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.217           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.478           ms/op
ClientPb.getUser                        sample  303846   3.161 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.873           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.781           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.392           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.164           ms/op
ClientPb.listUser                       sample  259916   3.691 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.173           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.382           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970           ms/op
