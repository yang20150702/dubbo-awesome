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
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 6.245 ops/ms
# Warmup Iteration   3: 8.798 ops/ms
Iteration   1: 9.554 ops/ms
Iteration   2: 9.795 ops/ms
Iteration   3: 9.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.657 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (9.554, 9.657, 9.795), stdev = 0.124
  CI (99.9%): [7.394, 11.920] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 8.999 ops/ms
# Warmup Iteration   3: 9.889 ops/ms
Iteration   1: 10.005 ops/ms
Iteration   2: 9.607 ops/ms
Iteration   3: 9.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.695 ±(99.9%) 5.040 ops/ms [Average]
  (min, avg, max) = (9.474, 9.695, 10.005), stdev = 0.276
  CI (99.9%): [4.655, 14.736] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
# Warmup Iteration   2: 8.586 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.732 ops/ms
Iteration   2: 9.942 ops/ms
Iteration   3: 9.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.773 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (9.646, 9.773, 9.942), stdev = 0.152
  CI (99.9%): [6.993, 12.554] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.064 ops/ms
# Warmup Iteration   2: 7.686 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.261 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (8.124, 8.261, 8.341), stdev = 0.120
  CI (99.9%): [6.078, 10.444] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.854 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.010 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
Iteration   3: 3.282 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.261 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.236, 3.261, 3.282), stdev = 0.023
  CI (99.9%): [2.838, 3.683] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.017 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.006 ms/op
Iteration   1: 3.256 ±(99.9%) 0.003 ms/op
Iteration   2: 3.219 ±(99.9%) 0.004 ms/op
Iteration   3: 3.250 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.241 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.219, 3.241, 3.256), stdev = 0.020
  CI (99.9%): [2.876, 3.607] (assumes normal distribution)


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
# Warmup Iteration   1: 8.938 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.004 ms/op
Iteration   1: 3.429 ±(99.9%) 0.008 ms/op
Iteration   2: 3.268 ±(99.9%) 0.005 ms/op
Iteration   3: 3.260 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.319 ±(99.9%) 1.743 ms/op [Average]
  (min, avg, max) = (3.260, 3.319, 3.429), stdev = 0.096
  CI (99.9%): [1.576, 5.062] (assumes normal distribution)


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
# Warmup Iteration   1: 9.341 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.005 ms/op
Iteration   1: 3.830 ±(99.9%) 0.010 ms/op
Iteration   2: 3.790 ±(99.9%) 0.007 ms/op
Iteration   3: 3.837 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.819 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.790, 3.819, 3.837), stdev = 0.025
  CI (99.9%): [3.357, 4.280] (assumes normal distribution)


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
# Warmup Iteration   1: 10.213 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.009 ms/op
Iteration   1: 3.481 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.992 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  19.719 ms/op
                 createUser·p0.9999: 21.981 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  22.317 ms/op
                 createUser·p0.9999: 32.845 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  19.489 ms/op
                 createUser·p0.9999: 27.000 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275396
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13485 
    [ 2.500,  5.000) = 251238 
    [ 5.000,  7.500) = 9400 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     19.582 ms/op
     p(99.9900) =     31.931 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 7.759 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
Iteration   1: 3.250 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.849 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 25.052 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295434
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16597 
    [ 2.500,  5.000) = 273570 
    [ 5.000,  7.500) = 4429 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     25.367 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 8.460 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.013 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.376 ms/op
                 getUser·p0.999:  14.717 ms/op
                 getUser·p0.9999: 25.145 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.417 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.672 ms/op
                 getUser·p0.999:  22.227 ms/op
                 getUser·p0.9999: 24.630 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.915 ms/op
                 getUser·p0.95:   4.345 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  9.773 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283558
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8032 
    [ 2.500,  5.000) = 267568 
    [ 5.000,  7.500) = 7039 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.154 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 9.585 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
Iteration   1: 4.003 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.606 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  21.616 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.392 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  15.606 ms/op
                 listUser·p0.9999: 18.465 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.377 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 15.880 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240321
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 229781 
    [ 5.000,  7.500) = 7846 
    [ 7.500, 10.000) = 1708 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 395 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     24.148 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.657 ± 2.263  ops/ms
ClientPb.existUser                       thrpt       3   9.695 ± 5.040  ops/ms
ClientPb.getUser                         thrpt       3   9.773 ± 2.781  ops/ms
ClientPb.listUser                        thrpt       3   8.261 ± 2.183  ops/ms
ClientPb.createUser                       avgt       3   3.261 ± 0.423   ms/op
ClientPb.existUser                        avgt       3   3.241 ± 0.365   ms/op
ClientPb.getUser                          avgt       3   3.319 ± 1.743   ms/op
ClientPb.listUser                         avgt       3   3.819 ± 0.462   ms/op
ClientPb.createUser                     sample  275396   3.486 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.773           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.582           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  295434   3.249 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.988           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.510           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.952           ms/op
ClientPb.getUser                        sample  283558   3.383 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.798           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.969           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  240321   3.994 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.377           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.148           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
