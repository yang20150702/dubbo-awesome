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
# Warmup Iteration   1: 1.770 ops/ms
# Warmup Iteration   2: 3.750 ops/ms
# Warmup Iteration   3: 7.417 ops/ms
Iteration   1: 7.390 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.704 ±(99.9%) 4.977 ops/ms [Average]
  (min, avg, max) = (7.390, 7.704, 7.890), stdev = 0.273
  CI (99.9%): [2.726, 12.681] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
# Warmup Iteration   2: 6.043 ops/ms
# Warmup Iteration   3: 7.423 ops/ms
Iteration   1: 8.354 ops/ms
Iteration   2: 8.638 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.385 ±(99.9%) 4.357 ops/ms [Average]
  (min, avg, max) = (8.164, 8.385, 8.638), stdev = 0.239
  CI (99.9%): [4.029, 12.742] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.249 ops/ms
# Warmup Iteration   2: 5.786 ops/ms
# Warmup Iteration   3: 7.604 ops/ms
Iteration   1: 7.529 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.882 ±(99.9%) 5.889 ops/ms [Average]
  (min, avg, max) = (7.529, 7.882, 8.163), stdev = 0.323
  CI (99.9%): [1.993, 13.771] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.024 ops/ms
# Warmup Iteration   2: 5.238 ops/ms
# Warmup Iteration   3: 6.249 ops/ms
Iteration   1: 6.974 ops/ms
Iteration   2: 6.614 ops/ms
Iteration   3: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.751 ±(99.9%) 3.556 ops/ms [Average]
  (min, avg, max) = (6.614, 6.751, 6.974), stdev = 0.195
  CI (99.9%): [3.195, 10.307] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 14.846 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.114 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.005 ms/op
Iteration   1: 4.144 ±(99.9%) 0.004 ms/op
Iteration   2: 4.035 ±(99.9%) 0.006 ms/op
Iteration   3: 4.018 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.066 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (4.018, 4.066, 4.144), stdev = 0.068
  CI (99.9%): [2.819, 5.312] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.625 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.006 ms/op
Iteration   1: 3.997 ±(99.9%) 0.006 ms/op
Iteration   2: 3.913 ±(99.9%) 0.005 ms/op
Iteration   3: 3.775 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.895 ±(99.9%) 2.046 ms/op [Average]
  (min, avg, max) = (3.775, 3.895, 3.997), stdev = 0.112
  CI (99.9%): [1.849, 5.941] (assumes normal distribution)


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
# Warmup Iteration   1: 13.350 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.192 ±(99.9%) 0.009 ms/op
Iteration   1: 4.066 ±(99.9%) 0.008 ms/op
Iteration   2: 4.015 ±(99.9%) 0.012 ms/op
Iteration   3: 4.116 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.066 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (4.015, 4.066, 4.116), stdev = 0.051
  CI (99.9%): [3.144, 4.987] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.248 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.455 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.060 ±(99.9%) 0.010 ms/op
Iteration   1: 5.075 ±(99.9%) 0.013 ms/op
Iteration   2: 4.727 ±(99.9%) 0.017 ms/op
Iteration   3: 4.855 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.886 ±(99.9%) 3.205 ms/op [Average]
  (min, avg, max) = (4.727, 4.886, 5.075), stdev = 0.176
  CI (99.9%): [1.680, 8.091] (assumes normal distribution)


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
# Warmup Iteration   1: 12.576 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.175 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.442 ±(99.9%) 0.018 ms/op
Iteration   1: 4.216 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.819 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  24.920 ms/op
                 createUser·p0.9999: 33.287 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   2: 4.303 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.823 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  13.282 ms/op
                 createUser·p0.9999: 27.460 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 4.157 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.987 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.874 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  28.608 ms/op
                 createUser·p0.9999: 31.195 ms/op
                 createUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 227103
  mean =      4.224 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201 
    [ 2.500,  5.000) = 202031 
    [ 5.000,  7.500) = 20980 
    [ 7.500, 10.000) = 2609 
    [10.000, 12.500) = 752 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     25.523 ms/op
     p(99.9900) =     31.613 ms/op
     p(99.9990) =     33.864 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.494 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.300 ±(99.9%) 0.016 ms/op
Iteration   1: 3.883 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.888 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  21.037 ms/op
                 existUser·p0.9999: 31.368 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   2: 4.144 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.774 ms/op
                 existUser·p0.999:  11.931 ms/op
                 existUser·p0.9999: 26.911 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.868 ms/op
                 existUser·p0.999:  18.630 ms/op
                 existUser·p0.9999: 27.488 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240082
  mean =      3.996 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 215 
    [ 2.500,  5.000) = 225788 
    [ 5.000,  7.500) = 11412 
    [ 7.500, 10.000) = 1958 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.888 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     18.642 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     31.614 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 12.843 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.197 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.015 ms/op
Iteration   1: 4.311 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   9.088 ms/op
                 getUser·p0.999:  23.749 ms/op
                 getUser·p0.9999: 26.187 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 4.107 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.912 ms/op
                 getUser·p0.999:  14.713 ms/op
                 getUser·p0.9999: 27.014 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 4.114 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.921 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  13.009 ms/op
                 getUser·p0.9999: 33.471 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229846
  mean =      4.175 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 210651 
    [ 5.000,  7.500) = 15338 
    [ 7.500, 10.000) = 2629 
    [10.000, 12.500) = 811 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.843 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.561 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     32.146 ms/op
     p(99.9990) =     33.889 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 15.177 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.959 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.133 ±(99.9%) 0.021 ms/op
Iteration   1: 4.839 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  29.590 ms/op
                 listUser·p0.9999: 34.800 ms/op
                 listUser·p1.00:   36.241 ms/op

Iteration   2: 4.712 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  17.312 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 4.954 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 19.711 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198435
  mean =      4.833 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 158143 
    [ 5.000,  7.500) = 34178 
    [ 7.500, 10.000) = 4830 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      9.077 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     33.530 ms/op
     p(99.9990) =     35.983 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.704 ± 4.977  ops/ms
ClientPb.existUser                       thrpt       3   8.385 ± 4.357  ops/ms
ClientPb.getUser                         thrpt       3   7.882 ± 5.889  ops/ms
ClientPb.listUser                        thrpt       3   6.751 ± 3.556  ops/ms
ClientPb.createUser                       avgt       3   4.066 ± 1.246   ms/op
ClientPb.existUser                        avgt       3   3.895 ± 2.046   ms/op
ClientPb.getUser                          avgt       3   4.066 ± 0.922   ms/op
ClientPb.listUser                         avgt       3   4.886 ± 3.205   ms/op
ClientPb.createUser                     sample  227103   4.224 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.819           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.602           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.523           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.613           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  240082   3.996 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.563           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.668           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.642           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  229846   4.175 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.561           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.413           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.146           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.013           ms/op
ClientPb.listUser                       sample  198435   4.833 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.179           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.398           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.431           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.530           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
