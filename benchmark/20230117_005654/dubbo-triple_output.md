# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.089 ops/ms
# Warmup Iteration   2: 2.548 ops/ms
# Warmup Iteration   3: 5.249 ops/ms
Iteration   1: 5.666 ops/ms
Iteration   2: 5.173 ops/ms
Iteration   3: 6.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.618 ±(99.9%) 7.717 ops/ms [Average]
  (min, avg, max) = (5.173, 5.618, 6.015), stdev = 0.423
  CI (99.9%): [≈ 0, 13.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 4.453 ops/ms
# Warmup Iteration   3: 6.053 ops/ms
Iteration   1: 6.289 ops/ms
Iteration   2: 6.279 ops/ms
Iteration   3: 6.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.325 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (6.279, 6.325, 6.408), stdev = 0.071
  CI (99.9%): [5.024, 7.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.663 ops/ms
# Warmup Iteration   2: 4.776 ops/ms
# Warmup Iteration   3: 5.719 ops/ms
Iteration   1: 6.132 ops/ms
Iteration   2: 5.955 ops/ms
Iteration   3: 6.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.063 ±(99.9%) 1.731 ops/ms [Average]
  (min, avg, max) = (5.955, 6.063, 6.132), stdev = 0.095
  CI (99.9%): [4.333, 7.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.584 ops/ms
# Warmup Iteration   2: 4.352 ops/ms
# Warmup Iteration   3: 4.998 ops/ms
Iteration   1: 5.111 ops/ms
Iteration   2: 5.261 ops/ms
Iteration   3: 5.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.209 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (5.111, 5.209, 5.261), stdev = 0.085
  CI (99.9%): [3.661, 6.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 20.133 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 6.861 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.013 ms/op
Iteration   1: 5.147 ±(99.9%) 0.022 ms/op
Iteration   2: 5.370 ±(99.9%) 0.012 ms/op
Iteration   3: 5.249 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.255 ±(99.9%) 2.036 ms/op [Average]
  (min, avg, max) = (5.147, 5.255, 5.370), stdev = 0.112
  CI (99.9%): [3.220, 7.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.741 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.874 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.259 ±(99.9%) 0.009 ms/op
Iteration   1: 5.147 ±(99.9%) 0.012 ms/op
Iteration   2: 5.142 ±(99.9%) 0.010 ms/op
Iteration   3: 5.082 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.124 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (5.082, 5.124, 5.147), stdev = 0.036
  CI (99.9%): [4.468, 5.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.283 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.748 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.304 ±(99.9%) 0.009 ms/op
Iteration   1: 5.346 ±(99.9%) 0.013 ms/op
Iteration   2: 5.548 ±(99.9%) 0.016 ms/op
Iteration   3: 5.197 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.364 ±(99.9%) 3.217 ms/op [Average]
  (min, avg, max) = (5.197, 5.364, 5.548), stdev = 0.176
  CI (99.9%): [2.147, 8.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.765 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 8.866 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.332 ±(99.9%) 0.014 ms/op
Iteration   1: 6.159 ±(99.9%) 0.015 ms/op
Iteration   2: 6.243 ±(99.9%) 0.012 ms/op
Iteration   3: 6.033 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.145 ±(99.9%) 1.928 ms/op [Average]
  (min, avg, max) = (6.033, 6.145, 6.243), stdev = 0.106
  CI (99.9%): [4.217, 8.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.145 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.583 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.081 ±(99.9%) 0.029 ms/op
Iteration   1: 5.547 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   8.226 ms/op
                 createUser·p0.99:   11.561 ms/op
                 createUser·p0.999:  24.972 ms/op
                 createUser·p0.9999: 28.458 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 5.281 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.527 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   9.521 ms/op
                 createUser·p0.999:  27.820 ms/op
                 createUser·p0.9999: 41.484 ms/op
                 createUser·p1.00:   42.533 ms/op

Iteration   3: 5.346 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  27.656 ms/op
                 createUser·p0.9999: 31.491 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178028
  mean =      5.389 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81771 
    [ 5.000, 10.000) = 93851 
    [10.000, 15.000) = 1935 
    [15.000, 20.000) = 225 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 142 
    [30.000, 35.000) = 30 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     25.624 ms/op
     p(99.9900) =     38.954 ms/op
     p(99.9990) =     42.175 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.525 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.021 ms/op
Iteration   1: 5.179 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   11.141 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 25.712 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 5.095 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.357 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   10.912 ms/op
                 existUser·p0.999:  17.990 ms/op
                 existUser·p0.9999: 27.023 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   3: 5.028 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.817 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   7.176 ms/op
                 existUser·p0.99:   10.543 ms/op
                 existUser·p0.999:  27.855 ms/op
                 existUser·p0.9999: 32.497 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188155
  mean =      5.100 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 120434 
    [ 5.000,  7.500) = 58955 
    [ 7.500, 10.000) = 6147 
    [10.000, 12.500) = 1474 
    [12.500, 15.000) = 748 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     18.050 ms/op
     p(99.9900) =     31.600 ms/op
     p(99.9990) =     32.805 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.362 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.023 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.017 ms/op
Iteration   1: 5.739 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.610 ms/op
                 getUser·p0.95:   9.224 ms/op
                 getUser·p0.99:   13.058 ms/op
                 getUser·p0.999:  23.996 ms/op
                 getUser·p0.9999: 25.901 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 5.464 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   11.715 ms/op
                 getUser·p0.999:  26.313 ms/op
                 getUser·p0.9999: 30.348 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 5.441 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   10.745 ms/op
                 getUser·p0.999:  14.156 ms/op
                 getUser·p0.9999: 31.334 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173075
  mean =      5.545 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 74246 
    [ 5.000,  7.500) = 85569 
    [ 7.500, 10.000) = 8837 
    [10.000, 12.500) = 3042 
    [12.500, 15.000) = 847 
    [15.000, 17.500) = 230 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     30.608 ms/op
     p(99.9990) =     31.761 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.329 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 7.881 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.123 ±(99.9%) 0.024 ms/op
Iteration   1: 6.276 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.873 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  28.771 ms/op
                 listUser·p0.9999: 32.605 ms/op
                 listUser·p1.00:   33.522 ms/op

Iteration   2: 6.545 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.714 ms/op
                 listUser·p0.999:  29.233 ms/op
                 listUser·p0.9999: 35.011 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.419 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.878 ms/op
                 listUser·p0.999:  24.853 ms/op
                 listUser·p0.9999: 28.347 ms/op
                 listUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149614
  mean =      6.411 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 7537 
    [ 5.000,  7.500) = 121934 
    [ 7.500, 10.000) = 15587 
    [10.000, 12.500) = 3164 
    [12.500, 15.000) = 855 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.494 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.913 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     27.603 ms/op
     p(99.9900) =     33.359 ms/op
     p(99.9990) =     35.490 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.618 ± 7.717  ops/ms
ClientPb.existUser                       thrpt       3   6.325 ± 1.301  ops/ms
ClientPb.getUser                         thrpt       3   6.063 ± 1.731  ops/ms
ClientPb.listUser                        thrpt       3   5.209 ± 1.547  ops/ms
ClientPb.createUser                       avgt       3   5.255 ± 2.036   ms/op
ClientPb.existUser                        avgt       3   5.124 ± 0.656   ms/op
ClientPb.getUser                          avgt       3   5.364 ± 3.217   ms/op
ClientPb.listUser                         avgt       3   6.145 ± 1.928   ms/op
ClientPb.createUser                     sample  178028   5.389 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.964           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.595           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.650           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.624           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.954           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.533           ms/op
ClientPb.existUser                      sample  188155   5.100 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.817           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.846           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.050           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.600           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  173075   5.545 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.517           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.036           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.608           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  149614   6.411 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.494           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.337           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.603           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.359           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.717           ms/op
