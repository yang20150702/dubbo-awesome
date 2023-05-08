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
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 5.256 ops/ms
# Warmup Iteration   3: 7.780 ops/ms
Iteration   1: 9.024 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.949 ±(99.9%) 1.943 ops/ms [Average]
  (min, avg, max) = (8.827, 8.949, 9.024), stdev = 0.107
  CI (99.9%): [7.005, 10.892] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.192 ops/ms
# Warmup Iteration   2: 8.963 ops/ms
# Warmup Iteration   3: 9.431 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.815 ops/ms
Iteration   3: 10.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.898 ±(99.9%) 4.782 ops/ms [Average]
  (min, avg, max) = (9.688, 9.898, 10.192), stdev = 0.262
  CI (99.9%): [5.116, 14.680] (assumes normal distribution)


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
# Warmup Iteration   1: 3.127 ops/ms
# Warmup Iteration   2: 7.917 ops/ms
# Warmup Iteration   3: 9.710 ops/ms
Iteration   1: 10.315 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.354 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (10.315, 10.354, 10.396), stdev = 0.040
  CI (99.9%): [9.621, 11.087] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.519 ops/ms
# Warmup Iteration   2: 7.892 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 8.157 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.246 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (8.157, 8.246, 8.335), stdev = 0.089
  CI (99.9%): [6.626, 9.866] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.558 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.004 ms/op
Iteration   1: 3.264 ±(99.9%) 0.006 ms/op
Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
Iteration   3: 3.257 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.258 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (3.254, 3.258, 3.264), stdev = 0.005
  CI (99.9%): [3.168, 3.348] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.769 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.008 ms/op
Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
Iteration   3: 3.049 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 0.515 ms/op [Average]
  (min, avg, max) = (3.031, 3.055, 3.086), stdev = 0.028
  CI (99.9%): [2.540, 3.570] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.060 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.469 ±(99.9%) 0.008 ms/op
Iteration   1: 3.278 ±(99.9%) 0.005 ms/op
Iteration   2: 3.203 ±(99.9%) 0.005 ms/op
Iteration   3: 3.266 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.249 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.203, 3.249, 3.278), stdev = 0.040
  CI (99.9%): [2.513, 3.985] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.565 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.005 ms/op
Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
Iteration   2: 3.915 ±(99.9%) 0.008 ms/op
Iteration   3: 3.489 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 3.927 ms/op [Average]
  (min, avg, max) = (3.489, 3.720, 3.915), stdev = 0.215
  CI (99.9%): [≈ 0, 7.646] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.739 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  14.150 ms/op
                 createUser·p0.9999: 24.813 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  15.271 ms/op
                 createUser·p0.9999: 21.934 ms/op
                 createUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 313886
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15646 
    [ 2.500,  5.000) = 294427 
    [ 5.000,  7.500) = 2846 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =     17.538 ms/op
     p(99.9900) =     23.810 ms/op
     p(99.9990) =     25.593 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 6.135 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.133 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.941 ms/op
                 existUser·p0.9999: 23.794 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  16.862 ms/op
                 existUser·p0.9999: 24.892 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.766 ms/op
                 existUser·p0.9999: 24.192 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301834
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13100 
    [ 2.500,  5.000) = 283720 
    [ 5.000,  7.500) = 4139 
    [ 7.500, 10.000) = 488 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     24.406 ms/op
     p(99.9990) =     25.329 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 8.031 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  16.099 ms/op
                 getUser·p0.9999: 23.470 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  10.560 ms/op
                 getUser·p0.9999: 26.191 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   3: 3.333 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  18.856 ms/op
                 getUser·p0.9999: 34.564 ms/op
                 getUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290734
  mean =      3.302 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11660 
    [ 2.500,  5.000) = 271661 
    [ 5.000,  7.500) = 6397 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     13.461 ms/op
     p(99.9900) =     32.763 ms/op
     p(99.9990) =     35.199 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 8.956 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.013 ms/op
Iteration   1: 3.960 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 27.655 ms/op
                 listUser·p1.00:   28.344 ms/op

Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  17.861 ms/op
                 listUser·p0.9999: 23.397 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.158 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.015 ms/op
                 listUser·p0.999:  15.731 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237596
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 223753 
    [ 5.000,  7.500) = 11760 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     17.315 ms/op
     p(99.9900) =     26.394 ms/op
     p(99.9990) =     28.242 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.949 ± 1.943  ops/ms
ClientPb.existUser                       thrpt       3   9.898 ± 4.782  ops/ms
ClientPb.getUser                         thrpt       3  10.354 ± 0.733  ops/ms
ClientPb.listUser                        thrpt       3   8.246 ± 1.620  ops/ms
ClientPb.createUser                       avgt       3   3.258 ± 0.090   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 0.515   ms/op
ClientPb.getUser                          avgt       3   3.249 ± 0.736   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 3.927   ms/op
ClientPb.createUser                     sample  313886   3.056 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.920           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.494           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.538           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.810           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.083           ms/op
ClientPb.existUser                      sample  301834   3.179 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.748           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.406           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952           ms/op
ClientPb.getUser                        sample  290734   3.302 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.034           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.461           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.455           ms/op
ClientPb.listUser                       sample  237596   4.038 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.315           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.394           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.344           ms/op
