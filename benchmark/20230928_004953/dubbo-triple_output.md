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
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.808 ops/ms
# Warmup Iteration   3: 8.902 ops/ms
Iteration   1: 9.351 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.404 ±(99.9%) 2.395 ops/ms [Average]
  (min, avg, max) = (9.307, 9.404, 9.553), stdev = 0.131
  CI (99.9%): [7.009, 11.799] (assumes normal distribution)


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
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 8.742 ops/ms
# Warmup Iteration   3: 9.623 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 9.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.887 ±(99.9%) 2.212 ops/ms [Average]
  (min, avg, max) = (9.753, 9.887, 9.988), stdev = 0.121
  CI (99.9%): [7.675, 12.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.489 ops/ms
Iteration   2: 9.353 ops/ms
Iteration   3: 9.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.431 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (9.353, 9.431, 9.489), stdev = 0.070
  CI (99.9%): [8.158, 10.704] (assumes normal distribution)


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
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 7.449 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 7.915 ops/ms
Iteration   3: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.945 ±(99.9%) 0.538 ops/ms [Average]
  (min, avg, max) = (7.915, 7.945, 7.974), stdev = 0.030
  CI (99.9%): [7.406, 8.483] (assumes normal distribution)


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
# Warmup Iteration   1: 9.596 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.005 ms/op
Iteration   1: 3.433 ±(99.9%) 0.004 ms/op
Iteration   2: 3.613 ±(99.9%) 0.003 ms/op
Iteration   3: 3.413 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.486 ±(99.9%) 2.004 ms/op [Average]
  (min, avg, max) = (3.413, 3.486, 3.613), stdev = 0.110
  CI (99.9%): [1.482, 5.490] (assumes normal distribution)


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
# Warmup Iteration   1: 7.332 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.007 ms/op
Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
Iteration   3: 3.227 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.243 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (3.218, 3.243, 3.285), stdev = 0.037
  CI (99.9%): [2.572, 3.915] (assumes normal distribution)


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
# Warmup Iteration   1: 8.017 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.005 ms/op
Iteration   1: 3.411 ±(99.9%) 0.003 ms/op
Iteration   2: 3.377 ±(99.9%) 0.004 ms/op
Iteration   3: 3.369 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.386 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.369, 3.386, 3.411), stdev = 0.022
  CI (99.9%): [2.981, 3.790] (assumes normal distribution)


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
# Warmup Iteration   1: 9.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.004 ms/op
Iteration   1: 3.925 ±(99.9%) 0.010 ms/op
Iteration   2: 4.003 ±(99.9%) 0.006 ms/op
Iteration   3: 3.932 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.953 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.925, 3.953, 4.003), stdev = 0.043
  CI (99.9%): [3.167, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 8.601 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.009 ms/op
Iteration   1: 3.500 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  19.583 ms/op
                 createUser·p0.9999: 24.899 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.441 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  22.285 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.593 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 24.418 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273402
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6440 
    [ 2.500,  5.000) = 261320 
    [ 5.000,  7.500) = 4659 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 166 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     24.729 ms/op
     p(99.9990) =     25.784 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 7.252 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.364 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.745 ms/op
                 existUser·p0.999:  19.495 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  10.928 ms/op
                 existUser·p0.9999: 24.218 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  18.276 ms/op
                 existUser·p0.9999: 25.974 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286133
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9188 
    [ 2.500,  5.000) = 271347 
    [ 5.000,  7.500) = 4769 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     15.743 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     26.486 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 8.820 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.009 ms/op
Iteration   1: 3.597 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  19.302 ms/op
                 getUser·p0.9999: 21.008 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.503 ms/op
                 getUser·p0.999:  19.350 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  17.630 ms/op
                 getUser·p0.9999: 26.778 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279056
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5337 
    [ 2.500,  5.000) = 265510 
    [ 5.000,  7.500) = 7011 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     23.596 ms/op
     p(99.9990) =     27.658 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 10.740 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.012 ms/op
Iteration   1: 4.084 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 24.171 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.999 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 16.702 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 4.055 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 17.817 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237389
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 229758 
    [ 5.000,  7.500) = 5736 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 483 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     14.641 ms/op
     p(99.9900) =     22.848 ms/op
     p(99.9990) =     25.174 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.404 ± 2.395  ops/ms
ClientPb.existUser                       thrpt       3   9.887 ± 2.212  ops/ms
ClientPb.getUser                         thrpt       3   9.431 ± 1.273  ops/ms
ClientPb.listUser                        thrpt       3   7.945 ± 0.538  ops/ms
ClientPb.createUser                       avgt       3   3.486 ± 2.004   ms/op
ClientPb.existUser                        avgt       3   3.243 ± 0.671   ms/op
ClientPb.getUser                          avgt       3   3.386 ± 0.404   ms/op
ClientPb.listUser                         avgt       3   3.953 ± 0.786   ms/op
ClientPb.createUser                     sample  273402   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.559           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.729           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.985           ms/op
ClientPb.existUser                      sample  286133   3.353 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.281           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.575           ms/op
ClientPb.getUser                        sample  279056   3.438 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.311           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.711           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.596           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  237389   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.641           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
