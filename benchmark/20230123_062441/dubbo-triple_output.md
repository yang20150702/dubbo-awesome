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
# Warmup Iteration   1: 1.612 ops/ms
# Warmup Iteration   2: 3.540 ops/ms
# Warmup Iteration   3: 6.760 ops/ms
Iteration   1: 7.261 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.813 ±(99.9%) 8.737 ops/ms [Average]
  (min, avg, max) = (7.261, 7.813, 8.116), stdev = 0.479
  CI (99.9%): [≈ 0, 16.550] (assumes normal distribution)


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
# Warmup Iteration   1: 2.336 ops/ms
# Warmup Iteration   2: 6.662 ops/ms
# Warmup Iteration   3: 7.720 ops/ms
Iteration   1: 8.232 ops/ms
Iteration   2: 8.541 ops/ms
Iteration   3: 8.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.428 ±(99.9%) 3.109 ops/ms [Average]
  (min, avg, max) = (8.232, 8.428, 8.541), stdev = 0.170
  CI (99.9%): [5.319, 11.537] (assumes normal distribution)


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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 6.488 ops/ms
# Warmup Iteration   3: 7.526 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.083 ±(99.9%) 3.198 ops/ms [Average]
  (min, avg, max) = (7.904, 8.083, 8.254), stdev = 0.175
  CI (99.9%): [4.885, 11.281] (assumes normal distribution)


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
# Warmup Iteration   1: 2.299 ops/ms
# Warmup Iteration   2: 6.129 ops/ms
# Warmup Iteration   3: 6.780 ops/ms
Iteration   1: 6.973 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 6.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.869 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (6.770, 6.869, 6.973), stdev = 0.101
  CI (99.9%): [5.022, 8.716] (assumes normal distribution)


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
# Warmup Iteration   1: 14.719 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.010 ms/op
Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
Iteration   2: 4.070 ±(99.9%) 0.010 ms/op
Iteration   3: 3.889 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.977 ±(99.9%) 1.654 ms/op [Average]
  (min, avg, max) = (3.889, 3.977, 4.070), stdev = 0.091
  CI (99.9%): [2.323, 5.630] (assumes normal distribution)


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
# Warmup Iteration   1: 11.779 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.008 ms/op
Iteration   1: 3.787 ±(99.9%) 0.010 ms/op
Iteration   2: 3.944 ±(99.9%) 0.004 ms/op
Iteration   3: 3.731 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.820 ±(99.9%) 2.011 ms/op [Average]
  (min, avg, max) = (3.731, 3.820, 3.944), stdev = 0.110
  CI (99.9%): [1.810, 5.831] (assumes normal distribution)


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
# Warmup Iteration   1: 11.751 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.008 ms/op
Iteration   1: 3.897 ±(99.9%) 0.005 ms/op
Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
Iteration   3: 4.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.947 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.897, 3.947, 4.029), stdev = 0.072
  CI (99.9%): [2.642, 5.251] (assumes normal distribution)


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
# Warmup Iteration   1: 14.023 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.381 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.948 ±(99.9%) 0.007 ms/op
Iteration   1: 4.747 ±(99.9%) 0.011 ms/op
Iteration   2: 4.853 ±(99.9%) 0.011 ms/op
Iteration   3: 4.723 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.774 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (4.723, 4.774, 4.853), stdev = 0.069
  CI (99.9%): [3.508, 6.040] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.297 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.984 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 4.716 ±(99.9%) 0.022 ms/op
Iteration   1: 4.126 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  14.161 ms/op
                 createUser·p0.9999: 26.230 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.835 ms/op
                 createUser·p0.999:  24.292 ms/op
                 createUser·p0.9999: 41.812 ms/op
                 createUser·p1.00:   42.402 ms/op

Iteration   3: 3.990 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 29.680 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236409
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221360 
    [ 5.000, 10.000) = 14281 
    [10.000, 15.000) = 487 
    [15.000, 20.000) = 57 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     40.090 ms/op
     p(99.9990) =     42.205 ms/op
     p(99.9999) =     42.402 ms/op
    p(100.0000) =     42.402 ms/op


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
# Warmup Iteration   1: 12.763 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.014 ms/op
Iteration   1: 4.103 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   7.194 ms/op
                 existUser·p0.999:  24.216 ms/op
                 existUser·p0.9999: 29.524 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   2: 3.841 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  24.768 ms/op
                 existUser·p0.9999: 28.061 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   3: 3.851 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  10.729 ms/op
                 existUser·p0.9999: 34.563 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244290
  mean =      3.928 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 331 
    [ 2.500,  5.000) = 233497 
    [ 5.000,  7.500) = 8881 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     33.297 ms/op
     p(99.9990) =     34.705 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 13.433 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.012 ms/op
Iteration   1: 4.226 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  25.352 ms/op
                 getUser·p0.9999: 32.965 ms/op
                 getUser·p1.00:   33.030 ms/op

Iteration   2: 4.057 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  13.025 ms/op
                 getUser·p0.9999: 38.142 ms/op
                 getUser·p1.00:   38.863 ms/op

Iteration   3: 4.001 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   7.832 ms/op
                 getUser·p0.999:  28.574 ms/op
                 getUser·p0.9999: 36.375 ms/op
                 getUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234426
  mean =      4.093 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 218647 
    [ 5.000,  7.500) = 11603 
    [ 7.500, 10.000) = 3137 
    [10.000, 12.500) = 596 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     25.414 ms/op
     p(99.9900) =     37.224 ms/op
     p(99.9990) =     38.316 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 15.465 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.471 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.991 ±(99.9%) 0.019 ms/op
Iteration   1: 4.761 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  24.379 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 4.794 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  21.900 ms/op
                 listUser·p0.9999: 24.609 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 4.723 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  17.244 ms/op
                 listUser·p0.9999: 22.443 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201569
  mean =      4.759 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 166783 
    [ 5.000,  7.500) = 28732 
    [ 7.500, 10.000) = 4821 
    [10.000, 12.500) = 657 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 147 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     25.619 ms/op
     p(99.9990) =     27.520 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.813 ± 8.737  ops/ms
ClientPb.existUser                       thrpt       3   8.428 ± 3.109  ops/ms
ClientPb.getUser                         thrpt       3   8.083 ± 3.198  ops/ms
ClientPb.listUser                        thrpt       3   6.869 ± 1.847  ops/ms
ClientPb.createUser                       avgt       3   3.977 ± 1.654   ms/op
ClientPb.existUser                        avgt       3   3.820 ± 2.011   ms/op
ClientPb.getUser                          avgt       3   3.947 ± 1.305   ms/op
ClientPb.listUser                         avgt       3   4.774 ± 1.266   ms/op
ClientPb.createUser                     sample  236409   4.060 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.236           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.402           ms/op
ClientPb.existUser                      sample  244290   3.928 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.855           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.297           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.734           ms/op
ClientPb.getUser                        sample  234426   4.093 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.224           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.863           ms/op
ClientPb.listUser                       sample  201569   4.759 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.755           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.151           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.619           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
