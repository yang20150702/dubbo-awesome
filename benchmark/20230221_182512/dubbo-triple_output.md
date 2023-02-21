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
# Warmup Iteration   1: 1.026 ops/ms
# Warmup Iteration   2: 2.120 ops/ms
# Warmup Iteration   3: 4.668 ops/ms
Iteration   1: 5.204 ops/ms
Iteration   2: 5.496 ops/ms
Iteration   3: 5.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.388 ±(99.9%) 2.929 ops/ms [Average]
  (min, avg, max) = (5.204, 5.388, 5.496), stdev = 0.161
  CI (99.9%): [2.459, 8.317] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.576 ops/ms
# Warmup Iteration   2: 4.360 ops/ms
# Warmup Iteration   3: 5.628 ops/ms
Iteration   1: 5.846 ops/ms
Iteration   2: 5.851 ops/ms
Iteration   3: 5.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.839 ±(99.9%) 0.295 ops/ms [Average]
  (min, avg, max) = (5.821, 5.839, 5.851), stdev = 0.016
  CI (99.9%): [5.545, 6.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.347 ops/ms
# Warmup Iteration   2: 4.050 ops/ms
# Warmup Iteration   3: 5.180 ops/ms
Iteration   1: 5.378 ops/ms
Iteration   2: 5.364 ops/ms
Iteration   3: 5.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.405 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (5.364, 5.405, 5.472), stdev = 0.059
  CI (99.9%): [4.337, 6.472] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.278 ops/ms
# Warmup Iteration   2: 3.780 ops/ms
# Warmup Iteration   3: 4.601 ops/ms
Iteration   1: 4.708 ops/ms
Iteration   2: 4.974 ops/ms
Iteration   3: 4.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.806 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (4.708, 4.806, 4.974), stdev = 0.146
  CI (99.9%): [2.146, 7.466] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.863 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 7.714 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.178 ±(99.9%) 0.009 ms/op
Iteration   1: 6.057 ±(99.9%) 0.008 ms/op
Iteration   2: 5.656 ±(99.9%) 0.013 ms/op
Iteration   3: 5.780 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.831 ±(99.9%) 3.748 ms/op [Average]
  (min, avg, max) = (5.656, 5.831, 6.057), stdev = 0.205
  CI (99.9%): [2.083, 9.579] (assumes normal distribution)


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
# Warmup Iteration   1: 18.115 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.004 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.543 ±(99.9%) 0.012 ms/op
Iteration   1: 5.609 ±(99.9%) 0.011 ms/op
Iteration   2: 5.584 ±(99.9%) 0.008 ms/op
Iteration   3: 5.437 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.543 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (5.437, 5.543, 5.609), stdev = 0.093
  CI (99.9%): [3.842, 7.244] (assumes normal distribution)


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
# Warmup Iteration   1: 19.338 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.000 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.088 ±(99.9%) 0.009 ms/op
Iteration   1: 5.917 ±(99.9%) 0.011 ms/op
Iteration   2: 5.802 ±(99.9%) 0.008 ms/op
Iteration   3: 5.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.883 ±(99.9%) 1.293 ms/op [Average]
  (min, avg, max) = (5.802, 5.883, 5.932), stdev = 0.071
  CI (99.9%): [4.590, 7.176] (assumes normal distribution)


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
# Warmup Iteration   1: 20.914 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 8.715 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.935 ±(99.9%) 0.013 ms/op
Iteration   1: 6.551 ±(99.9%) 0.012 ms/op
Iteration   2: 6.693 ±(99.9%) 0.012 ms/op
Iteration   3: 6.571 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.605 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (6.551, 6.605, 6.693), stdev = 0.077
  CI (99.9%): [5.202, 8.008] (assumes normal distribution)


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
# Warmup Iteration   1: 17.400 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 7.919 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.252 ±(99.9%) 0.033 ms/op
Iteration   1: 5.619 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   8.012 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 25.847 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 5.854 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.769 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.911 ms/op
                 createUser·p0.999:  27.603 ms/op
                 createUser·p0.9999: 29.413 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 5.871 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.395 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.479 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   12.485 ms/op
                 createUser·p0.999:  32.376 ms/op
                 createUser·p0.9999: 37.195 ms/op
                 createUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 166108
  mean =      5.779 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 39612 
    [ 5.000,  7.500) = 111972 
    [ 7.500, 10.000) = 11127 
    [10.000, 12.500) = 2145 
    [12.500, 15.000) = 767 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.380 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     22.639 ms/op
     p(99.9900) =     34.760 ms/op
     p(99.9990) =     37.662 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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
# Warmup Iteration   1: 17.470 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.640 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.020 ms/op
Iteration   1: 5.550 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.889 ms/op
                 existUser·p0.95:   7.832 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 28.425 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   2: 5.566 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.601 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.272 ms/op
                 existUser·p0.999:  27.165 ms/op
                 existUser·p0.9999: 31.990 ms/op
                 existUser·p1.00:   32.899 ms/op

Iteration   3: 5.627 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.650 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   7.307 ms/op
                 existUser·p0.95:   8.602 ms/op
                 existUser·p0.99:   11.370 ms/op
                 existUser·p0.999:  33.101 ms/op
                 existUser·p0.9999: 37.024 ms/op
                 existUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 171959
  mean =      5.581 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 65634 
    [ 5.000,  7.500) = 93182 
    [ 7.500, 10.000) = 10201 
    [10.000, 12.500) = 2176 
    [12.500, 15.000) = 480 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     20.416 ms/op
     p(99.9900) =     35.508 ms/op
     p(99.9990) =     37.644 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 20.170 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 7.582 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.871 ±(99.9%) 0.023 ms/op
Iteration   1: 5.523 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.245 ms/op
                 getUser·p0.50:   5.169 ms/op
                 getUser·p0.90:   6.906 ms/op
                 getUser·p0.95:   7.999 ms/op
                 getUser·p0.99:   10.830 ms/op
                 getUser·p0.999:  22.383 ms/op
                 getUser·p0.9999: 26.464 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 5.683 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.315 ms/op
                 getUser·p0.95:   8.372 ms/op
                 getUser·p0.99:   11.576 ms/op
                 getUser·p0.999:  29.614 ms/op
                 getUser·p0.9999: 33.317 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 5.674 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.184 ms/op
                 getUser·p0.99:   11.174 ms/op
                 getUser·p0.999:  25.556 ms/op
                 getUser·p0.9999: 28.499 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170515
  mean =      5.625 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 60547 
    [ 5.000,  7.500) = 96716 
    [ 7.500, 10.000) = 10148 
    [10.000, 12.500) = 2139 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.208 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     23.150 ms/op
     p(99.9900) =     32.461 ms/op
     p(99.9990) =     33.901 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 20.448 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 8.593 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.872 ±(99.9%) 0.029 ms/op
Iteration   1: 6.861 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.863 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.765 ms/op
                 listUser·p0.95:   10.109 ms/op
                 listUser·p0.99:   12.894 ms/op
                 listUser·p0.999:  25.854 ms/op
                 listUser·p0.9999: 34.581 ms/op
                 listUser·p1.00:   38.207 ms/op

Iteration   2: 6.668 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.342 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  30.805 ms/op
                 listUser·p0.9999: 38.945 ms/op
                 listUser·p1.00:   40.501 ms/op

Iteration   3: 6.759 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.386 ms/op
                 listUser·p0.999:  27.723 ms/op
                 listUser·p0.9999: 33.452 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141944
  mean =      6.762 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3561 
    [ 5.000, 10.000) = 131540 
    [10.000, 15.000) = 6184 
    [15.000, 20.000) = 322 
    [20.000, 25.000) = 122 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 86 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.425 ms/op
     p(50.0000) =      6.291 ms/op
     p(90.0000) =      8.552 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     13.042 ms/op
     p(99.9000) =     28.018 ms/op
     p(99.9900) =     36.740 ms/op
     p(99.9990) =     40.199 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.388 ± 2.929  ops/ms
ClientPb.existUser                       thrpt       3   5.839 ± 0.295  ops/ms
ClientPb.getUser                         thrpt       3   5.405 ± 1.068  ops/ms
ClientPb.listUser                        thrpt       3   4.806 ± 2.660  ops/ms
ClientPb.createUser                       avgt       3   5.831 ± 3.748   ms/op
ClientPb.existUser                        avgt       3   5.543 ± 1.701   ms/op
ClientPb.getUser                          avgt       3   5.883 ± 1.293   ms/op
ClientPb.listUser                         avgt       3   6.605 ± 1.403   ms/op
ClientPb.createUser                     sample  166108   5.779 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.380           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.600           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.639           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.760           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.749           ms/op
ClientPb.existUser                      sample  171959   5.581 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.249           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.416           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  170515   5.625 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.245           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.208           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.174           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  141944   6.762 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.425           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.945           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.042           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.018           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.740           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.501           ms/op
