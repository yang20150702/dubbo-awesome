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
# Warmup Iteration   1: 1.142 ops/ms
# Warmup Iteration   2: 2.506 ops/ms
# Warmup Iteration   3: 5.275 ops/ms
Iteration   1: 5.341 ops/ms
Iteration   2: 5.592 ops/ms
Iteration   3: 5.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.539 ±(99.9%) 3.255 ops/ms [Average]
  (min, avg, max) = (5.341, 5.539, 5.685), stdev = 0.178
  CI (99.9%): [2.284, 8.795] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.499 ops/ms
# Warmup Iteration   2: 4.191 ops/ms
# Warmup Iteration   3: 5.891 ops/ms
Iteration   1: 5.916 ops/ms
Iteration   2: 5.949 ops/ms
Iteration   3: 6.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.012 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (5.916, 6.012, 6.171), stdev = 0.138
  CI (99.9%): [3.487, 8.537] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.824 ops/ms
# Warmup Iteration   2: 5.076 ops/ms
# Warmup Iteration   3: 5.815 ops/ms
Iteration   1: 5.577 ops/ms
Iteration   2: 5.752 ops/ms
Iteration   3: 6.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.809 ±(99.9%) 4.842 ops/ms [Average]
  (min, avg, max) = (5.577, 5.809, 6.098), stdev = 0.265
  CI (99.9%): [0.967, 10.651] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.566 ops/ms
# Warmup Iteration   2: 4.329 ops/ms
# Warmup Iteration   3: 5.099 ops/ms
Iteration   1: 5.086 ops/ms
Iteration   2: 4.967 ops/ms
Iteration   3: 5.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.114 ±(99.9%) 2.973 ops/ms [Average]
  (min, avg, max) = (4.967, 5.114, 5.290), stdev = 0.163
  CI (99.9%): [2.141, 8.087] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.488 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.686 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.618 ±(99.9%) 0.010 ms/op
Iteration   1: 5.413 ±(99.9%) 0.010 ms/op
Iteration   2: 5.313 ±(99.9%) 0.013 ms/op
Iteration   3: 5.333 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.353 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (5.313, 5.353, 5.413), stdev = 0.053
  CI (99.9%): [4.386, 6.320] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 15.294 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.427 ±(99.9%) 0.005 ms/op
Iteration   1: 5.327 ±(99.9%) 0.013 ms/op
Iteration   2: 5.286 ±(99.9%) 0.007 ms/op
Iteration   3: 5.112 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.242 ±(99.9%) 2.090 ms/op [Average]
  (min, avg, max) = (5.112, 5.242, 5.327), stdev = 0.115
  CI (99.9%): [3.152, 7.332] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.966 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.304 ±(99.9%) 0.012 ms/op
Iteration   1: 5.373 ±(99.9%) 0.020 ms/op
Iteration   2: 5.361 ±(99.9%) 0.011 ms/op
Iteration   3: 5.380 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.371 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (5.361, 5.371, 5.380), stdev = 0.009
  CI (99.9%): [5.200, 5.543] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.206 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 8.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.318 ±(99.9%) 0.016 ms/op
Iteration   1: 6.177 ±(99.9%) 0.010 ms/op
Iteration   2: 6.295 ±(99.9%) 0.014 ms/op
Iteration   3: 6.061 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.178 ±(99.9%) 2.138 ms/op [Average]
  (min, avg, max) = (6.061, 6.178, 6.295), stdev = 0.117
  CI (99.9%): [4.040, 8.315] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.884 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.614 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.506 ±(99.9%) 0.038 ms/op
Iteration   1: 5.636 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   12.124 ms/op
                 createUser·p0.999:  23.921 ms/op
                 createUser·p0.9999: 31.828 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   2: 5.596 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   6.783 ms/op
                 createUser·p0.95:   7.569 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  16.805 ms/op
                 createUser·p0.9999: 26.528 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   3: 5.551 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   5.341 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.569 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  27.635 ms/op
                 createUser·p0.9999: 39.379 ms/op
                 createUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171510
  mean =      5.594 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 58703 
    [ 5.000, 10.000) = 110675 
    [10.000, 15.000) = 1587 
    [15.000, 20.000) = 258 
    [20.000, 25.000) = 132 
    [25.000, 30.000) = 104 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     23.904 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     39.996 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.279 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.397 ±(99.9%) 0.021 ms/op
Iteration   1: 5.366 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  23.233 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 5.289 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  23.953 ms/op
                 existUser·p0.9999: 30.241 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 5.248 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.835 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  15.778 ms/op
                 existUser·p0.9999: 28.371 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180923
  mean =      5.301 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 94331 
    [ 5.000,  7.500) = 76094 
    [ 7.500, 10.000) = 8155 
    [10.000, 12.500) = 1587 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     28.997 ms/op
     p(99.9990) =     31.300 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.268 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 6.537 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.681 ±(99.9%) 0.020 ms/op
Iteration   1: 5.431 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.580 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.660 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 25.301 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 5.440 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   7.504 ms/op
                 getUser·p0.99:   10.076 ms/op
                 getUser·p0.999:  14.500 ms/op
                 getUser·p0.9999: 26.554 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 5.381 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.602 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  25.679 ms/op
                 getUser·p0.9999: 33.229 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177055
  mean =      5.417 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 77265 
    [ 5.000,  7.500) = 90434 
    [ 7.500, 10.000) = 7266 
    [10.000, 12.500) = 1392 
    [12.500, 15.000) = 440 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.578 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     18.905 ms/op
     p(99.9900) =     32.253 ms/op
     p(99.9990) =     33.529 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.071 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.279 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 6.489 ±(99.9%) 0.027 ms/op
Iteration   1: 6.208 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.367 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  26.430 ms/op
                 listUser·p0.9999: 30.033 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 6.176 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.569 ms/op
                 listUser·p0.99:   12.177 ms/op
                 listUser·p0.999:  27.170 ms/op
                 listUser·p0.9999: 30.245 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   3: 6.247 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 28.861 ms/op
                 listUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154666
  mean =      6.210 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 13067 
    [ 5.000,  7.500) = 125657 
    [ 7.500, 10.000) = 12753 
    [10.000, 12.500) = 2052 
    [12.500, 15.000) = 571 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      7.537 ms/op
     p(95.0000) =      8.569 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.539 ± 3.255  ops/ms
ClientPb.existUser                       thrpt       3   6.012 ± 2.525  ops/ms
ClientPb.getUser                         thrpt       3   5.809 ± 4.842  ops/ms
ClientPb.listUser                        thrpt       3   5.114 ± 2.973  ops/ms
ClientPb.createUser                       avgt       3   5.353 ± 0.967   ms/op
ClientPb.existUser                        avgt       3   5.242 ± 2.090   ms/op
ClientPb.getUser                          avgt       3   5.371 ± 0.172   ms/op
ClientPb.listUser                         avgt       3   6.178 ± 2.138   ms/op
ClientPb.createUser                     sample  171510   5.594 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.453           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.904           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.831           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.042           ms/op
ClientPb.existUser                      sample  180923   5.301 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.686           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.668           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.371           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.997           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.326           ms/op
ClientPb.getUser                        sample  177055   5.417 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.290           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.136           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.338           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.905           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.253           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  154666   6.210 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.302           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.537           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.756           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.786           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.687           ms/op
