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
# Warmup Iteration   1: 1.782 ops/ms
# Warmup Iteration   2: 4.443 ops/ms
# Warmup Iteration   3: 7.773 ops/ms
Iteration   1: 8.399 ops/ms
Iteration   2: 8.185 ops/ms
Iteration   3: 8.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.320 ±(99.9%) 2.147 ops/ms [Average]
  (min, avg, max) = (8.185, 8.320, 8.399), stdev = 0.118
  CI (99.9%): [6.173, 10.467] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.465 ops/ms
# Warmup Iteration   2: 6.989 ops/ms
# Warmup Iteration   3: 8.187 ops/ms
Iteration   1: 8.950 ops/ms
Iteration   2: 8.680 ops/ms
Iteration   3: 8.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.836 ±(99.9%) 2.555 ops/ms [Average]
  (min, avg, max) = (8.680, 8.836, 8.950), stdev = 0.140
  CI (99.9%): [6.281, 11.391] (assumes normal distribution)


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
# Warmup Iteration   1: 2.742 ops/ms
# Warmup Iteration   2: 7.568 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 9.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.428 ±(99.9%) 9.960 ops/ms [Average]
  (min, avg, max) = (7.962, 8.428, 9.029), stdev = 0.546
  CI (99.9%): [≈ 0, 18.388] (assumes normal distribution)


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
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 6.262 ops/ms
# Warmup Iteration   3: 6.962 ops/ms
Iteration   1: 7.070 ops/ms
Iteration   2: 7.058 ops/ms
Iteration   3: 7.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.116 ±(99.9%) 1.656 ops/ms [Average]
  (min, avg, max) = (7.058, 7.116, 7.221), stdev = 0.091
  CI (99.9%): [5.460, 8.772] (assumes normal distribution)


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
# Warmup Iteration   1: 10.637 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.009 ms/op
Iteration   1: 4.155 ±(99.9%) 0.006 ms/op
Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
Iteration   3: 3.981 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.013 ±(99.9%) 2.361 ms/op [Average]
  (min, avg, max) = (3.903, 4.013, 4.155), stdev = 0.129
  CI (99.9%): [1.652, 6.374] (assumes normal distribution)


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
# Warmup Iteration   1: 8.833 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.003 ms/op
Iteration   1: 3.474 ±(99.9%) 0.011 ms/op
Iteration   2: 3.757 ±(99.9%) 0.011 ms/op
Iteration   3: 3.648 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.626 ±(99.9%) 2.607 ms/op [Average]
  (min, avg, max) = (3.474, 3.626, 3.757), stdev = 0.143
  CI (99.9%): [1.019, 6.233] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.301 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.308 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.006 ms/op
Iteration   1: 3.707 ±(99.9%) 0.005 ms/op
Iteration   2: 3.856 ±(99.9%) 0.004 ms/op
Iteration   3: 3.805 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.790 ±(99.9%) 1.378 ms/op [Average]
  (min, avg, max) = (3.707, 3.790, 3.856), stdev = 0.076
  CI (99.9%): [2.411, 5.168] (assumes normal distribution)


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
# Warmup Iteration   1: 15.225 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.012 ms/op
Iteration   1: 4.332 ±(99.9%) 0.013 ms/op
Iteration   2: 4.231 ±(99.9%) 0.012 ms/op
Iteration   3: 4.200 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.254 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (4.200, 4.254, 4.332), stdev = 0.069
  CI (99.9%): [2.991, 5.517] (assumes normal distribution)


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
# Warmup Iteration   1: 13.791 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.963 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.019 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.085 ms/op
                 createUser·p0.999:  11.000 ms/op
                 createUser·p0.9999: 24.267 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.635 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 26.982 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.626 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.452 ms/op
                 createUser·p0.999:  25.653 ms/op
                 createUser·p0.9999: 32.459 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260273
  mean =      3.686 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5208 
    [ 2.500,  5.000) = 246232 
    [ 5.000,  7.500) = 7459 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     21.520 ms/op
     p(99.9900) =     30.371 ms/op
     p(99.9990) =     33.233 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 9.886 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.670 ±(99.9%) 0.011 ms/op
Iteration   1: 3.541 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  9.767 ms/op
                 existUser·p0.9999: 33.618 ms/op
                 existUser·p1.00:   34.472 ms/op

Iteration   2: 3.654 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  21.164 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.293 ms/op

Iteration   3: 3.606 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   6.271 ms/op
                 existUser·p0.999:  10.737 ms/op
                 existUser·p0.9999: 35.848 ms/op
                 existUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 266509
  mean =      3.600 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2004 
    [ 2.500,  5.000) = 257501 
    [ 5.000,  7.500) = 5782 
    [ 7.500, 10.000) = 810 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 71 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     11.985 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     36.198 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.781 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.014 ms/op
Iteration   1: 3.706 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  17.105 ms/op
                 getUser·p0.9999: 25.735 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 3.586 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  26.045 ms/op
                 getUser·p0.9999: 43.325 ms/op
                 getUser·p1.00:   44.302 ms/op

Iteration   3: 3.761 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  23.758 ms/op
                 getUser·p0.9999: 30.622 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 260483
  mean =      3.683 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 252441 
    [ 5.000, 10.000) = 7495 
    [10.000, 15.000) = 236 
    [15.000, 20.000) = 55 
    [20.000, 25.000) = 86 
    [25.000, 30.000) = 121 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     17.974 ms/op
     p(99.9900) =     42.402 ms/op
     p(99.9990) =     43.581 ms/op
     p(99.9999) =     44.302 ms/op
    p(100.0000) =     44.302 ms/op


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
# Warmup Iteration   1: 12.853 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.235 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.493 ±(99.9%) 0.015 ms/op
Iteration   1: 4.674 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  24.853 ms/op
                 listUser·p0.9999: 28.312 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.722 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   8.894 ms/op
                 listUser·p0.999:  18.818 ms/op
                 listUser·p0.9999: 22.232 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.565 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206355
  mean =      4.653 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 172260 
    [ 5.000,  7.500) = 29050 
    [ 7.500, 10.000) = 3712 
    [10.000, 12.500) = 615 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =      8.756 ms/op
     p(99.9000) =     20.272 ms/op
     p(99.9900) =     27.144 ms/op
     p(99.9990) =     28.811 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.320 ± 2.147  ops/ms
ClientPb.existUser                       thrpt       3   8.836 ± 2.555  ops/ms
ClientPb.getUser                         thrpt       3   8.428 ± 9.960  ops/ms
ClientPb.listUser                        thrpt       3   7.116 ± 1.656  ops/ms
ClientPb.createUser                       avgt       3   4.013 ± 2.361   ms/op
ClientPb.existUser                        avgt       3   3.626 ± 2.607   ms/op
ClientPb.getUser                          avgt       3   3.790 ± 1.378   ms/op
ClientPb.listUser                         avgt       3   4.254 ± 1.263   ms/op
ClientPb.createUser                     sample  260273   3.686 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.371           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  266509   3.600 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.151           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.193           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.985           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.438           ms/op
ClientPb.getUser                        sample  260483   3.683 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.296           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.974           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.402           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.302           ms/op
ClientPb.listUser                       sample  206355   4.653 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.756           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.272           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
