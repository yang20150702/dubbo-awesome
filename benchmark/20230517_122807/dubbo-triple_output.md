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
# Warmup Iteration   1: 2.172 ops/ms
# Warmup Iteration   2: 6.064 ops/ms
# Warmup Iteration   3: 8.521 ops/ms
Iteration   1: 9.680 ops/ms
Iteration   2: 9.497 ops/ms
Iteration   3: 9.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.568 ±(99.9%) 1.791 ops/ms [Average]
  (min, avg, max) = (9.497, 9.568, 9.680), stdev = 0.098
  CI (99.9%): [7.777, 11.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 8.386 ops/ms
# Warmup Iteration   3: 9.244 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.922 ±(99.9%) 3.505 ops/ms [Average]
  (min, avg, max) = (9.726, 9.922, 10.110), stdev = 0.192
  CI (99.9%): [6.417, 13.426] (assumes normal distribution)


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
# Warmup Iteration   1: 2.976 ops/ms
# Warmup Iteration   2: 8.351 ops/ms
# Warmup Iteration   3: 9.389 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 8.812 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.179 ±(99.9%) 5.957 ops/ms [Average]
  (min, avg, max) = (8.812, 9.179, 9.435), stdev = 0.327
  CI (99.9%): [3.222, 15.137] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 7.207 ops/ms
# Warmup Iteration   3: 8.007 ops/ms
Iteration   1: 7.837 ops/ms
Iteration   2: 8.065 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.040 ±(99.9%) 3.493 ops/ms [Average]
  (min, avg, max) = (7.837, 8.040, 8.217), stdev = 0.191
  CI (99.9%): [4.546, 11.533] (assumes normal distribution)


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
# Warmup Iteration   1: 8.733 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.005 ms/op
Iteration   1: 3.399 ±(99.9%) 0.011 ms/op
Iteration   2: 3.450 ±(99.9%) 0.006 ms/op
Iteration   3: 3.259 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.369 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (3.259, 3.369, 3.450), stdev = 0.099
  CI (99.9%): [1.569, 5.170] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.593 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.005 ms/op
Iteration   1: 3.260 ±(99.9%) 0.003 ms/op
Iteration   2: 3.242 ±(99.9%) 0.005 ms/op
Iteration   3: 3.214 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.238 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.214, 3.238, 3.260), stdev = 0.023
  CI (99.9%): [2.813, 3.664] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.262 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.004 ms/op
Iteration   1: 3.486 ±(99.9%) 0.002 ms/op
Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
Iteration   3: 3.359 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.359, 3.428, 3.486), stdev = 0.064
  CI (99.9%): [2.255, 4.602] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.022 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.008 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
Iteration   2: 3.948 ±(99.9%) 0.008 ms/op
Iteration   3: 3.776 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.896 ±(99.9%) 1.898 ms/op [Average]
  (min, avg, max) = (3.776, 3.896, 3.965), stdev = 0.104
  CI (99.9%): [1.998, 5.794] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.859 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.013 ms/op
Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  19.638 ms/op
                 createUser·p0.9999: 22.643 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  23.396 ms/op
                 createUser·p0.9999: 35.096 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  15.024 ms/op
                 createUser·p0.9999: 29.889 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279180
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4653 
    [ 2.500,  5.000) = 266574 
    [ 5.000,  7.500) = 6854 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     19.557 ms/op
     p(99.9900) =     34.019 ms/op
     p(99.9990) =     35.993 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.962 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  19.864 ms/op
                 existUser·p0.9999: 22.200 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.768 ms/op
                 existUser·p0.9999: 23.537 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  17.278 ms/op
                 existUser·p0.9999: 25.507 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289482
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6126 
    [ 2.500,  5.000) = 276570 
    [ 5.000,  7.500) = 5642 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 184 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     17.286 ms/op
     p(99.9900) =     24.316 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 10.386 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.009 ms/op
Iteration   1: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  19.546 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  20.083 ms/op
                 getUser·p0.9999: 25.411 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.164 ms/op
                 getUser·p0.99:   6.140 ms/op
                 getUser·p0.999:  17.126 ms/op
                 getUser·p0.9999: 27.535 ms/op
                 getUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282063
  mean =      3.403 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2101 
    [ 2.500,  5.000) = 270958 
    [ 5.000,  7.500) = 7778 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.376 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.356 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 9.703 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  19.924 ms/op
                 listUser·p0.9999: 26.863 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 3.850 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.396 ms/op
                 listUser·p0.9999: 16.466 ms/op
                 listUser·p1.00:   16.499 ms/op

Iteration   3: 3.950 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.290 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 15.793 ms/op
                 listUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244738
  mean =      3.920 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 236154 
    [ 5.000,  7.500) = 6589 
    [ 7.500, 10.000) = 1164 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     25.937 ms/op
     p(99.9990) =     27.430 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.568 ± 1.791  ops/ms
ClientPb.existUser                       thrpt       3   9.922 ± 3.505  ops/ms
ClientPb.getUser                         thrpt       3   9.179 ± 5.957  ops/ms
ClientPb.listUser                        thrpt       3   8.040 ± 3.493  ops/ms
ClientPb.createUser                       avgt       3   3.369 ± 1.801   ms/op
ClientPb.existUser                        avgt       3   3.238 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 1.173   ms/op
ClientPb.listUser                         avgt       3   3.896 ± 1.898   ms/op
ClientPb.createUser                     sample  279180   3.437 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.557           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.019           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110           ms/op
ClientPb.existUser                      sample  289482   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.054           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.286           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.316           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.640           ms/op
ClientPb.getUser                        sample  282063   3.403 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.376           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.345           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.443           ms/op
ClientPb.listUser                       sample  244738   3.920 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.713           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.937           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
