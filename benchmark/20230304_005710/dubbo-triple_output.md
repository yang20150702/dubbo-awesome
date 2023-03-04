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
# Warmup Iteration   1: 1.780 ops/ms
# Warmup Iteration   2: 3.994 ops/ms
# Warmup Iteration   3: 7.334 ops/ms
Iteration   1: 7.426 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 8.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.832 ±(99.9%) 7.307 ops/ms [Average]
  (min, avg, max) = (7.426, 7.832, 8.227), stdev = 0.401
  CI (99.9%): [0.525, 15.139] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.488 ops/ms
# Warmup Iteration   2: 7.118 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.209 ±(99.9%) 5.631 ops/ms [Average]
  (min, avg, max) = (7.858, 8.209, 8.441), stdev = 0.309
  CI (99.9%): [2.578, 13.840] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.615 ops/ms
# Warmup Iteration   2: 6.791 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 7.951 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 7.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.942 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (7.879, 7.942, 7.995), stdev = 0.058
  CI (99.9%): [6.875, 9.008] (assumes normal distribution)


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
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 5.640 ops/ms
# Warmup Iteration   3: 6.658 ops/ms
Iteration   1: 7.052 ops/ms
Iteration   2: 6.829 ops/ms
Iteration   3: 7.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.007 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (6.829, 7.007, 7.139), stdev = 0.160
  CI (99.9%): [4.089, 9.924] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.199 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.846 ±(99.9%) 0.013 ms/op
Iteration   2: 3.986 ±(99.9%) 0.011 ms/op
Iteration   3: 3.990 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.940 ±(99.9%) 1.497 ms/op [Average]
  (min, avg, max) = (3.846, 3.940, 3.990), stdev = 0.082
  CI (99.9%): [2.443, 5.438] (assumes normal distribution)


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
# Warmup Iteration   1: 10.687 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.004 ms/op
Iteration   1: 4.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.710 ±(99.9%) 0.004 ms/op
Iteration   3: 3.778 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.834 ±(99.9%) 2.918 ms/op [Average]
  (min, avg, max) = (3.710, 3.834, 4.015), stdev = 0.160
  CI (99.9%): [0.917, 6.752] (assumes normal distribution)


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
# Warmup Iteration   1: 12.517 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.004 ms/op
Iteration   1: 3.959 ±(99.9%) 0.007 ms/op
Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
Iteration   3: 3.984 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.995 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.959, 3.995, 4.044), stdev = 0.044
  CI (99.9%): [3.199, 4.792] (assumes normal distribution)


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
# Warmup Iteration   1: 13.671 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.378 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.012 ms/op
Iteration   1: 4.668 ±(99.9%) 0.007 ms/op
Iteration   2: 4.643 ±(99.9%) 0.010 ms/op
Iteration   3: 4.668 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.660 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (4.643, 4.660, 4.668), stdev = 0.014
  CI (99.9%): [4.397, 4.922] (assumes normal distribution)


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
# Warmup Iteration   1: 11.396 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.930 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.017 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.725 ms/op
                 createUser·p0.999:  13.605 ms/op
                 createUser·p0.9999: 24.902 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  25.136 ms/op
                 createUser·p0.9999: 27.945 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.832 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  26.071 ms/op
                 createUser·p0.9999: 31.818 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245934
  mean =      3.900 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 329 
    [ 2.500,  5.000) = 237517 
    [ 5.000,  7.500) = 6206 
    [ 7.500, 10.000) = 1288 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     30.291 ms/op
     p(99.9990) =     32.703 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 11.676 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.084 ±(99.9%) 0.013 ms/op
Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 25.909 ms/op
                 existUser·p1.00:   28.443 ms/op

Iteration   2: 3.792 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.510 ms/op
                 existUser·p0.999:  24.849 ms/op
                 existUser·p0.9999: 28.713 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.772 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.817 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 36.635 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252446
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 244544 
    [ 5.000,  7.500) = 5715 
    [ 7.500, 10.000) = 1424 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     17.352 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     37.187 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 12.245 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
Iteration   1: 4.033 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   8.389 ms/op
                 getUser·p0.999:  22.053 ms/op
                 getUser·p0.9999: 24.548 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 3.926 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 29.814 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  27.805 ms/op
                 getUser·p0.9999: 29.567 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244368
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 231742 
    [ 5.000,  7.500) = 9441 
    [ 7.500, 10.000) = 2326 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     22.008 ms/op
     p(99.9900) =     29.590 ms/op
     p(99.9990) =     30.824 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 13.363 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.202 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.768 ±(99.9%) 0.017 ms/op
Iteration   1: 4.706 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 26.195 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 4.548 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.605 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.354 ms/op
                 listUser·p0.9999: 18.228 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207602
  mean =      4.619 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 186298 
    [ 5.000,  7.500) = 16967 
    [ 7.500, 10.000) = 3086 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     25.206 ms/op
     p(99.9990) =     29.521 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.832 ± 7.307  ops/ms
ClientPb.existUser                       thrpt       3   8.209 ± 5.631  ops/ms
ClientPb.getUser                         thrpt       3   7.942 ± 1.066  ops/ms
ClientPb.listUser                        thrpt       3   7.007 ± 2.918  ops/ms
ClientPb.createUser                       avgt       3   3.940 ± 1.497   ms/op
ClientPb.existUser                        avgt       3   3.834 ± 2.918   ms/op
ClientPb.getUser                          avgt       3   3.995 ± 0.796   ms/op
ClientPb.listUser                         avgt       3   4.660 ± 0.263   ms/op
ClientPb.createUser                     sample  245934   3.900 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.101           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.291           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  252446   3.801 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.227           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.618           ms/op
ClientPb.getUser                        sample  244368   3.929 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.856           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.590           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  207602   4.619 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.645           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.206           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.688           ms/op
