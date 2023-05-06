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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 6.110 ops/ms
# Warmup Iteration   3: 8.565 ops/ms
Iteration   1: 9.246 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 9.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.295 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (9.204, 9.295, 9.434), stdev = 0.123
  CI (99.9%): [7.060, 11.530] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.468 ops/ms
# Warmup Iteration   3: 9.627 ops/ms
Iteration   1: 9.883 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.830 ±(99.9%) 2.186 ops/ms [Average]
  (min, avg, max) = (9.693, 9.830, 9.914), stdev = 0.120
  CI (99.9%): [7.644, 12.016] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.005 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 9.169 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.283 ±(99.9%) 6.492 ops/ms [Average]
  (min, avg, max) = (9.076, 9.283, 9.694), stdev = 0.356
  CI (99.9%): [2.791, 15.775] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.665 ops/ms
# Warmup Iteration   2: 6.736 ops/ms
# Warmup Iteration   3: 7.854 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 7.933 ops/ms
Iteration   3: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.094 ±(99.9%) 3.828 ops/ms [Average]
  (min, avg, max) = (7.933, 8.094, 8.332), stdev = 0.210
  CI (99.9%): [4.266, 11.922] (assumes normal distribution)


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
# Warmup Iteration   1: 8.538 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
Iteration   1: 3.339 ±(99.9%) 0.007 ms/op
Iteration   2: 3.399 ±(99.9%) 0.008 ms/op
Iteration   3: 3.262 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.333 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (3.262, 3.333, 3.399), stdev = 0.069
  CI (99.9%): [2.077, 4.589] (assumes normal distribution)


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
# Warmup Iteration   1: 8.817 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.302 ±(99.9%) 0.004 ms/op
Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
Iteration   3: 3.333 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.268, 3.301, 3.333), stdev = 0.032
  CI (99.9%): [2.711, 3.892] (assumes normal distribution)


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
# Warmup Iteration   1: 9.463 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.006 ms/op
Iteration   1: 3.504 ±(99.9%) 0.007 ms/op
Iteration   2: 3.426 ±(99.9%) 0.009 ms/op
Iteration   3: 3.392 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.392, 3.441, 3.504), stdev = 0.058
  CI (99.9%): [2.391, 4.491] (assumes normal distribution)


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
# Warmup Iteration   1: 9.548 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.831 ±(99.9%) 0.015 ms/op
Iteration   2: 3.803 ±(99.9%) 0.004 ms/op
Iteration   3: 3.955 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.863 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.803, 3.863, 3.955), stdev = 0.081
  CI (99.9%): [2.389, 5.337] (assumes normal distribution)


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
# Warmup Iteration   1: 10.538 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.014 ms/op
Iteration   1: 3.316 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  20.382 ms/op
                 createUser·p0.9999: 22.392 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 26.273 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   3: 3.294 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  16.151 ms/op
                 createUser·p0.9999: 23.864 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285905
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9178 
    [ 2.500,  5.000) = 270419 
    [ 5.000,  7.500) = 5286 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     19.860 ms/op
     p(99.9900) =     25.534 ms/op
     p(99.9990) =     26.514 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 7.285 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.349 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.644 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 21.813 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  8.089 ms/op
                 existUser·p0.9999: 24.019 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.359 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 27.809 ms/op
                 existUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289431
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14185 
    [ 2.500,  5.000) = 267482 
    [ 5.000,  7.500) = 6847 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     26.282 ms/op
     p(99.9990) =     28.420 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 10.467 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  18.543 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   2: 3.398 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  12.015 ms/op
                 getUser·p0.9999: 23.959 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  23.725 ms/op
                 getUser·p0.9999: 31.359 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277991
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9279 
    [ 2.500,  5.000) = 261216 
    [ 5.000,  7.500) = 6520 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     31.767 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 10.240 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.014 ms/op
Iteration   1: 4.112 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  22.716 ms/op
                 listUser·p0.9999: 26.755 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   2: 4.030 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.672 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237547
  mean =      4.038 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 227576 
    [ 5.000,  7.500) = 7449 
    [ 7.500, 10.000) = 1732 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     23.798 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.295 ± 2.235  ops/ms
ClientPb.existUser                       thrpt       3   9.830 ± 2.186  ops/ms
ClientPb.getUser                         thrpt       3   9.283 ± 6.492  ops/ms
ClientPb.listUser                        thrpt       3   8.094 ± 3.828  ops/ms
ClientPb.createUser                       avgt       3   3.333 ± 1.256   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 0.591   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 1.050   ms/op
ClientPb.listUser                         avgt       3   3.863 ± 1.474   ms/op
ClientPb.createUser                     sample  285905   3.359 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.376           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.860           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.534           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.575           ms/op
ClientPb.existUser                      sample  289431   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.005           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.185           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.649           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  277991   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.249           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.599           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.869           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  237547   4.038 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.821           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.705           ms/op
