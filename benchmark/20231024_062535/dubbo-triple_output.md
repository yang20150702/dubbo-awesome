# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.447 ops/ms
# Warmup Iteration   2: 3.294 ops/ms
# Warmup Iteration   3: 6.856 ops/ms
Iteration   1: 6.677 ops/ms
Iteration   2: 7.033 ops/ms
Iteration   3: 7.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.097 ±(99.9%) 8.315 ops/ms [Average]
  (min, avg, max) = (6.677, 7.097, 7.582), stdev = 0.456
  CI (99.9%): [≈ 0, 15.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.117 ops/ms
# Warmup Iteration   2: 6.454 ops/ms
# Warmup Iteration   3: 6.874 ops/ms
Iteration   1: 7.719 ops/ms
Iteration   2: 8.232 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.061 ±(99.9%) 5.403 ops/ms [Average]
  (min, avg, max) = (7.719, 8.061, 8.232), stdev = 0.296
  CI (99.9%): [2.658, 13.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 5.500 ops/ms
# Warmup Iteration   3: 7.290 ops/ms
Iteration   1: 7.718 ops/ms
Iteration   2: 7.987 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.869 ±(99.9%) 2.508 ops/ms [Average]
  (min, avg, max) = (7.718, 7.869, 7.987), stdev = 0.137
  CI (99.9%): [5.361, 10.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.713 ops/ms
# Warmup Iteration   2: 5.087 ops/ms
# Warmup Iteration   3: 6.409 ops/ms
Iteration   1: 6.468 ops/ms
Iteration   2: 6.485 ops/ms
Iteration   3: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.456 ±(99.9%) 0.665 ops/ms [Average]
  (min, avg, max) = (6.415, 6.456, 6.485), stdev = 0.036
  CI (99.9%): [5.791, 7.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.400 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.301 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.540 ±(99.9%) 0.010 ms/op
Iteration   1: 4.074 ±(99.9%) 0.009 ms/op
Iteration   2: 3.974 ±(99.9%) 0.004 ms/op
Iteration   3: 4.095 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.048 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (3.974, 4.048, 4.095), stdev = 0.065
  CI (99.9%): [2.866, 5.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.582 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.006 ms/op
Iteration   1: 4.217 ±(99.9%) 0.006 ms/op
Iteration   2: 3.882 ±(99.9%) 0.005 ms/op
Iteration   3: 3.873 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.991 ±(99.9%) 3.581 ms/op [Average]
  (min, avg, max) = (3.873, 3.991, 4.217), stdev = 0.196
  CI (99.9%): [0.410, 7.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.173 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.006 ms/op
Iteration   1: 3.943 ±(99.9%) 0.005 ms/op
Iteration   2: 4.015 ±(99.9%) 0.003 ms/op
Iteration   3: 4.193 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.051 ±(99.9%) 2.349 ms/op [Average]
  (min, avg, max) = (3.943, 4.051, 4.193), stdev = 0.129
  CI (99.9%): [1.701, 6.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.993 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.850 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.203 ±(99.9%) 0.011 ms/op
Iteration   1: 4.997 ±(99.9%) 0.008 ms/op
Iteration   2: 4.989 ±(99.9%) 0.007 ms/op
Iteration   3: 5.119 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.035 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (4.989, 5.035, 5.119), stdev = 0.073
  CI (99.9%): [3.708, 6.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.735 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.097 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.783 ±(99.9%) 0.023 ms/op
Iteration   1: 4.199 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  15.598 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.023 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  25.683 ms/op
                 createUser·p0.9999: 30.286 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.961 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  26.980 ms/op
                 createUser·p0.9999: 31.195 ms/op
                 createUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236208
  mean =      4.065 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 213 
    [ 2.500,  5.000) = 223365 
    [ 5.000,  7.500) = 10074 
    [ 7.500, 10.000) = 1678 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     24.818 ms/op
     p(99.9900) =     30.413 ms/op
     p(99.9990) =     32.030 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.082 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.015 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.952 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  14.031 ms/op
                 existUser·p0.9999: 25.320 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 3.969 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  25.671 ms/op
                 existUser·p0.9999: 27.754 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 30.245 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241754
  mean =      3.968 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 227 
    [ 2.500,  5.000) = 228601 
    [ 5.000,  7.500) = 10189 
    [ 7.500, 10.000) = 2006 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     16.301 ms/op
     p(99.9900) =     29.715 ms/op
     p(99.9990) =     30.597 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.075 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.013 ms/op
Iteration   1: 4.023 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 22.025 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 4.258 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.423 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.654 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 23.625 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 4.215 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  14.648 ms/op
                 getUser·p0.9999: 26.588 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230488
  mean =      4.163 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 211096 
    [ 5.000,  7.500) = 15774 
    [ 7.500, 10.000) = 2220 
    [10.000, 12.500) = 674 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.752 ms/op
     p(99.9990) =     27.454 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.578 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 6.492 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.194 ±(99.9%) 0.018 ms/op
Iteration   1: 5.060 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  27.743 ms/op
                 listUser·p0.9999: 35.433 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   2: 4.977 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  24.407 ms/op
                 listUser·p0.9999: 30.769 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   3: 5.111 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190093
  mean =      5.049 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 128259 
    [ 5.000,  7.500) = 54826 
    [ 7.500, 10.000) = 5462 
    [10.000, 12.500) = 741 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     23.534 ms/op
     p(99.9900) =     33.816 ms/op
     p(99.9990) =     36.968 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.097 ± 8.315  ops/ms
ClientPb.existUser                       thrpt       3   8.061 ± 5.403  ops/ms
ClientPb.getUser                         thrpt       3   7.869 ± 2.508  ops/ms
ClientPb.listUser                        thrpt       3   6.456 ± 0.665  ops/ms
ClientPb.createUser                       avgt       3   4.048 ± 1.182   ms/op
ClientPb.existUser                        avgt       3   3.991 ± 3.581   ms/op
ClientPb.getUser                          avgt       3   4.051 ± 2.349   ms/op
ClientPb.listUser                         avgt       3   5.035 ± 1.327   ms/op
ClientPb.createUser                     sample  236208   4.065 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.630           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.635           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.818           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.413           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.473           ms/op
ClientPb.existUser                      sample  241754   3.968 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.538           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.095           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.815           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.301           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.715           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  230488   4.163 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.423           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.752           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  190093   5.049 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.534           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.816           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
