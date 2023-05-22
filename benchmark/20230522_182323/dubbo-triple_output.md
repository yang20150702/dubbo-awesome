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
# Warmup Iteration   1: 2.481 ops/ms
# Warmup Iteration   2: 6.352 ops/ms
# Warmup Iteration   3: 9.022 ops/ms
Iteration   1: 9.524 ops/ms
Iteration   2: 9.862 ops/ms
Iteration   3: 10.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.818 ±(99.9%) 5.017 ops/ms [Average]
  (min, avg, max) = (9.524, 9.818, 10.068), stdev = 0.275
  CI (99.9%): [4.801, 14.834] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ops/ms
# Warmup Iteration   2: 9.010 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.666 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.619 ±(99.9%) 2.862 ops/ms [Average]
  (min, avg, max) = (10.444, 10.619, 10.746), stdev = 0.157
  CI (99.9%): [7.757, 13.480] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.385 ops/ms
# Warmup Iteration   2: 8.939 ops/ms
# Warmup Iteration   3: 9.691 ops/ms
Iteration   1: 9.719 ops/ms
Iteration   2: 9.853 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.860 ±(99.9%) 2.635 ops/ms [Average]
  (min, avg, max) = (9.719, 9.860, 10.007), stdev = 0.144
  CI (99.9%): [7.225, 12.494] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 7.505 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.380 ±(99.9%) 2.026 ops/ms [Average]
  (min, avg, max) = (8.294, 8.380, 8.506), stdev = 0.111
  CI (99.9%): [6.354, 10.406] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.002 ms/op
Iteration   1: 3.176 ±(99.9%) 0.007 ms/op
Iteration   2: 3.207 ±(99.9%) 0.006 ms/op
Iteration   3: 3.282 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.176, 3.222, 3.282), stdev = 0.054
  CI (99.9%): [2.228, 4.215] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.042 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.016, 3.042, 3.087), stdev = 0.039
  CI (99.9%): [2.330, 3.754] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.004 ms/op
Iteration   1: 3.238 ±(99.9%) 0.004 ms/op
Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
Iteration   3: 3.276 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.238, 3.258, 3.276), stdev = 0.019
  CI (99.9%): [2.906, 3.609] (assumes normal distribution)


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
# Warmup Iteration   1: 9.139 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.007 ms/op
Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
Iteration   2: 3.697 ±(99.9%) 0.013 ms/op
Iteration   3: 3.761 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.697, 3.745, 3.777), stdev = 0.042
  CI (99.9%): [2.974, 4.516] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.299 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.069 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  12.239 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  20.557 ms/op
                 createUser·p0.9999: 23.334 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 23.273 ms/op
                 createUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295359
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12385 
    [ 2.500,  5.000) = 277341 
    [ 5.000,  7.500) = 4653 
    [ 7.500, 10.000) = 490 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     16.071 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.777 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 7.690 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
Iteration   1: 3.100 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.812 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 22.370 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  11.789 ms/op
                 existUser·p0.9999: 21.754 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 20.116 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305507
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27637 
    [ 2.500,  5.000) = 274094 
    [ 5.000,  7.500) = 3199 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     21.656 ms/op
     p(99.9990) =     22.870 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.767 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.010 ms/op
Iteration   1: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  19.972 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.299 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 23.406 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.343 ms/op
                 getUser·p0.9999: 24.448 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294213
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13067 
    [ 2.500,  5.000) = 274244 
    [ 5.000,  7.500) = 6085 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     16.799 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     25.998 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.650 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.012 ms/op
Iteration   1: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.484 ms/op
                 listUser·p0.9999: 20.759 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.736 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.409 ms/op
                 listUser·p0.9999: 20.265 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255515
  mean =      3.752 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 249249 
    [ 5.000,  7.500) = 4639 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.818 ± 5.017  ops/ms
ClientPb.existUser                       thrpt       3  10.619 ± 2.862  ops/ms
ClientPb.getUser                         thrpt       3   9.860 ± 2.635  ops/ms
ClientPb.listUser                        thrpt       3   8.380 ± 2.026  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 0.993   ms/op
ClientPb.existUser                        avgt       3   3.042 ± 0.712   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 0.351   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 0.771   ms/op
ClientPb.createUser                     sample  295359   3.245 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.929           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.645           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.071           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.134           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  305507   3.138 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.656           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  294213   3.261 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.799           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.773           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.575           ms/op
ClientPb.listUser                       sample  255515   3.752 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.495           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.103           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.955           ms/op
