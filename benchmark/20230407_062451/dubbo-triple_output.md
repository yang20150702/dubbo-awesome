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
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 5.992 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 9.155 ops/ms
Iteration   2: 9.281 ops/ms
Iteration   3: 9.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.285 ±(99.9%) 2.425 ops/ms [Average]
  (min, avg, max) = (9.155, 9.285, 9.420), stdev = 0.133
  CI (99.9%): [6.861, 11.710] (assumes normal distribution)


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
# Warmup Iteration   1: 2.761 ops/ms
# Warmup Iteration   2: 8.293 ops/ms
# Warmup Iteration   3: 9.133 ops/ms
Iteration   1: 9.532 ops/ms
Iteration   2: 9.528 ops/ms
Iteration   3: 9.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.531 ±(99.9%) 0.059 ops/ms [Average]
  (min, avg, max) = (9.528, 9.531, 9.534), stdev = 0.003
  CI (99.9%): [9.473, 9.590] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.517 ops/ms
# Warmup Iteration   2: 8.499 ops/ms
# Warmup Iteration   3: 9.030 ops/ms
Iteration   1: 9.530 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.372 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (9.274, 9.372, 9.530), stdev = 0.138
  CI (99.9%): [6.850, 11.894] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ops/ms
# Warmup Iteration   2: 7.278 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.980 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.946 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (7.890, 7.946, 7.980), stdev = 0.049
  CI (99.9%): [7.055, 8.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.076 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.006 ms/op
Iteration   1: 3.576 ±(99.9%) 0.006 ms/op
Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
Iteration   3: 3.414 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.474 ±(99.9%) 1.611 ms/op [Average]
  (min, avg, max) = (3.414, 3.474, 3.576), stdev = 0.088
  CI (99.9%): [1.863, 5.085] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.204 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.372 ±(99.9%) 0.010 ms/op
Iteration   2: 3.331 ±(99.9%) 0.006 ms/op
Iteration   3: 3.420 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.374 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.331, 3.374, 3.420), stdev = 0.045
  CI (99.9%): [2.561, 4.187] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.865 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.621 ±(99.9%) 0.006 ms/op
Iteration   1: 3.608 ±(99.9%) 0.004 ms/op
Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
Iteration   3: 3.339 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 2.626 ms/op [Average]
  (min, avg, max) = (3.339, 3.444, 3.608), stdev = 0.144
  CI (99.9%): [0.818, 6.070] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.401 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.008 ms/op
Iteration   1: 3.971 ±(99.9%) 0.013 ms/op
Iteration   2: 4.098 ±(99.9%) 0.008 ms/op
Iteration   3: 3.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.013 ±(99.9%) 1.347 ms/op [Average]
  (min, avg, max) = (3.970, 4.013, 4.098), stdev = 0.074
  CI (99.9%): [2.666, 5.360] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.727 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.009 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  18.635 ms/op
                 createUser·p0.9999: 21.748 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 3.491 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  21.503 ms/op
                 createUser·p0.9999: 25.154 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.604 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.684 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274940
  mean =      3.493 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5308 
    [ 2.500,  5.000) = 262818 
    [ 5.000,  7.500) = 5840 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.748 ms/op
     p(99.9900) =     26.297 ms/op
     p(99.9990) =     27.337 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.112 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.537 ms/op
                 existUser·p0.999:  20.328 ms/op
                 existUser·p0.9999: 24.838 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   3: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  17.857 ms/op
                 existUser·p0.9999: 23.933 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284675
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17611 
    [ 2.500,  5.000) = 261298 
    [ 5.000,  7.500) = 4824 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.769 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     24.102 ms/op
     p(99.9990) =     25.645 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 9.513 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
Iteration   1: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.368 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  20.465 ms/op
                 getUser·p0.9999: 32.242 ms/op
                 getUser·p1.00:   33.063 ms/op

Iteration   2: 3.502 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 25.692 ms/op
                 getUser·p1.00:   27.558 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  17.395 ms/op
                 getUser·p0.9999: 27.170 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275997
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10549 
    [ 2.500,  5.000) = 255384 
    [ 5.000,  7.500) = 8955 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     28.200 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 10.442 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.557 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.013 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  19.565 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 19.974 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.929 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.198 ms/op
                 listUser·p0.9999: 15.417 ms/op
                 listUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242055
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 234992 
    [ 5.000,  7.500) = 4642 
    [ 7.500, 10.000) = 1305 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     15.858 ms/op
     p(99.9900) =     24.444 ms/op
     p(99.9990) =     25.725 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.285 ± 2.425  ops/ms
ClientPb.existUser                       thrpt       3   9.531 ± 0.059  ops/ms
ClientPb.getUser                         thrpt       3   9.372 ± 2.522  ops/ms
ClientPb.listUser                        thrpt       3   7.946 ± 0.890  ops/ms
ClientPb.createUser                       avgt       3   3.474 ± 1.611   ms/op
ClientPb.existUser                        avgt       3   3.374 ± 0.813   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 2.626   ms/op
ClientPb.listUser                         avgt       3   4.013 ± 1.347   ms/op
ClientPb.createUser                     sample  274940   3.493 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.019           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.748           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.297           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  284675   3.370 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.069           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.769           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.419           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.102           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.756           ms/op
ClientPb.getUser                        sample  275997   3.475 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.368           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.200           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.063           ms/op
ClientPb.listUser                       sample  242055   3.963 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.858           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.444           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.919           ms/op
