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
# Warmup Iteration   1: 1.497 ops/ms
# Warmup Iteration   2: 3.255 ops/ms
# Warmup Iteration   3: 6.702 ops/ms
Iteration   1: 7.252 ops/ms
Iteration   2: 7.484 ops/ms
Iteration   3: 7.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.387 ±(99.9%) 2.202 ops/ms [Average]
  (min, avg, max) = (7.252, 7.387, 7.484), stdev = 0.121
  CI (99.9%): [5.186, 9.589] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 6.585 ops/ms
# Warmup Iteration   3: 8.145 ops/ms
Iteration   1: 7.902 ops/ms
Iteration   2: 8.185 ops/ms
Iteration   3: 8.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.047 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (7.902, 8.047, 8.185), stdev = 0.142
  CI (99.9%): [5.464, 10.631] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.796 ops/ms
# Warmup Iteration   3: 7.447 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 8.078 ops/ms
Iteration   3: 8.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.986 ±(99.9%) 5.583 ops/ms [Average]
  (min, avg, max) = (7.644, 7.986, 8.235), stdev = 0.306
  CI (99.9%): [2.402, 13.569] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.125 ops/ms
# Warmup Iteration   2: 5.187 ops/ms
# Warmup Iteration   3: 6.676 ops/ms
Iteration   1: 6.598 ops/ms
Iteration   2: 6.874 ops/ms
Iteration   3: 6.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.629 ±(99.9%) 4.211 ops/ms [Average]
  (min, avg, max) = (6.415, 6.629, 6.874), stdev = 0.231
  CI (99.9%): [2.418, 10.840] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.634 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.814 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.220 ±(99.9%) 0.007 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
Iteration   2: 3.904 ±(99.9%) 0.012 ms/op
Iteration   3: 4.121 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.969 ±(99.9%) 2.422 ms/op [Average]
  (min, avg, max) = (3.880, 3.969, 4.121), stdev = 0.133
  CI (99.9%): [1.547, 6.390] (assumes normal distribution)


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
# Warmup Iteration   1: 13.820 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.873 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.873 ±(99.9%) 0.009 ms/op
Iteration   2: 4.402 ±(99.9%) 0.009 ms/op
Iteration   3: 4.203 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.159 ±(99.9%) 4.876 ms/op [Average]
  (min, avg, max) = (3.873, 4.159, 4.402), stdev = 0.267
  CI (99.9%): [≈ 0, 9.035] (assumes normal distribution)


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
# Warmup Iteration   1: 13.864 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.263 ±(99.9%) 0.007 ms/op
Iteration   1: 4.145 ±(99.9%) 0.006 ms/op
Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
Iteration   3: 4.190 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.144 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (4.097, 4.144, 4.190), stdev = 0.047
  CI (99.9%): [3.290, 4.998] (assumes normal distribution)


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
# Warmup Iteration   1: 16.963 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.394 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.352 ±(99.9%) 0.008 ms/op
Iteration   1: 5.210 ±(99.9%) 0.006 ms/op
Iteration   2: 4.906 ±(99.9%) 0.013 ms/op
Iteration   3: 5.296 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.138 ±(99.9%) 3.737 ms/op [Average]
  (min, avg, max) = (4.906, 5.138, 5.296), stdev = 0.205
  CI (99.9%): [1.401, 8.874] (assumes normal distribution)


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
# Warmup Iteration   1: 14.337 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.158 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.023 ms/op
Iteration   1: 3.966 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.759 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  25.297 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 4.602 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.931 ms/op
                 createUser·p0.95:   7.086 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  15.083 ms/op
                 createUser·p0.9999: 32.278 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   3: 4.693 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   7.406 ms/op
                 createUser·p0.99:   10.994 ms/op
                 createUser·p0.999:  33.740 ms/op
                 createUser·p0.9999: 47.591 ms/op
                 createUser·p1.00:   48.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218338
  mean =      4.395 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 186436 
    [ 5.000, 10.000) = 29834 
    [10.000, 15.000) = 1643 
    [15.000, 20.000) = 164 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 104 
    [30.000, 35.000) = 82 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     25.843 ms/op
     p(99.9900) =     45.449 ms/op
     p(99.9990) =     48.198 ms/op
     p(99.9999) =     48.366 ms/op
    p(100.0000) =     48.366 ms/op


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
# Warmup Iteration   1: 13.923 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.340 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.364 ±(99.9%) 0.020 ms/op
Iteration   1: 4.187 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   6.349 ms/op
                 existUser·p0.99:   8.268 ms/op
                 existUser·p0.999:  17.953 ms/op
                 existUser·p0.9999: 27.287 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 3.732 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  13.730 ms/op
                 existUser·p0.9999: 27.473 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 4.225 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   5.439 ms/op
                 existUser·p0.95:   6.537 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  27.066 ms/op
                 existUser·p0.9999: 44.304 ms/op
                 existUser·p1.00:   46.858 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237827
  mean =      4.035 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216347 
    [ 5.000, 10.000) = 20530 
    [10.000, 15.000) = 707 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 158 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     17.810 ms/op
     p(99.9900) =     41.615 ms/op
     p(99.9990) =     45.969 ms/op
     p(99.9999) =     46.858 ms/op
    p(100.0000) =     46.858 ms/op


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
# Warmup Iteration   1: 13.801 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.276 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.486 ±(99.9%) 0.017 ms/op
Iteration   1: 4.228 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  27.863 ms/op
                 getUser·p0.9999: 33.649 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 4.243 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.891 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  13.570 ms/op
                 getUser·p0.9999: 29.683 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 4.399 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 30.924 ms/op
                 getUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 223643
  mean =      4.289 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 198504 
    [ 5.000,  7.500) = 19848 
    [ 7.500, 10.000) = 4053 
    [10.000, 12.500) = 712 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 110 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     26.881 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 14.768 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.784 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.188 ±(99.9%) 0.020 ms/op
Iteration   1: 5.136 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   7.623 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  25.223 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   2: 5.217 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  26.389 ms/op
                 listUser·p0.9999: 32.235 ms/op
                 listUser·p1.00:   32.637 ms/op

Iteration   3: 5.346 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  23.156 ms/op
                 listUser·p0.9999: 26.314 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 183435
  mean =      5.231 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 109707 
    [ 5.000,  7.500) = 63264 
    [ 7.500, 10.000) = 7590 
    [10.000, 12.500) = 1753 
    [12.500, 15.000) = 524 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.332 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     31.074 ms/op
     p(99.9990) =     32.446 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.387 ± 2.202  ops/ms
ClientPb.existUser                       thrpt       3   8.047 ± 2.583  ops/ms
ClientPb.getUser                         thrpt       3   7.986 ± 5.583  ops/ms
ClientPb.listUser                        thrpt       3   6.629 ± 4.211  ops/ms
ClientPb.createUser                       avgt       3   3.969 ± 2.422   ms/op
ClientPb.existUser                        avgt       3   4.159 ± 4.876   ms/op
ClientPb.getUser                          avgt       3   4.144 ± 0.854   ms/op
ClientPb.listUser                         avgt       3   5.138 ± 3.737   ms/op
ClientPb.createUser                     sample  218338   4.395 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.880           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.843           ms/op
ClientPb.createUser:createUser·p0.9999  sample          45.449           ms/op
ClientPb.createUser:createUser·p1.00    sample          48.366           ms/op
ClientPb.existUser                      sample  237827   4.035 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.581           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.874           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.200           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.810           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.615           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.858           ms/op
ClientPb.getUser                        sample  223643   4.289 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.680           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.881           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.326           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  183435   5.231 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.253           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.332           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.314           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.074           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.637           ms/op
