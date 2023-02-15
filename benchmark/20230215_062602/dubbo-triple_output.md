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
# Warmup Iteration   1: 1.723 ops/ms
# Warmup Iteration   2: 3.425 ops/ms
# Warmup Iteration   3: 6.851 ops/ms
Iteration   1: 7.338 ops/ms
Iteration   2: 7.747 ops/ms
Iteration   3: 7.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.603 ±(99.9%) 4.192 ops/ms [Average]
  (min, avg, max) = (7.338, 7.603, 7.747), stdev = 0.230
  CI (99.9%): [3.411, 11.795] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.211 ops/ms
# Warmup Iteration   2: 6.397 ops/ms
# Warmup Iteration   3: 7.641 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 7.967 ops/ms
Iteration   3: 7.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.049 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (7.946, 8.049, 8.234), stdev = 0.160
  CI (99.9%): [5.122, 10.976] (assumes normal distribution)


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
# Warmup Iteration   1: 2.329 ops/ms
# Warmup Iteration   2: 6.268 ops/ms
# Warmup Iteration   3: 7.527 ops/ms
Iteration   1: 7.934 ops/ms
Iteration   2: 7.851 ops/ms
Iteration   3: 7.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.847 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (7.756, 7.847, 7.934), stdev = 0.089
  CI (99.9%): [6.222, 9.472] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.272 ops/ms
# Warmup Iteration   2: 5.939 ops/ms
# Warmup Iteration   3: 6.186 ops/ms
Iteration   1: 6.538 ops/ms
Iteration   2: 6.460 ops/ms
Iteration   3: 6.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.554 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (6.460, 6.554, 6.664), stdev = 0.103
  CI (99.9%): [4.674, 8.434] (assumes normal distribution)


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
# Warmup Iteration   1: 13.311 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.008 ms/op
Iteration   1: 4.188 ±(99.9%) 0.008 ms/op
Iteration   2: 3.910 ±(99.9%) 0.011 ms/op
Iteration   3: 3.891 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.996 ±(99.9%) 3.029 ms/op [Average]
  (min, avg, max) = (3.891, 3.996, 4.188), stdev = 0.166
  CI (99.9%): [0.967, 7.026] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.092 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.008 ms/op
Iteration   1: 3.916 ±(99.9%) 0.008 ms/op
Iteration   2: 4.065 ±(99.9%) 0.009 ms/op
Iteration   3: 3.854 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.945 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (3.854, 3.945, 4.065), stdev = 0.109
  CI (99.9%): [1.960, 5.930] (assumes normal distribution)


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
# Warmup Iteration   1: 13.261 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.202 ±(99.9%) 0.005 ms/op
Iteration   1: 4.271 ±(99.9%) 0.006 ms/op
Iteration   2: 4.240 ±(99.9%) 0.007 ms/op
Iteration   3: 4.259 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.257 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (4.240, 4.257, 4.271), stdev = 0.016
  CI (99.9%): [3.974, 4.540] (assumes normal distribution)


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
# Warmup Iteration   1: 14.094 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.497 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.884 ±(99.9%) 0.012 ms/op
Iteration   1: 4.907 ±(99.9%) 0.019 ms/op
Iteration   2: 4.740 ±(99.9%) 0.014 ms/op
Iteration   3: 4.734 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.794 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (4.734, 4.794, 4.907), stdev = 0.098
  CI (99.9%): [3.011, 6.576] (assumes normal distribution)


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
# Warmup Iteration   1: 13.547 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 4.862 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.021 ms/op
Iteration   1: 4.153 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  11.596 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 4.049 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.530 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  24.250 ms/op
                 createUser·p0.9999: 25.536 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 4.203 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.942 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   4.858 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  13.098 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232047
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 318 
    [ 2.500,  5.000) = 215860 
    [ 5.000,  7.500) = 13728 
    [ 7.500, 10.000) = 1539 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     27.289 ms/op
     p(99.9990) =     28.610 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 12.368 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.013 ms/op
Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.473 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  19.988 ms/op
                 existUser·p0.9999: 33.486 ms/op
                 existUser·p1.00:   33.882 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 26.055 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  15.434 ms/op
                 existUser·p0.9999: 27.243 ms/op
                 existUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246195
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 236789 
    [ 5.000,  7.500) = 7600 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.725 ms/op
     p(99.9900) =     32.961 ms/op
     p(99.9990) =     33.817 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.222 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.932 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.010 ms/op
Iteration   1: 4.204 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.874 ms/op
                 getUser·p0.95:   6.242 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  14.270 ms/op
                 getUser·p0.9999: 25.637 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 4.069 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   8.348 ms/op
                 getUser·p0.999:  25.124 ms/op
                 getUser·p0.9999: 29.542 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 4.232 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 33.780 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230251
  mean =      4.167 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 211837 
    [ 5.000,  7.500) = 14795 
    [ 7.500, 10.000) = 2428 
    [10.000, 12.500) = 639 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     31.818 ms/op
     p(99.9990) =     34.059 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 13.993 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.574 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.443 ±(99.9%) 0.023 ms/op
Iteration   1: 5.189 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.699 ms/op
                 listUser·p0.999:  26.129 ms/op
                 listUser·p0.9999: 36.865 ms/op
                 listUser·p1.00:   37.487 ms/op

Iteration   2: 4.710 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.859 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  20.778 ms/op
                 listUser·p0.9999: 25.212 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   3: 5.108 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  19.163 ms/op
                 listUser·p0.9999: 23.558 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192091
  mean =      4.993 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 139717 
    [ 5.000,  7.500) = 44016 
    [ 7.500, 10.000) = 6040 
    [10.000, 12.500) = 1286 
    [12.500, 15.000) = 491 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      7.168 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     21.558 ms/op
     p(99.9900) =     36.097 ms/op
     p(99.9990) =     37.366 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.603 ± 4.192  ops/ms
ClientPb.existUser                       thrpt       3   8.049 ± 2.927  ops/ms
ClientPb.getUser                         thrpt       3   7.847 ± 1.625  ops/ms
ClientPb.listUser                        thrpt       3   6.554 ± 1.880  ops/ms
ClientPb.createUser                       avgt       3   3.996 ± 3.029   ms/op
ClientPb.existUser                        avgt       3   3.945 ± 1.985   ms/op
ClientPb.getUser                          avgt       3   4.257 ± 0.283   ms/op
ClientPb.listUser                         avgt       3   4.794 ± 1.782   ms/op
ClientPb.createUser                     sample  232047   4.134 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.530           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.751           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.289           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  246195   3.897 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.530           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.971           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.725           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.961           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  230251   4.167 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.747           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.743           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.818           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  192091   4.993 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.168           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.558           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.097           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.487           ms/op
