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
# Warmup Iteration   1: 1.371 ops/ms
# Warmup Iteration   2: 2.942 ops/ms
# Warmup Iteration   3: 6.055 ops/ms
Iteration   1: 6.903 ops/ms
Iteration   2: 6.839 ops/ms
Iteration   3: 7.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.926 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (6.839, 6.926, 7.035), stdev = 0.100
  CI (99.9%): [5.105, 8.746] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.717 ops/ms
# Warmup Iteration   2: 5.165 ops/ms
# Warmup Iteration   3: 7.031 ops/ms
Iteration   1: 7.056 ops/ms
Iteration   2: 6.803 ops/ms
Iteration   3: 7.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.987 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (6.803, 6.987, 7.102), stdev = 0.161
  CI (99.9%): [4.042, 9.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.935 ops/ms
# Warmup Iteration   2: 5.255 ops/ms
# Warmup Iteration   3: 6.727 ops/ms
Iteration   1: 6.768 ops/ms
Iteration   2: 6.741 ops/ms
Iteration   3: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.753 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (6.741, 6.753, 6.768), stdev = 0.014
  CI (99.9%): [6.498, 7.008] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.751 ops/ms
# Warmup Iteration   2: 4.454 ops/ms
# Warmup Iteration   3: 5.771 ops/ms
Iteration   1: 5.757 ops/ms
Iteration   2: 5.609 ops/ms
Iteration   3: 5.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.624 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (5.505, 5.624, 5.757), stdev = 0.127
  CI (99.9%): [3.314, 7.933] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.896 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.710 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.985 ±(99.9%) 0.006 ms/op
Iteration   1: 5.296 ±(99.9%) 0.007 ms/op
Iteration   2: 4.752 ±(99.9%) 0.018 ms/op
Iteration   3: 4.956 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.001 ±(99.9%) 5.015 ms/op [Average]
  (min, avg, max) = (4.752, 5.001, 5.296), stdev = 0.275
  CI (99.9%): [≈ 0, 10.016] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.613 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.012 ms/op
Iteration   1: 4.305 ±(99.9%) 0.007 ms/op
Iteration   2: 4.388 ±(99.9%) 0.011 ms/op
Iteration   3: 4.364 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.352 ±(99.9%) 0.784 ms/op [Average]
  (min, avg, max) = (4.305, 4.352, 4.388), stdev = 0.043
  CI (99.9%): [3.568, 5.137] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.061 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.673 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.003 ms/op
Iteration   1: 4.764 ±(99.9%) 0.005 ms/op
Iteration   2: 4.489 ±(99.9%) 0.005 ms/op
Iteration   3: 4.458 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.570 ±(99.9%) 3.071 ms/op [Average]
  (min, avg, max) = (4.458, 4.570, 4.764), stdev = 0.168
  CI (99.9%): [1.499, 7.641] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 15.662 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.506 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.007 ms/op
Iteration   1: 5.363 ±(99.9%) 0.008 ms/op
Iteration   2: 5.349 ±(99.9%) 0.008 ms/op
Iteration   3: 5.219 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.310 ±(99.9%) 1.453 ms/op [Average]
  (min, avg, max) = (5.219, 5.310, 5.363), stdev = 0.080
  CI (99.9%): [3.858, 6.763] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 15.838 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 5.914 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.024 ms/op
Iteration   1: 4.255 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.009 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.005 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  24.305 ms/op
                 createUser·p0.9999: 29.948 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   2: 4.417 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  13.855 ms/op
                 createUser·p0.9999: 28.656 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   3: 4.734 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.750 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  28.934 ms/op
                 createUser·p0.9999: 32.784 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 215173
  mean =      4.460 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 245 
    [ 2.500,  5.000) = 177952 
    [ 5.000,  7.500) = 33357 
    [ 7.500, 10.000) = 2843 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      8.227 ms/op
     p(99.9000) =     25.592 ms/op
     p(99.9900) =     31.473 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.375 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.650 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.937 ±(99.9%) 0.021 ms/op
Iteration   1: 4.713 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  14.732 ms/op
                 existUser·p0.9999: 34.814 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   2: 4.598 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.710 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   9.093 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 34.082 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   3: 4.652 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.948 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   10.174 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 35.652 ms/op
                 existUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 206087
  mean =      4.654 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 153038 
    [ 5.000,  7.500) = 46428 
    [ 7.500, 10.000) = 4796 
    [10.000, 12.500) = 1110 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 69 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.874 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      9.634 ms/op
     p(99.9000) =     17.361 ms/op
     p(99.9900) =     34.720 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 14.589 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.018 ms/op
Iteration   1: 5.084 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   6.947 ms/op
                 getUser·p0.95:   8.029 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  26.742 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   2: 4.632 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   4.456 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.398 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  15.942 ms/op
                 getUser·p0.9999: 31.931 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   3: 4.550 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.335 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  15.044 ms/op
                 getUser·p0.9999: 39.254 ms/op
                 getUser·p1.00:   39.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 202385
  mean =      4.744 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 152277 
    [ 5.000,  7.500) = 42113 
    [ 7.500, 10.000) = 5994 
    [10.000, 12.500) = 1218 
    [12.500, 15.000) = 381 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 114 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     37.356 ms/op
     p(99.9990) =     39.518 ms/op
     p(99.9999) =     39.846 ms/op
    p(100.0000) =     39.846 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.133 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 6.924 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.584 ±(99.9%) 0.023 ms/op
Iteration   1: 5.594 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.217 ms/op
                 listUser·p0.99:   10.732 ms/op
                 listUser·p0.999:  27.066 ms/op
                 listUser·p0.9999: 29.491 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 5.313 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.007 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.226 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  27.623 ms/op
                 listUser·p0.9999: 33.351 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 5.425 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   7.930 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  18.846 ms/op
                 listUser·p0.9999: 21.907 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 176308
  mean =      5.442 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 87009 
    [ 5.000,  7.500) = 77850 
    [ 7.500, 10.000) = 9235 
    [10.000, 12.500) = 1453 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.954 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     31.330 ms/op
     p(99.9990) =     33.635 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.926 ± 1.821  ops/ms
ClientPb.existUser                       thrpt       3   6.987 ± 2.945  ops/ms
ClientPb.getUser                         thrpt       3   6.753 ± 0.255  ops/ms
ClientPb.listUser                        thrpt       3   5.624 ± 2.309  ops/ms
ClientPb.createUser                       avgt       3   5.001 ± 5.015   ms/op
ClientPb.existUser                        avgt       3   4.352 ± 0.784   ms/op
ClientPb.getUser                          avgt       3   4.570 ± 3.071   ms/op
ClientPb.listUser                         avgt       3   5.310 ± 1.453   ms/op
ClientPb.createUser                     sample  215173   4.460 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.528           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.227           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.592           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.473           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  206087   4.654 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.634           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.361           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.720           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.307           ms/op
ClientPb.getUser                        sample  202385   4.744 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.952           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.956           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.152           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.510           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.356           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.846           ms/op
ClientPb.listUser                       sample  176308   5.442 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.954           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.355           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.247           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.330           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
