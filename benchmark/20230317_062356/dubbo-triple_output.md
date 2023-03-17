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
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 3.400 ops/ms
# Warmup Iteration   3: 7.018 ops/ms
Iteration   1: 7.475 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.815 ±(99.9%) 5.571 ops/ms [Average]
  (min, avg, max) = (7.475, 7.815, 8.066), stdev = 0.305
  CI (99.9%): [2.244, 13.385] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 6.873 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 8.214 ops/ms
Iteration   2: 8.547 ops/ms
Iteration   3: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.428 ±(99.9%) 3.389 ops/ms [Average]
  (min, avg, max) = (8.214, 8.428, 8.547), stdev = 0.186
  CI (99.9%): [5.039, 11.817] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.152 ops/ms
# Warmup Iteration   2: 6.423 ops/ms
# Warmup Iteration   3: 7.870 ops/ms
Iteration   1: 7.655 ops/ms
Iteration   2: 8.172 ops/ms
Iteration   3: 7.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.877 ±(99.9%) 4.849 ops/ms [Average]
  (min, avg, max) = (7.655, 7.877, 8.172), stdev = 0.266
  CI (99.9%): [3.028, 12.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.112 ops/ms
# Warmup Iteration   2: 5.312 ops/ms
# Warmup Iteration   3: 6.706 ops/ms
Iteration   1: 6.973 ops/ms
Iteration   2: 6.874 ops/ms
Iteration   3: 6.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.928 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (6.874, 6.928, 6.973), stdev = 0.050
  CI (99.9%): [6.009, 7.847] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 14.011 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.328 ±(99.9%) 0.004 ms/op
Iteration   1: 4.159 ±(99.9%) 0.008 ms/op
Iteration   2: 4.017 ±(99.9%) 0.012 ms/op
Iteration   3: 3.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.036 ±(99.9%) 2.093 ms/op [Average]
  (min, avg, max) = (3.932, 4.036, 4.159), stdev = 0.115
  CI (99.9%): [1.943, 6.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.234 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.008 ms/op
Iteration   1: 3.693 ±(99.9%) 0.011 ms/op
Iteration   2: 3.854 ±(99.9%) 0.002 ms/op
Iteration   3: 3.678 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.742 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (3.678, 3.742, 3.854), stdev = 0.097
  CI (99.9%): [1.963, 5.520] (assumes normal distribution)


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
# Warmup Iteration   1: 13.022 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.179 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.008 ms/op
Iteration   1: 4.029 ±(99.9%) 0.007 ms/op
Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
Iteration   3: 3.964 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.987 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.964, 3.987, 4.029), stdev = 0.037
  CI (99.9%): [3.321, 4.653] (assumes normal distribution)


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
# Warmup Iteration   1: 14.232 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.012 ms/op
Iteration   1: 4.683 ±(99.9%) 0.012 ms/op
Iteration   2: 4.563 ±(99.9%) 0.014 ms/op
Iteration   3: 4.673 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.640 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (4.563, 4.640, 4.683), stdev = 0.066
  CI (99.9%): [3.427, 5.853] (assumes normal distribution)


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
# Warmup Iteration   1: 13.308 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.616 ±(99.9%) 0.022 ms/op
Iteration   1: 4.002 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 28.770 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.913 ms/op
                 createUser·p0.999:  14.765 ms/op
                 createUser·p0.9999: 33.687 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   3: 4.097 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.215 ms/op
                 createUser·p0.999:  28.330 ms/op
                 createUser·p0.9999: 32.970 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238015
  mean =      4.037 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 222811 
    [ 5.000,  7.500) = 12063 
    [ 7.500, 10.000) = 2173 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     32.912 ms/op
     p(99.9990) =     34.257 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 11.014 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 25.783 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  13.033 ms/op
                 existUser·p0.9999: 29.876 ms/op
                 existUser·p1.00:   30.245 ms/op

Iteration   3: 3.892 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   7.700 ms/op
                 existUser·p0.999:  26.129 ms/op
                 existUser·p0.9999: 29.408 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246316
  mean =      3.895 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 299 
    [ 2.500,  5.000) = 237358 
    [ 5.000,  7.500) = 7070 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     16.231 ms/op
     p(99.9900) =     29.590 ms/op
     p(99.9990) =     30.623 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 13.076 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.335 ±(99.9%) 0.016 ms/op
Iteration   1: 4.052 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   6.177 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  23.042 ms/op
                 getUser·p0.9999: 24.783 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.856 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.835 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  24.743 ms/op
                 getUser·p0.9999: 28.171 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.992 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  13.462 ms/op
                 getUser·p0.9999: 31.653 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242066
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 227948 
    [ 5.000,  7.500) = 11149 
    [ 7.500, 10.000) = 2144 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     22.933 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.975 ms/op
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
# Warmup Iteration   1: 14.644 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.645 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.019 ms/op
Iteration   1: 4.684 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  25.723 ms/op
                 listUser·p0.9999: 32.702 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 4.553 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 22.772 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.801 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.916 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  19.683 ms/op
                 listUser·p0.9999: 24.872 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205114
  mean =      4.677 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 174661 
    [ 5.000,  7.500) = 26308 
    [ 7.500, 10.000) = 3246 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     32.129 ms/op
     p(99.9990) =     33.608 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.815 ± 5.571  ops/ms
ClientPb.existUser                       thrpt       3   8.428 ± 3.389  ops/ms
ClientPb.getUser                         thrpt       3   7.877 ± 4.849  ops/ms
ClientPb.listUser                        thrpt       3   6.928 ± 0.919  ops/ms
ClientPb.createUser                       avgt       3   4.036 ± 2.093   ms/op
ClientPb.existUser                        avgt       3   3.742 ± 1.779   ms/op
ClientPb.getUser                          avgt       3   3.987 ± 0.666   ms/op
ClientPb.listUser                         avgt       3   4.640 ± 1.213   ms/op
ClientPb.createUser                     sample  238015   4.037 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.565           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.782           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.674           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.912           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.389           ms/op
ClientPb.existUser                      sample  246316   3.895 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.989           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.231           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.590           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  242066   3.965 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.698           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.933           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.310           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  205114   4.677 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.955           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.129           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.620           ms/op
