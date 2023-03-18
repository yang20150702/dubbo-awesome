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
# Warmup Iteration   1: 2.036 ops/ms
# Warmup Iteration   2: 5.649 ops/ms
# Warmup Iteration   3: 8.815 ops/ms
Iteration   1: 9.166 ops/ms
Iteration   2: 9.171 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.236 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (9.166, 9.236, 9.371), stdev = 0.117
  CI (99.9%): [7.102, 11.371] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.054 ops/ms
# Warmup Iteration   2: 8.560 ops/ms
# Warmup Iteration   3: 9.596 ops/ms
Iteration   1: 9.590 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.858 ±(99.9%) 4.467 ops/ms [Average]
  (min, avg, max) = (9.590, 9.858, 10.069), stdev = 0.245
  CI (99.9%): [5.392, 14.325] (assumes normal distribution)


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
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 8.470 ops/ms
# Warmup Iteration   3: 9.276 ops/ms
Iteration   1: 9.568 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.525 ±(99.9%) 3.232 ops/ms [Average]
  (min, avg, max) = (9.331, 9.525, 9.677), stdev = 0.177
  CI (99.9%): [6.294, 12.757] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 7.295 ops/ms
# Warmup Iteration   3: 8.242 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 8.278 ops/ms
Iteration   3: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.203 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (7.985, 8.203, 8.346), stdev = 0.192
  CI (99.9%): [4.704, 11.701] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.990 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.005 ms/op
Iteration   1: 3.378 ±(99.9%) 0.010 ms/op
Iteration   2: 3.392 ±(99.9%) 0.004 ms/op
Iteration   3: 3.447 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 0.663 ms/op [Average]
  (min, avg, max) = (3.378, 3.406, 3.447), stdev = 0.036
  CI (99.9%): [2.743, 4.069] (assumes normal distribution)


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
# Warmup Iteration   1: 8.295 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.003 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
Iteration   3: 3.184 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.258 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (3.184, 3.258, 3.299), stdev = 0.064
  CI (99.9%): [2.087, 4.430] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.909 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.005 ms/op
Iteration   1: 3.439 ±(99.9%) 0.011 ms/op
Iteration   2: 3.291 ±(99.9%) 0.011 ms/op
Iteration   3: 3.289 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.340 ±(99.9%) 1.578 ms/op [Average]
  (min, avg, max) = (3.289, 3.340, 3.439), stdev = 0.086
  CI (99.9%): [1.762, 4.917] (assumes normal distribution)


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
# Warmup Iteration   1: 11.241 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.010 ms/op
Iteration   1: 4.008 ±(99.9%) 0.013 ms/op
Iteration   2: 3.942 ±(99.9%) 0.009 ms/op
Iteration   3: 3.997 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.982 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.942, 3.982, 4.008), stdev = 0.035
  CI (99.9%): [3.336, 4.629] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.012 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  20.034 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   25.919 ms/op

Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  20.731 ms/op
                 createUser·p0.9999: 25.928 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   3: 3.408 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  15.893 ms/op
                 createUser·p0.9999: 24.093 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285727
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5726 
    [ 2.500,  5.000) = 275143 
    [ 5.000,  7.500) = 3865 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     27.693 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 7.699 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
Iteration   1: 3.220 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 22.415 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.249 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  10.155 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  9.249 ms/op
                 existUser·p0.9999: 24.180 ms/op
                 existUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298895
  mean =      3.211 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14623 
    [ 2.500,  5.000) = 280130 
    [ 5.000,  7.500) = 3505 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 189 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     23.607 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 9.858 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.468 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.985 ms/op
                 getUser·p0.999:  20.931 ms/op
                 getUser·p0.9999: 31.221 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  10.392 ms/op
                 getUser·p0.9999: 24.067 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.510 ms/op
                 getUser·p0.99:   6.404 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 30.726 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283378
  mean =      3.385 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6301 
    [ 2.500,  5.000) = 268920 
    [ 5.000,  7.500) = 6777 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 11.397 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.015 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 21.665 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.925 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.275 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.932 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244439
  mean =      3.925 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 236905 
    [ 5.000,  7.500) = 5571 
    [ 7.500, 10.000) = 1244 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     21.008 ms/op
     p(99.9990) =     22.464 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.236 ± 2.134  ops/ms
ClientPb.existUser                       thrpt       3   9.858 ± 4.467  ops/ms
ClientPb.getUser                         thrpt       3   9.525 ± 3.232  ops/ms
ClientPb.listUser                        thrpt       3   8.203 ± 3.499  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 0.663   ms/op
ClientPb.existUser                        avgt       3   3.258 ± 1.171   ms/op
ClientPb.getUser                          avgt       3   3.340 ± 1.578   ms/op
ClientPb.listUser                         avgt       3   3.982 ± 0.646   ms/op
ClientPb.createUser                     sample  285727   3.356 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.202           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.998           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.663           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.428           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  298895   3.211 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.994           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.607           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.068           ms/op
ClientPb.getUser                        sample  283378   3.385 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.638           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  244439   3.925 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.008           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.008           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
