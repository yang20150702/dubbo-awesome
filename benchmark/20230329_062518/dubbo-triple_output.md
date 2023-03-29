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
# Warmup Iteration   1: 1.442 ops/ms
# Warmup Iteration   2: 3.294 ops/ms
# Warmup Iteration   3: 6.563 ops/ms
Iteration   1: 6.717 ops/ms
Iteration   2: 7.768 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.413 ±(99.9%) 10.998 ops/ms [Average]
  (min, avg, max) = (6.717, 7.413, 7.768), stdev = 0.603
  CI (99.9%): [≈ 0, 18.411] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 6.137 ops/ms
# Warmup Iteration   3: 7.685 ops/ms
Iteration   1: 8.054 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 7.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.974 ±(99.9%) 4.094 ops/ms [Average]
  (min, avg, max) = (7.720, 7.974, 8.147), stdev = 0.224
  CI (99.9%): [3.879, 12.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.925 ops/ms
# Warmup Iteration   2: 5.565 ops/ms
# Warmup Iteration   3: 7.430 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 7.758 ops/ms
Iteration   3: 7.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.703 ±(99.9%) 1.045 ops/ms [Average]
  (min, avg, max) = (7.644, 7.703, 7.758), stdev = 0.057
  CI (99.9%): [6.658, 8.749] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.063 ops/ms
# Warmup Iteration   2: 5.152 ops/ms
# Warmup Iteration   3: 6.435 ops/ms
Iteration   1: 6.325 ops/ms
Iteration   2: 6.739 ops/ms
Iteration   3: 6.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.566 ±(99.9%) 3.925 ops/ms [Average]
  (min, avg, max) = (6.325, 6.566, 6.739), stdev = 0.215
  CI (99.9%): [2.641, 10.491] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.814 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.269 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.785 ±(99.9%) 0.009 ms/op
Iteration   1: 4.154 ±(99.9%) 0.006 ms/op
Iteration   2: 4.079 ±(99.9%) 0.011 ms/op
Iteration   3: 4.191 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.141 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (4.079, 4.141, 4.191), stdev = 0.057
  CI (99.9%): [3.106, 5.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.859 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.918 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.005 ms/op
Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
Iteration   2: 4.021 ±(99.9%) 0.008 ms/op
Iteration   3: 3.815 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.920 ±(99.9%) 1.880 ms/op [Average]
  (min, avg, max) = (3.815, 3.920, 4.021), stdev = 0.103
  CI (99.9%): [2.040, 5.800] (assumes normal distribution)


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
# Warmup Iteration   1: 12.861 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.005 ms/op
Iteration   1: 4.285 ±(99.9%) 0.005 ms/op
Iteration   2: 3.981 ±(99.9%) 0.016 ms/op
Iteration   3: 4.138 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.135 ±(99.9%) 2.777 ms/op [Average]
  (min, avg, max) = (3.981, 4.135, 4.285), stdev = 0.152
  CI (99.9%): [1.358, 6.912] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.830 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.437 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.168 ±(99.9%) 0.008 ms/op
Iteration   1: 4.920 ±(99.9%) 0.011 ms/op
Iteration   2: 5.005 ±(99.9%) 0.006 ms/op
Iteration   3: 5.240 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.055 ±(99.9%) 3.031 ms/op [Average]
  (min, avg, max) = (4.920, 5.055, 5.240), stdev = 0.166
  CI (99.9%): [2.024, 8.086] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.754 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.271 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.738 ±(99.9%) 0.020 ms/op
Iteration   1: 4.297 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.812 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   8.217 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 35.694 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   2: 4.271 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.979 ms/op
                 createUser·p0.999:  26.051 ms/op
                 createUser·p0.9999: 30.000 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   3: 4.128 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.341 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  13.931 ms/op
                 createUser·p0.9999: 31.040 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 226740
  mean =      4.231 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 449 
    [ 2.500,  5.000) = 202230 
    [ 5.000,  7.500) = 21064 
    [ 7.500, 10.000) = 2154 
    [10.000, 12.500) = 521 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.812 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     25.322 ms/op
     p(99.9900) =     33.532 ms/op
     p(99.9990) =     36.385 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.448 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.013 ms/op
Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 25.403 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   2: 4.344 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.931 ms/op
                 existUser·p0.50:   4.010 ms/op
                 existUser·p0.90:   5.399 ms/op
                 existUser·p0.95:   6.447 ms/op
                 existUser·p0.99:   9.841 ms/op
                 existUser·p0.999:  25.434 ms/op
                 existUser·p0.9999: 29.021 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 4.177 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.825 ms/op
                 existUser·p0.99:   7.995 ms/op
                 existUser·p0.999:  17.793 ms/op
                 existUser·p0.9999: 32.987 ms/op
                 existUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 228687
  mean =      4.196 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 248 
    [ 2.500,  5.000) = 203760 
    [ 5.000,  7.500) = 20385 
    [ 7.500, 10.000) = 2873 
    [10.000, 12.500) = 992 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.716 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     31.630 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 14.776 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.687 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.570 ±(99.9%) 0.018 ms/op
Iteration   1: 4.542 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.096 ms/op
                 getUser·p0.90:   5.825 ms/op
                 getUser·p0.95:   7.324 ms/op
                 getUser·p0.99:   10.207 ms/op
                 getUser·p0.999:  25.559 ms/op
                 getUser·p0.9999: 28.344 ms/op
                 getUser·p1.00:   28.869 ms/op

Iteration   2: 3.979 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.950 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  15.024 ms/op
                 getUser·p0.9999: 38.142 ms/op
                 getUser·p1.00:   38.404 ms/op

Iteration   3: 4.107 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  11.651 ms/op
                 getUser·p0.9999: 30.167 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228734
  mean =      4.196 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 205493 
    [ 5.000,  7.500) = 18563 
    [ 7.500, 10.000) = 3402 
    [10.000, 12.500) = 754 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     24.242 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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
# Warmup Iteration   1: 16.234 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 5.899 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.118 ±(99.9%) 0.023 ms/op
Iteration   1: 5.229 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.685 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   10.773 ms/op
                 listUser·p0.999:  27.881 ms/op
                 listUser·p0.9999: 31.257 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   2: 4.785 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  21.211 ms/op
                 listUser·p0.9999: 28.156 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   3: 4.963 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   10.665 ms/op
                 listUser·p0.999:  18.530 ms/op
                 listUser·p0.9999: 20.090 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192502
  mean =      4.986 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 139534 
    [ 5.000,  7.500) = 44093 
    [ 7.500, 10.000) = 6836 
    [10.000, 12.500) = 1158 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 218 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.833 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     21.315 ms/op
     p(99.9900) =     29.753 ms/op
     p(99.9990) =     31.986 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.413 ± 10.998  ops/ms
ClientPb.existUser                       thrpt       3   7.974 ±  4.094  ops/ms
ClientPb.getUser                         thrpt       3   7.703 ±  1.045  ops/ms
ClientPb.listUser                        thrpt       3   6.566 ±  3.925  ops/ms
ClientPb.createUser                       avgt       3   4.141 ±  1.035   ms/op
ClientPb.existUser                        avgt       3   3.920 ±  1.880   ms/op
ClientPb.getUser                          avgt       3   4.135 ±  2.777   ms/op
ClientPb.listUser                         avgt       3   5.055 ±  3.031   ms/op
ClientPb.createUser                     sample  226740   4.231 ±  0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.812            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.990            ms/op
ClientPb.createUser:createUser·p0.90    sample           5.046            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.800            ms/op
ClientPb.createUser:createUser·p0.99    sample           8.036            ms/op
ClientPb.createUser:createUser·p0.999   sample          25.322            ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.532            ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438            ms/op
ClientPb.existUser                      sample  228687   4.196 ±  0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.716            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.916            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.079            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.013            ms/op
ClientPb.existUser:existUser·p0.99      sample           8.782            ms/op
ClientPb.existUser:existUser·p0.999     sample          18.481            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.630            ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914            ms/op
ClientPb.getUser                        sample  228734   4.196 ±  0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.085            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.916            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.014            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.833            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.815            ms/op
ClientPb.getUser:getUser·p0.999         sample          24.242            ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.045            ms/op
ClientPb.getUser:getUser·p1.00          sample          38.404            ms/op
ClientPb.listUser                       sample  192502   4.986 ±  0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.833            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.833            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.315            ms/op
ClientPb.listUser:listUser·p0.99        sample          10.109            ms/op
ClientPb.listUser:listUser·p0.999       sample          21.315            ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.753            ms/op
ClientPb.listUser:listUser·p1.00        sample          32.440            ms/op
