# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 11.906 ops/ms
# Warmup Iteration   3: 12.340 ops/ms
Iteration   1: 12.745 ops/ms
Iteration   2: 12.728 ops/ms
Iteration   3: 12.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.725 ±(99.9%) 0.380 ops/ms [Average]
  (min, avg, max) = (12.703, 12.725, 12.745), stdev = 0.021
  CI (99.9%): [12.346, 13.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.367 ops/ms
# Warmup Iteration   2: 13.257 ops/ms
# Warmup Iteration   3: 13.067 ops/ms
Iteration   1: 13.271 ops/ms
Iteration   2: 13.155 ops/ms
Iteration   3: 13.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.174 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (13.096, 13.174, 13.271), stdev = 0.089
  CI (99.9%): [11.548, 14.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.607 ops/ms
# Warmup Iteration   2: 12.321 ops/ms
# Warmup Iteration   3: 12.713 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 12.824 ops/ms
Iteration   3: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.784 ±(99.9%) 0.865 ops/ms [Average]
  (min, avg, max) = (12.732, 12.784, 12.824), stdev = 0.047
  CI (99.9%): [11.919, 13.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ops/ms
# Warmup Iteration   2: 10.361 ops/ms
# Warmup Iteration   3: 10.610 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.667 ±(99.9%) 0.316 ops/ms [Average]
  (min, avg, max) = (10.648, 10.667, 10.679), stdev = 0.017
  CI (99.9%): [10.352, 10.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.037 ms/op [Average]
  (min, avg, max) = (2.504, 2.506, 2.508), stdev = 0.002
  CI (99.9%): [2.469, 2.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.443, 2.460, 2.484), stdev = 0.021
  CI (99.9%): [2.077, 2.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.448, 2.461, 2.476), stdev = 0.014
  CI (99.9%): [2.201, 2.720] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.719 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
Iteration   3: 3.022 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.024 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.008, 3.024, 3.043), stdev = 0.018
  CI (99.9%): [2.702, 3.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.722 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.697 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.677 ms/op
                 createUser·p0.999:  9.452 ms/op
                 createUser·p0.9999: 14.891 ms/op
                 createUser·p1.00:   15.712 ms/op

Iteration   3: 2.569 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  8.306 ms/op
                 createUser·p0.9999: 11.867 ms/op
                 createUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374994
  mean =      2.557 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 179960 
    [ 2.500,  3.750) = 190370 
    [ 3.750,  5.000) = 3735 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     14.361 ms/op
     p(99.9990) =     15.671 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.712 ms/op
                 existUser·p0.999:  6.084 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  8.583 ms/op
                 existUser·p0.9999: 12.732 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  8.789 ms/op
                 existUser·p0.9999: 11.268 ms/op
                 existUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385492
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 193322 
    [ 2.500,  3.750) = 188425 
    [ 3.750,  5.000) = 2812 
    [ 5.000,  6.250) = 479 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.661 ms/op
     p(99.9900) =     12.820 ms/op
     p(99.9990) =     13.536 ms/op
     p(99.9999) =     13.681 ms/op
    p(100.0000) =     13.681 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.615 ms/op
                 getUser·p0.999:  7.592 ms/op
                 getUser·p0.9999: 13.337 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.022 ms/op
                 getUser·p0.999:  5.751 ms/op
                 getUser·p0.9999: 13.242 ms/op
                 getUser·p1.00:   13.517 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  6.567 ms/op
                 getUser·p0.9999: 11.730 ms/op
                 getUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387754
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 193343 
    [ 2.500,  3.750) = 190589 
    [ 3.750,  5.000) = 2962 
    [ 5.000,  6.250) = 401 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.847 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 13.419 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.743 ms/op
                 listUser·p0.9999: 11.608 ms/op
                 listUser·p1.00:   12.190 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.345 ms/op
                 listUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316755
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 90696 
    [ 2.500,  3.750) = 185765 
    [ 3.750,  5.000) = 32456 
    [ 5.000,  6.250) = 6167 
    [ 6.250,  7.500) = 716 
    [ 7.500,  8.750) = 377 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.425 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     14.268 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.725 ± 0.380  ops/ms
ClientPb.existUser                       thrpt       3  13.174 ± 1.626  ops/ms
ClientPb.getUser                         thrpt       3  12.784 ± 0.865  ops/ms
ClientPb.listUser                        thrpt       3  10.667 ± 0.316  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.037   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.383   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   3.024 ± 0.322   ms/op
ClientPb.createUser                     sample  374994   2.557 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.796           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.361           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.712           ms/op
ClientPb.existUser                      sample  385492   2.488 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.881           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.661           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.820           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.681           ms/op
ClientPb.getUser                        sample  387754   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.169           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.238           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  316755   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.813           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.425           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.483           ms/op
